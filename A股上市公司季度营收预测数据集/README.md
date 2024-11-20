# A股上市公司季度营收预测数据集

## 描述

FDDC2018金融算法挑战赛01－A股上市公司季度营收预测。https://tianchi.aliyun.com/competition/entrance/231660/introduction

## 数据列表

* 数据名称
* null.txt
* 0-read me_CN.pdf.txt
* 0-read me_EN.pdf
* FDDC_financial_data.zip
* Financial Terms.pdf

## 数据描述

本赛题用到的数据包括历史财务数据、宏观数据、行情数据、行业数据。

各数据包含的主要字段的名词解析以及财务数据的中英文对照。

### 财务数据

财务数据包括三张表，分别为:

* 资产负债表 Balance Sheet、
* 利润表 Income Statement、
* 现金流量表 Cash Flow Statement。

其中，由于非金融上市公司、证券、银行、保险四大行业的财务报表在结构上存在差异，所以每个类别又分为4个相对应的文档（csv格式）。

这三张表代表了一个公司全部的财务信息，三大财务报表分析是投资的基础。

* 资产负债表：代表一个公司的资产与负债及股东权益，资产负债表是所有表格的基础。

* 利润表：代表一个公司的利润来源，而净利润则直接影响资产负债表中股东权益的变化。

* 现金流量表：代表一个公司的现金流量，更代表资产负债表的变化。现金流量表是对资产负债表变化的解释。现金的变化最终反映到资产负债表的现金及等价物一项。而现金的变化源泉则是净利润。净利润经过“经营”、“投资”、“筹资”三项重要的现金变动转变为最终的现金变化。

![VcRgfk](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/VcRgfk.png)

### 宏观数据

* 宏观数据 Macro Industry 是指一系列宏观经济学的统计指标， 包括生产总值(GDP)、国民总收入（GNI）、劳动者报酬、消费水平等。宏观经济周期是影响周期性行业的关键因素之一，对上市公司的经营情况也有直接的影响。

### 行业数据

* 行业数据 Industry Data 行业数据可以指示某个行业的发展态势，上市公司都会有自己所在的行业，分析行业的发展趋势、所处阶段等可对上市公司经营情况做出大体的判断（如从汽车行业每月的销量数据中，可以看到行业的景气程度）。

### 行情数据

* 公司经营数据 Company Operation Data 一般为月度数据，代表特定公司主营业务月度的统计值，与公司营收密切相关，每个公司指标不一样。

* 行情数据 Market Data 行情数据代表上市公司股票月度交易行情，主要包括价格、成交量、成交额、换手率等。

## 财务术语中英文对照大全


### 一、会计与会计理论

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 会计 | accounting |
| 决策人 | Decision Maker |
| 投资人 | Investor |
| 股东 | Shareholder |
| 债权人 | Creditor |
| 财务会计 | Financial Accounting |
| 管理会计 | Management Accounting |
| 成本会计 | Cost Accounting |
| 私业会计 | Private Accounting |
| 公众会计 | Public Accounting |
| 注册会计师 | CPA Certified Public Accountant |
| 国际会计准则委员会 | IASC |
| 美国注册会计师协会 | AICPA |
| 财务会计准则委员会 | FASB |
| 管理会计协会 | IMA |
| 美国会计学会 | AAA |
| 税务稽核署 | IRS |
| 独资企业 | Proprietorship |
| 合伙人企业 | Partnership |
| 公司 | Corporation |
| 会计目标 | Accounting Objectives |
| 会计假设 | Accounting Assumptions |
| 会计要素 | Accounting Elements |
| 会计原则 | Accounting Principles |
| 会计实务过程 | Accounting Procedures |
| 财务报表 | Financial Statements |
| 财务分析 | Financial Analysis |
| 会计主体假设 | Separate-entity Assumption |
| 货币计量假设 | Unit-of-measure Assumption |
| 持续经营假设 | Continuity(Going-concern) Assumption |
| 会计分期假设 | Time-period Assumption |
| 资产 | Asset |
| 负债 | Liability |
| 业主权益 | Owner's Equity |
| 收入 | Revenue |
| 费用 | Expense |
| 收益 | Income |
| 亏损 | Loss |
| 历史成本原则 | Cost Principle |
| 收入实现原则 | Revenue Principle |
| 配比原则 | Matching Principle |
| 全面披露原则 | Full-disclosure (Reporting) Principle |
| 客观性原则 | Objective Principle |
| 一致性原则 | Consistent Principle |
| 可比性原则 | Comparability Principle |
| 重大性原则 | Materiality Principle |
| 稳健性原则 | Conservatism Principle |
| 权责发生制 | Accrual Basis |
| 现金收付制 | Cash Basis |
| 财务报告 | Financial Report |
| 流动资产 | Current assets |
| 流动负债 | Current Liabilities |
| 长期负债 | Long-term Liabilities |
| 投入资本 | Contributed Capital |
| 留存收益 | Retained Earning |

