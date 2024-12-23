# Wine Quality Data 

## 文档

### 葡萄酒质量数据集（Wine Quality Dataset）

这是一个用于分析和预测**葡萄酒质量**的数据集，基于化学属性和感官数据来预测葡萄酒的评分。该数据集由 Cortez 等人在 2009 年提出，用于研究化学成分对葡萄酒质量的影响。

---

### 数据集的特点

#### 1. 输入变量
数据集中有 11 个输入变量，代表通过物理和化学测试测量的葡萄酒特性：

- **fixed acidity（固定酸度）**：葡萄酒中无法蒸发的酸，如酒石酸。
- **volatile acidity（挥发性酸度）**：易挥发酸的含量，如乙酸；高含量会导致醋味。
- **citric acid（柠檬酸）**：微量增加新鲜感。
- **residual sugar（残余糖分）**：发酵后剩余的糖分，影响甜度。
- **chlorides（氯化物）**：葡萄酒中的盐分含量。
- **free sulfur dioxide（游离二氧化硫）**：对微生物的抗性和抗氧化性。
- **total sulfur dioxide（总二氧化硫）**：包括结合态和游离态二氧化硫。
- **density（密度）**：与酒精含量和糖分有关。
- **pH**：酸碱度，影响味道平衡。
- **sulphates（硫酸盐）**：增加葡萄酒的防腐性。
- **alcohol（酒精含量）**：对感官影响显著。

#### 2. 输出变量
- **quality（质量）**：根据感官评分（通常由品酒师评估），得分在 0 到 10 之间，表示葡萄酒的整体质量。

---

### 用途

该数据集常用于机器学习任务：
- **回归分析**：预测质量得分。
- **分类分析**：将质量分为不同等级（如好酒、差酒）。
- **特征选择**：找出最影响质量的化学成分。

---

### 相关研究背景

Cortez 等人在论文《Modeling wine preferences by data mining from physicochemical properties》中，利用机器学习方法（如决策树、SVM、神经网络）分析了葡萄酒的质量，并验证了化学特性对感官评分的相关性。

---

### 总结

这个数据集是一种经典的多维数据集，适合新手用于学习数据科学和机器学习的各类算法。


### 简介 (Introduction)

该数据来自UCI Machine Learning Repository https://archive.ics.uci.edu/ml/datasets/wine+quality  
其中包含红葡萄酒和白葡萄酒的数据sample.

### 来源 (Source)

Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez  
A. Cerdeira, F. Almeida, T. Matos and J. Reis, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal  
@2009

### 字段信息 (Attribute Info)

For more information, read [Cortez et al., 2009].  
Input variables (based on physicochemical tests):

* fixed acidity
* volatile acidity
* citric acid
* residual sugar
* chlorides
* free sulfur dioxide
* total sulfur dioxide
* density
* pH
* sulphates
* alcohol  
  Output variable (based on sensory data):  
  12 - quality (score between 0 and 10)

### 参考文献 (Relevant Papers)

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties.  
In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

### 引用要求 (Citation Request)

Please include this citation if you plan to use this database:  
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.  
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.