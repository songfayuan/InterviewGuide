点击订阅[Java 面试进阶指南](https://xiaozhuanlan.com/javainterview?rel=javaguide)(专为 Java 面试方向准备)。[为什么要弄这个专栏?](https://shimo.im/./9BJjNsNg7S4dCnz3/)

<h1 align="center">Java 学习/面试指南</h1>
<p align="center">
<a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
	<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/logo - 副本.png" width=""/>
</a>

## 目录

- [Java](#java)
  - [基础](#基础)
  - [容器](#容器)
  - [并发](#并发)
  - [JVM](#jvm)
  - [I/O](#io)
  - [Java 8](#java-8)
  - [编程规范](#编程规范)
- [网络](#网络)
- [操作系统](#操作系统)
  - [Linux 相关](#linux相关)
- [数据结构与算法](#数据结构与算法)
  - [数据结构](#数据结构)
  - [算法](#算法)
- [数据库](#数据库)
  - [MySQL](#mysql)
  - [Redis](#redis)
- [系统设计](#系统设计)
  - [设计模式(工厂模式、单例模式 ... )](#设计模式)
  - [常用框架(Spring、Zookeeper ... )](#常用框架)
  - [数据通信(消息队列、Dubbo ... )](#数据通信)
  - [网站架构](#网站架构)
- [面试指南](#面试指南)
  - [备战面试](#备战面试)
  - [常见面试题总结](#常见面试题总结)
  - [面经](#面经)
- [工具](#工具)
  - [Git](#git)
  - [Docker](#Docker)
- [资料](#资料)
  - [书单](#书单)
  - [Github 榜单](#Github榜单)
- [待办](#待办)
- [说明](#说明)

## Java

### 基础

- [Java 基础知识回顾](java/Java基础知识.md)
- [Java 基础知识疑难点总结](java/Java疑难点.md)
- [J2EE 基础知识回顾](java/J2EE基础知识.md)

### 容器

- [Java 容器常见面试题/知识点总结](java/collection/Java集合框架常见面试题.md)
- [ArrayList 源码学习](java/collection/ArrayList.md)
- [LinkedList 源码学习](java/collection/LinkedList.md)
- [HashMap(JDK1.8)源码学习](java/collection/HashMap.md)

### 并发

- [Java 并发基础常见面试题总结](java/Multithread/JavaConcurrencyBasicsCommonInterviewQuestionsSummary.md)
- [Java 并发进阶常见面试题总结](java/Multithread/JavaConcurrencyAdvancedCommonInterviewQuestions.md)
- [并发容器总结](java/Multithread/并发容器总结.md)
- [乐观锁与悲观锁](essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
- [JUC 中的 Atomic 原子类总结](java/Multithread/Atomic.md)
- [AQS 原理以及 AQS 同步组件总结](java/Multithread/AQS.md)

### JVM

- [一 Java 内存区域](java/jvm/Java内存区域.md)
- [二 JVM 垃圾回收](java/jvm/JVM垃圾回收.md)
- [三 JDK 监控和故障处理工具](java/jvm/JDK监控和故障处理工具总结.md)
- [四 类文件结构](java/jvm/类文件结构.md)
- [五 类加载过程](java/jvm/类加载过程.md)
- [六 类加载器](java/jvm/类加载器.md)

### I/O

- [BIO,NIO,AIO 总结 ](java/BIO-NIO-AIO.md)
- [Java IO 与 NIO 系列文章](java/Java%20IO与NIO.md)

### Java 8

- [Java 8 新特性总结](java/What's%20New%20in%20JDK8/Java8Tutorial.md)
- [Java 8 学习资源推荐](java/What's%20New%20in%20JDK8/Java8教程推荐.md)

### 编程规范

- [Java 编程规范](java/Java编程规范.md)

## 网络

- [计算机网络常见面试题](network/计算机网络.md)
- [计算机网络基础知识总结](network/干货：计算机网络知识总结.md)
- [HTTPS 中的 TLS](network/HTTPS中的TLS.md)

## 操作系统

### Linux 相关

- [后端程序员必备的 Linux 基础知识](operating-system/后端程序员必备的Linux基础知识.md)
- [Shell 编程入门](operating-system/Shell.md)

## 数据结构与算法

### 数据结构

- [数据结构知识学习与面试](dataStructures-algorithms/数据结构.md)

### 算法

- [算法学习资源推荐](dataStructures-algorithms/算法学习资源推荐.md)
- [几道常见的字符串算法题总结 ](dataStructures-algorithms/几道常见的子符串算法题.md)
- [几道常见的链表算法题总结 ](dataStructures-algorithms/几道常见的链表算法题.md)
- [剑指 offer 部分编程题](dataStructures-algorithms/剑指offer部分编程题.md)
- [公司真题](dataStructures-algorithms/公司真题.md)
- [回溯算法经典案例之 N 皇后问题](dataStructures-algorithms/Backtracking-NQueens.md)

## 数据库

### MySQL

- [MySQL 学习与面试](database/MySQL.md)
- [一千行 MySQL 学习笔记](database/一千行MySQL命令.md)
- [MySQL 高性能优化规范建议](database/MySQL高性能优化规范建议.md)
- [数据库索引总结](database/MySQL%20Index.md)
- [事务隔离级别(图文详解)](<database/事务隔离级别(图文详解).md>)
- [一条 SQL 语句在 MySQL 中如何执行的](database/一条sql语句在mysql中如何执行的.md)

### Redis

- [Redis 总结](database/Redis/Redis.md)
- [Redlock 分布式锁](database/Redis/Redlock分布式锁.md)
- [如何做可靠的分布式锁，Redlock 真的可行么](database/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)

## 系统设计

### 设计模式

- [设计模式系列文章](system-design/设计模式.md)

### 常用框架

#### Spring

- [Spring 学习与面试](system-design/framework/spring/Spring.md)
- [Spring 常见问题总结](system-design/framework/spring/SpringInterviewQuestions.md)
- [Spring 中 bean 的作用域与生命周期](system-design/framework/spring/SpringBean.md)
- [SpringMVC 工作原理详解](system-design/framework/spring/SpringMVC-Principle.md)
- [Spring 中都用到了那些设计模式?](system-design/framework/spring/Spring-Design-Patterns.md)

#### ZooKeeper

- [ZooKeeper 相关概念总结](system-design/framework/ZooKeeper.md)
- [ZooKeeper 数据模型和常见命令](system-design/framework/ZooKeeper数据模型和常见命令.md)

### 数据通信

- [数据通信(RESTful、RPC、消息队列)相关知识点总结](system-design/data-communication/summary.md)
- [Dubbo 总结：关于 Dubbo 的重要知识点](system-design/data-communication/dubbo.md)
- [消息队列总结](system-design/data-communication/message-queue.md)
- [RabbitMQ 入门](system-design/data-communication/rabbitmq.md)
- [RocketMQ 的几个简单问题与答案](system-design/data-communication/RocketMQ-Questions.md)

### 网站架构

- [一文读懂分布式应该学什么](system-design/website-architecture/分布式.md)
- [8 张图读懂大型网站技术架构](system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [【面试精选】关于大型网站系统架构你不得不懂的 10 个问题](system-design/website-architecture/【面试精选】关于大型网站系统架构你不得不懂的10个问题.md)

## 面试指南

### 备战面试

- [【备战面试 1】程序员的简历就该这样写](essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)
- [【备战面试 2】初出茅庐的程序员该如何准备面试？](essential-content-for-interview/PreparingForInterview/interviewPrepare.md)
- [【备战面试 3】7 个大部分程序员在面试前很关心的问题](essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)
- [【备战面试 4】Github 上开源的 Java 面试/学习相关的仓库推荐](essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)
- [【备战面试 5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](essential-content-for-interview/PreparingForInterview/如果面试官问你“你有什么问题问我吗？”时，你该如何回答.md)
- [【备战面试 6】美团面试常见问题总结（附详解答案）](essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)

### 常见面试题总结

- [第一周（2018-8-7）](essential-content-for-interview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (为什么 Java 中只有值传递、==与 equals、 hashCode 与 equals)
- [第二周（2018-8-13）](<essential-content-for-interview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md>)(String 和 StringBuffer、StringBuilder 的区别是什么？String 为什么是不可变的？、什么是反射机制？反射机制的应用场景有哪些？......)
- [第三周（2018-08-22）](java/collection/Java集合框架常见面试题.md) （Arraylist 与 LinkedList 异同、ArrayList 与 Vector 区别、HashMap 的底层实现、HashMap 和 Hashtable 的区别、HashMap 的长度为什么是 2 的幂次方、HashSet 和 HashMap 区别、ConcurrentHashMap 和 Hashtable 的区别、ConcurrentHashMap 线程安全的具体实现方式/底层具体实现、集合框架底层数据结构总结）
- [第四周(2018-8-30).md](<essential-content-for-interview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md>) （主要内容是几道面试常问的多线程基础题。）

### 面经

- [5 面阿里,终获 offer(2018 年秋招)](essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服 2019 实习生面经总结(已拿口头 offer)](<essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结(已拿口头offer).md>)
- [2019 年蚂蚁金服、头条、拼多多的面试总结](essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)

## 工具

### Git

- [Git 入门](tools/Git.md)

### Docker

- [Docker 入门](tools/Docker.md)
- [一文搞懂 Docker 镜像的常用操作！](tools/Docker-Image.md)

## 资料

### 书单

- [Java 程序员必备书单](data/java-recommended-books.md)

### Github 榜单

- [Java 项目月榜单](github-trending/JavaGithubTrending.md)

---

## 待办

- [x] [Java 8 新特性总结](./java/What's%20New%20in%20JDK8/Java8Tutorial.md)
- [x] [Java 8 新特性详解](./java/What's%20New%20in%20JDK8/Java8教程推荐.md)
- [ ] Java 多线程类别知识重构(---正在进行中---)
- [x] [BIO,NIO,AIO 总结 ](./java/BIO-NIO-AIO.md)
- [ ] Netty 总结(---正在进行中---)
- [ ] 数据结构总结重构(---正在进行中---)

## 联系我

添加我的微信备注“Github”,回复关键字 **“加群”** 即可入群。

![我的微信](https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-2/JavaGuide.jpg)

## 公众号

- 如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号。
- 由本文档衍生的专为面试而生的《Java 面试突击》V2.0 PDF 版本公众号后台回复 **"Java 面试突击"** 即可免费领取！
- 一些 Java 工程师常用学习资源公众号后台回复关键字 **“1”** 即可免费无套路获取。

<p align="center">
<img src="https://user-gold-cdn.xitu.io/2018/11/28/167598cd2e17b8ec?w=258&h=258&f=jpeg&s=27334" width=""/>
</p>
