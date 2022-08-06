# EMM
EMM企业移动管理平台

## 指掌易EMM解析
指掌易EMM主要包括沙箱引擎、沙箱控制器和APP-SDK组成。
* 沙箱引擎（Sandbox Engine）SDK：由需要沙箱化的应用来集成，核心是沙箱引擎库。
* 沙箱控制器 （Sandbox Controller）SDK：由独立于沙箱之外的管控客户端集成，实现对沙箱应用的权限、行为、数据的管理。
* APP-SDK：是Controller-SDK的一个子集+Sandbox Engine sdk，使得应用自身可动态的执行相应的安全策略。

指掌易的安全功能，建立在独有的安全应用容器（沙箱）基础上。一个普通应用安装前，指掌易自动对应用宝进行“加壳”，应用启动后，运行在指掌易的虚拟容器里，由于应用运行在沙箱环境中，因此应用的所有行为均在沙箱的监控下，针对需要管控的行为进行适配和根据功能配置对该行为进行管控，从而做到自动化的安全防护，并能够在系统无感知的前提下对应用进行管理，有效保证系统和其他应用的稳定性。

## VirtualApp源码分析
* [Android 双开沙箱 VirtualApp 源码分析（一）](https://blog.csdn.net/ganyao939543405/article/details/76146760)
* [VirtualApp解析](https://www.jianshu.com/nb/21276638)
* [VirtualApp源码分析——（一）VA启动](https://blog.csdn.net/weixin_35016347/article/details/80193017)
* [VirtualApp沙盒基本原理](https://blog.csdn.net/earbao/article/details/71156623)
* [Android虚拟化引擎VirtualApp探究](https://developer.aliyun.com/article/616978)
* [VirtualApp原理解析(1)--初始化及注入流程](https://blog.csdn.net/leif_/article/details/72420934)
* [VirtualApp框架--- Application启动过程](https://blog.csdn.net/suningning/article/details/52073191)

## 沙箱技术
* [基于虚拟化及重定向技术的Android沙箱的设计与实现](http://www.doc88.com/p-7129181636860.html)

## 加固技术
* [基于Android重打包的应用程序安全策略加固系统设计](https://www.doc88.com/p-2095552902950.html)
* [Android应用安全加固技术研究与实现](https://www.doc88.com/p-6981533664632.html)
* [Android应用安全加固技术研究与实现](https://www.doc88.com/p-6478639576884.html)
* [基于android应用的安全加固系统的设计与实现](https://www.doc88.com/p-7334990393423.html)
* [android 软件安全加固技术研究与实现](https://www.doc88.com/p-0909694508682.html)
* [基于android平台的so加固技术研究](https://www.doc88.com/p-5029750143826.html)
* [加密与加壳相结合的Android应用安全加固技术的研究与实现](https://www.doc88.com/p-9416474581678.html)
* [Android应用本地代码的安全加固及安全性评估
](https://www.doc88.com/p-9738410423907.html)

## 文件加密
* [Android平台下文件透明加密技术的研究与实现](https://www.doc88.com/p-1136394037185.html)
* [基于Android平台的文件透明加密的设计与实现
](https://www.doc88.com/p-7784997422678.html)


## 重打包
* [apk反编译，smali文件修改，重新打包](https://blog.csdn.net/wxk105/article/details/62231068)

## 防泄漏
* [面向移动智能终端的DLP系统设计与实现](https://www.doc88.com/p-1933536793694.html)


## 其他EMM厂商资料

* [用友](https://iuap.yonyoucloud.com/doc/mobile_emm.html#/md-build/mobile_emm/articles/emm/2-/ydgl.md?key=%E7%A7%BB%E5%8A%A8%E7%AE%A1%E7%90%86)
* [用友UMM](https://moli.yonyoucloud.com/molidoc/docs/ummdoc/34)
* [天畅移动信贷](https://www.techown.com/mf/mobile_credit.html)
* [深信服](https://www.sangfor.com.cn/product-and-solution/sangfor-security/emm)
* [京联云企业](http://www.pekall.com/index.html)
* [联信摩贝](http://www.trustmobi.com/zh/)
* [指掌易](https://www.zhizhangyi.com/pdt_emm.html)
