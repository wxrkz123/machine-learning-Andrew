# 吴恩达机器学习 · Python 实现

Andrew Ng 经典课程 *Machine Learning*（Coursera）的 8 个编程作业，原作业为 MATLAB/Octave，本仓库用 **Python（NumPy / SciPy / Matplotlib / scikit-learn）** 重新实现，并附带课程讲义。

## 作业列表

| 作业 | 主题 | 代码 |
| --- | --- | --- |
| ex1 | 线性回归 | `linear_regression_with_one_variable.py`、`linear_regression_with_multiple_variables.py` |
| ex2 | 逻辑回归 | `logistic_regression.py`、`regularized_logistic_regression.py` |
| ex3 | 多分类与神经网络前向传播 | `Multi_class_Classification.py`、`feedforward_propagation_algorithm.py` |
| ex4 | 神经网络反向传播 | `feedforward.py` |
| ex5 | 偏差与方差 | `bias_vs_variance.py` |
| ex6 | 支持向量机 / 垃圾邮件分类 | `svm.py`、`spam_classifier.py` |
| ex7 | K-means 聚类与 PCA | `k_means_clustering.py`、`image_compression.py`、`PCA.py`、`face_image.py` |
| ex8 | 异常检测与推荐系统 | `anomaly_detection.py`、`recommender_system.py` |

每个作业目录下都有原题 PDF（`exN.pdf`）和所需数据（`.txt` / `.mat`）。

`machine-learning/吴恩达机器学习讲义/` 收录了 Lecture 1–18 的讲义 PDF。

## 环境

```bash
pip install numpy scipy matplotlib scikit-learn nltk
```

> ex6 的垃圾邮件分类用到了 `nltk`（词干提取）。

## 运行

脚本里用相对路径读取数据，请先进入对应作业目录再运行：

```bash
cd machine-learning/ex1_linear_regression
python linear_regression_with_one_variable.py
```

## 说明

- 课程、作业题目、数据与讲义版权归 Andrew Ng / Stanford / Coursera 所有，这里仅用于个人学习。
- 代码为个人练习，欢迎参考与指正。
