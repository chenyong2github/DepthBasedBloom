# DepthBasedBloom
在复杂场景下，当把glow相机的render target跟主相机分开，glow相机便没有了主相机的depth buffer（color buffer和depth buffer组成render target），这样会导致glow相机绘制到了被遮挡的内容......
http://blog.chenyong.me/2017/06/22/glow/

Screenshots:
![](https://raw.githubusercontent.com/chenyong2github/DepthBasedBloom/master/Screenshots/5.jpg)
