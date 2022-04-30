# MachineLearning
Projects implementing Machine Learning methods.

# 信用卡欺诈异常检测
------
使用scipy统计工具，计算数据的概率密度函数；通过交叉验证和F1值找到最佳阈值

通过训练有监督模型，孤立森林（Isolation Forest），预测数据是否异常

# 银行客户流失预测
-----
使用Python预测银行用户流失概率；进行数据清洗、分类特征转换、数据标准化；

训练有监督模型（随机森林、K近邻、逻辑回归）；调节超参数优化模型；

通过k-fold交叉验证评估模型性能（accuracy、precision、recall、ROC、AUC）

分析特征重要性找出最有影响力的特征

# 泰坦尼克存活预测、红酒质量预测
---
用集成学习（Bagging），线性判别分析（LDA），支持向量机（SVM）预测泰坦尼克存活率；

使用R语言进行数据预处理：用称号的中位数填充年龄缺失值等；调节各个模型的参数找到有最佳效果的模型；

用回归方法（Ridge Regression、Lasso Regression、Elastic Net Regression）、回归树、主成分分析（PCA）、KMeans聚类预测红酒质量；根据均方误差评估回归模型；

# 自然语言处理：手表用户评论分析
---
用Python将用户评论分类以挖掘潜在语义；通过分词、保留词根、移除低语义词处理文本文件；运用TF-IDF做特征筛选；

使用无监督机器学习方法（KMeans聚类、层次聚类、LDA）训练模型；调节参数，根据分类识别主题与关键词；

# 美国P2P平台LendingClub贷款违约预测
-----
进行数据清洗、分类特征转换、数据标准化；

训练有监督模型（随机森林、K近邻、逻辑回归）；调节超参数优化模型；

通过k-fold交叉验证评估模型性能（accuracy、precision、recall、ROC、AUC）

分析特征重要性找出最有影响力的特征
