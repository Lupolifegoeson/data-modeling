# 机器学习常用模型
## 关联性分析
### Apriori算法
关联分析中最基本的算法（然而已被淘汰），发现数据集中各个数据项的关联程度。
### FP-growth算法
frequent pattern算法，同样是查找频繁项集，但是比Apriori更快。
## 分类
### 朴素贝叶斯分类器
朴素贝叶斯分类器的基本假设是：样本向量中各个元素相互独立。
该方法是文本分类中的一个基本方法。
### 决策树
用于离散数据分类的决策树
### KNN
异常简单的KNN实现。
### Logistic Regression
逻辑回归分类器，利用特征之间的线性关系和sigmoid函数对输入数据进行二分类。
### sklearnSVM
python sklearn机器学习库中对SVM的API
### SVM
线性SVM分类器，运用简单的SMO算法进行加速。
## 聚类
### K-means聚类
通过自定义的K-means算法，对鸢尾花数据集进行聚类，并将真实标签与聚类标签对比，结果表明聚类效果良好。
## 时间序列
## 异常点监测
## 聚合
### adaboost
boosting聚合方法的代表之一：AdaBoost（自适应Boost）
通过调整样本权重和子分类器预测权重来聚合
### bagging聚合代表——随机森林
随机森林解决连续性数据集的分类问题。
## 回归
### CART
Classification and Regression Tree 分类回归树
### 线性回归
逐步线性回归
