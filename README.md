# FAST 流媒体应用原型设计
## 功能分析

作为一个基于FAST(free ad-supported streaming television，免费广告支持的流媒体电视)的应用，类似Pluto TV，主要功能应包括：

* 1.直播频道浏览和观看
* 2.点播内容库
* 3.个性化推荐
* 4.节目表/指南
* 5.搜索功能
* 6.用户账户管理

特殊说明：直播频道不止包括电视台的直播频道，更重要的是根据分类内容整合的轮播频道，比如喜剧电影会一直播放喜剧电影。用户像看电视一样，不能操作快进，只能看当前播放的内容。

## 界面规划

基于上述功能，我们需要设计以下界面： 

* 1.启动/欢迎页
* 2.主页（有banner广告位）
* 3.直播频道页（直接播放推荐的频道）
* 4.点播内容页
* 5.内容详情页
* 6.全屏播放页（横屏时）
* 7.搜索页面(支持搜索直播频道的名称，节目以及点播内容的名称，演员，类型等)
* 8.个人中心页

## 交互设计

### 1.启动/欢迎页

* 显示FAST的Logo
* 短暂停留后自动进入主页

### 2.主页/发现页

* 顶部导航栏
* 轮播图/广告位
* 频道分类/推荐内容
* 搜索框
* 底部导航栏

### 3.直播频道页

* 顶部播放窗（固定）
* 有时间进度条的频道列表
* 底部导航栏

### 4.点播内容页

* 顶部导航栏
* 按类型展示内容海报
* 底部导航栏

### 5.内容详情页

* 顶部播放窗（固定）
* 展示该影片的介绍、选集信息和相关影片推荐
* 底部导航栏

### 6.搜索页

* 支持直播频道名称、当前直播节目的搜索
* 支持点播内容的搜索
* 搜索结果有相应角标告诉用户是【直播】还是【点播】
