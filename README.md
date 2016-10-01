# **东南大学选课助手1.0测试版**

***本软件仅供辅助选课使用，严禁任何商业用途***



本软件的使用姿势

A.直接下载jwc-catcher压缩包，执行里面的应用程序（推荐）

B.下载源代码，放到Python环境下运行（需要PIL模块）



### 本软件能做什么？

##### 1.同时值守多门不同类别的课程

##### 2.一键抢所有服从推荐/任意人文/自然/经管通选

##### 3.在正常和非常时查看任意学期课表



### 本软件的优点？

##### 1.小巧精悍，易于使用和二次开发。

##### 2.每门值守课程都拥有单独的线程，刷课速度很快。

##### 3.丑陋但简单明了的UI界面



### 本软件的缺点？

##### 1.开发周期太短，未充分测试，代码结构尚可优化

##### 2.由于请求频率高，对网速依赖性较大

##### 3.开发者已没有体育课，故未开发体育课程的选择



UI功能说明：

![图片](http://obdvl7z18.bkt.clouddn.com/image/jwc/01.jpg)

红区：功能按钮——所有可用功能的入口集合

蓝区：可选课程列表——列出所有可选课程（为了防止用户误退课，已选择的院系服从推荐课程、院系统一安排课程不会显示）

绿区：值守课程状态池——输出正在请求的课程及其详细状态



效果预览图（忘记截图，只找到这么一张了）

![图片](http://obdvl7z18.bkt.clouddn.com/image/jwc/03.png)



### 使用说明

1.**自己的浏览器和本软件可以都打开选课系统**，不会出现冲突
2.你的网络越快，软件的反应就越快，请求频率会越高，seu有线是最好的，电信有线宽带次之，较强的seu无线又次之，尽量不要在教学楼选课。

3.本软件最适场景是某门或某几门课程的长期值守。

4.软件的基本运行方式：
进入后能看到自己还未选上的服从推荐和所有的人文自然经管seminar跨院系，点击某一门课后，点【开始选择】进行刷课，遇到冲突的时候该门课会自动停止刷（这时可以用浏览器打开选课系统退掉冲突的课），不冲突的课程会一直刷到成功选上为止。

**红区功能的说明：**
【一键抢院系内所有服从推荐】**只适合什么课都没选时的情况**，效果相当于对每个院系课都点了【开始所选】。这个按钮**使用的时候要注意**，因为**用这个按钮选中的课程蓝区不会提示**，选完之后要用浏览器打开选课系统看看选上了哪些。


【一键抢人文/自然/经管】刷到的结果是随机的。对于这些通选课最好守着几门自己喜欢的来刷。不管是否已经选上了，都可以刷，所以可以先选一门不喜欢的，然后去刷喜欢的。


【停止所选】选中你正在刷的某门课，再点击这个按钮，就会停止刷该门课。


【停止所有】停止所有正在刷的课，如果网络卡了或者程序卡了，这个按钮很有用。



【查看课表】用于查看某个学期的课表，在教务处不提供课表查询页面时这个功能也可以使用。



【关于】关于本软件的一些信息。



*tips*

*在任何界面发现软件无响应，可以结束程序重新开，不会产生不良影响*

*本软件不支持绕过系统代理，如果你没看懂，只要记住用时不要开翻墙工具*





**TODO**

优化代码结构，补齐测试，修bug，从用户使用软件的流程上完善本软件，美化界面，增强健壮性降低APP CRASH的概率等等等等

如果你感兴趣，欢迎发起PullRequest，也可以在MIT协议下去修改



### **很惭愧，就做了一点微小的工作，谢谢大家！**