### 二、会计循环

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 会计循环 | Accounting Procedure/Cycle |
| 会计信息系统 | Accounting information System |
| 账户 | Ledger |
| 会计科目 | Account |
| 会计分录 | Journal entry |
| 原始凭证 | Source Document |
| 日记账 | Journal |
| 总分类账 | General Ledger |
| 明细分类账 | Subsidiary Ledger |
| 试算平衡 | Trial Balance |
| 现金收款日记账 | Cash receipt journal |
| 现金付款日记账 | Cash disbursements journal |
| 销售日记账 | Sales Journal |
| 购货日记账 | Purchase Journal |
| 普通日记账 | General Journal |
| 工作底稿 | Worksheet |
| 调整分录 | Adjusting entries |
| 结账 | Closing entries |

### 三、现金与应收账款

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 现金 | Cash |
| 银行存款 | Cash in bank |
| 库存现金 | Cash in hand |
| 流动资产 | Current assets |
| 偿债基金 | Sinking fund |
| 定额备用金 | Imprest petty cash |
| 支票 | Check(cheque) |
| 银行对账单 | Bank statement |
| 银行存款调节表 | Bank reconciliation statement |
| 在途存款 | Outstanding deposit |
| 在途支票 | Outstanding check |
| 应付凭单 | Vouchers payable |
| 应收账款 | Account receivable |
| 应收票据 | Note receivable |
| 起运点交货价 | F.O.B shipping point |
| 目的地交货价 | F.O.B destination point |
| 商业折扣 | Trade discount |
| 现金折扣 | Cash discount |
| 销售退回及折让 | Sales return and allowance |
| 坏账费用 | Bad debt expense |
| 备抵法 | Allowance method |
| 备抵坏账 | Bad debt allowance |
| 损益表法 | Income statement approach |
| 资产负债表法 | Balance sheet approach |
| 账龄分析法 | Aging analysis method |
| 直接冲销法 | Direct write-off method |
| 带息票据 | Interest bearing note |
| 不带息票据 | Non-interest bearing note |
| 出票人 | Maker |
| 受款人 | Payee |
| 本金 | Principal |
| 利息率 | Interest rate |
| 到期日 | Maturity date |
| 本票 | Promissory note |
| 贴现 | Discount |
| 背书 | Endorse |
| 拒付费 | Protest fee com |

### 四、存货

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 存货 | Inventory |
| 商品存货 | Merchandise inventory |
| 产成品存货 | Finished goods inventory |
| 在产品存货 | Work in process inventory |
| 原材料存货 | Raw materials inventory |
| 起运地离岸价格 | F.O.B shipping point |
| 目的地抵岸价格 | F.O.B destination |
| 寄销 | Consignment |
| 寄销人 | Consignor |
| 承销人 | Consignee |
| 定期盘存 | Periodic inventory |
| 永续盘存 | Perpetual inventory |
| 购货 | Purchase |
| 购货折让和折扣 | Purchase allowance and discounts |
| 存货盈余或短缺 | Inventory overages and shortages |
| 分批认定法 | Specific identification |
| 加权平均法 | Weighted average |
| 先进先出法 | First-in, first-out or FIFO |
| 后进先出法 | Lost-in, first-out or LIFO |
| 移动平均法 | Moving average |
| 成本或市价孰低法 | Lower of cost or market or LCM |
| 市价 | Market value |
| 重置成本 | Replacement cost |
| 可变现净值 | Net realizable value |
| 上限 | Upper limit |
| 下限 | Lower limit |
| 毛利法 | Gross margin method |
| 零售价格法 | Retail method |
| 成本率 | Cost ratio |

### 五、长期投资

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 长期投资 | Long-term investment |
| 长期股票投资 | Investment on stocks |
| 长期债券投资 | Investment on bonds |
| 成本法 | Cost method |
| 权益法 | Equity method |
| 合并法 | Consolidation method |
| 股利宣布日 | Declaration date |
| 股权登记日 | Date of record |
| 除息日 | Ex-dividend date |
| 付息日 | Payment date |
| 债券面值 | Face value, Par value |
| 债券折价 | Discount on bonds |
| 债券溢价 | Premium on bonds |
| 票面利率 | Contract interest rate, stated rate |
| 市场利率 | Market interest ratio, Effective rate |
| 普通股 | Common Stock |
| 优先股 | Preferred Stock |
| 现金股利 | Cash dividends |
| 股票股利 | Stock dividends |
| 清算股利 | Liquidating dividends |
| 到期日 | Maturity date |
| 到期值 | Maturity value |
| 直线摊销法 | Straight-Line method of amortization |
| 实际利息摊销法 | Effective-interest method of amortization |

