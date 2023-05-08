# Jittor 手写数字生成 Conditional GAN
![image-20230507210441008](result.png)

## 简介
| 简单介绍项目背景、项目特点

本项目包含了第三届计图挑战赛计图 - 手写数字生成的代码实现。本项目的特点是：通过Embedding对标签进行编码整合到图像数据中进行训练，达到生成对应标签的数字图片。

## 安装 
| 介绍基本的硬件需求、运行环境、依赖安装方法

本项目可在 2 张 2080 上运行，训练时间约为 2 小时。

#### 运行环境
- ubuntu 20.04 LTS
- python >= 3.7
- jittor >= 1.3.0

#### 下载数据集
下载地址：http://yann.lecun.com/exdb/mnist

将下载的数据直接放到`<root>/mnist_data ` 中无需解压。

## 训练
直接运行CGAN.py中的函数train()
## 推理
更改test中的number，运行函数test()
