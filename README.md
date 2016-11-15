# AwesomeTools

``` 
牛逼工具集 
```

## PHP
> 世界上最好的语言

### 工具类

#### [Composer](https://getcomposer.org) | [快速开始](https://getcomposer.org/doc/00-intro.md) | [国内镜像](http://pkg.phpcomposer.com)
> Composer 是 PHP 的一个依赖管理工具。它允许你申明项目所依赖的代码库，它会在你的项目中为你安装他们。

### 框架类
#### [Laravel](https://laravel.com)  | [快速开始](https://laravel.com/docs/5.3) | [中文文档](http://laravelacademy.org/laravel-docs-5_2)
> Laravel是一套简洁、优雅的PHP Web开发框架(PHP Web Framework)。它可以让你从面条一样杂乱的代码中解脱出来；它可以帮你构建一个完美的网络APP，而且每行代码都可以简洁、富于表达力。

### 网络请求
#### [Goutte](https://github.com/FriendsOfPHP/Goutte) | 快速开始 `composer require fabpot/goutte`
> Goutte 是一个抓取网站数据的 PHP 库。它提供了一个优雅的 API，这使得从远程页面上选择特定元素变得简单。

#### [DomCrawler](https://github.com/symfony/dom-crawler) | [文档](https://symfony.com/doc/current/components/dom_crawler.html) | 快速开始 `composer require symfony/dom-crawler`
> 优雅地解析HTML、XML文档的DOM结构。

#### [Dingo API](https://github.com/dingo/api) | [Wiki](https://github.com/dingo/api/wiki) | 快速开始 `composer require dingo/api:1.0.x@dev`
> Laravel 或 Lumen 下面想做API接口用它就对了。

## 数据库
### 关系型数据库
#### MySQL
#### SQLite

### NoSQL
#### Memcache
#### Redis
#### MongoDB

## iOS
### 工具类
#### [CocoaPods](https://cocoapods.org) | [快速开始](https://guides.cocoapods.org)
> Mac & iOS 平台下的第三方库管理工具，必备。

#### [BugTags](https://www.bugtags.com) | [快速开始](https://docs.bugtags.com/zh/start/integrate/ios/cocoapods.html)
> 目前国内最好用的崩溃分析，Bug收集平台。

#### [MLeaksFinder](https://github.com/Zepo/MLeaksFinder) | 快速开始 `pod 'MLeaksFinder'`
> 精准 iOS 内存泄露检测工具。

#### [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) | [文档](https://github.com/CocoaLumberjack/CocoaLumberjack/tree/master/Documentation) | [利用 CocoaLumberjack 搭建自己的 Log 系统](http://www.cocoachina.com/ios/20150311/11300.html) | 快速开始 `pod 'CocoaLumberjack'`
> Mac和iOS上一个集快捷、简单、强大和灵活于一身的日志框架。专为Objective-C设计，利用了多线程、GCD（如果可用）、无锁原子操作Objective-C运行时的动态特性。

#### [SFHFKeychainUtils](https://github.com/stoneros/SFHFKeychainUtils) | 快速开始 `pod 'SFHFKeychainUtils'`
> 用于安全的保存用户名密码等机密信息。

#### [FLEX](https://github.com/Flipboard/FLEX) | 快速开始 `pod 'FLEX', '~> 2.0', :configurations => ['Debug']`
> 带图形界面的Debug调试工具。

#### [YYKit](https://github.com/ibireme/YYKit) 
> YYKit 是一组庞大、功能丰富的 iOS 组件。强大到很多事情都可以用它搞定了。如果你非嫌它太大，可以拆开用啊。 YYCategories简直是日常必备。

#### [JKCategories](https://github.com/shaojiankui/JKCategories) | 快速安装 `pod 'JKCategories'`
> 强大到不行不行的Category扩展包，比YYCategories还要多，也是必备之选，选哪个好呢？发愁。

### 界面控件
#### [MBProgressHUD](https://github.com/jdg/MBProgressHUD) | 快速开始 `pod 'MBProgressHUD'`
> iOS里最火的进度条显示框之一，比老二更灵活一些。

#### [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) | 快速开始 `pod 'SVProgressHUD'`
> iOS里最火的进度条显示框之二。

#### [JZNavigationExtension](https://github.com/JazysYu/JZNavigationExtension) | 快速开始 `pod 'JZNavigationExtension'`
> 修改UINavigationController样式、增加全局收拾等，使你的导航控制器更加强大。

#### [RxWebViewController](https://github.com/Roxasora/RxWebViewController) | [其他维护版](https://github.com/yang0013/RxWebViewController) [使用说明](http://www.jianshu.com/p/9c4efe602b59)
> 类似微信那样的WebView组件，作者有弃更嫌疑，建议看看其他维护者的。

