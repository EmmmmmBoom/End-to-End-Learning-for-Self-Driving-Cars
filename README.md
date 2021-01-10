https://github.com/EmmmmmBoom/End-to-End-Learning-for-Self-Driving-Cars

# Nvidia SelfDriving

Keras implementation of [End to End Learning for Self-Driving Cars](https://arxiv.org/pdf/1604.07316.pdf) by Nvidia.

# Network

The network consists of 5 convolution layers (three 5x5 and two 3x3), and 4 fully connected layers on top.

# Howto

To start training run `python train.py`. The data needs to be in the `driving_dataset` folder.

# Project 3 (开放式项目) ：自动驾驶之方向盘操纵

根据汽车前方摄像头捕捉的画面控制汽车方向盘转动的方向和角度是自动驾驶要解决的核心问题. 这一个项目旨在向您介绍如何使用深度神经网络解决回归(Regression)的问题. 不同于分类识别(Classification/Recognition)等场景, 回归(Regression)场景中, 神经网络输出的值是一个连续的值. 通过这个课程的学习, 您还能将学到的深度学习技术用于通过人脸判断人的年龄, 美颜指数等等领域. 在这一个项目里, 您也有机会学习到许多图像增强的技术, 用于提高网络的性能.

Part 1: 图像预处理

Part 2: 数据增强

Part 3: 设计网络结构

训练图像对应的CSV文件git repo中的data文件夹下面
