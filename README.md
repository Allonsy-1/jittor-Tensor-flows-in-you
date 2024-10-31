# Jittor 挑战赛-热身赛 Conditional GAN
             
## 简介

本项目是厦门大学"Tensor flows in you"队参加第四届计图人工智能挑战赛热身赛时所使用的代码。在数字图片数据集 MNIST 上训练一个将随机噪声和类别标签映射为数字图片的Conditional GAN模型，并生成下方给定用户随机ID对应的数字图片结果。
20250872020311
[result.png](https://www.gitlink.org.cn/Allons_y/jittor/tree/master/result.png)
             
## 安装 
             
本项目可在1张3090上运行，训练时间约为20分钟。

#### 运行环境

- Ubuntu 18.04 LTS
- python >= 3.7
- jittor >= 1.3.0

#### 安装依赖

执行以下命令安装 python 依赖
pip install jittor

## 训练
             
运行以下命令：
python CGAN.py
即可在同一目录下进行训练并生成 result.png

## 致谢
感谢jittor官方提供的[示例代码](https://www.educoder.net/competitions/Jittor-5),基于示例代码填充注释为 TODO 的部分完成了该赛题