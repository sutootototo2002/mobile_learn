移动端那些事

01课笔记

	1.介绍Emulation是使用：chrome中的一个插件
	
	2.移动端事件：
                ontouchend事件
	            ontouchend事件必须用事件监听的方式写

02课笔记
   
   viewport的写法

    1、移动设备上的viewport就是设备的屏幕上能用来显示我们的网页的那一块区域
    2、利用利用meta标签对viewport进行控制
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
    
    
![](http://i.imgur.com/SbvvDDE.png)

    width:直接去设置具体数值大部分的安卓手机不支持，但ios支持
    user-scalable:是否缩放 （no||yes）
    initial-scale 初始比例
    minimum-scale 允许缩放的最小比例
    maximum-scale 允许缩放的最大比例
    target-densitydpi:
        -dpi_value 70-400
        -device-dpi 设备默认像素
        -high-dpi 高像素密度
        -medium-dpi中等像素密度
        -low-dpi 低像素密度
        -webkit内核已不准备再支持
    