---
title: iOS面试题1
date: 2018-04-19 23:33:41
tags: iOS面试题
---
## 背景
近期自己在负责公司iOS工程师的技术一面工作，这是一个机会，我可以在准备面试题中对自己研发踩坑进行梳理总结、对自己已有的知识体系进行打磨；面试过程也是对思维、职业规划的交流沟通，能在繁忙的研发工作中触发自己的思考。

所以这里总结一些iOS研发基础知识题目仅供参考（答案后续更新中）。

## 语言（OC）
1. ARC下不显示声明property的修饰符，默认有哪些

2. 修饰符`weak`与`assign`的区别

3. `__block`与`__weak`解释

4. KVO原理，如何手动触发KVO

5. +load与+initialize调用时机与区别

6. category的优缺点，如何添加一个property

7. property与ivar的区别

## 内存
1. 简单介绍iOS内存管理模式

2. ARC是在编译时还是运行时完成，需要注意的规则举例

3. autoreleasepool介绍，常见的使用场景

4. 举一个循环引用的例子

5. 一个object对象的内存数据结构是怎样的，block的内存数据结构呢

6. 深拷贝与浅拷贝

## Runtime
1. main()方法之前运行时都完成了哪些内容

2. SEL与IMP的区别

3. 什么时候会报unrecognized selector错误，iOS有哪些机制来避免走到这一步

4. 简单介绍一下method swizzing的过程

5. 在OC中为什么向nil调用方法不会crash

6. 对于一个objc对象实例，它的isa指针的指向关系是怎样的