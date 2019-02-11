# stock_img_clf
CNN、随机森林应用于股票四种形态A形（先涨后跌），U形（先跌后涨），R形（上涨），D形（下跌）的识别，基于keras，后端为tensorflow。准确率为96%左右。
cnn_hyper.py 为超参数优化；someplots.py为cnn层输、通道、热力图可视化等；vectorization.py为数据预处理；random_forest.py为cnn特征提取，拟合随机森林分类器。