### 六、固定资产

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 固定资产 | Plant assets or Fixed assets |
| 原值 | Original value |
| 预计使用年限 | Expected useful life |
| 预计残值 | Estimated residual value |
| 折旧费用 | Depreciation expense |
| 累计折旧 | Accumulated depreciation |
| 账面价值 | Carrying value |
| 应提折旧成本 | Depreciation cost |
| 净值 | Net value |
| 在建工程 | Construction-in-process |
| 磨损 | Wear and tear |
| 过时 | Obsolescence |
| 直线法 | Straight-line method (SL) |
| 工作量法 | Units-of-production method (UOP) |
| 加速折旧法 | Accelerated depreciation method |
| 双倍余额递减法 | Double-declining balance method (DDB) |
| 年数总和法 | Sum-of-the-years-digits method (SYD) |
| 以旧换新 | Trade in |
| 经营租赁 | Operating lease |
| 融资租赁 | Capital lease |
| 廉价购买权 | Bargain purchase option (BPO) |
| 资产负债表外筹资 | Off-balance-sheet financing |
| 最低租赁付款额 | Minimum lease payments |

### 七、无形资产

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 无形资产 | Intangible assets |
| 专利权 | Patents |
| 商标权 | Trademarks, Trade names |
| 著作权 | Copyrights |
| 特许权或专营权 | Franchises |
| 商誉 | Goodwill |
| 开办费 | Organization cost |
| 租赁权 | Leasehold |
| 摊销 | Amortization |

### 八、流动负债

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 负债 | Liability |
| 流动负债 | Current liability |
| 应付账款 | Account payable |
| 应付票据 | Notes payable |
| 贴现票据 | Discount notes |
| 长期负债一年内到期部分 | Current maturities of long-term liabilities |
| 应付股利 | Dividends payable |
| 预收收益 | Prepayments by customers |
| 存入保证金 | Refundable deposits |
| 应付费用 | Accrual expense |
| 增值税 | value added tax |
| 营业税 | Business tax |
| 应付所得税 | Income tax payable |
| 应付奖金 | Bonuses payable |
| 产品质量担保负债 | Estimated liabilities under product warranties |
| 赠品和兑换券 | Premiums, coupons and trading stamps |
| 或有事项 | Contingency |
| 或有负债 | Contingent |
| 或有损失 | Loss contingencies |
| 或有利得 | Gain contingencies |
| 永久性差异 | Permanent difference |
| 时间性差异 | Timing difference |
| 应付税款法 | Taxes payable method |
| 纳税影响会计法 | Tax effect accounting method |
| 递延所得税负债法 | Deferred income tax liability method |

### 九、长期负债

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 长期负债 | Long-term Liabilities |
| 应付公司债券 | Bonds payable |
| 有担保品的公司债券 | Secured Bonds |
| 抵押公司债券 | Mortgage Bonds |
| 保证公司债券 | Guaranteed Bonds |
| 信用公司债券 | Debenture Bonds |
| 一次还本公司债券 | Term Bonds |
| 分期还本公司债券 | Serial Bonds |
| 可转换公司债券 | Convertible Bonds |
| 可赎回公司债券 | Callable Bonds |
| 可要求公司债券 | Redeemable Bonds |
| 记名公司债券 | Registered Bonds |
| 无记名公司债券 | Coupon Bonds |
| 普通公司债券 | Ordinary Bonds |
| 收益公司债券 | Income Bonds |
| 名义利率，票面利率 | Nominal rate |
| 实际利率 | Actual rate |
| 有效利率 | Effective rate |
| 溢价 | Premium |
| 折价 | Discount |
| 面值 | Par value |
| 直线法 | Straight-line method |
| 实际利率法 | Effective interest method |
| 到期直接偿付 | Repayment at maturity |
| 提前偿付 | Repayment at advance |
| 偿债基金 | Sinking fund |
| 长期应付票据 | Long-term notes payable |
| 抵押借款 | Mortgage loan |

