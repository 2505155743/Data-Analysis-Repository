<img width="3901" height="2376" alt="608528363-de308470-1144-4431-90ba-b12a78a2980b" src="https://github.com/user-attachments/assets/26441d65-c8c3-4f80-9aed-9638f1644e2a" /># Data-Analysis-Repository
数据分析项目集：RFM用户分群 & 用户流失预警

项目一：电商用户精细化分群与运营策略 (RFM模型)
技术栈：Python (Pandas, NumPy, Matplotlib, Seaborn), RFM模型, 数据可视化

数据来源：UCI Machine Learning Repository - Online Retail Dataset
（原始数据较大，请从 UCI官网 下载）


核心成果：

识别出仅占总数 33% 的“重要价值客户”，贡献了平台 64.2% 的销售额
精准定位到 594 名高价值但 3 个月以上未消费的“重要挽留客户”，设计定向召回方案
发现大额首购后流失的“重要保持客户”，提出首购后复购引导策略
项目文件：

电商用户精细化分群（RFM模型）.ipynb - 完整分析代码
rfm_segments_result.csv - 用户分群结果
RFM_Dashboard.png - 分析仪表盘
RFM Dashboard

项目二：用户流失预警与可解释性运营策略优化
技术栈：Python (Pandas, Scikit-learn, Imbalanced-learn, Matplotlib), 逻辑回归, SMOTE, 特征系数分析, 成本效益模拟

数据来源：Kaggle - Telco Customer Churn
（原始数据请从 Kaggle 下载）

核心成果：

通过 SMOTE 处理 26.5% 类别不平衡，逻辑回归模型 AUC 达 0.833
特征系数分析发现：多服务捆绑（ServiceCount）是最大保护因子，光纤/月付用户为主要流失风险
模拟最优干预策略：仅触达 45% 用户即可挽留 82% 流失者，预计年净收益 £406,092
模型效果： ROC Curve

特征重要性： Feature Coefficients

项目文件：

电信服务商用户流失预警与可解释性运营策略优化.ipynb - 完整分析代码
