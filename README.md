# YOLO系列目标检测模型复现

## 简介
本项目是YOLO的目标检测模型实现，用于VOC2007数据集。

## 项目结构
- `data/`: 存放数据集和标签
- `models/`: 模型定义文件
- `utils/`: 工具函数
- `train.py`: 训练脚本
- `detect.py`: 检测脚本

## 依赖项
- Python 3.8
- PyTorch 1.7

## 安装指南
安装依赖：
pip install -r requirements.txt

## 使用说明
运行检测：
python test.py --save --cuda -m yolov1_r18 --root C:\Users\32725\Desktop\VOCdevkit --weight C:\Users\32725\Desktop\weights\yolov1_r18_voc.pth

## 训练过程


## 评估和结果

