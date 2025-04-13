# Thyroid-Cancer-Risk-predict
原始数据在[data](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/data)，该数据来自[kaggle](https://www.kaggle.com/datasets/ankushpanday1/thyroid-cancer-risk-prediction-dataset)


## 需要的库
需要安装[pytorch](https://pytorch.org/)(建议12.4版本以上)，和相关的机器学习库。

## 数据预处理
Data preprocess数据预处理过程，预处理结果保存在[data](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/data)。

若需要降维，请使用[method](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/method)里的AE.ipynb。最后会降成2、4、6维三种，均保存在[data](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/data)，建议选择6维。

AE是一种自编码器，原理见[paper](https://arxiv.org/abs/2201.03898)


## 机器学习模型
