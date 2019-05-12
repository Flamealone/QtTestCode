# 摄像头获取图像出现镜像现象
可通过函数
```c++
QImage QImage::mirrored(bool horizontal = ..., bool vertical = ...) 
```
进行转换，该函数返回图像的镜像，镜像的水平和垂直方向取决于horizontal,vertical两个参数是否设置为true/false;
