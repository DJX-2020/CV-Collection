cfg：保存网络结构配置文件的目录
data：保存数据集配置文件的目录（由data.zip解压后调用）
utils：yolov3完整实现及训练验证过程中所必须的一些函数，比如损失计算函数、预测结果绘制函数等
model.py：构建yolov3模型的脚本
train.py：训练yolov3的脚本，包括保存训练好的参数、绘制损失及评价指标曲线等功能
detect.py：训练yolov3的脚本，使用测试例检验训练好的yolo模型的检测效果