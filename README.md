# Awesome iOS

A curated list of most common & awesome iOS frameworks, libraries, tools, components and much more.

<!-- MarkdownTOC -->

- [Websites](#websites)
- [Tools](#tools)
- [Foundation](#foundation)
- [Test](#test)
- [Database, ORM, Cache](#database-orm-cache)
- [Networking](#networking)
- [Data/File Archive & Unarchive](#datafile-archive--unarchive)
- [UI Frameworks](#ui-frameworks)
- [UI Components](#ui-components)
- [UI Effects](#ui-effects)
- [Media](#media)

<!-- /MarkdownTOC -->

## Websites

- [Cocoa Controls](https://www.cocoacontrols.com) - Lists custom controls and views for iOS and macOS
- [vsouza/awesome-ios](https://github.com/vsouza/awesome-ios) - A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects
- [iOS LibHunt](https://ios.libhunt.com) - Your go-to iOS Toolbox
- [GitHub Objective-C Topics](https://github.com/topics/objective-c)
- [Open source iOS Apps](https://github.com/dkhamsing/open-source-ios-apps)
- [Open source macOS Apps](https://github.com/serhii-londar/open-source-mac-os-apps)
- [TimLiu-iOS](https://github.com/Tim9Liu9/TimLiu-iOS) - iOS开发常用三方库、插件、知名博客等
- [cjwirth/awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui)
- [ameizi/awesome-ios-animation](https://github.com/ameizi/awesome-ios-animation)
- [jobbole/awesome-ios-cn](https://github.com/jobbole/awesome-ios-cn)
- [iOS-Monitor-Platform](https://github.com/aozhimin/iOS-Monitor-Platform) - iOS 性能监控 SDK —— Wedjat（华狄特）开发过程的调研和整理
- [iOS 资源大全中文版](https://github.com/duzhi5368/AwesomeAllInOne/wiki/iOS-%E8%B5%84%E6%BA%90%E5%A4%A7%E5%85%A8%E4%B8%AD%E6%96%87%E7%89%88)
- [iOS Good Practices](https://github.com/futurice/ios-good-practices) - Good ideas for iOS development, by Futurice developers.
- [掘金翻译计划](https://github.com/xitu/gold-miner) - 一个翻译优质互联网技术文章的社区
- [Flat UI Colors](https://flatuicolors.com) - 280 handpicked colors ready for COPY & PASTE
- [iOS-InterviewQuestion-collection](https://github.com/liberalisman/iOS-InterviewQuestion-collection) - iOS 开发者在面试过程中，常见的一些面试题

## Tools

- [fastlane](https://fastlane.tools) - The easiest way to automate building and releasing your iOS and Android apps.
- [Appium](https://github.com/appium/appium) - Appium is an open source, cross-platform test automation tool for native, hybrid and mobile web and desktop apps.
- [XcodeGen](https://github.com/yonaskolb/XcodeGen) - A command line tool written in Swift that generates your Xcode project using your folder structure and a project spec.
- [XcodeProj](https://github.com/tuist/xcodeproj) - Read, update and write your Xcode projects
- [DoraemonKit](https://github.com/didi/DoraemonKit) - 简称 "DoKit" 。一款功能齐全的客户端（ iOS 、Android、微信小程序 ）研发助手，你值得拥有。
- [Buck](https://github.com/facebook/buck) - A fast build system that encourages the creation of small, reusable modules over a variety of platforms and languages. https://buck.build
- [Chisel](https://github.com/facebook/chisel) - Chisel is a collection of LLDB commands to assist debugging iOS apps.
- [Fui](https://github.com/dblock/fui) - Find unused Objective-C imports.
- [LLDebugTool](https://github.com/HDB-Li/LLDebugTool) - LLDebugTool is a debugging tool for developers and testers that can help you analyze and manipulate data in non-xcode situations.
- [JSDebugger](https://github.com/SatanWoo/JSDebugger) - JavaScript-Based Debugger For Inspecting Running State Of Your Application
- [MTHawkeye](https://github.com/meitu/MTHawkeye) - Profiling / Debugging assist tools for iOS. (Memory Leak, OOM, ANR, Hard Stalling, Network, OpenGL, Time Profile ...)
- [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole) - In-App debug console for your UIWebView & WKWebView
- [xcconfigs](https://github.com/jspahrsummers/xcconfigs) - Common Xcode configuration files/settings.
- [Uncrustify](https://github.com/uncrustify/uncrustify) - A source code beautifier for C, C++, C#, ObjectiveC, D, Java, Pawn and VALA
- [Space Commander](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C as a team without even trying.
- [OCLint](http://oclint.org) - A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C
- [NSLogger](https://github.com/fpillet/NSLogger) - A modern, flexible logging tool
- [Flipper](https://github.com/facebook/flipper) - A desktop debugging platform for mobile developers.
- [FLEX (Flipboard Explorer)](https://github.com/Flipboard/FLEX) - A set of in-app debugging and exploration tools for iOS development.
- [Aspects](https://github.com/steipete/Aspects) - Delightful, simple library for aspect oriented programming in Objective-C and Swift.
- [Stinger](https://github.com/eleme/Stinger) - Stinger is a high-efficiency library with great compatibility, for aop in Objective-C, using libffi.
- [MLeaksFinder](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time.
- [FBRetainCycleDetector](https://github.com/facebook/FBRetainCycleDetector) - An iOS library that finds retain cycles using runtime analysis.
- [DWURecyclingAlert](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling
- [LSSafeProtector](https://github.com/lsmakethebest/LSSafeProtector) - 强大的防止crash框架，不改变原代码支持KVO自释放，可以检测到dealloc时未释放的kvo，等19种crash
- [TimeProfiler](https://github.com/maniackk/TimeProfiler) - Recording all OC methods in the main thread takes time
- [XXShield](https://github.com/ValiantCat/XXShield) - It's a library can avoid some crash in iOS project written by Objective-C.
- [JSPatch](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime.
- [Mango](https://github.com/YPLiang19/Mango) - MangoFix is a DSL which syntax is very similar to Objective-C，MangoFix is also an iOS App hotfix SDK.
- [ANYMethodLog](https://github.com/qhd/ANYMethodLog) - Log any method call of object in Objective-C 打印 Objective-C 对象中的任何方法
- [NWPusher](https://github.com/noodlewerk/NWPusher) - OS X and iOS application and framework to play with the Apple Push Notification service (APNs)
- [Knuff](https://github.com/KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNs).
- [MessageThrottle](https://github.com/yulingtianxia/MessageThrottle) - A lightweight Objective-C message throttle and debounce library.
- [iOSMixProject](https://github.com/JourneyYoung/iOSMixProject) - 马甲包混淆工程
- [KLGenerateSpamCode](https://github.com/klaus01/KLGenerateSpamCode) - iOS 马甲应用工具：垃圾代码生成器
- [WHC_Scan](https://github.com/netyouli/WHC_Scan) - 高效强大扫描分析iOS和Android项目里没有使用的类Mac开源工具，清理项目垃圾类，让项目结构干净清爽

## Foundation

- [ESFramework](https://github.com/ElfSundae/ESFramework) - ESFramework is an efficient, lightweight foundational framework for iOS, macOS, watchOS, and tvOS.
- [Nimbus](https://github.com/jverkoey/nimbus) - Nimbus is an iOS framework whose feature set grows only as fast as its documentation.
- [YYKit](https://github.com/ibireme/YYKit) - A collection of iOS components.
- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework.
- [LxDBAnything](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol!
- [KVOController](https://github.com/facebook/KVOController) - Simple, modern, thread-safe key-value observing.
- [libextobjc](https://github.com/jspahrsummers/libextobjc) - A Cocoa library to extend the Objective-C programming language.
- [ProtocolKit](https://github.com/forkingdog/ProtocolKit) - Protocol extension for Objective-C
- [NullSafe](https://github.com/nicklockwood/NullSafe) - NullSafe is a simple category on NSNull that returns nil for unrecognised messages instead of throwing an exception
- [fishhook](https://github.com/facebook/fishhook) - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS.
- [PromiseKit](https://github.com/mxcl/PromiseKit) - Promises for Swift & ObjC.
- [KKJSBridge](https://github.com/karosLi/KKJSBridge) - 一站式解决 WKWebView 支持离线包，Ajax 请求，表单请求和 Cookie 同步的问题 (基于 Ajax Hook 和 Cookie Hook)
- [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/OSX bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews.
- [ISHPermissionKit](https://github.com/iosphere/ISHPermissionKit) - A polite and unified way of asking for permission on iOS.
- [TDTouchID](https://github.com/greezi/TDTouchID) - TDTouchID是一个封装好的指纹验证库,可以用来做iOSAPP的登录/支付等验证。
- [LocationManager](https://github.com/intuit/LocationManager) - Easily get the device's current location on iOS.
- [MGJRouter](https://github.com/meili/MGJRouter) - 一个高效/灵活的 iOS URL Router
- [ZIKRouter](https://github.com/Zuikyo/ZIKRouter) - Interface-oriented router for discovering modules, and injecting dependencies with protocol in Objective-C and Swift.
- [JLRoutes](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API
- [QTEventBus](https://github.com/LeoMobileDeveloper/QTEventBus) - iOS事件总线，支持AppDelegate解耦，支持基于响应链的局部总线
- [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links.
- [BeeHive](https://github.com/alibaba/BeeHive) - 🐝 BeeHive is a solution for iOS Application module programs, it absorbed the Spring Framework API service concept to avoid coupling between modules.
- [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions.
- [XExtensionItem](https://github.com/tumblr/XExtensionItem) - Easier sharing of structured data between iOS applications and share extensions
- [YBTaskScheduler](https://github.com/indulgeIn/YBTaskScheduler) - iOS task scheduler, reduce the burden of CPU and memory. / iOS 任务调度器，为 CPU 和内存减负（用于性能优化）
- [coobjc](https://github.com/alibaba/coobjc) - coobjc provides coroutine support for Objective-C and Swift.
- [BMChineseSort](https://github.com/Baymax0/BMChineseSort) - 列表中文分组排序工具，支持字符串数组&模型数组 （支持swift）
- [libPhoneNumber-iOS](https://github.com/iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library)
- [getClientInfo](https://github.com/PengfeiWang666/iOS-getClientInfo) - iOS中获取各种设备信息ID的方法总结(iPhone 11 已更新)
- [MotionOrientation](https://github.com/rushairer/MotionOrientation) - An observer to notify the orientation of iOS device changed, using CoreMotion for taking the orientation in 'Orientation Lock'.

## Test

- [Quick](https://github.com/Quick/Quick) - The Swift (and Objective-C) testing framework.
- [KIF](https://github.com/kif-framework/KIF) - Keep It Functional - An iOS Functional Testing Framework
- [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!

## Database, ORM, Cache

- [protobuf](https://developers.google.com/protocol-buffers/) - Protocol Buffers - Google's data interchange format.
- [MJExtension](https://github.com/CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion framework between JSON and model.
- [PINCache](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS, tvOS and OS X
- [MMKV](https://github.com/Tencent/MMKV) - An efficient, small mobile key-value storage framework developed by WeChat.
- [SPTPersistentCache](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours.
- [WCDB](https://github.com/Tencent/wcdb) - WCDB is a cross-platform database framework developed by WeChat.
- [FMDB](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite.
- [JQFMDB](https://github.com/gaojunquan/JQFMDB) - FMDB的封装,操作简单,线程安全,扩展性强,直接操作model或dictionary
- [CTPersistance](https://github.com/casatwy/CTPersistance) - iOS Database Persistence Layer with SQLite
- [LKDBHelper](https://github.com/li6185377/LKDBHelper-SQLite-ORM) - 全自动的插入,查询,更新,删除， an automatic database operation thread-safe and not afraid of recursive deadlock
- [SQLitePersistentObjects](https://github.com/ElfSundae/SQLitePersistentObjects) - Persistent Objects for Cocoa & Cocoa Touch that using SQLite.
- [SAMKeychain](https://github.com/soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS.
- [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS, watchOS, tvOS and macOS. Makes using Keychain APIs as easy as NSUserDefaults.

## Networking

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful networking framework.
- [ESAPIClient](https://github.com/ElfSundae/ESAPIClient) - An API client library built on top of AFNetworking and AFNetworkingExtension.
- [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - A high level request util based on AFNetworking
- [YBNetwork](https://github.com/indulgeIn/YBNetwork) - 基于 AFNetworking 网络中间层，注重性能，设计简洁，易于拓展
- [SDWebImage](https://github.com/SDWebImage/SDWebImage) - Asynchronous image downloader with cache support as a UIImageView category.
- [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS.
- [SocketRocket](https://github.com/facebook/SocketRocket) - A conforming Objective-C WebSocket client library.
- [Starscream](https://github.com/daltoniam/Starscream) - A conforming WebSocket (RFC 6455) client library in Swift.
- [Jetfire](https://github.com/acmacalister/jetfire) - WebSocket RFC 6455 client library for iOS and OSX.
- [PocketSocket](https://github.com/zwopple/PocketSocket) - Objective-C websocket library for building things that work in realtime on iOS and OS X.
- [Mars](https://github.com/Tencent/mars) - Mars is a cross-platform network component developed by WeChat.
- [RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases
- [NEKit](https://github.com/zhuhaow/NEKit) - A toolkit for Network Extension Framework

## Data/File Archive & Unarchive

- [FastCoding](https://github.com/nicklockwood/FastCoding) - A faster and more flexible binary file format replacement for NSCoding, Property Lists and JSON
- [SSZipArchive](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS, macOS and tvOS.
- [GZIP](https://github.com/nicklockwood/GZIP) - A simple NSData category for gzipping/unzipping data in iOS and Mac OS.
- [LzmaSDKObjC](https://github.com/OlehKulykov/LzmaSDKObjC) - Lzma SDK for Swift and Objective-C ( iOS & MacOS ) based on extended functionality of the C++ LZMA SDK code.
- [UnrarKit](https://github.com/abbeycode/UnrarKit) - Easily read RAR archives on Mac and iOS
- [SARUnArchiveANY](https://github.com/saru2020/SARUnArchiveANY) - A very useful library for Unarchiving the .zip, .rar, .7z files for iOS.
- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - Encrypt/Decrypt: AES. Hash: MD5, SHA(SHA1, SHA224, SHA256, SHA384, SHA512). Encode/Decode: Base64, Hex.

## UI Frameworks

- [Masonry](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax.
- [SDAutoLayout](https://github.com/gsdios/SDAutoLayout) - One line of code to implement automatic layout. 一行代码搞定自动布局！支持Cell和Tableview高度自适应，Label和ScrollView内容自适应，致力于做最简单易用的AutoLayout库。
- [WHC_AutoLayoutKit](https://github.com/netyouli/WHC_AutoLayoutKit) - iOS/Mac OS X平台上目前使用最简单开发构建UI速度最快的自动布局开源库，强悍的动态布局约束处理能力
- [Material Components](https://github.com/material-components/material-components-ios) - Modular and customizable Material Design UI components for iOS
- [PureLayout](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & OS X Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible.
- [Chameleon](https://github.com/viccalexander/Chameleon) - Color framework for Swift & Objective-C (Gradient colors, hexcode support, colors from images & more).
- [Colours](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods
- [Wonderful](https://github.com/dsxNiubility/Wonderful) - 一个关于色彩的库 Include wonderfulcolor api, marquee, colorLabel, Gradient, Separate
- [IconFontKit](https://github.com/ElfSundae/IconFontKit) - Icon fonts toolkit for iOS.
- [Texture](https://github.com/TextureGroup/Texture) - Texture is an iOS framework built on top of UIKit that keeps even the most complex user interfaces smooth and responsive.
- [IGListKit](https://github.com/Instagram/IGListKit) - A data-driven UICollectionView framework for building fast and flexible lists.
- [AsyncDisplayKit](https://github.com/facebookarchive/AsyncDisplayKit) - Smooth asynchronous user interfaces for iOS apps.
- [ComponentKit](https://github.com/facebook/componentkit) - ComponentKit is an Objective-C++ view framework for iOS that is heavily inspired by React.
- [Pop](https://github.com/facebook/pop) - An extensible iOS and OS X animation library, useful for physics-based interactions.
- [FastImageCache](https://github.com/path/FastImageCache) - [_DEAD_] [Mallory's fork](https://github.com/mallorypaine/FastImageCache) - iOS library for quickly displaying images while scrolling
- [Yoga](https://github.com/facebook/yoga) - Yoga is a cross-platform layout engine which implements Flexbox.
- [Material Components](https://github.com/material-components/material-components-ios) - Material Components for iOS (MDC-iOS) helps developers execute Material Design.
- [QMUI](https://github.com/Tencent/QMUI_iOS) - QMUI iOS 是一个致力于提高项目 UI 开发效率的解决方案
- [FlatUIKit](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS.
- [MessageKit](https://github.com/MessageKit/MessageKit) - A community-driven replacement for JSQMessagesViewController.
- [NIM_iOS_UIKit](https://github.com/netease-im/NIM_iOS_UIKit) - 网易云信 iOS UI 组件，提供聊天界面，文本消息，图片消息，语音消息，视频消息，地理位置消息，自定义消息（阅后即焚）等消息示例
- [QIMUIKit](https://github.com/qunarcorp/libqimuikit-ios) [Demo](https://github.com/qunarcorp/imsdk-ios) - Startalk is a high-performace IM software for business. 去哪儿 Startalk IM.
- [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) - 一个类似微信App的IM应用，拥有发送文字、图片、语音、视频、地理位置消息，管理本地通信录、分享朋友圈、漂流交友、摇一摇和更多有趣的功能。
- [PPStickerKeyboard](https://github.com/VernonVan/PPStickerKeyboard) - iOS 表情键盘
- [Signal-iOS](https://github.com/signalapp/Signal-iOS) - Signal is a free, open source, messaging app for simple private communication with friends.
- [Wildfirechat Chat](https://github.com/wildfirechat/ios-chat) - 全开源的即时通讯(野火IM)系统 高仿微信
- [TLChat](https://github.com/tbl00c/TLChat) - 高仿微信，iOSAppTemplate代码重构。此版本TLChat基于TLKit、 ZZFLEX实现.
- [YHFlutterAdapter](https://github.com/jiisd/YHFlutterAdapter) - 三行代码组件化集成 Flutter！可用于已有 iOS 项目，对原工程无侵入，无需更改原项目配置，集成后可直接以组件形式开发 Flutter 业务。

## UI Components

- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS and tvOS app.
- [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - an iOS drop-in class that displays a translucent HUD with an indicator and/or labels while work is being done in a background thread.
- [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) - A collection of awesome loading animations
- [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - An easy way to use pull-to-refresh.
- [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS
- [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
- [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) - A drop-in universal solution for moving text fields out of the way of the keyboard in iOS
- [Harpy](https://github.com/ArtSabintsev/Harpy) - Notify users when a new version of your app is available and prompt them to upgrade.
- [BLKFlexibleHeightBar](https://github.com/bryankeller/BLKFlexibleHeightBar) - Create condensing header bars like those seen in the Facebook, Square Cash, and Safari iOS apps.
- [UIScrollView-InfiniteScroll](https://github.com/pronebird/UIScrollView-InfiniteScroll) - Infinite scroll implementation as a category for UIScrollView.
- [ContainerView](https://github.com/mrustaa/ContainerView) - ContainerView is designed to add a cool swim from the bottom to the animation with the effect of scale, controlled by the help of a gesture, scrollView also takes control.
- [XLForm](https://github.com/xmartlabs/XLForm) - XLForm is the most flexible and powerful iOS library to create dynamic table-view forms.
- [LMForm](https://github.com/MaricleZhang/LMForm) - iOS表单配置框架
- [MGBoxKit](https://github.com/sobri909/MGBoxKit) - Simple, quick iOS tables, grids, and more
- [UFKit](https://github.com/czl620/UFKit) - 快速集成表单
- [InAppSettingsKit](https://github.com/futuretap/InAppSettingsKit) - Easily add in-app settings to your iPhone apps.
- [SCIndexView](https://github.com/TalkingJourney/SCIndexView) - SCIndexView provide a index view like Wechat.
- [LYEmptyView](https://github.com/dev-liyang/LYEmptyView) - 一行代码集成空白页面占位图(无数据、无网络占位图)
- [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display
- [SPButton](https://github.com/SPStore/SPButton) - 自定义按钮，图片可在上、左、下、右，可调整图文间距
- [BButton](https://github.com/jessesquires/BButton) - Twitter Bootstrap buttons for iOS.
- [TORoundedButton](https://github.com/TimOliver/TORoundedButton) - A high-performance button control with rounded corners for iOS.
- [HJCornerRadius](https://github.com/panghaijiao/HJCornerRadius) - A category for UIImageView with support for cornerRadius automatically
- [HYBImageCliped](https://github.com/CoderJackyHuang/HYBImageCliped) - 高效处理圆角的扩展
- [YXYDashLayer](https://github.com/yulingtianxia/YXYDashLayer) - Colorful Rounded Rect Dash Border
- [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton) - Flat button with 9 different states using POP
- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - Beautiful, highly customizable, animated checkboxes for iOS.
- [M80AttributedLabel](https://github.com/xiangwangfeng/M80AttributedLabel) - Another attributed label using CoreText
- [MPITextKit](https://github.com/meitu/MPITextKit) - Powerful text framework for iOS to display rich text based on TextKit.
- [STULabel](https://github.com/stephan-tolksdorf/STULabel) - A faster and more flexible label view for iOS
- [TTTAttributedLabel](https://github.com/TTTAttributedLabel/TTTAttributedLabel) - A drop-in replacement for UILabel that supports attributes, data detectors, links, and more
- [TYAttributedLabel](https://github.com/12207480/TYAttributedLabel) - 简单，强大的属性文本控件(无需了解CoreText)，支持图文混排显示，支持添加链接，image和UIView控件，支持自定义排版显示
- [YBAttributeTextTapAction](https://github.com/lyb5834/YBAttributeTextTapAction) - 一行代码添加文本点击事件/a fast way to implement click event text
- [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view
- [MarqueeLabel](https://github.com/cbpowell/MarqueeLabel) - A drop-in replacement for UILabel, which automatically adds a scrolling marquee effect when the label's text does not fit inside the specified frame.
- [UUMarqueeView](https://github.com/iceyouyou/UUMarqueeView) - Customizable marquee view. #Marquee,MarqueeView,跑马灯,滚屏,上翻,左滑,多行,自定义
- [RollingNotice](https://github.com/maltsugar/RollingNotice) - 滚动公告、轮播广告，支持灵活自定义cell
- [RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView) - A light-weight UITextView subclass that automatically grows and shrinks.
- [GrowTextView](https://github.com/jalyResource/GrowTextView) - 一个比较完美的高度自适应输入框
- [SHSPhoneComponent](https://github.com/Serheo/SHSPhoneComponent) - UITextField and NSFormatter subclasses for formatting phone numbers. Allow different formats for different countries(patterns).
- [CRBoxInputView](https://github.com/CRAnimation/CRBoxInputView) - Verify code input view. Support security type for password.短信验证码输入框，支持密文模式
- [WLUnitField](https://github.com/zhwayne/WLUnitField) - 一种验证码输入 UI 控件
- [PPNumberButton](https://github.com/jkpang/PPNumberButton) - iOS中一款高度可定制性商品计数按钮(京东/淘宝/饿了么/美团外卖/百度外卖样式)
- [InputKit](https://github.com/tingxins/InputKit) - InputKit, an Elegant Kit to limits your input text, inspired by BlocksKit, written in both Objective-C & ⚡️Swift.
- [AnimatedField](https://github.com/alberdev/AnimatedField) - Animated UITextField with check & filter for default types (email, url, password, price, date...) for iOS
- [ZCAnimatedLabel](https://github.com/overboming/ZCAnimatedLabel) - UILabel replacement with fine-grain appear/disappear animation
- [MDRadialProgress](https://github.com/mdinacci/MDRadialProgress) - A custom UIView useful to represent progress in discrete steps.
- [ZZCircleProgress](https://github.com/zhouxing5311/ZZCircleProgress) - CAAnimation实现的高度可定制化环形进度条
- [SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView) - Autoscroll Banner. 无限循环图片、文字轮播器。
- [NewPagedFlowView](https://github.com/PageGuo/NewPagedFlowView) - 电影票卡片式无限自动轮播图
- [PSCarouselView](https://github.com/saildog/PSCarouselView) - A drop-in carousel view. Most of Apps put it in their first screen.
- [ActionSheetPicker-3.0](https://github.com/skywinder/ActionSheetPicker-3.0) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
- [BRPickerView](https://github.com/91renb/BRPickerView) - iOS中常用的选择器组件，主要包括：日期选择器、时间选择器、地址选择器、自定义字符串选择器。高度封装，提供了两种使用方式，支持自定义主题样式，适配深色模式。
- [JFCitySelector](https://github.com/zhifenx/JFCitySelector) - 轻量、灵活、可自定义的三级城市选择器
- [TBActionSheet](https://github.com/yulingtianxia/TBActionSheet) - A Custom&Powerful Action Sheet For iOS. 一个 ActionSheet 满足所有样式！超高自由度的可定制！
- [LCActionSheet](https://github.com/iTofu/LCActionSheet) - 一款简约而不失强大的 ActionSheet，微博、微信和 QQ 都采用了极其类似的样式，完全支持 Swift。
- [SPAlertController](https://github.com/SPStore/SPAlertController) - 提醒对话框，风格和微信原生几乎零误差。
- [LEEAlert](https://github.com/lixiang1994/LEEAlert) - 优雅的可自定义 Alert ActionSheet
- [WMZDialog](https://github.com/wwmz/WMZDialog) - 功能样式最多的最齐全的的弹窗控件 控件全部采用链式编程，所有属性均可定制
- [FWPopupView](https://github.com/choiceyou/FWPopupView) - 弹窗控件：支持AlertView、Sheet、自定义视图的PopupView。Sheet仿微信样式。
- [RMActionController](https://github.com/CooperRS/RMActionController) - This is an iOS control for presenting any UIView in an UIAlertController like manner
- [STPopup](https://github.com/kevin0571/STPopup) - STPopup provides STPopupController, which works just like UINavigationController in popup style, for both iPhone and iPad.
- [ISHPullUp](https://github.com/iosphere/ISHPullUp) - Vertical split view controller with pull up gesture as seen in the iOS 10 Maps app.
- [PageMenu](https://github.com/PageMenu/PageMenu) - A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram)
- [JXCategoryView](https://github.com/pujiaxin33/JXCategoryView) - A powerful and easy to use category view (segmentedcontrol, segmentview, pagingview, pagerview, pagecontrol) (腾讯新闻、今日头条、QQ音乐、网易云音乐、京东、爱奇艺、腾讯视频、淘宝、天猫、简书、微博等所有主流APP分类切换滚动视图)
- [SGPagingView](https://github.com/kingsic/SGPagingView) - A powerful and easy to use segment control 【QQ、淘宝、微博、腾讯、网易新闻、今日头条等标题滚动视图】
- [TYPagerController](https://github.com/12207480/TYPagerController) - page scroll view and controller,simple,high custom,and have many tabBar styles,,support Objective-C and swift
- [YNPageViewController](https://github.com/yongyuandouneng/YNPageViewController) - 特斯拉组件、QQ联系人布局、多页面嵌套滚动、悬停效果、美团、淘宝、京东、微博、腾讯新闻、网易新闻、今日头条等标题滚动视图
- [WMPageController](https://github.com/wangmchn/WMPageController) - An easy solution to page controllers like NetEase News
- [GKPageScrollView](https://github.com/QuintGao/GKPageScrollView) - 类似微博、抖音、网易云等个人详情页滑动嵌套效果
- [VTMagic](https://github.com/tianzhuo112/VTMagic) - A page container library for iOS
- [SPPageMenu](https://github.com/SPStore/SPPageMenu) - 分页菜单，功能非常齐全，满足绝大多数APP
- [BulletinBoard](https://github.com/alexaubry/BulletinBoard) - General-purpose contextual cards for iOS
- [FFPopup](https://github.com/JonyFang/FFPopup) - Presenting custom views as a popup in iOS.
- [YBPopupMenu](https://github.com/lyb5834/YBPopupMenu) - 快速集成 popupMenu
- [FTPopOverMenu](https://github.com/liufengting/FTPopOverMenu) - FTPopOverMenu is a pop over menu for iOS which is maybe the easiest one to use
- [CustomPopoverView](https://github.com/maltsugar/CustomPopoverView) - Custom popover view
- [zhPopupController](https://github.com/snail-z/zhPopupController) - Popup your custom view is easy, support custom mask style, transition effects and gesture to drag.
- [LNPopupController](https://github.com/LeoNatan/LNPopupController) - LNPopupController is a framework for presenting view controllers as popups of other view controllers, much like the Apple Music and Podcasts apps.
- [HWPanModal](https://github.com/HeathWang/HWPanModal) - presents controller from bottom and drag to dismiss, high customize. 实现任意形式的底部弹框；知乎、抖音弹出评论效果。
- [HWPopController](https://github.com/HeathWang/HWPopController) - Popup UIViewController with multiple animations
- [HHHorizontalPagingView](https://github.com/Huanhoo/HHHorizontalPagingView) - 一个实现上下滚动时菜单悬停在顶端，并且可以左右滑动切换的视图
- [DOPDropDownMenu-Enhanced](https://github.com/12207480/DOPDropDownMenu-Enhanced) - DOPDropDownMenu 添加双列表 优化版 新增图片支持
- [WMZDropDownMenu](https://github.com/wwmz/WMZDropDownMenu) - 一个能几乎实现所有App各种类型筛选菜单的控件
- [UUChatTableView](https://github.com/ZhipingYang/UUChatTableView) - Cocoa UI component for group or private chat bubbles with text, images and audio support
- [FSCalendar](https://github.com/WenchaoD/FSCalendar) - A fully customizable iOS calendar library, compatible with Objective-C and Swift
- [Context-Menu](https://github.com/Yalantis/Context-Menu.iOS) - You can easily add awesome animated context menu to your app.
- [MZFormSheetPresentationController](https://github.com/m1entus/MZFormSheetPresentationController) - provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet.
- [RTRootNavigationController](https://github.com/rickytan/RTRootNavigationController) - Implicitly make every view controller has its own navigation bar
- [ISHHoverBar](https://github.com/iosphere/ISHHoverBar) - A floating UIToolBar replacement as seen in the iOS 10 Maps app, supporting both vertical and horizontal orientation.
- [LBXScan](https://github.com/MxABC/LBXScan) - A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing、ZBar、iOS系统AVFoundation扫码封装，扫码界面效果封装)
- [ScanQRcode](https://github.com/wsl2ls/ScanQRcode) - 在利用原生API的条件下封装的二维码扫描工具，支持二维码的扫描、识别图中二维码、生成自定义颜色和中心图标的二维码、监测环境亮度、打开闪光灯这些功能，仿照微信的扫一扫功能。
- [WeScan](https://github.com/WeTransfer/WeScan) - Document Scanning Made Easy for iOS
- [TOCropViewController](https://github.com/TimOliver/TOCropViewController) - A view controller for iOS that allows users to crop portions of UIImage objects.
- [CWLateralSlide](https://github.com/ChavezChen/CWLateralSlide) - One line of code to integrate 0 coupling side drawer！一行代码集成0耦合侧滑抽屉！
- [GKNavigationBarViewController](https://github.com/QuintGao/GKNavigationBarViewController) - iOS自定义导航栏-导航栏联动
- [HXPhotoPicker](https://github.com/SilenceLove/HXPhotoPicker) - 照片/图片选择器 - 支持LivePhoto、GIF图片选择、3DTouch预览、在线下载iCloud上的资源、浏览网络图片功能
- [TZImagePickerController](https://github.com/banchichen/TZImagePickerController) - 一个支持多选、选原图和视频的图片选择器，同时有预览、裁剪功能，支持iOS6+
- [DZNPhotoPickerController](https://github.com/dzenbot/DZNPhotoPickerController) - A photo search/picker for iOS using popular image providers like 500px, Flickr, Instagram, Giphy, Google & Bing Images
- [KNPhotoBrowser](https://github.com/LuKane/KNPhotoBrowser) - 微信 和 微博 图片浏览器, UIViewControlelr + CollectionView , 完美适配 iPhone 以及 各种 iPad ,屏幕旋转功能 , 适配SDWebImage 5.0
- [YBImageBrowser](https://github.com/indulgeIn/YBImageBrowser) - iOS 图片浏览器 (支持视频) / image browser (support video)
- [ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser) - 方便易用的相册多选框架，支持预览/相册内拍照及录视频、拖拽/滑动选择，3DTouch预览，编辑裁剪图片/视频，导出视频(可添加水印，粒子特效，视频转码)；支持多语言国际化
- [IDMPhotoBrowser](https://github.com/thiagoperes/IDMPhotoBrowser) - IDMPhotoBrowser is a new implementation based on MWPhotoBrowser.
- [KSPhotoBrowser](https://github.com/skx926/KSPhotoBrowser) - A beautiful photo browser with interactive dismissal animation.一个小而美的图片浏览器。
- [GKPhotoBrowser](https://github.com/QuintGao/GKPhotoBrowser) - iOS仿微信、今日头条等图片浏览器
- [PhotoBrowser](https://github.com/cuzv/PhotoBrowser) - PhotoBrowser is a light weight photo browser, like the wechat, weibo image viewer.
- [PYPhotoBrowser](https://github.com/ko1o/PYPhotoBrowser) - An easy way to browse photo(image) for iOS.
- [LGPhotoBrowser](https://github.com/gang544043963/LGPhotoBrowser) - 照片浏览器，相册选择器，自定义照相机（支持单拍、连拍）
- [XHLaunchAd](https://github.com/CoderZhuXH/XHLaunchAd) - The screen opening advertising solutions - 开屏广告、启动广告解决方案-支持静态/动态图片广告,mp4视频广告,全屏/半屏广告、兼容iPhone/iPad.
- [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) - 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等 WRNavigationBar which allows you to change NavigationBar's appearance dynamically
- [CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController) - An animated tabBar supported by Lottie with one line of code 一行代码实现 Lottie 动画 TabBar
- [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating
- [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) - The waterfall (i.e., Pinterest-like) layout for UICollectionView.
- [ZLCollectionView](https://github.com/czl0325/ZLCollectionView) - 为应对类似淘宝首页，京东首页，国美首页的复杂布局而写的多样化的UICollectionView
- [FDWaveformView](https://github.com/fulldecent/FDWaveformView) - Reads an audio file and displays the waveform
- [IQAudioRecorderController](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface.
- [HGPersonalCenterExtend](https://github.com/ArchLL/HGPersonalCenterExtend) - 解决UIScrollView嵌套滑动手势冲突问题，适用于复杂的首页或个人主页
- [AAChartKit](https://github.com/AAChartModel/AAChartKit) - An elegant and friendly chart library for iOS
- [WMDragView](https://github.com/zhengwenming/WMDragView) - WMDragView致力于让任意View都可以自由悬浮拖曳（可拖动，悬浮按钮），类似于iOS的AssistiveTouch效果，微信浮窗
- [MMMaterialDesignSpinner](https://github.com/misterwell/MMMaterialDesignSpinner) - An iOS activity spinner modeled after Google's Material Design Spinner
- [XLCardSwitch](https://github.com/mengxianliang/XLCardSwitch) - 利用余弦函数特性实现可以居中放大的图片浏览工具
- [XLFoldClock](https://github.com/mengxianliang/XLFoldClock) - 翻页时钟
- [XLPaymentHUD](https://github.com/mengxianliang/XLPaymentHUD) - 支付宝支付动画
- [IIGuideViewController](https://github.com/whatsbug/IIGuideViewController) - A Library for making animated tutorials inside your app (新手引导、新手教程、功能介绍、功能引导)
- [TTGTagCollectionView](https://github.com/zekunyan/TTGTagCollectionView) - showing different size tag views in a vertical or horizontal scrollable view. 标签流显示控件，同时支持文字或自定义View
- [JXBWKWebView](https://github.com/xiubojin/JXBWKWebView) - iOS基于WKWebView的二次封装，功能丰富

## UI Effects

- [Shimmer](https://github.com/facebook/shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app.
- [HHTransition](https://github.com/yuwind/HHTransition) - 主流转场动画，无侵入，API简单易用。
- [TLTransitions](https://github.com/LoongerTao/TLTransitions) - 快速实现控制器的转场和View的快速popover显示，并支持自定义动画、手势退场
- [XLBubbleTransition](https://github.com/mengxianliang/XLBubbleTransition) - iOS ViewController间切换的转场动画
- [NNNavigationBar](https://github.com/amisare/NNNavigationBar) - 实现导航条背景渐变过渡动画的轻量级框架
- [BBGestureBack](https://github.com/Bonway/BBGestureBack) - Full screen return gesture（全屏手势返回 滑动返回 pop 动画效果）类淘宝、京东等全屏滑动返回效果
- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - A UINavigationController's category to enable fullscreen pop gesture with iOS7+ system style.
- [TABAnimated](https://github.com/tigerAndBull/TABAnimated) - A skeleton screen framework based on native for iOS. (一个由iOS原生组件映射出骨架屏的框架，包含快速植入，低耦合，兼容复杂视图等特点，提供国内主流骨架屏动画的加载方案，同时支持自定制动画。)
- [AnimatedTransitionGallery](https://github.com/shu223/AnimatedTransitionGallery) - A gallery app of custom animated transitions for iOS.
- [DCAnimationKit](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations.
- [KMNavigationBarTransition](https://github.com/MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations. And you don't need to write any line of code for it, it all happens automatically.
- [LYCustomTransition](https://github.com/dev-liyang/LYCustomTransition) - iOS自定义交互式转场动画-仿微信图片浏览器转场动画、仿iOS系统相册图片浏览转场动画、仿酷狗转场动画 + 交互式图片浏览器
- [iCarousel](https://github.com/nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS
- [SVGAPlayer](https://github.com/yyued/SVGAPlayer-iOS) - Render After Effects / Animate CC (Flash) animations natively.
- [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / OS X, using native rendering (CoreAnimation)
- [LiveSendGift](https://github.com/Jonhory/LiveSendGift) - 直播发送弹幕效果
- [Lottie](https://github.com/airbnb/lottie-ios) - An iOS library to natively render After Effects vector animations
- [iOS-Modal](https://github.com/xiaopin/iOS-Modal) - iOS 模态窗口，内置类似淘宝添加购物车的模态视图动画，内部使用 iOS8 推出的UIPresentationController来实现模态窗口功能。
- [DYFBlurEffect](https://github.com/dgynfi/DYFBlurEffect) - 一行代码实现图像模糊化，并支持系统UIVisualEffectView
- [LMDropdownView](https://github.com/lminhtm/LMDropdownView) - LMDropdownView is a simple dropdown view inspired by Tappy

## Media

- [mobile-ffmpeg](https://github.com/tanersener/mobile-ffmpeg) - FFmpeg for Android, iOS and tvOS
- [AudioKit](https://github.com/AudioKit/AudioKit) - Swift audio synthesis, processing, & analysis platform for iOS, macOS and tvOS
- [SwiftyCam](https://github.com/Awalz/SwiftyCam) - A simple, Snapchat-style iOS Camera framework for easy photo and video capture.
- [TheAmazingAudioEngine](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine) - Core Audio, Cordially: A sophisticated framework for iOS audio applications, built so you don't have to.
- [SRGMediaPlayer](https://github.com/SRGSSR/srgmediaplayer-apple) - The SRG Media Player library provides a simple way to add universal audio / video playback support to any application.
- [SGPlayer](https://github.com/libobjc/SGPlayer) - A powerful media play framework for iOS, macOS, and tvOS.
- [KSYLive_iOS](https://github.com/ksvc/KSYLive_iOS) - 金山云直播SDK [ iOS推流+播放 ]融合版 支持美颜滤镜(Beauty Filter)、美声(Beauty Voice)、软硬编(Software/Hardware Encoder) 、网络自适应(Network Auto Adapt)、混音(Audio Mixer)、混响(Reverb)、画中画(PIP)
- [KSYMediaPlayer_iOS](https://github.com/ksvc/KSYMediaPlayer_iOS) - 金山云iOS播放SDK（KSYUN Live Streaming player SDK），支持RTMP HTTP-FLV HLS 协议（supporting RTMP HTTP-FLV HLS protocol），直播延时2-3秒（Living delay 2 or 3 seconds）
- [KSYDiversityLive_iOS](https://github.com/ksvc/KSYDiversityLive_iOS) - 金山云SDK多样化接入方式，提供直播全链路数据开放，支持第三方连麦、录屏、美颜、贴纸、摄像头等多媒体处理方案提供商接入，共建移动直播大生态。
- [SRS](https://github.com/ossrs/srs) - SRS is a RTMP/HLS/WebRTC/SRT/GB28181 streaming cluster, high efficiency, stable and simple.
- [HaishinKit](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS, tvOS.
- [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS (iPhone, iPad)
- [DOUAudioStreamer](https://github.com/douban/DOUAudioStreamer) - A Core Audio based streaming audio player for iOS and macOS
- [FreeStreamer](https://github.com/muhku/FreeStreamer) - A low-memory footprint streaming audio player for iOS and OS X
- [LFLiveKit](https://github.com/17media/LFLiveKit) - LaiFeng IOS Live Kit,H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate
- [AWLive](https://github.com/hardman/AWLive) - 最简单的iOS 推流代码，视频捕获，软编码(faac，x264)，硬编码（aac，h264），横屏直播，美颜，flv编码，rtmp协议
- [LiveVideoCoreSDK](https://github.com/runner365/LiveVideoCoreSDK) - iOS 的手机视频直播，基于开源videocore进行了改进
- [LFRtmp](https://github.com/liuf1986/LFRtmp) - 一个全开源的纯OC实现的RTMP推流SDK支持AAC、H264、美颜滤镜、AMF编解码。
- [rtmp-wrapper](https://github.com/minsikzzang/rtmp-wrapper) - librtmp wrapper class for iOS use
- [HTTPLiveStreaming](https://github.com/whiteblue3/HTTPLiveStreaming) - iOS / Mac OSX H.264 / AAC Hardware Encoding and Streaming over RTP / RTSP using Video Tool Box
- [re](https://github.com/creytiv/re) - Generic library for real-time communications with async IO support
- [GStreamer](https://gstreamer.freedesktop.org/) - a flexible, fast and multiplatform multimedia framework.
- [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Support customization of any player SDK and control layer(支持定制任何播放器SDK和控制层)
- [PBJVision](https://github.com/piemonte/PBJVision) -  iOS Media Capture – features touch-to-record video, slow motion, and photography
- [SCRecorder](https://github.com/rFlex/SCRecorder) - iOS camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing
- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support.
- [SuperPlayer](https://github.com/tencentyun/SuperPlayer_iOS) - 超级播放器是基于腾讯云播放器SDK的播放器，能快速的集成视频信息拉取、横竖屏切换、清晰度选择、弹幕、直播时移等功能。
- [PLPlayerKit](https://github.com/pili-engineering/PLPlayerKit) - PLPlayerKit 是一个适用于 iOS 的音视频播放器 SDK，可高度定制化和二次开发，特色是支持 RTMP, HTTP-FLV 和 HLS 直播流媒体播放。
- [SJVideoPlayer](https://github.com/changsanjiang/SJVideoPlayer) - 短视频播放器 可接入 ijkplayer aliplayer alivodplayer plplayer
- [JSQSystemSoundPlayer](https://github.com/jessesquires/JSQSystemSoundPlayer) - A fancy Obj-C wrapper for Cocoa System Sound Services
- [GoPlay](https://github.com/dKingbin/GoPlay) - GoPlay is a media player framework for iOS. Based on FFmpeg and OpenGL ES 2.0. support all formats and custom your own filters by GLSL.
- [KTVHTTPCache](https://github.com/ChangbaDevs/KTVHTTPCache) - A powerful media cache framework.
- [novocaine](https://github.com/alexbw/novocaine) - An analgesic for high-performance audio on iOS and OSX.
- [WAVideoBox](https://github.com/CoderHenry66/WAVideoBox) - 秒级! 三行代码实现iOS视频压缩、变速、混音、合并、GIF水印、旋转、换音、裁剪 ! 支持不同分辩率，支持你能想到的各种混合操作!
- [MCamera](https://github.com/MaximAlien/MCamera) - CameraViewController which allows to take photos, set filters, peform image blurring and more
- [SDAVAssetExportSession](https://github.com/rs/SDAVAssetExportSession) - AVAssetExportSession drop-in replacement with customizable audio&video settings
