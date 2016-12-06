# JLChart
A simple Line Chart for iOS.
>Tips:项目里要用,花了点时间写了一下,比较简单粗暴...一拍脑门就出来了...不过显示效果还是蛮好的~~~有些功能未实现,暂时没这个需求...思路可供参考....思路可供参考....

###1.先放图,效果还是满足需求的~~~
![demo1.png](http://upload-images.jianshu.io/upload_images/1631676-1160cc61190ede0c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![demo2.gif](http://upload-images.jianshu.io/upload_images/1631676-52edb6c3903fa79a.gif?imageMogr2/auto-orient/strip)
###2.介绍
####2.1 JLChartPointItem
原始的X/Y数据,以及计算后的X/Y坐标数据
####2.2 JLChartPointSet
JLChartPointItem的点集合,包括点的类型等属性,项目中按需求只有3种,普通点,买入点,调仓点.
####2.3 JLLineChartData
JLChartPointSet的集合,每个JLLineChartData对应一条线,包括线宽,线颜色等属性...有的属性暂时没需求,也就没实现...
###3 第一种是仿余额宝收益走势
####3.1 结构大概这样
![demo1.png](http://upload-images.jianshu.io/upload_images/1631676-5984b258ab1ccb73.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###4 第二种支持多个曲线,支持触摸显示
####4.1 结构大概这样
![demo2.png](http://upload-images.jianshu.io/upload_images/1631676-27760415855354a4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###5 GitHub下载地址:
####[JLChart](https://github.com/JimmyStudio/JLChart.git "Title")
####感兴趣来个star呗
![hhh.gif](http://upload-images.jianshu.io/upload_images/1631676-15ca2eb7e2845614.gif?imageMogr2/auto-orient/strip)
大概就这样,简单粗暴,有改进再更新咯,有问题问问我咯.虽然我也不一定很懂咯
![yooo.jpg](http://upload-images.jianshu.io/upload_images/1631676-b41e9b67103661a6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###6 顺便打个广告,项目叫"来点财",AppStore搜一下咯~
![hhh.gif](http://upload-images.jianshu.io/upload_images/1631676-15ca2eb7e2845614.gif?imageMogr2/auto-orient/strip)
###7 [简书联系](http://www.jianshu.com/p/aa6ff584c594)
###8 LICENSE MIT