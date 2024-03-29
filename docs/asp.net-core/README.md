---
title: 新书上市
date: 2020-09-21
tags:
 - ASP.NET Core
categories:
 -  .NET
---

 2018年.NET Core 2.0发布后，开始逐步学习.NET Core 并逐步在新的项目中使用ASP.NET Core。并且零零散散写的写了将近30篇学习笔记发到园子里，包括ASP.NET Core的一些”**<span style="color: #ff6600;">使用方法</span>**“和“**<span style="color: #ff6600;">源码阅读笔记</span>**”。直到后来出版社的张爽编辑问我是否考虑把这些内容写成一本书。我开始对原来的博文进行整理，去年10.1之前.NET Core 3发布，将原来写的内容更新后11月份交稿。对于我来说，写实体书和网上发博客区别太大了，我的博文偏口语化，而且对于一些简单的知识点觉得“大家都懂的”，就一带而过了，经常有“跳跃”的感觉。而在实体书中，语法措辞方面就要非常注意了，感谢出版社的编辑们的耐心指导和纠正。疫情拖慢了好多事情的进度，到现在，期待已久的书终于上市了。个人喜欢学习新技术，热衷技术分享，希望能为.NET生态的活跃尽一份绵薄之力。

     所以<span style="color: #ff6600;">本书不是一本大而全的书</span>。ASP.NET Core采用模块化设计，并提供了丰富的配置和扩展的方法，构建一个应用可以有多种不同的选择及细节定制。而<span style="color: #ff6600;">本书只会讲这“条条大路通罗马”中的一条或两条主流的路，使读者能简单、快速的了解ASP.NET Core的常用使用方法及相关的源码逻辑，快速上手。</span>**其他的细节可以在使用过程中逐步学习。

