# Industrial_Steam_Prediction
机器学习实战项目一：工业蒸汽量预测

现阶段实现基本的特征工程、模型训练
* 特征工程：统一训练集与测试集的分布，根据相关性删除特征
* 模型训练：分别使用xgboost算法、GBDT回归算法、随机森林算法、贝叶斯线性回归法、LightGBM回归算法、决策树回归算法、Lasso回归算法进行训练，并用交叉验证方法验证误差
* 最后测得mse=0.1418

更新时间：2023.1.8 23:37

现阶段实现程度：
* 特征工程：删除分布差异较大属性、Lasso嵌入法选择特征、利用相关性删除特征、PCA降维（效果不好）
* 数据处理：z-score归一化处理（效果不好）、线性归一化处理（效果不好）
* 模型训练：分别使用xgboost算法、GBDT回归算法、随机森林算法、贝叶斯线性回归法、LightGBM回归算法、决策树回归算法、Lasso回归算法进行训练，并用交叉验证方法验证误差
* 模型融合：按不同权重进行融合
* 最后测得mse=0.1412

更新时间：2023.1.10 1:15

现阶段实现程度：
* 数据处理：异常值处理，查看数据分布图，可视化线性回归情况，归一化数据
* 特征工程：删除分布不一致特征，删除相关性较小特征
* 模型训练：xgboost算法、GBDT回归算法、随机森林算法、贝叶斯线性回归法、LightGBM回归算法、决策树回归算法、Lasso回归算法进行训练，并用交叉验证方法验证误差
* 模型融合：按不同权重融合
* 最后测得mse=0.1365

更新时间：2023.1.11 13:01
