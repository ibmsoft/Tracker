# Tracker

![Tracker Screen Shot](http://files.gracecode.com/2012_07_16/1342425568.png)

使用 Android 设备的 GPS 记录轨迹并共享，根据大陆国情，使用百度地图、新浪微博组件
。Tracker 是开放源代码项目，所有的代码可以从[这里获得](https://github.com/feelinglucky/tracker)。


## 下载包

* [GooglePlay Market](https://play.google.com/store/apps/details?id=com.gracecode.tracker)
* [AppChina Market（应用汇）](http://www.appchina.com/soft_detail_325808_0_10.html)


## 编译

项目为标准的 Android 应用，所以您可以使用你喜欢的 IDE (在 Mac 下推荐使用
[IntelliJ IDEA](http://www.jetbrains.com/idea/))打开它。

同时，Tracker 基于以下项目库以及 jar 包，您需要引入

* 友盟统计分析（lib 目录）
* 百度地图 jar 包（lib 目录）
* [Android ActionBar](https://github.com/johannilsson/android-actionbar)
* [Andoird GraphView](https://github.com/jjoe64/GraphView)

代码在 Android SDK 2.2(Level 10)下编译通过。


## 更新记录

### 1.6.0

* 增加速度图表和分享到微博功能
* 增加地图进度条，可显示特定位置的速度和时间
* 调整部分可能导致崩溃的问题

### 1.5.3

* 节省电力，增加存储缓存功能（可能会造成数据总计不及时）
* 调节列表页排序方式
* 部分小细节更改和更新

### 1.5.2

* 根据新浪微博审核要求，更新部分文案和细节

### 1.5

* 新增新浪微博分享
* 调整地图显示精度、增加「开始」和「结束」标示
* 更新地图、友盟组件
* 修复部分 Bug，改进性能

### 1.4

* 改进地图显示，使用抗锯齿

### 1.2

* 增加用户反馈功能
* 调整部分界面细节

### 1.0

* 初始化版本


## FAQ

### 点击「开始」按钮以后，如何停止记录？

长按红色的「停止」按钮即可

### 新浪微博分享功能是否记录用户名和密码？

Tracker 本身不会记录任何用户个人信息。Tracker 的新浪微博分享功能使用友盟组件，
详情请参见： http://dev.umeng.com/doc/document_sh_android.html


## TODO

* 增加百度地图离线地图下载功能
* 导出为 kml 文件
* 小屏幕机型适配
* 更多？您帮我想想？


## 联系方式

* Blog: [http://www.gracecode.com/](http://www.gracecode.com/)
* Twitter: [@feelinglucky](https://twitter.com/feelinglucky)
* 新浪微博: [@手气还不错](http://weibo.com/feelinglucky)

