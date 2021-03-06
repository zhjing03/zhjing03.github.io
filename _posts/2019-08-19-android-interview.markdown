---
layout:     post
title:      "Android知识"
subtitle:   ""
date:       2019-03-07
author:     "Aaron"
header-img: "img/post-bg-js-version.jpg"
tags:
    - interview
    - 基础
---

## Android总结

[面试题汇总](https://www.cnblogs.com/lfs2640666960/p/9707141.html)

### 一、Android基础组件

#### 1、启动流程

[Android启动流程init启动](https://jsonchao.github.io/2019/02/18/Android系统启动流程之init进程启动/)

[系统启动流程](https://www.jianshu.com/p/657336b545bd)

[App启动流程](https://blog.csdn.net/oheg2010/article/details/82826415)

[Android APK安装过程源码解析](https://blog.csdn.net/c10WTiybQ1Ye3/article/details/78098471)

#### 2、Activity　
- Activity生命周期

  https://juejin.im/post/5c90e7c36fb9a0711103cc46

  https://www.cnblogs.com/JohnTsai/p/4052676.html

- Activity的任务栈&启动模式

   [Activity启动模式与任务栈(Task)全面深入记录(上)](https://blog.csdn.net/javazejian/article/details/52071885)

  [Activity启动模式与任务栈(Task)全面深入记录(下)](https://blog.csdn.net/javazejian/article/details/52072131)

  [Activity任务栈的使用](https://blog.csdn.net/zhu522959034/article/details/79003847)

- 启动过程

  [3分钟看懂Activity启动流程](https://juejin.im/entry/58f5b68e61ff4b005807ab47)

  [App 竟然是这样跑起来的](https://juejin.im/post/5c4180566fb9a049a62cdfd7)

#### 3、Fragment

- Fragment的生命周期

  [Fragment生命周期](https://www.jianshu.com/p/01d6949f2710)

- Fragment的通讯，回退栈

  [Android Fragment 真正的完全解析(上)](http://blog.csdn.net/lmj623565791/article/details/37970961)

  [Android Fragment 你应该知道的一切(下)](https://blog.csdn.net/lmj623565791/article/details/42628537)

  [Android Fragment 你应该知道的一切](https://blog.csdn.net/lmj623565791/article/details/42628537)

* Fragment坑

  [Fragment全解析系列：那些年踩过的坑](https://www.jianshu.com/p/d9143a92ad94)

  。。。

#### 4、Service

* 什么是Service，和Thread的区别

  [Android Service完全解析，关于服务你所需知道的一切](https://blog.csdn.net/guolin_blog/article/details/11952435)

  [Service启动流程源码分析](http://codemx.cn/2018/04/24/AndroidOS010-Service/)

#### 5、广播

- Broadcast的作用和注册方式

  [BroadcastReceiver普通广播、有序广播、拦截广播、本地广播、Sticky广播、系统广播](https://blog.csdn.net/qq_30379689/article/details/53341313)

- 广播机制分析

  [Android Broadcast广播机制分析](http://gityuan.com/2016/06/04/broadcast-receiver/)

### 二、进程

#### 1、Binder机制

[Binder学习指南](https://cloud.tencent.com/developer/article/1329601)

[3分钟带你看懂android的Binder机制](https://juejin.im/post/5c444a67f265da612c5e29e1)

[写给 Android 应用工程师的 Binder 原理剖析](https://zhuanlan.zhihu.com/p/35519585)

#### 2、其他进程通信机制

[几种进程通信方式的对比总结](https://blog.csdn.net/u011240877/article/details/72863432)

### 3、进程优先级算法

[解读Android进程优先级ADJ算法](http://gityuan.com/2018/05/19/android-process-adj/)

### 三、线程

#### 1、 Android线程通信(Handler 机制)

[ThreadLocal-面试必问深度解析](https://www.jianshu.com/p/98b68c97df9b)

[ThreadLocal内存泄漏真因探究](https://www.jianshu.com/p/a1cd61fa22da)

[Handler机制的原理(知乎)](https://www.zhihu.com/question/19703357)

[图解Handler](https://blog.csdn.net/carson_ho/article/details/80175876)

[android Handler机制原理 4个组成部分源码解析](https://blog.csdn.net/csdn1125550225/article/details/80384670)

[Android消息机制源码分析](https://juejin.im/post/5aa24e17518825557207f96b)

[从源码角度简析 Android 消息机制](https://juejin.im/entry/58cb8ffe570c350058966ce4)

#### 2、Java 线程和线程池

[Android 线程和线程池一篇就够了](https://juejin.im/entry/593109e72f301e005830cd76)

[Android 线程池原理及使用](https://www.jianshu.com/p/7b2da1d94b42)

[Java 编程要点之并发（Concurrency）详解](https://waylau.com/essential-java-concurrency/)

[生产者消费者](https://juejin.im/post/5aeec675f265da0b7c072c56)

#### 3、HandlerThread、IntentService源码

[HandlerThread以及IntentService详解](https://blog.csdn.net/SEU_Calvin/article/details/52440418)

[HandlerThread和IntentService源码解析](https://juejin.im/post/5a3884406fb9a044fb07df95)

#### 4、AsyncTask

[这是一份详细的AsyncTask使用教程](https://blog.csdn.net/carson_ho/article/details/79314325)

[Android AsyncTask 详解](https://juejin.im/post/5bd3fa0ff265da0a8a6af0bc)

[大话Android多线程(六) AsyncTask知识扫盲](https://juejin.im/post/5a85a6066fb9a06337573955)

[再谈Android AsyncTask的优缺点](https://www.cnblogs.com/yanyojun/p/6414919.html)

#### 5、并发集合

ConcurrentHashMap的实现原理

### 四、内存&优化

#### 1、LRUCache

[HashMap源码分析（JDK 1.8）](https://zhuanlan.zhihu.com/p/34280652)

[HashMap源码解析（JDK8）](https://blog.csdn.net/zxt0601/article/details/77413921)

[LruCache原理和用法与LinkedHashMap](https://blog.csdn.net/qq_25806863/article/details/77548468)

[彻底解析Android缓存机制——LruCache](https://www.jianshu.com/p/b49a111147ee)

#### 2、引用

[Android 强引用，弱引用，软引用，虚引用 基本概念](https://blog.csdn.net/Mr_LiaBill/article/details/48344483)

[Android优化中弱引用WeakReference的知识](https://blog.csdn.net/printfcc/article/details/79131479)

[Android开发优化之的强引用、软引用、弱引用的使用](https://www.jianshu.com/p/8488079a939b)

#### 3、内存泄漏

[Android内存泄漏的八种可能（上）](https://www.jianshu.com/p/ac00e370f83d)

[Android内存泄漏定位、分析、解决全方案](https://segmentfault.com/a/1190000018118285)

[Android 内存泄漏查找和解决 (长篇)](https://juejin.im/entry/589542ed2f301e0069054007)

[Android 内存泄漏分析](https://juejin.im/post/5a9266246fb9a0634214becc)

[LeakCanary使用及原理](https://www.jianshu.com/p/09431b063bbf)

#### 4、OOM、ANR

[内存泄漏全解析，从此拒绝 ANR，让 OOM 远离你的身边，跟内存泄漏 say byebye](https://juejin.im/entry/58b527b5ac502e00589adefd)

[Android造成OOM 和ANR的原因及解决办法](https://www.jianshu.com/p/fcb13999558b)

[关于ANR异常捕获与分析，你所需要知道的一切](https://blog.csdn.net/codezjx/article/details/78648333)

#### 5、java内存模型

[Android基础之Java内存模型](https://www.zybuluo.com/TryLoveCatch/note/882064)

[理解Android Java垃圾回收机制](https://blog.csdn.net/omnispace/article/details/50991489)

### 五、图片加载

#### 1、Glide

[Glide源码导读](https://www.cnblogs.com/angeldevil/p/5841979.html)

[Android图片加载框架最全解析](https://blog.csdn.net/guolin_blog/article/details/53759439)

[Glide 源码分析解读-基于最新版Glide 4.9.0](https://www.jianshu.com/p/9bb50924d42a)

#### 2、Bitmap处理

[聊聊Bitmap的那些事儿](https://www.jianshu.com/p/0fbcadfd4213)

[让你彻底了解 bitmap 高效加载](https://juejin.im/entry/5937995aa22b9d00580f7891)

### 六、网络请求 

#### 1、HTTP（S）、TCP、UDP协议

[HTTP协议详解，真的很经典](https://www.cnblogs.com/li0803/archive/2008/11/03/1324746.html)

[tcp、http指南](https://juejin.im/post/5ad4094e6fb9a028d7011069)

[TCP协议与UDP协议的区别](https://blog.csdn.net/qq_18425655/article/details/51955674)

[TCP和UDP的9个区别是什么](https://blog.csdn.net/lzuacm/article/details/50945225)

[面试官问到TCP/IP怎么回答才过关](https://juejin.im/post/5b189ca0f265da6e1e1adcbf)

[TCP 为什么是三次握手四次挥手？](https://www.jianshu.com/p/7d0f91345483)

[RUDP](https://www.cnblogs.com/lixiang-share/p/7152870.html)

[常见问题](https://juejin.im/post/5a8102e0f265da4e710f5910)

[HTTPS运行流程（超详细）](https://zhuanlan.zhihu.com/p/60033345)

[理解Http请求与响应](https://www.jianshu.com/p/51a61845e66a#)

#### 2、Cookie、Session、token

https://www.cnblogs.com/wxinyu/p/9154178.html

https://www.zybuluo.com/Dukebf/note/856502

#### 3、OkHttp

[Okio深入分析——基础使用部分](https://www.jianshu.com/p/3e0935bf2d45)

[OkHttp完全解析](https://blog.csdn.net/lmj623565791/article/details/47911083)

[OkHttp使用完全教程](https://www.jianshu.com/p/ca8a982a116b)

[Android OKHttp使用详解](https://www.jianshu.com/p/2663ce3da0db)

[OkHttp总结](https://blog.csdn.net/u012881042/article/details/79759203)

[okhttp3 拦截器源码分析](https://www.jianshu.com/p/01c136a3f5af)

[OkHttp3源码解析(一 - 三)之请求流程](https://www.jianshu.com/p/02445b48c752)

[OKHttp源码解析 10篇](https://www.jianshu.com/p/82f74db14a18)

#### 3、Retrofit

[Retrofit解析1之前哨站 --10篇](https://www.jianshu.com/p/52f3ca09e2ed)

[Android Retrofit 2.0 的详细 使用攻略](https://www.jianshu.com/p/a3e162261ab6)

[Android：手把手带你 深入读懂 Retrofit 2.0 源码](https://www.jianshu.com/p/0c055ad46b6c)

#### 4、常用加密算发

[浅谈常见的七种加密算法及实现](https://juejin.im/post/5b48b0d7e51d4519962ea383#heading-19)

### 七、存储

#### 1、sqlite数据库

[Android可能出现的SQL注入以及防范](https://blog.csdn.net/fjnu_se/article/details/90728113)

[SQLite优化总结](https://www.cnblogs.com/xuecanmeng/p/5459334.html)

[索引优化](https://www.jianshu.com/p/ceceb9638d2e)

#### 2、DiskLruCache

[DiskLruCache完全解析，硬盘缓存的最佳方案](https://blog.csdn.net/guolin_blog/article/details/28863651)

### 八、View相关

#### 1、View绘制流程

[View体系——View的绘制流程](https://www.jianshu.com/p/a5ea8174d912)

[View绘制流程（2篇）](https://www.jianshu.com/p/3b6d0c17cdb0)

[Android自定义View之requestLayout方法和invalidate方法](https://www.jianshu.com/p/a6ea264a07b8)

[为什么你的自定义View wrap_content不起作用？](https://blog.csdn.net/carson_ho/article/details/62037760)

#### 2、View绘制生命周期

[Android View与Activity生命周期的关系](https://www.jianshu.com/p/88054f481f17)

[View.post()](https://www.cnblogs.com/dasusu/p/8047172.html)

#### 3、事件分发机制

[图解 Android 事件分发机制](https://www.jianshu.com/p/e99b5e8bd67b)

[Android 如何处理滑动冲突](https://www.jianshu.com/p/dbf1c6c51c76)

[Android事件分发机制详解：史上最全面、最易懂](https://www.jianshu.com/p/38015afcdb58)

[android中的事件传递和处理机制](https://www.cnblogs.com/fuly550871915/p/4983682.html)

#### 4、动画

[Android：手把手带你全面了解 动画的原理&使用](https://juejin.im/entry/5acabe416fb9a028dc414c6d)

#### 5、RecyclerView相关

[Android 控件 RecyclerView](https://www.jianshu.com/p/4f9591291365)

[【进阶】RecyclerView源码解析 5篇](https://www.jianshu.com/p/c52b947fe064)

### 九、热门技术

#### 1、插件化 原理

[插件化原理](https://mp.weixin.qq.com/s/Uwr6Rimc7Gpnq4wMFZSAag?utm_source=androidweekly&utm_medium=website)

##### VirtualAPK

[VirtualApk 资源篇](https://www.notion.so/1fce1a910c424937acde9528d2acd537)

[VirtualApk源码解析](https://blog.csdn.net/lmj623565791/article/details/75000580)

#### 2、热修复

[热修复基本原理](https://blog.csdn.net/csdn_lqr/article/details/78534065)

[各个热修复比较](https://www.cnblogs.com/popfisher/p/8543973.html)

#### 4、RxJava

### 十、应用内通信组件

#### 1、EventBus

#### 2、模块化、组件化

### 十一、设计

#### 0、uml

https://design-patterns.readthedocs.io/zh_CN/latest/read_uml.html

#### 1、MVC、MVP、MVVM

[选择恐惧症的福音！教你认清MVC，MVP和MVVM]([http://zjutkz.net/2016/04/13/%E9%80%89%E6%8B%A9%E6%81%90%E6%83%A7%E7%97%87%E7%9A%84%E7%A6%8F%E9%9F%B3%EF%BC%81%E6%95%99%E4%BD%A0%E8%AE%A4%E6%B8%85MVC%EF%BC%8CMVP%E5%92%8CMVVM/](http://zjutkz.net/2016/04/13/选择恐惧症的福音！教你认清MVC，MVP和MVVM/))

[MVC、MVP、MVVM，我到底该怎么选？](https://juejin.im/post/5b3a3a44f265da630e27a7e6)

[Android ViewModel+liveData+lifecycle+databinding打造MVVM](https://juejin.im/post/5cabf2925188251b0b7a5baa)

#### 2、单例

#### 3、设计SDK考虑的事情

[如何开发一个优秀的SDK](http://www.androidchina.net/7053.html)

#### 4、设计模式

[学习并理解 23 种设计模式](https://github.com/xietao3/Study-Plan/blob/master/DesignPatterns/README.md)

[精讲版本](http://c.biancheng.net/view/1317.html)

[秒懂系列](https://blog.csdn.net/ShuSheng0007)



##### 创建型

##### 结构型

##### 行为





