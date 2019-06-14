[ESPNet: Efficient Spatial Pyramid of Dilated Convolutions for Semantic Segmentation](https://arxiv.org/pdf/1803.06815.pdf)
-  
本文提出了一个新的模块efﬁcient spatial pyramid (ESP).它把标准卷积分为2步，1. pointwise convolution点卷积->减少计算量，将高维特征映射到低维特征；2.spatial pyramid of dilated convolutions->增大感受野，因为融合了不同大小的感受野，又称pyramid
  
![](https://github.com/renchenliang/daily-paper-computer-vision/blob/master/light-weight/image/QQ%E5%9B%BE%E7%89%8720190614154357.png)


[ESPNetv2: A Light-weight, Power Efficient, and General Purpose Convolutional Neural Network](https://arxiv.org/abs/1811.11431)
-
  [github代码](https://github.com/sacmehta/ESPNetv2) <br>
   -
   本文在ESPNetv1网络的基础上，进一步提升了性能。ESPNetv2性能超过ESPNetv1 4%，少2-4倍的FLOPS。目前轻量级网络的设计方法主要分为以下几类：1、模型压2、量化  3、轻量级网络的设计
    ESPNetv2重点：
    1. Depth-wise dilated separable convolution
    ![](https://github.com/renchenliang/daily-paper-computer-vision/blob/master/light-weight/image/QQ%E5%9B%BE%E7%89%8720190614140458.png)
