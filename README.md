# iOS室内地图导航（可直接商用）

# 说明
这个是从我们自己的App（影秀城）中剥离出来的成熟模块。App上线至今一年多，开发团队开始考虑代码重构。模块化、组件化是重构的一部分，导航模块的剥离就属于其中的一个模块。

# 关于室内导航哪些事
从方案开始自己做是不现实的，所有我们找到方案方-北京智慧图。事实上，国内能提供商业化的室内导航方案就那么几家，没什么选择余地。
我们选择智慧图有两个原因：报价便宜，而且答应提供UI模块。我们想象的UI模块就是那种不要自己开发拿来就可以用的。可是最后拿到手的UI实在是。。。但毕竟价格还是便宜，所有撸起袖子自己干吧。（后期和智慧图的合作还是很顺畅，执行效率很高。）
设计产品的时候参考了喵街和万达的飞凡App。开始写代码时候发现这块功能的工作量完全赶得上写一款工具型App，而且人机交互点非常很多。Just Enjoy！

# 视频Demo
https://github.com/smallhorse87/indoormap/blob/master/1546053802910500.mp4

# 功能
- 实时室内定位，室内地图，实时导航，语音提示
- 地图上点击选择目的，搜索选择目的地
- 记录历史目的地
- 记录常用目的地
- 实时监测蓝牙是否打开

# 特性

- 全面功能实现，直接集成就可以使用。
- 手动代码布局，集成方便。
- 适配刘海屏幕
- 支持iOS9以上
- 使用MVVM架构

# 使用向导
- 工程设置中，Enable Bitcode：NO。
- 参考样例工程，添加必要的frameworks。
- 参考样例工程，在plist中添加权限：定位，蓝牙。
- 参考样例工程，配置https。
- 参考样例工程，初始化模块。


# TODO
1. 以喵街App为参考，不断优化体验。
2. 通过cocoapod集成。制作pod过程中，发现某个静态文件上传不了，所以暂时搁置了。

# 遇到问题或寻求合作
- 我们的官网：http://www.inshowcity.com/
- QQ：164790906
- 邮箱：smallhorse87@163.com
