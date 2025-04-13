# Thyroid-Cancer-Risk-predict
该任务为二分类预测任务。原始数据在[data](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/data)，该数据来自[kaggle](https://www.kaggle.com/datasets/ankushpanday1/thyroid-cancer-risk-prediction-dataset)


## 注意事项
需要安装[pytorch](https://pytorch.org/)(建议12.4版本以上)，和相关的机器学习库。
请修改自己的文件路径。

## 数据预处理
[Data preprocess.ipynb](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/edit/main/Data preprocess.ipynb)数据预处理过程，预处理结果保存在[data](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/data)。

若需要降维，请使用[method](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/method)里的AE.ipynb。最后会降成2、4、6维三种，均保存在[data](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/data)，建议选择6维。

AE是一种自编码器，可用于异常值检测和降维，原理见[paper](https://arxiv.org/abs/2201.03898)


## 机器学习、深度学习模型
这些模型可以在[method](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/method)找到，机器学习模型使用随机搜随调整超参数。

深度学习使用了MLP模型，用Adam优化。

## 模型结果保存
模型预测结果均保存在[predict](https://github.com/Yewan-zhu/Thyroid-Cancer-Risk-predict/tree/main/predict),以csv格式保存。