<span style="font-size: 18px; background-color: #ffffff; color: #ff6600;">错过的朋友看这里：在张队的公众号“dotNET跨平台”中继续送出五本，欢迎参与，<span style="text-decoration: underline; color: #3366ff;">[<span style="background-color: #ffffff; color: #3366ff; text-decoration: underline;">地址</span>](https://mp.weixin.qq.com/s/eClo1GBumXONYJMcYAuakw)</span>。张队的公众号每天都会更新一些前言而且专业的文章，是个学习的好地方。</span>

## 1. 本书简介：

![](/blogimages/MyBook/548134-20200919214053731-753611660.jpg)

<div class="title"> </div>
<div class="brief-intro_text"><span style="color: #ff6600;">图书简介及标题含义：</span>对于用过.NET Framework版本的MVC的朋友来说，学习ASP.NET Core就像学习使用一部新手机。手机内部组成结构可能有或大或小改变，各个元器件的性能可能有提升，元器件之间的兼容性可能更好。但在操作方式上，用户除了要学习如何使用个别的新功能以及适应系统更快的反应速度外，并没有太多改变。 </div>
<div class="brief-intro_text">　　所以本书就是把这部新手机<span style="color: #ff6600;">“拆解”</span>， 分部从使用及内部结构的角度进行讲解分析。本书内容主要分为三部分。第一部分是ASP.NET Core的使用说明，简要介绍如何使用ASP.NET Core创建项目及其与ASP.NET 4.x的不同点；第二部分是真机拆解，讲解ASP.NET Core框架的内部运行逻辑；第三部分是通过一个项目案例回顾全书知识点，并介绍如何在ASP.NET Core中对用户进行认证和授权。</div>


**第一部分：从使用角度介绍ASP.NET Core。**

第 1 章 ASP.NET Core概述： 介绍为什么要使用 ASP.NET Core，它的优势是什么，它为什么能跨平台。

第 2 章 开发环境：介绍开发环境的准备。

第 3 章 项目结构：新建一个项目，逐一介绍项目中的各个文件夹和文件的用途，从整体的角度了解项目的构成。

第 4 章 _Layout与_ViewStart：介绍两个特殊的View，了解View的加载顺序。

第 5 章 TagHelper：介绍ASP.NET Core的新成员TagHelper的使用。

第 6 章 应用的跨平台部署： 以一个例子介绍如何将项目部署到CentOS中，包括Nginx的安装和SSL的申请及设置。

**第二部分：解析ASP.NET Core框架的内部处理机制。**

**7～14章：介绍应用启动过程中都做了哪些准备;** 

第 7 章 架构概览：从宏观的角度了解ASP.NET Core 的运行机制 以及ASP.NET Core Application的架构。

第 8 章 应用启动：介绍应用启动过程中都干了些什么，一些关键组件是如何被加载的。

第 9 章 后台服务：介绍如何创建一后台服务，应用场景是什么。

第 10 章 依赖注入：介绍ASP.NET Core的依赖注入，在ASP.NET Core中，绝大部分组件都是通过依赖注入提供的。

第 11 章 日志：介绍ASP.NET Core的日志系统，日志的级别，如何写入到文件中。

第 12 章 配置：介绍常见的配置方式以及系统框架对配置的内部处理机制。

第 13 章 配置的Options模式：介绍另一种配置方式，Options模式。

第 14 章 请求处理管道：介绍ASP.NET Core的请求处理管道，这是ASP.NET Core的核心概念之一。

**15～20章：介绍应用启动后，收到用户的请求后是如何处理并返回结果的。**

第 15 章 静态文件访问与授权：介绍ASP.NET Core对静态文件的处理方式。

第 16 章 路由：介绍Endpoint路由的使用及处理机制。

第 17 章 Action的执行：介绍Action是如何被执行的。

第 18 章 Action参数的映射与模型绑定：介绍请求的参数是如何和Action中的参数一一绑定的，不同类型的参数是如何被处理的。

第 19 章 Filter详解：各种Filter是如何生效的，如何自定义Filter。

第 20 章 控制返回数据格式：如何控制Acton返回的数据类型，涉及到结果的格式转换是如何实现的。

**第三部分：案例**

第 21 章 项目实践：通过一个项目案例回顾一下本书涉及到的知识，并介绍一下如何在ASP.NET Core中对用户进行认证和授权，Swagger的使用等，是一个ASP.NET Core + 微信小程序 + MongoDB的项目，供读者参考。


## 2. 作者建议

本书主要是借助一些例子配合ASP.NET Core的源码进行讲解，建议读者也可以打开源码调试，跟着例子试一试。这样有两个好处：

第一：熟悉架构内部的处理流程。

从一个小例子起，就像调试自己的代码一样看看ASP.NET Core的内部架构是如何处理的，能够方便对本书内容的理解并加深对知识点的印象。

第二：学习ASP.NET Core的架构设计模式。

在源码学习的过程中多思考，想想为什么要这样设计？好处是什么？都用到了哪些设计模式？想想哪些地方是用来方便我们使用的脚手架，哪些地方是预留给我们做扩展的。整套源代码还是很庞大的，不求完全吃透，但大体学习下来还是受益匪浅的。

在平时的学习过程中，有两个建议：

第一：多实践，多积累。

可以想一个实用的小项目，尽可能的包含自己正在学习和近期想要学习的技术。不要担心没学过没用过，现在网上有好多分享的例子，或者读一些技术书籍。不求多久能完成，每天完成一点，一个个问题被解决的同时，也是一个个知识点的积累。

第二：多交流，多分享。

比如写博客、参与技术交流群、参加技术沙龙等，与其他编程爱好者一起学习和讨论。经常会发现某些问题别人原来有更好的处理方法，别人也可以帮助指出自己的不足。最后，要体验分享的快乐。


## 3. 章节截图


![](/blogimages/MyBook/548134-20200921103110566-1062305345.png)

![](/blogimages/MyBook/548134-20200921103153410-1380080825.png)

 ![](/blogimages/MyBook/548134-20200921103224226-388088365.png)

 ![](/blogimages/MyBook/548134-20200921103249342-732920541.png)

 ![](/blogimages/MyBook/548134-20200921103314560-2047184015.png)

 ![](/blogimages/MyBook/548134-20200921103334879-2004162800.png)

![](/blogimages/MyBook/548134-20200921103400892-1708439751.png)

 ![](/blogimages/MyBook/548134-20200921103430412-723944801.png)

 ![](/blogimages/MyBook/548134-20200921103459054-815546334.png)

 ![](/blogimages/MyBook/548134-20200921103517545-2124815069.png)

 ![](/blogimages/MyBook/548134-20200921103542090-1952556563.png)