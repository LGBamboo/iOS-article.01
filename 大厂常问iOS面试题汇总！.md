### 返回目录:[全网各大厂iOS面试题-题集大全](https://github.com/LGBamboo/iOS-Advanced)

# 大厂常问iOS面试题汇总！

## Runloop & KVO
## runloop

1.  app如何接收到触摸事件的
2.  为什么只有主线程的`runloop`是开启的
3.  为什么只在主线程刷新UI
4.  `PerformSelector`和`runloop`的关系
5.  如何使线程保活

## KVO

1.  实现原理
2.  如何手动关闭kvo
3.  通过KVC修改属性会触发KVO么
4.  哪些情况下使用kvo会崩溃，怎么防护崩溃
5.  kvo的优缺点

# runtime相关问题

### 结构模型

1.  介绍下runtime的内存模型（isa、对象、类、metaclass、结构体的存储信息等）
2.  为什么要设计metaclass
3.  `class_copyIvarList` & `class_copyPropertyList`区别
4.  `class_rw_t` 和 `class_ro_t` 的区别
5.  `category`如何被加载的,两个category的`load`方法的加载顺序，两个category的同名方法的加载顺序
6.  `category` & `extension`区别，能给NSObject添加Extension吗，结果如何
7.  消息转发机制，消息转发机制和其他语言的消息机制优劣对比
8.  在方法调用的时候，`方法查询-> 动态解析-> 消息转发` 之前做了什么
9.  `IMP`、`SEL`、`Method`的区别和使用场景
10.  `load`、`initialize`方法的区别什么？在继承关系中他们有什么区别
11.  说说消息转发机制的优劣

# Block

1.  `block`的内部实现，结构体是什么样的
2.  block是类吗，有哪些类型
3.  一个`int`变量被 `__block` 修饰与否的区别？block的变量截获
4.  `block`在修改`NSMutableArray`，需不需要添加`__block`
5.  怎么进行内存管理的
6.  `block`可以用`strong`修饰吗
7.  解决循环引用时为什么要用`__strong、__weak`修饰
8.  `block`发生`copy`时机
9.  `Block`访问对象类型的`auto变量`时，在`ARC和MRC`下有什么区别

# 多线程

主要以GCD为主

1.  `iOS`开发中有多少类型的线程？分别对比
2.  `GCD`有哪些队列，默认提供哪些队列
3.  `GCD`有哪些方法api
4.  `GCD`主线程 & 主队列的关系
5.  如何实现同步，有多少方式就说多少
6.  `dispatch_once`实现原理
7.  什么情况下会死锁
8.  有哪些类型的线程锁，分别介绍下作用和使用场景
9.  `NSOperationQueue`中的`maxConcurrentOperationCount`默认值
10.  `NSTimer、CADisplayLink、dispatch_source_t` 的优劣

# 性能优化

如何做启动优化，如何监控
如何做卡顿优化，如何监控
如何做耗电优化，如何监控
如何做网络优化，如何监控

# 架构设计

1.  手动埋点、自动化埋点、可视化埋点
2.  `MVC、MVP、MVVM`设计模式
3.  常见的设计模式
4.  单例的弊端
5.  常见的路由方案，以及优缺点对比
6.  如果保证项目的稳定性
7.  设计一个图片缓存框架(LRU)
8.  如何设计一个`git diff`
9.  设计一个线程池？画出你的架构图
10.  你的app架构是什么，有什么优缺点、为什么这么做、怎么改进

# 数据结构与算法

1.  八大排序算法
2.  栈&队列
3.  字符串处理
4.  链表
5.  二叉树相关操作
6.  深搜广搜
7.  基本的动态规划题、贪心算法、二分查找

### 返回目录:[全网各大厂iOS面试题-题集大全](https://github.com/LGBamboo/iOS-Advanced)

***
### 更多精选大厂 · iOS面试题答案PDF文集

![](https://upload-images.jianshu.io/upload_images/17495317-e01b6f4e054727b7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 获取加小编的iOS技术交流圈：**[937 194 184](https://jq.qq.com/?_wv=1027&k=5PARXCI)**，直接获取
