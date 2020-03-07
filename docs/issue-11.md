# 极客阅读周刊: 第 11 期

<br /><br />
<img width="500" src="https://cdn.nlark.com/yuque/0/2020/png/639317/1579223265494-6784ed04-76db-4281-896b-e1a9df34564d.png#align=left&display=inline&height=176&name=image.png&originHeight=352&originWidth=1080&size=85689&status=done&style=none&width=540">

「极客阅读周刊」分享值得阅读的技术文章，每周五发布。

> 「极客阅读 」汇聚了国内外最优质的技术博客、产品动态、公众号文章。开发者可以在极客阅读一站式的阅读到来自互联网技术大咖的文章。
> <br /><br />
> <img width="400" src="https://cdn.nlark.com/yuque/0/2020/png/639317/1578021644053-627fd9fc-33fc-43dd-94bd-df2c1af39b10.png?x-oss-process=image/resize,w_1458" />
> <br /><br />
> **「极客阅读 」官网：[geeker-read.com](https://geeker-read.com)**

<br /><br />

### [今日头条算法原理详解（全）](https://mp.weixin.qq.com/s?__biz=MjM5NDkxMTgyNw==&mid=2653059940&idx=1&sn=b6d9ec48ea31245192d1a592ef96bc04&chksm=bd5658588a21d14e0db7a65bc5d4707294392cac7ca7c94d272b977404932281e5030d4fb101&scene=27#wechat_redirect)

> 今日头条委托资深算法架构师曹欢欢博士，公开今日头条的算法原理，以期推动整个行业问诊算法、建言算法；通过让算法透明，来消除各界对算法的误解，并逐步推动整个行业让算法更好的造福社会。


![](https://imgkr.cn-bj.ufileos.com/bb75198f-0f3f-4b98-bd8b-42d4e80d0cd9.png)

<br /><br />

### [MySQL 数据库之互联网常用分库分表方案](https://www.cnblogs.com/littlecharacter/p/9342129.html)

> 1. 分库分表，首先得知道瓶颈在哪里，然后才能合理地拆分（分库还是分表？水平还是垂直？分几个？）。且不可为了分库分表而拆分。
> 2. 选 key 很重要，既要考虑到拆分均匀，也要考虑到非 partition key 的查询。
> 3. 只要能满足需求，拆分规则越简单越好。

![](https://imgkr.cn-bj.ufileos.com/5fc6514e-53af-48d0-8517-9651fb50b5c4.png)

<br /><br />

### [秒杀系统设计与实现.互联网工程师进阶与分析](https://github.com/qiurunze123/miaosha)

> 高并发大流量如何进行秒杀架构知识系统的整理。

![](https://imgkr.cn-bj.ufileos.com/d6e810e6-ef9b-4d2f-95ca-d75feaf0f2c5.png)

![](https://imgkr.cn-bj.ufileos.com/a1810349-abb4-4787-b98d-ebbfa4e483d7.png)

<br /><br />

### [看优酷 Node 重构之路，Serverless SSR 未来可期](https://mp.weixin.qq.com/s/ofLVwcCvbWLCfUD7ldvm5A)

> 在 2017 年底，优酷只有 Passport 和土豆的部分页面用 Node.js，PC 和 H5 核心页面还都是 PHP 模板渲染。而最近 2 年，基于阿里巴巴的技术体系，我们对 PC、H5 多端进行了技术改造。在 2019 年，React SSR 第一次且成功地扛起双 11 重任，具有一定意义。

![](https://imgkr.cn-bj.ufileos.com/a23283f3-acb5-4af1-a0b5-e277ad8d4b7c.png)

<br /><br />

### [DDD 领域驱动设计基本理论知识总结](https://www.cnblogs.com/netfocus/archive/2011/10/10/2204949.html)

> 2004 年 Eric Evans 发表 Domain-Driven Design –Tackling Complexity in the Heart of Software （领域驱动设计），简称 Evans DDD。领域驱动设计分为两个阶段：
>
>以一种领域专家、设计人员、开发人员都能理解的通用语言作为相互交流的工具，在交流的过程中发现领域概念，然后将这些概念设计成一个领域模型；
> 由领域模型驱动软件设计，用代码来实现该领域模型；
> 
> 由此可见，领域驱动设计的核心是建立正确的领域模型。

![](https://imgkr.cn-bj.ufileos.com/61938855-340a-4295-9328-8a38be82ee1e.png)

<br /><br />

### [携程 Hadoop 跨机房架构实践](https://mp.weixin.qq.com/s/z4G0A6axVrd9dpefEh6BsQ)

> **作者：昱康**，携程架构师，对分布式计算和存储、调度、查询引擎、在线离线混部、高并发等方面有浓厚兴趣。
>
> 本文将分享携程 Hadoop 跨机房架构实践，包含 Hadoop 在携程的发展情况，整个跨机房项目的背景，我们跨机房的架构选型思路和落地实践，相关的改造和对未来的展望，希望给大家一些启迪。

![](https://imgkr.cn-bj.ufileos.com/27b7c490-dd7a-4aa3-812c-f4a9765d825f.png)

<br /><br />

### [Go 语言 101](https://gfw.go101.org/article/101.html)

> 《Go 语言 101》是一本着墨于 Go 语法和语义的编程指导书（Go 1.14 就绪）。 这本书也搜集了很多 Go 编程中的细节和讲解了一些底层实现原理（不含具体实现细节）。 这本书的宗旨是尽量帮助 Go 程序员更深和更全面地理解 Go。 此书同时适合 Go 初学者和有一定经验的 Go 程序员阅读。

![](https://imgkr.cn-bj.ufileos.com/992c8950-adf1-4058-b713-4b94d534263a.png)

<br /><br />

### [Go 语言之禅](https://studygolang.com/articles/26789)

> 本文来自 [David](https://twitter.com/davecheney) 在 GopherCon Israel 2020 上的演讲。文章很长，如果您希望阅读精简版，请移步到 [the-zen-of-go.netlify.com](https://the-zen-of-go.netlify.com/)。阅读英文原版：[The Zen of Go](https://dave.cheney.net/2020/02/23/the-zen-of-go)。

![](https://imgkr.cn-bj.ufileos.com/8280a21f-4ca0-4ed4-952c-83ebc26ab2e6.png)

### [快速全面掌握 Kafka](https://mp.weixin.qq.com/s/9fJchPJa_raHSkvo29bkEA)

> Kafka 是目前主流的分布式消息引擎及流处理平台，经常用做企业的消息总线、实时数据管道，本文挑选了 Kafka 的几个核心话题，帮助大家快速掌握 Kafka。

![](https://imgkr.cn-bj.ufileos.com/aead63b8-b77b-4415-a52c-45d744cc9be7.png)

<br /><br />

### [Advanced usage of Python requests - timeouts, retries, hooks](https://findwork.dev/blog/advanced-usage-python-requests-timeouts-retries-hooks/)

> requests 在Python社区中简单、直观且无处不在。 与 HTTP 交互的大多数程序都使用标准库中的请求或 urllib3。

![](https://imgkr.cn-bj.ufileos.com/17ef40fb-8249-474d-90d6-ffbceda7c559.png)

<br /><br />

### [如何设计便于单手操作的手机 App (英文)](https://www.smashingmagazine.com/2020/02/design-mobile-apps-one-hand-usage/)

> 真实 app 案例，图文并茂。有太多只能单手操作手机的应用场景了。

![](https://imgkr.cn-bj.ufileos.com/e6a86223-4a8d-434a-aec2-3bbbfe9045bb.png)

<br /><br />

### [闲鱼基于 flutter 技术的架构演进与创新](https://yq.aliyun.com/live/1213)

> **演讲：于佳**，花名宗心，闲鱼技术团队客户端负责人。
>
> 随着去年 Flutter beta 版本在端侧的可行性验证完成，闲鱼团队进行了 Flutter 的架构全面升级和研发智能化的建设。在架构演进的过程中，产生了较多的技术创新和实践。

![](https://imgkr.cn-bj.ufileos.com/8a4143ec-a5c6-445e-a5ca-7e00ad6cf9fd.png)

<br /><br />

### [图卷积网络 (GCN) 新手村完全指南](https://zhuanlan.zhihu.com/p/54505069)

> 图卷积网络 Graph Convolutional Network，简称 GCN，最近两年大热，取得不少进展。
>
> 最近，清华大学孙茂松教授组在 arXiv 发布了论文 Graph Neural Networks: A Review of Methods and Applications，作者对现有的 GNN 模型做了详尽且全面的综述。GCN 就是 GNN 中的一种重要的分支。
>
> 但是对于 GCN 的萌新，看着这篇综述可能还是会困难重重、不知所措。
>
> 写这篇文章的目的，就是帮助萌新们掌握GCN的重要概念和理论，走出新手村。

![](https://imgkr.cn-bj.ufileos.com/2ef54c87-0e96-4106-acb2-bb20bf9f5bc2.gif)

<br /><br />

### [金丝雀发布、滚动发布、蓝绿发布到底有什么差别？关键点是什么？](https://www.cnblogs.com/apanly/p/8784096.html)

> 作为技术人员，大家可能听说过“滚动发布”和“蓝绿发布”等术语，但是很多人并不清楚这些术语背后的原理。本文试图总结当前主流的发布策略，每个的优劣，适用性，让开发人员特别是架构师对现代发布技术有一个更为清晰全面的认识，让大家能够根据自己的企业上下文，对发布策略做出正确的选型和实践。

![](https://imgkr.cn-bj.ufileos.com/c2c77ed8-8ed4-472a-a021-1ca6bffee087.png)

<br /><br />

### [微前端在美团外卖的实践](https://mp.weixin.qq.com/s/l17Uo6Q7up44uZI_VojFzw)

> 自美团外卖广告团队，他们参考业界优秀方案，同时也深度结合了广告端实际业务的情况，提出了基于 React 的中心路由基座式微前端方案。

![](https://imgkr.cn-bj.ufileos.com/bf971697-5574-4626-b941-54bc04e2a31b.png)

<br /><br />

### [ES2020 Features in simple examples](https://carloscaballero.io/es2020-features-in-simple-examples/)

> 自 2015 年发布 ES6 以来，JavaScript 一直在快速发展，每次迭代中都会出现大量新功能。 JavaScript 语言规范的新版本每年更新一次，新语言功能建议的定稿比以往更快。这意味着新功能将以前所未有的速度被整合到现代浏览器和其他 JavaScript 运行时引擎（如 Node.js）中。

![](https://imgkr.cn-bj.ufileos.com/c4a62472-f7db-4d05-9d92-302a1b83d5c9.png)

<br /><br />

### [【视频】Cookie 是什么？](https://www.bilibili.com/video/av92307534/)

![](https://imgkr.cn-bj.ufileos.com/758fe67e-ab72-4617-ad7c-2ee578e64742.png)

<br /><br />

### [13 个整合营销的基本理论](https://www.inneed.club/articles/detail/87egz7jakd)

> 要做好策划、写好策划案，必然会用到一些科学理论，掌握下面13条营销基本理论知识，迅速提升你的策划专业度！

![](https://imgkr.cn-bj.ufileos.com/f71e42b1-5fca-4606-ac07-6aeed1cd12a3.png)


![](https://imgkr.cn-bj.ufileos.com/82cf3b13-1f9e-4e4e-8970-1b5f29d6be9b.png)

本期周刊同时同步到微信公众号(geeker-read)、[语雀]( https://www.yuque.com/wxyu/geeker-read-weekly)和 [GitHub](https://github.com/geeker-read/weekly_issues)。

<br />

<img width="450" src="https://cdn.nlark.com/yuque/0/2020/webp/639317/1579223318544-5d0c1619-bb50-41ee-b3c5-4aa931028902.webp#align=left&display=inline&height=370&originHeight=493&originWidth=600&size=0&status=done&style=none&width=450" />
