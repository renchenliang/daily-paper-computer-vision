
[Joint Face Detection and Facial Motion Retargeting for Multiple Faces](https://arxiv.org/abs/1902.10744)
-
![image](https://github.com/renchenliang/daily-paper-computer-vision/blob/master/face%20recognition/image/QQ%E5%9B%BE%E7%89%8720190612152651.png)
  该文提出一个轻量级网络生成68landmark，并可以进行2d Alighment与3d Alighment。实验结果：人脸检测时间：34ms; Single face network(SFN)时间为15ms. 即1张人脸为49ms，5个人脸为109ms，10个人脸为184ms。  Mutiple face network(MFN)在任意多的人脸为39ms。

[Joint 3D Face Reconstruction and Dense Alignment with Position Map Regression Network](https://arxiv.org/abs/1803.07835)
-
[github](https://github.com/YadiraF/PRNet)
-
本文主要是从一幅二维脸部图像进行脸部三维重构以及dense alignment. 运行时间为100fps
![](https://github.com/renchenliang/daily-paper-computer-vision/blob/master/face%20recognition/image/QQ%E5%9B%BE%E7%89%8720190615174941.png)

[ArcFace: Additive Angular Margin Loss for Deep Face Recognition](https://arxiv.org/abs/1801.07698)
-
[github](https://github.com/deepinsight/insightface)
-
  本文在multiplicative angular margin cos(m)与additive cosine margin(cos   m)的基础上，提出了更有分辨力的additive angular margin (ArcFace，cos( + m)) 
  人脸识别的精度的提高从高到低主要取决于3个方面：数据量、网络结构、损失函数。

![softmax](https://github.com/renchenliang/daily-paper-computer-vision/blob/master/face%20recognition/image/softmax.png)
softmax是将一串数值转化为0-1概率，经过e的放大之后，使得原来大的数更大，小的更小，从而得出概率最大的一类。

![](https://github.com/renchenliang/daily-paper-computer-vision/blob/master/face%20recognition/image/Augular-softmax-loss.png)
在softmax损失基础上，另|W|=1，b=0,得到Augular-softmax-loss。
