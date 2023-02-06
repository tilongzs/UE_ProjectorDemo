# UE_ProjectorDemo
Developed with Unreal Engine 5.1

投影效果图：
![demo](https://github.com/tilongzs/UE_ProjectorDemo/blob/main/demo.png?raw=true)
参考视频教程：https://www.bilibili.com/video/BV1iZ4y1D7nK


基本原理：
1. 三种颜色（RGB）的聚光灯分别投射相应颜色的图像，叠加成图像原始颜色。
2. 在灯光函数中调整UV，从而将聚光灯的圆形光限制在与图像比例（如16:9）相同的矩形区域内。