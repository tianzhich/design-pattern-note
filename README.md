<!--
 * @description: 
 * @Author: tianzhi
 * @Date: 2020-04-26 09:11:18
 * @LastEditors: tianzhi
 * @LastEditTime: 2020-04-26 11:32:13
 -->
# Design Pattern Note
[《设计模式之禅》](https://book.douban.com/subject/25843319/)读书笔记，包含第二部分：设计模式。

## 阅前请看

1. 这个Repo是我复习《设计模式之禅》第二部分：23种设计模式的读书笔记，笔记中包含了核心类图和代码，还是示例代码。由于代码都是Java版本，我用Typescript又实现了一遍示例。

2. 为什么使用Typescript？我这里主要是借助Typescript对先进特性的兼容，能够使用一些“类 Java”的面向对象编程设计。

3. 但是阅读Typescript代码时，你需要知道其实TS（或JS）本质是通过原型链来实现面向对象设计的，如果想了解更多关于JavaScript的面向设计精髓，可以看我的[这篇文章](https://juejin.im/post/5ea29046f265da47ea2be75d)。

## JavaScript强大的原型生态

下面是JavaScript强大的动态原型生态链，我将基于它，来实现《设计模式之禅》的23大设计模式。

![JavaScript的原型链](./javascript_prototype_chain.png)