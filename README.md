# DeepLearning
This is a repository for me to learn deep learning.

## PCBDetectionBasedOnYOLOv8
这是一个关于PCB缺陷检测的检测系统，history用于存储检测历史(格式为json)，model用于存储模型权重文件(.bt)，ui用于存储主程序和ui文件
基于基础YOLOv8，在主干网络嵌入CBAM注意力，颈部网络嵌入CA注意力机制，在map50评分上高于基础模型平均5个百分点
采用技术：OpenCV, YOLOv8, CBAM, Coordinate Attn, PyTorch
运行需要YOLOv8官网代码包环境支持(环境安装: pip install ultralytics )
主程序入口: PCBDetectionSystem/ui/main.py
