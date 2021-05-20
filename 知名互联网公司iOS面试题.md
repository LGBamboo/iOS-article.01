## 知名互联网公司iOS面试题

**猿辅导 3.2**

1.  组件化架构介绍？
2.  `WKWebView`白板问题？如何收到`WKWebView`崩溃？`OC`与`JS`如何交互？如何保证`JS`收到`OC`执行成功的信息？(交互可靠性)
3.  `App crash`信息收集，以及如何保证`app`不崩溃？
4.  日志系统构建？实时上传日志与延时上传？
5.  `Swift`如何实现`KVO`?
6.  `GCD`实现最大线程并发数？(使用`dispatch_semaphore`)、手动实现队列最大并发
7.  算法：

*   删除排序链表中的重复元素
*   整型字符串相加(考虑进位问题)

**好未来 3.4**

1.  `For in`循环内增加删除元素，引起的问题？
2.  精准统计`ViewController`页面加载耗时，从`viewdidload->viewdidappear`？
3.  `wkwebview`性能优化

**贝壳找房 3.5**

1.  项目中的反作弊方案
2.  组件化技术选型考虑(url调度方案优缺点)、`target-action`组件方案的优缺点
3. ` runtime`的`isa`、`weak`在`runtime`的结构：用`weak`修饰`obj`的`key`和`value`分别是啥？
4.  `category`的`runtime`结构里为什么不能增加成员变量：成员变量在编译的时候决定，运行时不能修改
5.  `autoreleasepool`的底层原理、`autoreleasepoolpage`的结构

**快手 3.7**

1.  `Load`方法调用时机，什么时候被添加到`runtime`？`A`类调用`B`类，`A`没有被`import`，`B`被`Aimport`，那`A`和`B`的`load`、`initialize`方法是否被调用？
2.  `https`和`http`的区别？`ssl`是什么?与`tls`的区别？
3.  `Realm`数据库底层实现原理？`coredata`是数据库吗？对象型数据库与关系型的区别？
4.  算法：归并排序
5.  对跨平台开发如`flutter`、`React Native`的看法？

**蘑菇街 3.10**

1.  架构升级组件化方案（`Target-Action`方案：[https://casatwy.com/?from=inf&wvr=5&loc=infblog](https://link.zhihu.com/?target=https%3A//casatwy.com/%3Ffrom%3Dinf%26wvr%3D5%26loc%3Dinfblog)）
2.  `WebView`性能优化（[https://tech.meituan.com/2017/06/09/webviewperf.html](https://link.zhihu.com/?target=https%3A//tech.meituan.com/2017/06/09/webviewperf.html)）
3.  `Http`与`Socket`？`socket`长连接如何保持？以及连接如何关闭
4.  `IM`即时通讯的原理
5.  `AFNetworking`源码：网络状态监听的实现、`NSURLSection`与`NSURLConnection`的区别？
6.  iOS13的适配？([https://juejin.im/post/5d00af64e51d455d88219ee2](https://link.zhihu.com/?target=https%3A//juejin.im/post/5d00af64e51d455d88219ee2))

***
### 更多精选大厂 · iOS面试题答案PDF文集

![](https://upload-images.jianshu.io/upload_images/17495317-e01b6f4e054727b7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 获取加小编的iOS技术交流圈：**[937 194 184](https://jq.qq.com/?_wv=1027&k=5PARXCI)**，直接获取
