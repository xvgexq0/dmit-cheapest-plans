# DMIT最便宜套餐：$36.90/年和$6.90/月到底差在哪，如何按线路与用途选

搜索“DMIT最便宜套餐”，真正需要弄清楚的不是“DMIT 有没有便宜 VPS”，而是：**最低一次性价格是多少、最低月付是多少、这两个价格对应什么线路，以及便宜之后少了什么。**

按 DMIT 当前公开价格页，最低的长期账单入口是 **WEE，$36.90/年**，折算约 **$3.08/月**；而最低月付价格则是 **TINY，$6.90/月**。这两款都属于 Tier 1 网络，不是 Premium CN2 GIA 线路。DMIT 当前在洛杉矶、香港和东京的价格页都能看到 $6.90/月的 Tier 1 TINY，以及 $36.90/年的 WEE。

所以，看到“DMIT 最便宜套餐 $36.90/年”时，别直接把它理解成“$36.90 就能买到一台 CN2 GIA 入门机”。**线路类型才是这道题的关键。**

[👉 查看 DMIT 当前联盟入口与套餐](https://bit.ly/DmiT)

## 先把答案说清楚：DMIT 最便宜的是哪款？

如果你的标准是“我这次付款最少”，答案是 **WEE：$36.90/年**。

当前公开配置为：

* 1 vCore
* 1GB RAM
* 20GB SSD
* 1000GB Max (IN, OUT)
* 年付
* Tier 1 网络

DMIT 的官方价格页目前明确展示这一配置和 **$36.90/年**价格。

如果你的标准是“以后每个月只想付多少钱”，答案则是 **TINY：$6.90/月**。

TINY 也是 1 vCore、1GB RAM、20GB SSD，但流量提高到 **2000GB Max (IN, OUT)**，计费方式改成月付。这个价格在 DMIT 当前多个地区的 Tier 1 价格中都出现。

换句话说：

> **WEE 是最低总账单，TINY 是最低月付。两者都不是面向中国大陆路由优化的 Premium 套餐。**

这点比“$6.90”四个数字本身更值得记住。

## 为什么 $36.90/年的 WEE 这么便宜？

因为 DMIT 现在的价格结构，本质上是在卖不同的网络路线。

官网把网络分成 Premium、Eyeball 和 Tier 1。Premium 强调中国大陆优化路线，包括 CN2 GIA；Eyeball 是在国际网络上增加面向中国大陆用户的合理尽力路由；Tier 1 则主要面向国际连接和亚太、美洲之间的低成本网络需求。DMIT 对 LAX Tier 1 的定位也很直接：如果你不需要中国大陆专项路由，它就是价格更低的选择。

因此，**WEE 和 TINY 便宜，不是因为它们偷偷把 Premium 套餐打了骨折价，而是因为它们属于另一种网络定位。**

这会直接影响购买场景。

如果服务器主要服务北美用户、做个人开发环境、监控、备份、CI/CD、下载中转、测试节点，Tier 1 的低价就很好理解。

但如果你的核心需求是“中国大陆晚高峰访问体验”，那么只看 CPU、内存和磁盘容量，往往会得出错误结论。DMIT 自己也把 Premium 网络明确定位到中国大陆和亚太低延迟场景。

## $6.90/月的 TINY 和 $36.90/年的 WEE，哪个更适合入门？

这两个套餐配置接近，但账单逻辑不一样。

| 套餐   |     CPU |  内存 |  SSD |                   流量 | 周期 |           价格 |
| ---- | ------: | --: | ---: | -------------------: | -- | -----------: |
| WEE  | 1 vCore | 1GB | 20GB | 1000GB Max (IN, OUT) | 年付 | **$36.90/年** |
| TINY | 1 vCore | 1GB | 20GB | 2000GB Max (IN, OUT) | 月付 |  **$6.90/月** |

WEE 的年付价格折算约 $3.08/月；TINY 按当前价格一年持续购买则是 $82.80。也就是说，**如果你本来就准备长期使用，同样是 Tier 1 入门机，WEE 的首年账单明显更低；如果你更看重按月付费和可控投入，TINY 更灵活。**

不过这里还有一个现实问题：WEE 只有 1000GB Max (IN, OUT) 流量，而 TINY 有 2000GB。对于流量需求轻的测试机、监控机、低频服务，这个差别可能完全没有感觉；对于下载、镜像同步或者中转用途，2000GB 的空间就更实际。

## 全套餐对比表：从最低价一路看到高配

DMIT 的当前价格体系已经不只是传统的 TINY / STARTER / MINI 一条线，而是同时叠加了**地区、网络系列、硬件平台**几个维度。下面把当前公开价格页中与 Cloud Instance 直接相关、能明确辨识的主要销售系列放在一起，重点看价格梯度与配置差异。价格以 DMIT 当前公开页面为准，官方也提醒价格和产品可能因调整而出现更新滞后。

### 洛杉矶 LAX

| 系列 | 套餐 | 核心配置与价格 | 购买 |
| --- | --- | --- | --- |
| LAX.AS3.Pro | TINY | 1 vCore / 2GB / 20GB SSD / 1000GB / **$10.90/月** | [ 查看 TINY](https://bit.ly/DmiT) |
|  | Pocket | 2 vCore / 2GB / 40GB / 1500GB / **$16.90/月** | [ 查看 Pocket](https://bit.ly/DmiT) |
|  | STARTER | 2 vCore / 2GB / 80GB / 3000GB / **$34.90/月** | [ 查看 STARTER](https://bit.ly/DmiT) |
|  | MINI | 4 vCore / 4GB / 80GB / 5000GB / **$62.90/月** | [ 查看 MINI](https://bit.ly/DmiT) |
|  | MICRO | 4 vCore / 4GB / 160GB / 7000GB / **$87.90/月** | [ 查看 MICRO](https://bit.ly/DmiT) |
|  | MEDIUM | 6 vCore / 8GB / 160GB / 15000GB / **$199.90/月** | [ 查看 MEDIUM](https://bit.ly/DmiT) |
| LAX.AN5.Pro | MINI | 4 vCore / 4GB / 80GB / 5000GB / **$79.90/月** | [ 查看 MINI](https://bit.ly/DmiT) |
|  | MICRO | 4 vCore / 4GB / 160GB / 7000GB / **$110.90/月** | [ 查看 MICRO](https://bit.ly/DmiT) |
|  | MEDIUM | 6 vCore / 8GB / 160GB / 15000GB / **$289.90/月** | [ 查看 MEDIUM](https://bit.ly/DmiT) |
|  | LARGE | 8 vCore / 16GB / 320GB / 25000GB / **$499.90/月** | [ 查看 LARGE](https://bit.ly/DmiT) |
|  | GIANT | 12 vCore / 24GB / 640GB / 50000GB / **$1009.90/月** | [ 查看 GIANT](https://bit.ly/DmiT) |
| LAX.AS3.T1 | WEE | 1 vCore / 1GB / 20GB / 1000GB Max (IN, OUT) / **$36.90/年** | [ 查看 WEE](https://bit.ly/DmiT) |
|  | TINY | 1 vCore / 1GB / 20GB / 2000GB Max (IN, OUT) / **$6.90/月** | [ 查看 TINY](https://bit.ly/DmiT) |
|  | STARTER | 2 vCore / 2GB / 40GB / 4000GB Max (IN, OUT) / **$12.90/月** | [ 查看 STARTER](https://bit.ly/DmiT) |
|  | MINI | 2 vCore / 4GB / 80GB / 8000GB Max (IN, OUT) / **$21.90/月** | [ 查看 MINI](https://bit.ly/DmiT) |
|  | MICRO | 4 vCore / 4GB / 120GB / 16000GB Max (IN, OUT) / **$32.90/月** | [ 查看 MICRO](https://bit.ly/DmiT) |
| LAX.AN5.T1 Volume | V2C2G | 2 vCore / 2GB / 40GB / 5000GB / **$14.90/月** | [ 查看 V2C2G](https://bit.ly/DmiT) |
|  | V2C4G | 2 vCore / 4GB / 80GB / 10000GB / **$23.90/月** | [ 查看 V2C4G](https://bit.ly/DmiT) |
|  | V4C4G | 4 vCore / 4GB / 120GB / 20000GB / **$36.90/月** | [ 查看 V4C4G](https://bit.ly/DmiT) |
|  | V4C8G | 4 vCore / 8GB / 160GB / 40000GB / **$52.90/月** | [ 查看 V4C8G](https://bit.ly/DmiT) |
|  | V8C16G | 8 vCore / 16GB / 240GB / 80000GB / **$119.90/月** | [ 查看 V8C16G](https://bit.ly/DmiT) |
|  | V12C24G | 12 vCore / 24GB / 320GB / 160000GB / **$199.90/月** | [ 查看 V12C24G](https://bit.ly/DmiT) |
| LAX.AN5.T1 General | G2C4G | 2 vCore / 4GB / 80GB / 4000GB / **$16.90/月** | [ 查看 G2C4G](https://bit.ly/DmiT) |
|  | G4C8G | 4 vCore / 8GB / 160GB / 8000GB / **$36.90/月** | [ 查看 G4C8G](https://bit.ly/DmiT) |
|  | G8C16G | 8 vCore / 16GB / 320GB / 12000GB / **$79.90/月** | [ 查看 G8C16G](https://bit.ly/DmiT) |
|  | G12C24G | 12 vCore / 24GB / 480GB / 240000GB / **$119.90/月** | [ 查看 G12C24G](https://bit.ly/DmiT) |
|  | G16C32G | 16 vCore / 32GB / 640GB / 320000GB / **$199.90/月** | [ 查看 G16C32G](https://bit.ly/DmiT) |

LAX 的一个特点是，同样叫 TINY，不同线路的价格和配置并不一样。官方当前页面把 AS3、AN4、AN5 硬件平台以及 Premium、Eyeball、Tier 1 网络分开展示；其中 LAX AS3 还特别标注仍处于构建与优化阶段，可能出现**磁盘性能下降和更低 SLA**。

### 香港 HKG

香港当前的硬件平台明确是 **AN5 和 AS3**。DMIT 表示 AN5 目前只提供 Premium 网络，而 AS3 同时出现在 Eyeball 与 Tier 1 网络；HKG Eyeball 还处于 Beta。

| 系列 | 套餐 | 核心配置与价格 | 购买 |
| --- | --- | --- | --- |
| HKG AN5 Premium | MINI | 4 vCore / 4GB / 80GB / 1500GB / **$149.90/月** | [ 查看 MINI](https://bit.ly/DmiT) |
|  | MICRO | 4 vCore / 4GB / 160GB / 2000GB / **$199.90/月** | [ 查看 MICRO](https://bit.ly/DmiT) |
|  | MEDIUM | 6 vCore / 8GB / 160GB / 2500GB / **$279.90/月** | [ 查看 MEDIUM](https://bit.ly/DmiT) |
|  | LARGE | 8 vCore / 16GB / 320GB / 3000GB / **$359.90/月** | [ 查看 LARGE](https://bit.ly/DmiT) |
|  | GIANT | 12 vCore / 24GB / 640GB / 6000GB / **$759.90/月** | [ 查看 GIANT](https://bit.ly/DmiT) |
| HKG AS3 Eyeball | TINY | 1 vCore / 1GB / 20GB / 500GB / **$39.90/月** | [ 查看 TINY](https://bit.ly/DmiT) |
|  | STARTER | 1 vCore / 2GB / 40GB / 1000GB / **$79.90/月** | [ 查看 STARTER](https://bit.ly/DmiT) |
|  | MINI | 2 vCore / 4GB / 60GB / 1500GB / **$126.90/月** | [ 查看 MINI](https://bit.ly/DmiT) |
|  | MICRO | 4 vCore / 4GB / 80GB / 2000GB / **$179.90/月** | [ 查看 MICRO](https://bit.ly/DmiT) |
|  | MEDIUM | 4 vCore / 8GB / 160GB / 2500GB / **$239.90/月** | [ 查看 MEDIUM](https://bit.ly/DmiT) |
| HKG AS3 Eyeball v2 | TINYv2 | 1 vCore / 1GB / 20GB / 1000GB / **$29.90/月** | [ 查看 TINYv2](https://bit.ly/DmiT) |
|  | STARTERv2 | 1 vCore / 2GB / 40GB / 2000GB / **$59.90/月** | [ 查看 STARTERv2](https://bit.ly/DmiT) |
|  | MINIv2 | 2 vCore / 2GB / 60GB / 3000GB / **$89.90/月** | [ 查看 MINIv2](https://bit.ly/DmiT) |
|  | MICROv2 | 4 vCore / 4GB / 80GB / 4000GB / **$129.90/月** | [ 查看 MICROv2](https://bit.ly/DmiT) |
|  | MEDIUMv2 | 4 vCore / 8GB / 160GB / 6000GB / **$199.90/月** | [ 查看 MEDIUMv2](https://bit.ly/DmiT) |
|  | LARGEv2 | 8 vCore / 16GB / 320GB / 12000GB / **$389.90/月** | [ 查看 LARGEv2](https://bit.ly/DmiT) |
|  | GIANTv2 | 8 vCore / 24GB / 640GB / 24000GB / **$789.90/月** | [ 查看 GIANTv2](https://bit.ly/DmiT) |
| HKG AS3 Tier 1 | WEE | 1 vCore / 1GB / 20GB / 1000GB Max (IN, OUT) / **$36.90/年** | [ 查看 WEE](https://bit.ly/DmiT) |
|  | TINY | 1 vCore / 1GB / 20GB / 2000GB Max (IN, OUT) / **$6.90/月** | [ 查看 TINY](https://bit.ly/DmiT) |
|  | STARTER | 1 vCore / 2GB / 40GB / 4000GB Max (IN, OUT) / **$12.90/月** | [ 查看 STARTER](https://bit.ly/DmiT) |
|  | MINI | 2 vCore / 2GB / 60GB / 8000GB Max (IN, OUT) / **$21.90/月** | [ 查看 MINI](https://bit.ly/DmiT) |
|  | MICRO | 4 vCore / 4GB / 80GB / 16000GB Max (IN, OUT) / **$32.90/月** | [ 查看 MICRO](https://bit.ly/DmiT) |
|  | MEDIUM | 4 vCore / 8GB / 160GB / 32000GB Max (IN, OUT) / **$49.90/月** | [ 查看 MEDIUM](https://bit.ly/DmiT) |
|  | LARGE | 8 vCore / 16GB / 320GB / 64000GB Max (IN, OUT) / **$99.90/月** | [ 查看 LARGE](https://bit.ly/DmiT) |
|  | GIANT | 8 vCore / 24GB / 640GB / 128000GB Max (IN, OUT) / **$199.90/月** | [ 查看 GIANT](https://bit.ly/DmiT) |

香港这里尤其容易看晕，因为“低价”并不意味着都是同一种路线。比如 **HKG.AS3.EB.TINYv2 是 $29.90/月**，而 HKG Tier 1 TINY 只有 **$6.90/月**；另一方面，HKG Premium 当前公开价格又从 MINI 的 $149.90/月开始。

所以“香港 DMIT TINY 多少钱”这种问题，单独回答一个数字其实意义不大，必须带上线路。

### 东京 TYO

东京当前公开 Tier 1 价格同样从 **WEE $36.90/年、TINY $6.90/月**开始。官方页面列出的 Tier 1 价格包括：TINY $6.90、STARTER $12.90、MINI $21.90、MICRO $32.90、MEDIUM $49.90、LARGE $99.90、GIANT $199.90；规格从 1 vCore/1GB/20GB SSD 起，一直到 8 vCore/24GB/640GB SSD。

东京 Premium AS3 的公开入门档则明显更贵：当前可核对到的 TINY 为 **$21.90/月**，1 vCPU、750MB RAM、15GB SSD、500GB 流量；STARTER $39.90/月、MINI $79.90/月、MICRO $159.90/月、MEDIUM $259.90/月。

这也是为什么“DMIT 最便宜套餐”和“DMIT 最便宜 Premium 套餐”是两个完全不同的问题。

## 真正便宜的方案，适合跑什么？

### 个人测试机

这是 WEE/TINY 最典型的用途。

比如跑一个轻量 API、反代、监控、DNS、Webhook、Cron 任务或者开发环境，1 vCore + 1GB RAM 并不算豪华，但如果应用本身很轻，这个配置足够把服务器先跑起来。

这里最大的优势不是“性能特别强”，而是**初始成本非常低**。

尤其是 WEE，$36.90/年就能把服务器账单压到相当低的水平。

### 备份和低频服务

Tier 1 的主要卖点不是中国大陆优化，而是国际连接和更低的价格。DMIT 对 Tier 1 的官方定位包含备份、归档、批处理、内部工具、监控以及不需要中国大陆专项路由的工作负载。

这种场景下，把预算从 Premium 路由上省下来，通常比单纯堆 CPU 更符合需求。

### 面向中国大陆用户的网站

这时候不要因为看到了 $6.90，就直接下单。

DMIT 自己对 Premium 网络的定位就是中国大陆访问优化，并明确列出 CN2 GIA、专门的中国大陆互联等能力。香港 Premium 页面还给出了约 15ms 的中国大陆参考延迟和低丢包指标；东京 Premium 则给出约 28ms 的参考延迟。

这里真正应该比较的是：

**Tier 1 的低账单 vs Premium 的网络路线。**

如果你的服务器每天都要承受大陆用户访问，那么每月省下来的十几二十美元，未必能抵消你对延迟、路由和晚高峰体验的要求。

## DMIT 的价格为什么看起来“同名套餐一大堆”？

这是很多第一次看 DMIT 价格页的人最容易踩的坑。

你会同时看到：

* TINY
* STARTER
* MINI
* MICRO
* MEDIUM
* LARGE
* GIANT
* TINYv2
* STARTERv2
* V2C2G
* G2C4G

这些并不是一个统一的产品表，而是不同地区、网络系列和硬件平台下的不同实例卡。

例如 LAX 当前同时存在 AS3、AN5，以及 Tier 1 下的 Volume、General 等不同系列。AN5 的 Tier 1 Volume 套餐直接把资源重点放在流量上，例如 V2C2G 提供 5000GB、V2C4G 提供 10000GB，而常规 TINY 则只有 2000GB Max (IN, OUT)。

因此，不要用“同样都是 MINI”来判断价格是否贵。

正确的比较方式是：

**地区 + 网络 + 硬件平台 + CPU/RAM + 流量 + 计费周期。**

这套方法看起来麻烦一点，却能避免把完全不同的产品放在一起硬比。

## “最便宜”之外，还要看这几个限制

### LAX AS3 目前有官方警告

这点值得单独拿出来说。

DMIT 当前官方页面明确写着，**LAX AS3 仍处于构建和优化阶段**，在此期间可能遇到较低的磁盘性能和低于成熟平台的 SLA。

所以即使某个 AS3 套餐看起来便宜，也不要把它和成熟平台默认看成完全一样。

### Tier 1 的核心卖点并不是中国大陆优化

DMIT 当前对 Tier 1 的说明非常明确：它面向亚太、北美和其他国际连接，不提供针对中国大陆的专项路由增强。

所以，**$6.90 的价格成立，但它不是“低价 CN2 GIA”这件事。**

### IP 地理可用性也可能有限

DMIT 在 Tier 1 产品价格页上专门提醒：分配的 IP 地址并不保证在所有国家或地区都可用。

如果你需要某个固定国家/地区的 IP 用于业务、支付、平台登录或地区识别，这个限制不应该在付款之后才发现。

## 有没有退款保护？

有，但要看条件。

DMIT 当前退款文档写得很具体：新订单在 **3 天内**，且 VM 流量使用不超过 **30GB**，可以申请全额退款；在 **30 天内**也有按剩余价值计算的部分退款机制，具体金额还会受到实际使用量和退款规则影响。

同时，退款并不是无条件适用于所有情况。例如续费订单、部分网络/IP 问题、违反服务条款等都可能影响退款资格；退款后实例数据会被删除且不可恢复。

这对第一次试 DMIT 的用户比较重要：与其看别人一句“这个套餐好不好”，不如结合自己的真实访问来源、流量和用途做一次小规模验证。

## 价格之外，DMIT 现在还有哪些能力？

DMIT 当前 Cloud Instance 页面强调的是 KVM 虚拟化、AMD EPYC 平台、NVMe SSD、免费即时开通、快照与自动备份，并提供洛杉矶、香港、东京三个主要区域。

官方当前硬件定位也比较清楚：

* **AN5**：AMD EPYC 9005 系列，强调新一代性能。
* **AN4**：AMD EPYC 9004 系列，更偏成熟、均衡的通用计算。
* **AS3**：AMD EPYC 7003 系列，DMIT 将其定位为价格更有竞争力的方案。

所以如果你看到一个贵很多的 AN5 套餐，不应该只问“为什么这么贵”，而应该问“我是不是确实需要这一档 CPU/存储/流量组合”。

## DMIT 最便宜套餐怎么选？给你一个实际判断方法

如果你只是想花最少的钱弄一台 DMIT：

**WEE $36.90/年**先看。

如果你想按月付费，同时希望比 WEE 多一点流量：

**TINY $6.90/月**。

如果服务器主要服务中国大陆用户，不要只盯这两个价格。往 Premium 方向看，更有意义的是比较同地区的 Premium 入门套餐。例如 LAX 当前 AS3 Pro TINY 为 **$10.90/月**，配置为 1 vCore、2GB RAM、20GB SSD、1000GB 流量；这比 Tier 1 TINY 贵，但资源和网络定位也不同。

如果你的业务是大流量国际传输，则可以直接看 LAX AN5 Tier 1 Volume：V2C2G $14.90/月起，流量从 5000GB 起步，比标准 TINY 更适合流量优先的场景。

最后，如果只是想知道一个最简单的结论：

**最低年付：WEE，$36.90/年。**

**最低月付：TINY，$6.90/月。**

**这两个都是 Tier 1，不是 Premium CN2 GIA。**

**如果目标用户主要在中国大陆，不要把“最便宜”直接等同于“最适合”。**

[👉 查看当前 DMIT 套餐](https://bit.ly/DmiT)

## 常见问题

### DMIT 最便宜套餐现在是不是 $6.90？

按月付价格看，是 **$6.90/月的 TINY**；按一次购买的总金额看，则有 **$36.90/年的 WEE**。两者都是 Tier 1。

### $36.90/年是不是 CN2 GIA？

不是。当前公开的 $36.90/年 WEE 属于 Tier 1 网络，DMIT 的 Premium 网络才强调 CN2 GIA 等中国大陆优化路线。

### TINY 和 WEE 哪个便宜？

WEE 更便宜，按一年总账单计算只有 $36.90；TINY 是 $6.90/月，连续购买一年就是 $82.80。TINY 的优势在于流量额度更高，而且采用月付。

### DMIT 有没有比 $6.90 更便宜的长期价格？

目前公开价格页里，WEE 的 $36.90/年是更低的年度总价入口；折算月成本约 $3.08。

### 新手该直接买最便宜的吗？

如果用途只是测试、监控、开发环境、备份或其他轻量工作，Tier 1 入门款确实更符合“先低成本跑起来”的思路。若核心需求是中国大陆访问，则应该把网络路线放到 CPU 和价格之前考虑。DMIT 当前对 Premium、Eyeball、Tier 1 的定位本身就是不同的。

### DMIT 价格会不会变化？

会。DMIT 当前官方价格页明确注明，产品和价格可能因调整而出现更新滞后，因此下单时应以实际结算页面显示为准。
