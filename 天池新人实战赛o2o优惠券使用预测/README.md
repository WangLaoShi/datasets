# 天池新人实战赛 o2o 优惠券使用预测

## 数据

本赛题提供用户在 2016 年 1 月 1 日至 2016 年 6 月 30 日之间真实线上线下消费行为，预测用户在 2016 年 7 月领取优惠券后 15 天以内的使用情况。

**注意：为了保护用户和商家的隐私，所有数据均作匿名处理，同时采用了有偏采样和必要过滤。**

## 评价方式

本赛题目标是预测投放的优惠券是否核销。

针对此任务及一些相关背景知识，使用优惠券核销预测的平均 AUC（ ROC 曲线下面积）作为评价标准。

即对每个优惠券 coupon_id 单独计算核销预测的 AUC 值，再对所有优惠券的AUC值求平均作为最终的评价标准。

关于 AUC 的含义与具体计算方法，可参考[维基百科](https://zh.wikipedia.org/wiki/ROC%E6%9B%B2%E7%BA%BF#.E6.9B.B2.E7.B7.9A.E4.B8.8B.E9.9D.A2.E7.A9.8D.EF.BC.88AUC.EF.BC.89)

## 字段表

### Table 1:  用户线下消费和优惠券领取行为

**Field**     | **Description**   
------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------
User_id       | 用户 ID                                                                                                                                                   
Merchant_id   | 商户 ID                                                                                                                                                   
Coupon_id     | 优惠券 ID：null 表示无优惠券消费，此时 Discount_rate 和 Date_received 字段无意义                                                                                                  
Discount_rate | 优惠率：$x \in [0,1] $ 代表折扣率；x:y 表示满 x 减 y 。单位是元                                                                                                                    
Distance      | user 经常活动的地点离该 merchant 的最近门店距离是 x*500 米（如果是连锁店，则取最近的一家门店），$x \in [0,10]$；null 表示无此信息，0 表示低于 500 米，10 表示大于 5 公里；                                                       
Date_received | 领取优惠券日期                                                                                                                                                
Date          | 消费日期：如果 Date=null & Coupon_id != null，该记录表示领取优惠券但没有使用，即负样本；如果 Date!=null & Coupon_id = null，则表示普通消费日期；如果Date!=null & Coupon_id != null，则表示用优惠券消费日期，即正样本；   

### Table 2:  用户线上点击/消费和优惠券领取行为

**Field**     | **Description**   
------------- | ---------------------------------------------------------------------------------------------------------------------------------------------
User_id       | 用户 ID                                                                                                                                         
Merchant_id   | 商户 ID                                                                                                                                         
Action        | 0 点击， 1 购买，2 领取优惠券                                                                                                                             
Coupon_id     | 优惠券 ID：null 表示无优惠券消费，此时 Discount_rate 和 Date_received 字段无意义。“fixed” 表示该交易是限时低价活动。                                                                   
Discount_rate | 优惠率：$x \in [0,1]$ 代表折扣率；x:y 表示满 x 减 y；“fixed” 表示低价限时优惠；                                                                                              
Date_received | 领取优惠券日期                                                                                                                                      
Date          | 消费日期：如果 Date=null & Coupon_id != null，该记录表示领取优惠券但没有使用；如果 Date!=null & Coupon_id = null，则表示普通消费日期；如果 Date!=null & Coupon_id != null，则表示用优惠券消费日期；   

### Table 3：用户 O2O 线下优惠券使用预测样本

**Field**     | **Description**   
------------- | --------------------------------------------------------------------------------------------------
User_id       | 用户 ID                                                                                              
Merchant_id   | 商户 ID                                                                                              
Coupon_id     | 优惠券 ID                                                                                             
Discount_rate | 优惠率：$x \in [0,1]$ 代表折扣率；x:y 表示满 x 减 y.                                                                   
Distance      | user 经常活动的地点离该 merchant 的最近门店距离是 x*500 米（如果是连锁店，则取最近的一家门店），$ x \in [0,10]$；null 表示无此信息，0 表示低于 500 米，10 表示大于 5 公里；  
Date_received | 领取优惠券日期                                                                                             

### Table 4：选手提交文件字段

其中user_id,coupon_id和date_received均来自Table 3,而Probability为预测值

**Field**     | **Description**  
------------- | -----------------
User_id       | 用户 ID             
Coupon_id     | 优惠券 ID            
Date_received | 领取优惠券日期          
Probability   | 15 天内用券概率，由参赛选手给出 