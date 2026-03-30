# Data Preprocessing — 课程实验 TODO

## 课程日程

| 周次 | 主题 | 备注 |
|------|------|------|
| 第一周 | 绪论 | 介绍课程 |
| 第二周 | 数据治理 | 讲授3学时，1学时翻转（学生讲LDA） |
| 第三周 | 数据预处理 | 实验1周 |
| 第四周 | 分类 | 讲授3学时，1学时翻转（学生讲softmax） |
| 第五周 | 分类 | 实验1周 |
| 第六周 | 集成学习 | 讲授3学时，1学时翻转（学生讲GBDT） |
| 第七周 | 集成学习 | 实验1周 |
| 第八周 | 课堂翻转 | 逻辑回归、岭回归、LASSO、双聚类、麻雀算法、朴素贝叶斯、CART、MCMC |
| 第九周 | 聚类 | 讲授3学时，1学时翻转（学生讲自组织映射） |
| 第十周 | 聚类 | 实验1周 |
| 第十一周 | 群智能 | 讲授3学时，1学时翻转（学生讲蜻蜓算法） |
| 第十二周 | 群智能 | 实验1周 |
| 第十三周 | 强化学习 | 讲授3学时，1学时翻转（学生讲DQN） |
| 第十四周 | 提示学习 | 讲授2学时，2学时实验 |
| 第十五周 | 结课汇报 | 学生讲项目 |

---

# Pipeline 1 - Data Preprocessing

## 1. Spider Experiment (HYR)

- [x] 1.1 Bazhuayu Test (Retrieve specific webpage)
- [ ] 1.2 Introduction of Scrapy (PPT)
- [x] 1.3 Experiment Environment Configuration
  - [x] VS Code (Downloading & Setup & add-ins)
  - [x] Python (Downloading & Setup)
  - [x] Scrapy (pip)
  - [x] Other dependencies (pip)
- [x] 1.4 Scrapy Coding
  - [x] How to start a Scrapy project
  - [x] How to find useful information from webpage (HTML & CSS)
  - [x] How to extract useful information from webpage (Template)
  - [x] How to set up validation webpage (RegEx)
  - [x] How to persistent spider results (Excel)
  - [x] How to run a Scrapy project

## 2. Feature Selection

- [x] 2.1 Experiment Environment Configuration (pip)
- [x] 2.2 Dataset Introduction (iris)
- [x] 2.3 SFFS etc. (2D Scatter chart)
- [x] 2.4 Anova Introduction (2D Scatter chart & Boxplot)
- [x] 2.5 Classification Result Comparison (acc, Training cost, prediction cost of different feature selection and all features)

## 3. Feature Extraction

- [x] 3.1 Experiment Environment Configuration (pip)
- [x] 3.2 Dataset Introduction (iris)
- [x] 3.3 LDA Introduction (Linear Discriminant Analysis, 2D Scatter chart)
- [x] 3.4 PCA Introduction (2D Scatter chart)
- [x] 3.5 Classification Result Comparison (acc, Training cost, prediction cost of different feature extraction and all features)

---

# Pipeline 2 – Classification & Regression

## 4. SVM Experiment (CC)

- [x] 4.1 Brief Introduction of SVM
- [x] 4.2 Brief Introduction of scikit-learn (PPT)
- [x] 4.3 SVM for Classification with cross validation (iris, Decision surface plot)
- [x] 4.4 SVM for Classification with feature selection and extraction (iris, Decision surface plot)
- [x] 4.5 SVM with different kernels and grid searching
- [x] 4.6 SVR for Regression (California housing, scatter curve plot)
- [x] 4.7* Explore SVR with feature selection, feature extraction, different kernels and grid searching (California housing)

## 5. ANN Experiment (DXD)

- [x] 5.1 Brief Introduction of ANN with sklearn
- [x] 5.2 ANN for Classification with cross validation (iris, ROC curve plot)
- [x] 5.3 ANN for Classification with feature selection and extraction (iris, ROC curve plot)
- [x] 5.4 ANN with different Activation Functions, output layers and learning models
- [x] 5.5 ANN for Regression (California housing, scatter curve plot)
- [x] 5.6* Explore ANN with feature selection, feature extraction, different Activation Functions, output layers and learning models (California housing)

---

# Pipeline 3 – Ensemble Learning

## 6. Random Forest Experiment (CC)

- [ ] 6.1 Brief Introduction of RF (main idea & parameters)
- [ ] 6.2 RF for Classification with cross validation (iris, Decision surface plot)
- [ ] 6.3 List the most important top-10 features by RF and introduce the selection strategy
- [ ] 6.4 RF for Regression (California housing, scatter curve plot)
- [ ] 6.5* Explore RF with different parameters (California housing, scatter curve plot)