### 十、业主权益

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 权益 | Equity |
| 业主权益 | Owner's equity |
| 股东权益 | Stockholder's equity |
| 投入资本 | Contributed capital |
| 缴入资本 | Paid-in capital |
| 股本 | Capital stock |
| 资本公积 | Capital surplus |
| 留存收益 | Retained earnings |
| 核定股本 | Authorized capital stock |
| 实收资本 | Issued capital stock |
| 发行在外股本 | Outstanding capital stock |
| 库藏股 | Treasury stock |
| 普通股 | Common stock |
| 优先股 | Preferred stock |
| 累积优先股 | Cumulative preferred stock |
| 非累积优先股 | Noncumulative preferred stock |
| 完全参加优先股 | Fully participating preferred stock |
| 部分参加优先股 | Partially participating preferred stock |
| 非部分参加优先股 | Nonpartially participating preferred stock |
| 现金发行 | Issuance for cash |
| 非现金发行 | Issuance for noncash consideration |
| 股票的合并发行 | Lump-sum sales of stock |
| 发行成本 | Issuance cost |
| 成本法 | Cost method |
| 面值法 | Par value method |
| 捐赠资本 | Donated capital |
| 盈余分配 | Distribution of earnings |
| 股利 | Dividend |
| 股利政策 | Dividend policy |
| 宣布日 | Date of declaration |
| 股权登记日 | Date of record |
| 除息日 | Ex-dividend date |
| 股利支付日 | Date of payment |
| 现金股利 | Cash dividend |
| 股票股利 | Stock dividend |
| 拨款 | appropriation |

### 十一、财务报表

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 财务报表 | Financial Statement |
| 资产负债表 | Balance Sheet |
| 收益表 | Income Statement |
| 账户式 | Account Form |
| 报告式 | Report Form |
| 编制（报表） Prepare |
| 工作底稿 | Worksheet |
| 多步式 | Multi-step |
| 单步式 | Single-step |

### 十二、财务状况变动表

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 财务状况变动表中的现金基础 | SCFP.Cash Basis（现金流量表） |
| 财务状况变动表中的营运资金基础 | SCFP.Working Capital Basis（资金来源与运用表） |
| 营运资金 | Working Capital |
| 全部资源概念 | All-resources concept |
| 直接交换业务 | Direct exchanges |
| 正常营业活动 | Normal operating activities |
| 财务活动 | Financing activities |
| 投资活动 | Investing activities |

### 十三、财务报表分析

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 财务报表分析 | Analysis of financial statements |
| 比较财务报表 | Comparative financial statements |
| 趋势百分比 | Trend percentage |
| 比率 | Ratios |
| 普通股每股收益 | Earnings per share of common stock |
| 股利收益率 | Dividend yield ratio |
| 价益比 | Price-earnings ratio |
| 普通股每股账面价值 | Book value per share of common stock |
| 资本报酬率 | Return on investment |
| 总资产报酬率 | Return on total asset |
| 债券收益率 | Yield rate on bonds |
| 已获利息倍数 | Number of times interest earned |
| 债券比率 | Debt ratio |
| 优先股收益率 | Yield rate on preferred stock |
| 营运资本 | Working Capital |
| 周转 | Turnover |
| 存货周转率 | Inventory turnover |
| 应收账款周转率 | Accounts receivable turnover |
| 流动比率 | Current ratio |
| 速动比率 | Quick ratio |
| 酸性试验比率 | Acid test ratio |

### 十四、合并财务报表

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 合并财务报表 | Consolidated financial statements |
| 吸收合并 | Merger |
| 创立合并 | Consolidation |
| 控股公司 | Parent company |
| 附属公司 | Subsidiary company |
| 少数股权 | Minority interest |
| 权益联营合并 | Pooling of interest |
| 购买合并 | Combination by purchase |
| 权益法 | Equity method |
| 成本法 | Cost method |

### 十五、物价变动中的会计计量

| 中文术语                 | 英文术语                        |
|--------------------------|---------------------------------|
| 物价变动之会计 | Price-level changes accounting |
| 一般物价水平会计 | General price-level accounting |
| 货币购买力会计 | Purchasing-power accounting |
| 统一币值会计 | Constant dollar accounting |
| 历史成本 | Historical cost |
| 现行价值会计 | Current value accounting |
| 现行成本 | Current cost |
| 重置成本 | Replacement cost |
| 物价指数 | Price-level index |
| 国民生产总值物价指数 | Gross national product implicit price deflator (or GNP deflator) |
| 消费物价指数 | Consumer price index (or CPI) |
| 批发物价指数 | Wholesale price index |
| 货币性资产 | Monetary assets |
| 货币性负债 | Monetary liabilities |
| 货币购买力损益 | Purchasing-power gains or losses |
| 资产持有损益 | Holding gains or losses |
| 未实现的资产持有损益 | Unrealized holding gains or losse |

