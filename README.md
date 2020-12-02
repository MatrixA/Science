## Welcome to My Science Board
This board is recording my research progress of underwater SLAM, including papers I read, projects I run and plans I made.

### Papers
I think there are three types of papers. Following papers are all about SLAM.
1. Review


2. Method
* [施小成, 和王晓娟. 《一种面向AUV水下对接的双目视觉测距方法》. 计算机测量与控制, 期 10 (2008年): 1460-1462+1488.](#一种面向AUV水下对接的双目视觉测距方法)
* [张勋, 肖遥和李凡贡. 《基于测距声纳与光视觉的水下目标定位方法研究》. 船舶工程 38, 期 05 (2016年): 74–78.](#基于测距声纳与光视觉的水下目标定位方法研究)


3. Application

### Projects
I will run some SLAM demo on Github. In order to realize docking, I will create my own system.
1. SLAM

2. Object Detection


2020-11-29 A BERT model for classify style of 5 writers'(LuXun,WangXiaobo,QianZhongshu,Moyan,ZhangAiling) article. 97% accuracy.

### Plans
Before 2021, I think 50 abstracts are needed at least.
In addition, I should design a method to dock efficiently.

### Ref
Datasets:KITTI etc.

### Tools
* Roam Research
* Zotero
* 印象笔记

[ThisSite](https://matrixa.github.io/Science/)

# Main
## 一种面向AUV水下对接的双目视觉测距方法
提出了改进的NCC方法，采用了图像金字塔、纹理控制和视差控制改进了传统NCC方法的时间性能，双向匹配保证精度。模拟实验证明有一定效果，但未进行水试。
可学习的点主要有对接驳的特性应用、图像金字塔、算法性能的实用分析对比。

## 基于测距声纳与光视觉的水下目标定位方法研究
用两个声纳和一个光学相机完成测距。通过测距声纳计算得到目标中心的位置，然后在视觉图像上标记出来并提取边缘角点，最后算出目标长宽以及中心位置。
可学习的点主要有传统图像处理(顶帽变换)、传感器布设与结合、几何分析。
[返回board](#papers)
