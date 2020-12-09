## Welcome to My Science Board
This board is recording my research progress of underwater SLAM, including papers I read, projects I run and plans I made.

### Papers
I think there are three types of papers. Following papers are all about SLAM.
1. Review
* [Hidalgo, Franco, 和Thomas Bräunl. 《Review of underwater SLAM techniques》. 收入 2015 6th International Conference on Automation, Robotics and Applications (ICARA), 306–311. IEEE, 2015.](#Review-of-underwater-SLAM-techniques)||16
* [Cadena, Cesar, Luca Carlone, Henry Carrillo, Yasir Latif, Davide Scaramuzza, José Neira, Ian Reid和John J. Leonard. 《Past, present, and future of simultaneous localization and mapping: Toward the robust-perception age》. IEEE Transactions on robotics 32, 期 6 (2016年): 1309–1332.](#past-present-and-future-of-simultaneous-localization-and-mapping-toward-the-robust-perception-age)||1438

2. Method
* [施小成, 和王晓娟. 《一种面向AUV水下对接的双目视觉测距方法》. 计算机测量与控制, 期 10 (2008年): 1460-1462+1488.](#一种面向AUV水下对接的双目视觉测距方法)
* [张勋, 肖遥和李凡贡. 《基于测距声纳与光视觉的水下目标定位方法研究》. 船舶工程 38, 期 05 (2016年): 74–78.](#基于测距声纳与光视觉的水下目标定位方法研究)
* [Mallios, Angelos, Pere Ridao, David Ribas和Emili Hernández. 《Scan matching SLAM in underwater environments》. Autonomous Robots 36, 期 3 (2014年): 181–198.](#Scan-matching-SLAM-in-underwater-environments)||63
* [Roznere, Monika, 和Alberto Quattrini Li. 《Underwater-Monocular-Image-Depth-Estimation-using-Single-beam-Echosounder》, 不详.](#)



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
Datasets:[UDID](http://vision.is.tohoku.ac.jp/~liushuang/a-vision-based-underwater-docking-system/dataset/UDID_datasets.zip)  
KITTI etc.

### Tools
* Roam Research
* Zotero
* 印象笔记

[ThisSite](https://matrixa.github.io/Science/)

# Main
## 一种面向AUV水下对接的双目视觉测距方法
提出了改进的NCC方法，采用了图像金字塔、纹理控制和视差控制改进了传统NCC方法的时间性能，双向匹配保证精度。模拟实验证明有一定效果，但未进行水试。  
可学习的点主要有对接驳的特性应用、图像金字塔、算法性能的实用分析对比。  
[返回board](#papers)
## 基于测距声纳与光视觉的水下目标定位方法研究
用两个声纳和一个光学相机完成测距。通过测距声纳计算得到目标中心的位置，然后在视觉图像上标记出来并提取边缘角点，最后算出目标长宽以及中心位置。  
可学习的点主要有传统图像处理(顶帽变换)、传感器布设与结合、几何分析。  
[返回board](#papers)
## Review of underwater SLAM techniques
This paper presents a review of the approaches used in state-of-the-art SLAM techniques:Extented Kalman Filters SLAM(EKF-SLAM), FastSLAM, GraphSLAM and its application in underwater environments.  
[返回board](#papers)
## Past, present, and future of simultaneous localization and mapping: Toward the robust-perception age
We survey the current state of SLAM and consider future directions.  
[返回board](#papers)
## Scan matching SLAM in underwater envirionments
This paper proposes a pose-based algorithm to solve the full simutaneously localization and mapping problem for AUVs in unknown and possibaly unstructured environments.  
[返回board](#papers)
## Underwater Monocular Image Depth Estimation using Single-beam Echosounder
论文的主要贡献在于提供了标定声纳测深仪和相机的标定方法，并且用于校正单目相机的深度估计，这一方法还能用于颜色校正。
可学习的点主要在于相机和深度仪融合的方式：最小化测量值与估计值的误差来获得位姿，再计算校正后的深度。
[返回board](#papers)