## 7. XGBoost Experiment (ZJC)

- [ ] 7.1 Brief Introduction of XGBoost (main idea & parameters)
- [ ] 7.2 XGBoost for Classification with cross validation (iris, ROC curve plot)
- [ ] 7.3 List the top-10 features by XGBoost and introduce the selection strategy
- [ ] 7.4 XGBoost for Regression (California housing, scatter curve plot)
- [ ] 7.5* Explore XGBoost with different parameters (California housing, scatter curve plot)

## 8. Kaggle Experiment (DXD)

- [ ] 8.1 Brief Introduction of Kaggle
- [ ] 8.2 How to Register a team on Kaggle
- [ ] 8.3 How to use the dataset from Kaggle
- [ ] 8.4 How to submit Ur Results or Codes to Kaggle
- [ ] 8.5 How to check Ur rank

---

# Pipeline 4 – Clustering

## 9. K-means Clustering Experiment (ZJC)

- [ ] 9.1 Brief Introduction of K-means (main idea & parameters)
- [ ] 9.2 K-means for clustering with visualization (iris, scatter plot by PCA each iter, mark the center)
- [ ] 9.3 Explore K-means with different parameters (K, iters, assessed by DBI)

## 10. Affinity Propagation Clustering Experiment (ZJC)

- [ ] 10.1 Brief Introduction of AP (main idea & parameters)
- [ ] 10.2 AP for clustering with visualization (iris, scatter plot by t-SNE each iter, mark the center)
- [ ] 10.3 Explore AP with different parameters (p, iters, assessed by DBI with KM)

## 11. DBSCAN Experiment (LSH)

- [ ] 11.1 Brief Introduction of DBSCAN (main idea & parameters)
- [ ] 11.2 DBSCAN for clustering with visualization (iris, scatter plot by PCA, mark the core)
- [ ] 11.3 Explore DBSCAN with different parameters (min_samples and eps, assessed by DBI with KM)

## 12. Agglomerative Clustering Experiment (WH)

- [ ] 12.1 Brief Introduction of Agglomerative (main idea & parameters)
- [ ] 12.2 Agglomerative for clustering with visualization (iris, tree plot by t-SNE each iter)
- [ ] 12.3 Explore Agglomerative with different parameters (linkage, assessed by DBI with KM)

---

# Pipeline 5 – Optimization

## 13. Particle Swarm Optimization Experiment (CC)

- [ ] 13.1 Brief Introduction of PSO (main idea & parameters)
- [ ] 13.2 PSO for House price prediction with feature selection & parameter optimization (curve plot each iter, compare results before optimization)
- [ ] 13.3 Explore PSO with different parameters (iters, weights)

## 14. Genetic Algorithm Experiment (CC & HYR)

- [ ] 14.1 Brief Introduction of GA (main idea & parameters)
- [ ] 14.2 GA for House price prediction with feature selection & parameter optimization (curve plot each iter, compare results before optimization and PSO)
- [ ] 14.3 GA for TSP (curve plot each iter, visualization of best solution)
- [ ] 14.4 Explore GA with different parameters (iters, different selector, crossover)

## 15. PPO Experiment (ZJC)

- [ ] 15.1 Brief Introduction of Reinforcement Learning and PPO (main idea & parameters)
- [ ] 15.2 PPO for TSP (curve plot each iter, visualization of best solution, comparison with GA)
- [ ] 15.3 Explore PPO with different parameters

---

## 实验文件索引

| 文件 | Pipeline | 状态 |
|------|----------|------|
| `01_spider.ipynb` | Pipeline 1 | ✅ 完成 |
| `02_feature_selection.ipynb` | Pipeline 1 | ✅ 完成 |
| `03_feature_extraction.ipynb` | Pipeline 1 | ✅ 完成 |
| `04_svm.ipynb` | Pipeline 2 | ✅ 完成 |
| `05_ann.ipynb` | Pipeline 2 | ✅ 完成 |
| `06_random_forest.ipynb` | Pipeline 3 | 待开发 |
| `07_xgboost.ipynb` | Pipeline 3 | 待开发 |
| `08_kaggle.ipynb` | Pipeline 3 | 待开发 |
| `09_kmeans.ipynb` | Pipeline 4 | 待开发 |
| `10_ap.ipynb` | Pipeline 4 | 待开发 |
| `11_dbscan.ipynb` | Pipeline 4 | 待开发 |
| `12_agglomerative.ipynb` | Pipeline 4 | 待开发 |
| `13_pso.ipynb` | Pipeline 5 | 待开发 |
| `14_ga.ipynb` | Pipeline 5 | 待开发 |
| `15_ppo.ipynb` | Pipeline 5 | 待开发 |