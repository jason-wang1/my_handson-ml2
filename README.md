# my_handson-ml2
本项目是《机器学习实战：基于Scikit-Learn、Keras和TensorFlow（原书第二版）》的配套项目代码

## 环境要求
* python 3.8
* jupyter 1.0.0
* matplotlib 3.4.3
* pandas 1.3.3
* scipy 1.7.1
* scikit-learn 0.24.2

## 章节
- [02_end_to_end_machine_learning_project.ipynb](https://github.com/jason-wang1/my_handson-ml2/blob/master/02_end_to_end_machine_learning_project.ipynb)
    - 构造回归模型预测加州不同区域房价的中位数
    - 数据探索与统计、数据可视化、特征选择（相关性分析）、缺失值处理、特征转换pipeline、模型选择（线性回归、决策树、随机森林）
    
- [03_classification.ipynb](https://github.com/jason-wang1/my_handson-ml2/blob/master/03_classification.ipynb)
    - 构造分类模型对手写数字图片进行分类
    - 二分类模型预测5与非5：SGDClassifier、RandomForest
    - 评估指标（准确率、混淆矩阵、精确率、召回率、F1score、分类阈值、ROC、AUC）
    - 多分类模型预测0~9：SVM、SGDClassifier
    - 混淆矩阵进行误差分析并改进模型