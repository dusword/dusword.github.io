---
title: JVM类加载机制
tags:
  - jvm
  - 性能调优
categories:
  - 性能调优
  - jvm性能调优
keywords:
  - jvm
  - 性能调优
  - 类加载机制
description: JVM类加载机制
abbrlink: de06556f
date: 2025-01-20 00:34:15
updated: 2025-01-20 00:34:15
---
## 从JDK源码级别彻底剖析JVM类加载机制

当我们用java命令运行某个类的main函数启动程序时，首先需要通过类加载器把主类加载到
JVM。
![图片](类加载过程.png)