#### [XHLaunchAd](https://github.com/CoderZhuXH/XHLaunchAd) | 快速开始 `pod 'XHLaunchAd'`
> 几行代码接入启动页广告, 自带图片下载、缓存相关功能, 无任何第三方依赖 - 支持静态/动态、全屏/半屏广告。

#### [FCAlertView](https://github.com/nimati/FCAlertView) | 快速开始 `pod 'FCAlertView'`
> Objective C写的一个扁平化风格的AlertView。

#### [iRate](https://github.com/nicklockwood/iRate) | 快速开始 `pod 'iRate'`
> 提醒用户去AppStore给写好评的弹框。

#### [WZLBadge](https://github.com/weng1250/WZLBadge) | 快速开始 `pod 'WZLBadge'`
> 支持多种形式多种动画风格的推送小红点。

#### [HYBLoopScrollView](https://github.com/CoderJackyHuang/HYBLoopScrollView) | 快速开始 `pod 'HYBLoopScrollView'`
> 一行代码接入轮播组件，自带图片下载、缓存相关功能，无任何第三方依赖、轻量级组件。

#### [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) | 快速开始 `pod 'IQKeyboardManager'`
> 自动处理键盘事件，解决键盘弹起遮挡UITextField/UITextView的一种很实用的工具。无需输入任何代码,不需要额外的设置。

#### [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) | 快速开始 `pod 'DZNEmptyDataSet'`
> TableView 没数据时提示页面

#### [TZImagePickerController](https://github.com/banchichen/TZImagePickerController) |  快速开始 `pod 'TZImagePickerController'`
> 一个支持多选、选原图和视频的图片选择器，同时有预览功能，适配了iOS6789系统。最像微信。

#### [HHRouter](https://github.com/Huohua/HHRouter) | 快速开始 `pod 'HHRouter'`
> Yet another URL Router for iOS.

#### [EAIntroView](https://github.com/ealeksandrov/EAIntroView) | 快速开始 `pod 'EAIntroView'`
> EAIntroView 是一个用来实现软件启动时介绍的控件,支持多个视图进行滑动显示。

#### [HMSegmentedControl](https://github.com/HeshamMegid/HMSegmentedControl) | 快速开始 `pod 'HMSegmentedControl'`
> HMSegmentedControl 是 UISegmentedControl 的替代品,模仿了 Google Currents 使用的效果。


### 图形处理
#### [GPUImage](https://github.com/BradLarson/GPUImage) | 快速开始  `pod 'GPUImage'`
> GPUImage是现在做滤镜最主流的开源框架,没有之一。

### 网络
#### [Reachability](https://github.com/tonymillion/Reachability) | 快速开始 `pod 'Reachability'`
> 判断设备网络连接情况。相对于苹果官方的Reachability,这是一个更加高级、更加好用的Reachability,支持ARC、支持block、使用GCD方式来通知网络的变化。

### 动画特效
#### [RMPZoomTransitionAnimator](https://github.com/recruit-mp/RMPZoomTransitionAnimator) | 快速开始 `pod 'RMPZoomTransitionAnimator'`
> 一个放大缩小的动效开源库，可以实现图片的放大缩小效果。

## Android
### 工具类
#### [BugTags](https://www.bugtags.com) | [快速开始](https://docs.bugtags.com/zh/start/integrate/android/index.html)
> 目前国内最好用的崩溃分析，Bug收集平台。

## Javascript

## CSS

## MAC软件
### 开发工具
#### [SourceTree](https://www.sourcetreeapp.com) 
> 我觉得是Mac下最好用的git客户端软件了，不服来辩。而且支持Windows哦！

### 文本编辑
#### [MWeb](http://zh.mweb.im) 
> 强大的Markdown编辑器，对中文支持很好，优点：支持表格，实时预览，不足：暂无iCloud同步。

### 原型设计
#### [Axure RP](http://www.axure.com.cn)
> 一个专业的快速原型设计工具，支持Windows、Mac。

#### [StarUML](http://staruml.io)
> 一个强大的UML工具，丰富的插件，支持Windows、Mac、Linux。

### 图形设计
#### [Sketch](http://www.sketchcn.com) | [下载试用](http://www.sketchs.cn)
> Mac系统下的一款优秀的矢量图形设计工具，设计APP界面，我觉得比PhotoShop更方便。


----
添加模板
----
#### [名称](官网地址) | [链接1](URL1) | [链接2](URL2) | 快速开始 ``
> 描述

