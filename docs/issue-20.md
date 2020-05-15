# 极客阅读周刊: 第 19 期


<br /><br />
<img width="500" src="https://cdn.nlark.com/yuque/0/2020/png/639317/1579223265494-6784ed04-76db-4281-896b-e1a9df34564d.png#align=left&display=inline&height=176&name=image.png&originHeight=352&originWidth=1080&size=85689&status=done&style=none&width=540">

「极客阅读周刊」分享值得阅读的技术文章，每周发布。

> 「极客阅读 」汇聚了国内外最优质的技术博客、产品动态、公众号文章。开发者可以在极客阅读一站式的阅读到来自互联网技术大咖的文章。
> <br /><br />
> <img width="400" src="https://cdn.nlark.com/yuque/0/2020/png/639317/1578021644053-627fd9fc-33fc-43dd-94bd-df2c1af39b10.png?x-oss-process=image/resize,w_1458" />
> <br /><br />
> **「极客阅读 」官网：[geeker-read.com](https://geeker-read.com)**

<br />

---

### [腾讯 Elasticsearch 海量规模背后的内核优化剖析](https://zhuanlan.zhihu.com/p/139725905)

> Elasticsearch 在腾讯内部广泛应用于日志实时分析、结构化数据分析、全文检索等场景，目前单集群规模达到千级节点、万亿级吞吐，同时腾讯联合 Elastic 公司在腾讯云上提供了内核增强版 ES 云服务。海量规模、丰富的应用场景推动着腾讯对原生 ES 进行持续的高可用、高性能、低成本等全方位优化。本次分享主要剖析腾讯对 Elasticsearch 海量规模下的内核优化与实践，希望能和广大 ES 爱好者共同探讨推动 ES 技术的发展。

![](https://imgkr.cn-bj.ufileos.com/ef537f04-943a-439e-bd44-9f068c6d61ec.png)

<br /><br />

### [图解 HTTP 缓存](https://www.zoo.team/article/http-cache)

> HTTP 的缓存机制，可以说这是前端工程师需要掌握的重要知识点之一。本文将针对 HTTP 缓存整体的流程做一个详细的讲解，争取做到大家读完整篇文章后，对缓存有一个整体的了解。

![](https://imgkr.cn-bj.ufileos.com/b9e1753f-0f43-4a72-b94b-bdf06da2609d.png)

<br /><br />

### [大规格文件的上传优化](https://aotu.io/notes/2020/05/12/file-upload/)

> 在开发过程中，收到这样一个问题反馈，在网站上传 100 MB 以上的文件经常失败，重试也要等老半天，这就难为需要上传大规格文件的用户了。那么应该怎么做才能快速上传，就算失败了再次发送也能从上次中断的地方继续上传呢？下文为你揭晓答案~

![](https://imgkr.cn-bj.ufileos.com/b441142e-e2a4-4e0f-b518-981da4d2cafb.png)

<br /><br />

### [建设企业级微前端方案丨GMTC](https://www.infoq.cn/video/CzvqIFld796QzoVXdMEx)

> 张浩 (网易资深前端开发工程师)
>
> 严选数据产品前端负责人。先后负责过网易企业邮箱、网易有钱、网易严选等大型项目的前端架构设计及开发。当前致力于大前端与通用能力建设、工程化与效率工具、企业级应用架构等领域研究。

![](https://imgkr.cn-bj.ufileos.com/d640ab13-e481-41b7-bc11-1d413a9039e1.png)

<br /><br />

### [了解 CSS min()/max()/clamp()数学函数](https://www.zhangxinxu.com/wordpress/2020/04/css-min-max-clamp/)

> min()/max()/clamp() 这 3 个数学函数是现代浏览器 2018 年底开始支持的，因此，如果你胆儿足够肥，是可以在实际项目中小范围使用的。

![](https://imgkr.cn-bj.ufileos.com/ba5ff1fc-e6d6-450a-89af-07ea0efdb389.png)

<br /><br />

### [前端布局必须了解的 css 选择器](https://juejin.im/post/5eaf64276fb9a0435749c23a)

![](https://imgkr.cn-bj.ufileos.com/5924034d-c621-4547-a744-1acbda957ad6.png)

<br /><br />

### [Deno 1.0 正式发布！](https://www.infoq.cn/article/KRAc4z0zVZRc0dcWu3Xz)

> Deno 是一个新的运行时，用于在 Web 浏览器之外执行 JavaScript 和 TypeScript。
>
> Deno 试图提供一个独立的工具来快速编写功能复杂的脚本。Deno 是（并将始终是）单个可执行文件。就像 Web 浏览器一样，它知道如何获取外部代码。

![](https://imgkr.cn-bj.ufileos.com/72543162-4b8d-4533-a35b-f242db360d71.png)

<br /><br />

### [Deno 1.0: What you need to know](https://blog.logrocket.com/deno-1-0-what-you-need-to-know/)

> Deno 已于 2020-05-13 发布 1.0

![](https://imgkr.cn-bj.ufileos.com/910f8278-ad9a-4d87-925b-ed44a07c09f8.png)

<br /><br />

### [HTTP/3 原理与实践](https://mp.weixin.qq.com/s/7tKgSmkMWHdIyvrTWJE8sg)

> 2015 年 HTTP/2 标准发表后，大多数主流浏览器也于当年年底支持该标准。此后，凭借着多路复用、头部压缩、服务器推送等优势，HTTP/2 得到了越来越多开发者的青睐。不知不觉的 HTTP 已经发展到了第三代，鹅厂也紧跟技术潮流，很多项目也在逐渐使用 HTTP/3。本文基于 QQ兴趣部落接入 HTTP/3 的实践，聊一聊 HTTP/3 的原理以及业务接入的方式。

![](https://imgkr.cn-bj.ufileos.com/5f52f14c-cca6-4c36-9958-578ea2cce816.gif)

<br /><br />

### [美团命名服务的挑战与演进](https://tech.meituan.com/2020/05/14/octo-mns-2.0.html)

> 命名服务主要解决微服务拆分后带来的服务发现、路由隔离等需求，是服务治理的基石。美团命名服务（以下简称 MNS）作为服务治理体系OCTO的核心模块，目前承载美团上万项服务，日均调用达到万亿级别。为了更好地支撑美团各项飞速发展的业务，MNS 开始从 1.0 向 2.0 演进。本文将围绕本次演进的初衷、实现方案以及落地的效果等方面进行展开，同时本文还介绍了命名服务作为一个技术中台组件，对业务的重要价值以及推动业务升级的一些成果。希望本文对大家能够有所启发。

![](https://imgkr.cn-bj.ufileos.com/4e443543-0907-4c6c-a205-97dbbcb7a7d5.png)

<br /><br />

### [花椒敏感词系统架构详细](https://mp.weixin.qq.com/s/GXVlcyGd9WsPGw0oSGmxgw)

> 直播系统主要是以内容为主，好的内容可以吸引用户来欣赏，也能为公司带来可观的收益，既然有传播的入口，那么必然有负面内容的出现，随着平台用户量不断扩大，内容的监管也是必不可少的一个环节，比如国家监管部门要求拦截词语包括涉政、非法、宗教、暴恐、版权等，以及平台自身需要拦截的词语包括竞品挖人、低俗、广告等垃圾词，那么我们本章就从文本内容的管控角度介绍下花椒敏感词服务的定制和应用。

![](https://imgkr.cn-bj.ufileos.com/71cb67e2-a00c-46a2-8a51-bf89a0aea9a7.png)

<br /><br />

### [在搜索引擎广告关键词生成上，算法可以做什么？](https://mp.weixin.qq.com/s/OB2r761_8xcR2CXKS3JwYQ)

> 一个搜索引擎广告生态，通常有三个参与方：广告主、搜索用户以及搜索引擎。搜索引擎广告是指广告主根据自己的产品或服务的内容、特点等，确定相关的关键词，撰写广告内容并自主定价在搜索引擎端投放的广告。当用户在搜索引擎上搜索到广告主投放的关键词时，相应的广告就会展示，并在用户点击后对广告主进行收费。

![](https://imgkr.cn-bj.ufileos.com/f189e967-1f7c-45de-b5af-5e9e14d36c24.png)

<br /><br />

### [微服务到底该多大？如何设计微服务的粒度？](https://www.infoq.cn/article/wBQGFQjPRME3BdrbLOcv)

> 当你想到“微服务”这个词时，首先看到的是前缀“微”（Micro）。据An Introduction to Greek一书的介绍，在柏拉图和亚里士多德那里，μικρός只表示少或小。在日常英语中，“微”往往表示小得异乎寻常的东西——毕竟，“微米”是一米的百万分之一，而“显微镜”是用来观察那些用肉眼看不见的东西，因为它们的尺寸太小。

![](https://imgkr.cn-bj.ufileos.com/eba2d516-79d0-4f29-8b44-7f1594de55e2.png)

<br /><br />

### [每个开发人员应了解的 TCP 知识（英文）](https://robertovitillo.com/what-every-developer-should-know-about-tcp/)

> 一篇短文章，使用相对简单的语言，解释了 TCP 协议的设计思想。

![](https://imgkr.cn-bj.ufileos.com/23d1a699-860e-47c8-ade8-b86fe247c6b2.png)


<br />

本期周刊同时同步到微信公众号(geeker-read)、[语雀]( https://www.yuque.com/wxyu/geeker-read-weekly)和 [GitHub](https://github.com/geeker-read/weekly_issues)。

<br />

<img width="450" src="https://cdn.nlark.com/yuque/0/2020/webp/639317/1579223318544-5d0c1619-bb50-41ee-b3c5-4aa931028902.webp#align=left&display=inline&height=370&originHeight=493&originWidth=600&size=0&status=done&style=none&width=450" />