## Important Points in Financial Data

### 1. Introduction of different DATE column

![zny2Ip](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/zny2Ip.png)

* END_DATE represent the accounting period.

* END_DATE_REP is the accounting period which the report is in. For example, the END_DATE_REP of 2016 ANNUAL REPORT is ‘2016-12-31’. 

* PUBLISH_DATE is the publishing date of the report announced in the Stock Exchange, accurate to days.

* ACT_PUBTIME is the specific time (scanned by crawler) of publish, precisely counted by minutes.

* UPDATE_TIME is the latest update time in Datayes, which is a system field.

There is not only the current period data recorded in a financial report, but also previous periods data, which may disclose some adjustments. 

Dealing with this circumstance, we record all the historical data instead of replace history by the latest. 

Therefore, you will find that there are several records with the same END_DATE but different END_DATE_REP or PUBLISH_DATE.

In the following example, the company with PARTY_ID=66732, published a report on 2015-02-06, recording data ended on 2014-09-30. 

In the report, the company disclose some latest information of the previous financial reports, including 2011 Annual Report, 2012 Annual Report and 2014 Q3 report.

![kNeCi6](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/kNeCi6.png)

### 2. Introduction of REPORT_TYPE and FISCAL_PERIOD

![HbybNj](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/HbybNj.png)

REPORT_TYPE and FISCAL_PERIOD are corresponded.

* A- Annual Report, with 12 months’ fiscal period.

* Q1- First Quarterly Report, with 3 months’ fiscal period.

* S1- Semi Annual Report, with 6 months’ fiscal period. 

* S3- Third Quarterly Report, with 9 months’ fiscal period.

### 3. Introduction of MERGED_FLAG

This column is used to distinguish consolidated report and parent company’s report. MERGED_FLAG=1 refers to consolidated report.

### 4. Explanation of dividing industries into separate sheets

Because the main business types of the financial industry are different from the general industry and commerce, and so are the data maintenance methods, the three type of financial statements are divided into four major industries according to the company's business nature, including Banking, Security, Insurance and general business industries.

Players can obtain data according to the nature of the company in their corresponding industry statements.

## 财务数据中的重要点

### 1. 不同 DATE 列的介绍

![zny2Ip](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/zny2Ip.png)

* **END_DATE** 代表会计期末日期。

* **END_DATE_REP** 是报表所在的会计期末日期。例如，2016年年度报告的 **END_DATE_REP** 为 ‘2016-12-31’。

* **PUBLISH_DATE** 是报告在证券交易所发布的日期，精确到天。

* **ACT_PUBTIME** 是报告发布的具体时间（通过爬虫获取），精确到分钟。

* **UPDATE_TIME** 是在 Datayes 系统中的最新更新时间。

财务报告中不仅记录了当前期间的数据，还包括前期数据，这些数据可能会披露一些调整。为了解决这种情况，我们记录所有历史数据，而不是用最新数据替换历史数据。

因此，您会发现有多个记录具有相同的 **END_DATE**，但 **END_DATE_REP** 或 **PUBLISH_DATE** 不同。

例如， PARTY_ID=66732 的公司在 2015-02-06 发布了一份报告，记录了截至 2014-09-30 的数据。在这份报告中，该公司披露了包括 2011 年年度报告、2012 年年度报告和 2014 年第三季度报告的最新信息。

![kNeCi6](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/kNeCi6.png)

### 2. **REPORT_TYPE** 和 **FISCAL_PERIOD** 的介绍

![HbybNj](https://upiclw.oss-cn-beijing.aliyuncs.com/uPic/HbybNj.png)

**REPORT_TYPE** 和 **FISCAL_PERIOD** 是对应的。

* **A** - 年度报告，财务期间为 12 个月。

* **Q1** - 第一季度报告，财务期间为 3 个月。

* **S1** - 半年度报告，财务期间为 6 个月。

* **S3** - 第三季度报告，财务期间为 9 个月。

### 3. **MERGED_FLAG** 的介绍

该列用于区分合并报表和母公司报表。**MERGED_FLAG=1** 表示合并报表。

### 4. 按行业划分成单独表格的解释

由于金融行业的主要业务类型与一般的工业和商业不同，因此数据维护方式也有所不同。根据公司的业务性质，将三类财务报表划分为四大行业，包括银行、证券、保险以及一般商业行业。

用户可以根据公司所属行业在相应的行业报表中获取数据。
