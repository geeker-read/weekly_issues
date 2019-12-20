# 极客阅读周刊: 第 1 期

「极客阅读周刊」分享值得阅读的技术文章，每周五发布。

> 「极客阅读 App」汇聚了国内外最优质的技术博客、产品动态、公众号文章。开发者可以在极客阅读一站式的阅读到来自互联网技术大咖的文章。[点击去了解和下载 App](https://www.yuque.com/docs/share/74c8695f-d2ce-4dbd-aee1-b92be37ecdf4?#)

## 文章

### [GraphQL-BFF：微服务背景下的前后端数据交互方案](https://weibo.com/ttarticle/p/show?id=2309404398215846821987&sudaref=39.106.34.209&display=0&retcode=6102) - By: 工业聚


> 随着多终端、多平台、多业务形态、多技术选型等各方面的发展，前后端的数据交互，日益复杂。
>
> 同一份数据，可能以多种不同的形态和结构，在多种场景下被消费。
>
> 在理想情况下，这些复杂性可以全部由后端承担。前端只管从后端接口里，拿到已然整合完善的数据。
>
> 然而，不管是因为后端的领域模型，还是因为微服务架构。作为前端，我们感受到的是，后端提供的接口，越发不够前端友好。我们必须自行组合多个后端接口，才能获取到完整的数据结构。
>
> 面向领域模型的后端需求，跟面向页面呈现的前端需求，出现了不可调和的矛盾。
>
> 在这种背景下，本着谁受益谁开发的原则。我们最后选择使用 Node.js 搭建专门服务于前端页面呈现的后端，亦即 Backend-For-Frontend，简称 BFF。
>
> 我们面临了很多不同的技术选型，主要围绕在权衡 RESTful API 和 GraphQL。
>
> 正如标题所示，我们最终选用的是 GraphQL as BFF。
>
> 本文将介绍我们对 GraphQL 所作的考察、探索、权衡、技术选型与设计等多方面的内容，希望能给大家带来一些启发。

### [支付宝的架构到底有多牛逼！还没看完我就跪了！](https://mp.weixin.qq.com/s?__biz=MzAxNjk4ODE4OQ==&mid=2247487629&idx=2&sn=c13621174af486f1f83ca84c053dd939&chksm=9bed31ffac9ab8e99b9a2c4207c9898a4ad73aff230b7bf815fdddef38e831c0fa351ce4e9b2#rd) By: 方志朋


> 自 2008 年双 11 以来，在每年双 11 超大规模流量的冲击上，蚂蚁金服都会不断突破现有技术的极限。2010 年双 11 的支付峰值为 2 万笔/分钟，到 2017 年双 11 时这个数字变为了 25.6 万笔/秒。
>
> 2018 年双 11 的支付峰值为 48 万笔/秒，2019 年双 11 支付峰值为 54.4 万笔/秒，创下新纪录，是 2009 年第一次双 11 的 1360 倍。
> 
> 在如此之大的支付 TPS 背后除了削峰等锦上添花的应用级优化，最解渴最实质的招数当数基于分库分表的单元化了，蚂蚁技术称之为 LDC（逻辑数据中心）。
> 
> 本文不打算讨论具体到代码级的分析，而是尝试用最简单的描述来说明其中最大快人心的原理。
> 
> 我想关心分布式系统设计的人都曾被下面这些问题所困扰过：
> * 支付宝海量支付背后最解渴的设计是啥？换句话说，实现支付宝高 TPS 的最关键的设计是啥？
> * LDC 是啥？LDC 怎么实现异地多活和异地灾备的？
> * CAP 魔咒到底是啥？P 到底怎么理解？
> * 什么是脑裂？跟 CAP 又是啥关系？
> * 什么是 PAXOS，它解决了啥问题？
> * PAXOS 和 CAP 啥关系？PAXOS 可以逃脱 CAP 魔咒么？
> * Oceanbase 能逃脱 CAP 魔咒么？

### [盘点ES7、ES8、ES9、ES10新特性](https://github.com/ljianshu/Blog/issues/76) By: ljianshu


> 从 ECMAScript 2016（ES7）开始，版本发布变得更加频繁，每年发布一个新版本，好在每次版本的更新内容并不多，本文会细说这些新特性，尽可能和旧知识相关联，帮你迅速上手这些特性。

> ![](https://cdn.nlark.com/yuque/0/2019/png/639317/1576213258123-5567a7da-f206-4f51-a827-ca5c8388e0a8.png)

### [你不知道的 JSON.stringify() 的威力](https://github.com/NieZhuZhu/Blog/issues/1) By: 弹铁蛋同学


> 其实有很多有用的东西，当时学习了，也记住了，但是时间久了就是记不住，所以导致在日常开发中总是想不起来原来这个东西可以这么用，而去选择了更加复杂和麻烦的方式。其实我们日常学习的知识就是拿来用的，即使你今天把知识点背下来了，没有去思考这个知识点我们可以用来干嘛，不需要几天就会慢慢地忘掉。所以今天我们来了解一下在日常学习时你遗漏掉或者忘掉或者没有思考过的你不知道的 JSON.stringify() 的威力。

### [你真的懂 package.json 吗?](https://juejin.im/post/5dea1095e51d4558083322e2) By: MasonEast


> 在Node.js中，模块是一个库或框架，也是一个 Node.js 项目。Node.js 项目遵循模块化的架构，当我们创建了一个 Node.js 项目，意味着创建了一个模块，这个模块的描述文件，被称为 package.json。
我之前看别人项目中 package.json 文件的 scripts 这样写：
>
> ```
> "dev": "rimraf \"config/.conf.json\" && rimraf \"src/next.config.js\" && cpx \".conf.json\" \"config/\" && nodemon server/index.ts",
> "clean": "rimraf ./dist && mkdir dist",
> "prebuild": "npm run clean",
> "build": "cross-env NODE_ENV=production webpack"
> ```
>
> 当时看的有点懵， 于是又补了下相关知识， 发现原来package.json有很多地方被我们忽略了呀， 如果有道友和我一样有点懵的话， 本文不容错过。

### [9 道题自查你是否掌握 JavaScript Promises（英文）](https://danlevy.net/javascript-promises-quiz/)


> 检查下自己是否真的理解透露了 Promise

### [逐行剖析 Vue.js 源码，九大模块，逐个击破](https://nlrx-wjc.github.io/Learn-Vue-Source-Code/)


> 本系列博文将用来记录博主对 Vue 源码的整个学习过程，以及自己对源码的一些理解。一方面开阔自己的知识视野，另一方面也希望这些文字能够带给他人些许帮助。

### [一文详解微服务架构](https://www.cnblogs.com/skabyy/p/11396571.html) By: 古霜卡比


> 本文将介绍微服务架构和相关的组件，介绍他们是什么以及为什么要使用微服务架构和这些组件。本文侧重于简明地表达微服务架构的全局图景，因此不会涉及具体如何使用组件等细节。
> 
> 要理解微服务，首先要先理解不是微服务的那些。通常跟微服务相对的是单体应用，即将所有功能都打包成在一个独立单元的应用程序。从单体应用到微服务并不是一蹴而就的，这是一个逐渐演变的过程。本文将以一个网上超市应用为例来说明这一过程。

本期周刊同时同步到微信公众号(geeker-read)、[语雀](https://www.yuque.com/books/share/8cc684ae-4d87-483b-82e5-5128e32d4cef?#)和 [GitHub](https://github.com/geeker-read/weekly_issues)。

<img src="https://cdn.nlark.com/yuque/0/2019/png/639317/1576222303738-6abc107b-8e76-4433-b504-87a16df22f71.png" width="150" />

(扫一扫关注公众号)
