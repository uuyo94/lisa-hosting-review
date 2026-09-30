# LisaHost：从套餐、线路到退款与口碑，一次看懂这家 VPS 主机商值不值得考虑

搜索 **LisaHost**，真正需要弄清楚的通常不是“它是不是一家 VPS 商家”，而是几个非常实际的问题：现在到底有哪些套餐、价格怎么算、住宅 IP 和普通原生 IP 有什么区别、哪些线路更适合不同地区访问，以及退款政策到底有没有限制。

我重新核对了 LisaHost 当前官网页面。可以确认，LisaHost 目前以 VPS/VDS 为主，产品覆盖美国、香港、新加坡、台湾、日本、英国、韩国、德国、越南等地区，并大量提供原生 IP、双 ISP 住宅 IP、CN2 GIA、AS9929、AS4837、BGP 等不同线路组合。官网同时明确写有“即时自动开通”和部分产品 **48 小时不满意无条件退款**，但不同产品的退款规则并不完全一样，住宅类 VDS 里就存在“仅退网站余额”的特殊情况。

所以，这篇不只看“月付多少钱”，而是把 LisaHost 真正影响购买决定的地方拆开讲。

## LisaHost 是什么，当前主要卖什么

从官网导航和产品页来看，LisaHost 的产品核心不是传统意义上的低价共享虚拟主机，而是 VPS、VDS、住宅 IP VPS 以及面向不同地区网络的专线型产品。

官网当前能直接确认的产品线包括：

美国 9929 双 ISP 住宅 IP VPS、美国 4837 双 ISP 住宅 IP VPS、美国西雅图及洛杉矶家庭宽带静态住宅 IP VDS、美国 CERA CN2 GIA 高防 VPS、纽约和芝加哥双 ISP 住宅 IP VPS；亚洲地区则有香港 CMI/CU2/CN2、香港 iCable、香港 HGC、新加坡 BGP、台湾 BGP、日本 IIJ、日本 ISP、日本原生 IP、韩国双 ISP；另外还增加了德国 9929 双栈原生 IP、德国双 ISP 住宅 VDS、越南双 ISP 住宅 IP，以及专门的年付特价产品。

官网首页目前还把一台 **2 元、1 天、1 核 1GB、10GB SSD、1GB 流量**的美国 CN2 GIA 试用产品直接放在热销产品区域。基础套餐则显示为 **35 元/月**，1 核 1GB、20GB SSD、500GB 流量。

这里有一个很容易误会的地方：**LisaHost 的“住宅 IP”“原生 IP”“双 ISP”“VDS”不是同一个概念。** 买之前先确定自己真正需要的是线路、IP 属性，还是计算资源，否则很容易为了一个自己根本用不到的特性多付很多钱。

## LisaHost 套餐怎么读：先看 IP 和线路，再看 CPU

LisaHost 的套餐命名很长，但真正影响体验的参数其实集中在几个地方。

### 1. 原生 IP 和双 ISP 住宅 IP

官网大量产品都直接把“双 ISP 家宽住宅 IP”“原生 IP”放在产品名称里。

例如，美国 9929 产品从精简版到豪华版，分别是 1 核 1GB、1 核 1GB、2 核 2GB、4 核 4GB，而对应的流量和带宽逐级提高；同时还提供独立的不限流量 Lite/Pro。

美国 4837 产品则从 **68 元/月**起，基础版是 1 核 1GB、20GB NVMe、300Mbps、3000GB 月流量；进阶版为 2 核 2GB、40GB NVMe、500Mbps、8000GB；豪华版达到 4 核 4GB、80GB NVMe、1Gbps、20000GB。不限流量版本则从 398 元/月起。

从规格差异可以看出，贵出来的钱并不只是“换一个 IP”。CPU、内存、磁盘、带宽以及流量额度都会一起增长。

### 2. CN2 GIA 与 9929，不是简单的“谁更快”

官网将美国 CN2 GIA 产品描述为“国际精品网络”，而 9929 产品则明确使用美国洛杉矶机房并提供双 ISP 家宽住宅 IP。CERA 产品还叠加了高防能力。

例如美国 CERA CN2 高防产品目前公开显示：

| 套餐 | 价格 | 核心配置 | 防御/限制 |
| --- | ---: | --- | --- |
| 试用 | 2 元/天 | 1 核 / 1GB / 10GB SSD / 10Mbps / 1GB 双向流量 | 每用户限购一次；不退款 |
| 精简版 | 40 元/月 | 1 核 / 512MB / 10GB SSD / 10Mbps / 100GB 双向流量 | 默认 50G，可付费提升到 100G |
| 基础版 | 50 元/月 | 1 核 / 1GB / 20GB SSD / 15Mbps / 500GB 双向流量 | 默认 50G，可付费提升到 100G |
| 进阶版 | 256 元/季 | 2 核 / 2GB / 20GB SSD / 25Mbps / 1200GB | 默认 50G，可付费提升到 100G |
| 豪华版 | 396 元/月 | 4 核 / 4GB / 40GB SSD / 50Mbps / 3000GB | 默认 50G，可付费提升到 100G |

这些页面均标注为美国洛杉矶 CERA 机房、CN2 GIA 国际精品网络；部分套餐还有“限售”或特价限制。

所以，如果你真正需要的是抗攻击能力、CN2 GIA 或特定网络环境，不能只拿 40 元的套餐和 68 元的套餐做 CPU/内存对比。

## 全套餐对比表

下面这张表按照 LisaHost 当前公开产品分类整理。价格使用本次抓取时官网页面实际显示的人民币价格；官网很多产品标注“限时特价”，因此价格可能发生变化。对于部分动态页面没有完整稳定返回全部字段的产品，我没有用第三方文章里的猜测数字补齐。

| 产品线 | 套餐/方案 | 核心配置或主要参数 | 当前公开价格与周期 | 购买 |
| --- | --- | --- | ---: | --- |
| 美国 9929 | 精简版 | 1 核 / 1GB / 10GB NVMe / 50Mbps / 1000GB | 68 元/月 | [ 查看美国 9929 套餐](https://bit.ly/LIsahost) |
| 美国 9929 | 基础版 | 1 核 / 1GB / 20GB NVMe / 60Mbps / 2000GB | 88 元/月 | [ 查看美国 9929 套餐](https://bit.ly/LIsahost) |
| 美国 9929 | 进阶版 | 2 核 / 2GB / 40GB NVMe / 80Mbps / 4000GB | 158 元/月 | [ 查看美国 9929 套餐](https://bit.ly/LIsahost) |
| 美国 9929 | 豪华版 | 4 核 / 4GB / 80GB NVMe / 100Mbps / 8000GB | 899 元/月 | [ 查看美国 9929 套餐](https://bit.ly/LIsahost) |
| 美国 9929 | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 20Mbps / 不限流量 | 498 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 美国 9929 | 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 50Mbps / 不限流量 | 1288 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 美国 9929 | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 50Mbps / 600GB | 499 元/年 | [ 查看年付方案](https://bit.ly/LIsahost) |
| 美国 4837 | 基础版 | 1 核 / 1GB / 20GB NVMe / 300Mbps / 3000GB | 68 元/月 | [ 查看美国 4837 套餐](https://bit.ly/LIsahost) |
| 美国 4837 | 进阶版 | 2 核 / 2GB / 40GB NVMe / 500Mbps / 8000GB | 100 元/月 | [ 查看美国 4837 套餐](https://bit.ly/LIsahost) |
| 美国 4837 | 豪华版 | 4 核 / 4GB / 80GB NVMe / 1Gbps / 20000GB | 699 元/月 | [ 查看美国 4837 套餐](https://bit.ly/LIsahost) |
| 美国 4837 | 不限流量 Lite | 2 核 / 2GB / 20GB NVMe / 200Mbps / 不限 | 398 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 美国 4837 | 不限流量 Pro | 8 核 / 8GB / 80GB NVMe / 500Mbps / 不限 | 998 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 美国 4837 | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 600GB | 399 元/年 | [ 查看年付方案](https://bit.ly/LIsahost) |
| 美国精品网络 | 基础版 | 1 核 / 1GB / 20GB SSD / 60Mbps / 2000GB | 132 元/季 | [ 查看精品网络](https://bit.ly/LIsahost) |
| 美国精品网络 | 进阶版 | 2 核 / 2GB / 40GB SSD / 80Mbps / 4000GB | 223 元/季 | [ 查看精品网络](https://bit.ly/LIsahost) |
| 美国精品网络 | 豪华版 | 4 核 / 4GB / 80GB SSD / 100Mbps / 8000GB | 508 元/季 | [ 查看精品网络](https://bit.ly/LIsahost) |
| 美国 CERA CN2 高防 | 试用 | 1 核 / 1GB / 10GB SSD / 10Mbps / 1GB 双向流量 | 2 元/天 | [ 进入 CERA 试用](https://bit.ly/LIsahost) |
| 美国 CERA CN2 高防 | 精简版 | 1 核 / 512MB / 10GB SSD / 10Mbps / 100GB 双向流量 | 40 元/月 | [ 查看 CERA 高防](https://bit.ly/LIsahost) |
| 美国 CERA CN2 高防 | 基础版 | 1 核 / 1GB / 20GB SSD / 15Mbps / 500GB 双向流量 | 50 元/月 | [ 查看 CERA 高防](https://bit.ly/LIsahost) |
| 美国 CERA CN2 高防 | 进阶版 | 2 核 / 2GB / 20GB SSD / 25Mbps / 1200GB | 256 元/季 | [ 查看 CERA 高防](https://bit.ly/LIsahost) |
| 美国 CERA CN2 高防 | 豪华版 | 4 核 / 4GB / 40GB SSD / 50Mbps / 3000GB | 396 元/月 | [ 查看 CERA 高防](https://bit.ly/LIsahost) |
| 西雅图家庭宽带 VDS | 基础版 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 3000GB | 169 元/月 | [ 查看家庭宽带 VDS](https://bit.ly/LIsahost) |
| 西雅图家庭宽带 VDS | 进阶版 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 6000GB | 299 元/月 | [ 查看家庭宽带 VDS](https://bit.ly/LIsahost) |
| 西雅图家庭宽带 VDS | 豪华版 | 4 核 / 4GB / 80GB NVMe / 300Mbps / 20000GB | 699 元/月 | [ 查看家庭宽带 VDS](https://bit.ly/LIsahost) |
| 西雅图家庭宽带 VDS | 100Mbps 不限流量 | 2 核 / 2GB / 40GB NVMe / 100Mbps / 不限 | 399 元/月 | [ 查看不限流量 VDS](https://bit.ly/LIsahost) |
| 西雅图家庭宽带 VDS | 200Mbps 不限流量 | 4 核 / 4GB / 80GB NVMe / 200Mbps / 不限 | 599 元/月 | [ 查看不限流量 VDS](https://bit.ly/LIsahost) |
| 洛杉矶 Astound 家庭宽带 VDS | 基础版 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 3000GB | 169 元/月 | [ 查看洛杉矶住宅 VDS](https://bit.ly/LIsahost) |
| 洛杉矶 Astound 家庭宽带 VDS | 进阶版 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 6000GB | 299 元/月 | [ 查看洛杉矶住宅 VDS](https://bit.ly/LIsahost) |
| 洛杉矶 Astound 家庭宽带 VDS | 豪华版 | 4 核 / 4GB / 80GB NVMe / 300Mbps / 20000GB | 699 元/月 | [ 查看洛杉矶住宅 VDS](https://bit.ly/LIsahost) |
| 洛杉矶 Astound 家庭宽带 VDS | 100Mbps 不限流量 | 2 核 / 2GB / 40GB NVMe / 100Mbps / 不限 | 399 元/月 | [ 查看不限流量 VDS](https://bit.ly/LIsahost) |
| 洛杉矶 Astound 家庭宽带 VDS | 200Mbps 不限流量 | 4 核 / 4GB / 80GB NVMe / 200Mbps / 不限 | 599 元/月 | [ 查看不限流量 VDS](https://bit.ly/LIsahost) |
| 西雅图/洛杉矶家庭宽带 | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 1000GB | 899 元/年 | [ 查看年付家庭宽带](https://bit.ly/LIsahost) |
| 加州 T-Mobile/Frontier | 100Mbps 不限流量 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 不限 | 399 元/月 | [ 查看该住宅线路](https://bit.ly/LIsahost) |
| 加州 T-Mobile/Frontier | 200Mbps 不限流量 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 不限 | 599 元/月 | [ 查看该住宅线路](https://bit.ly/LIsahost) |
| 加州 T-Mobile/Frontier | 300Mbps 不限流量 | 4 核 / 4GB / 80GB NVMe / 300Mbps / 不限 | 899 元/月 | [ 查看该住宅线路](https://bit.ly/LIsahost) |
| 美国纽约 | 基础版 | 1 核 / 1GB / 20GB NVMe / 300Mbps / 3000GB | 68 元/月 | [ 查看纽约方案](https://bit.ly/LIsahost) |
| 美国纽约 | 进阶版 | 2 核 / 2GB / 40GB NVMe / 500Mbps / 8000GB | 100 元/月 | [ 查看纽约方案](https://bit.ly/LIsahost) |
| 美国纽约 | 豪华版 | 4 核 / 4GB / 80GB NVMe / 1Gbps / 20000GB | 300 元/月 | [ 查看纽约方案](https://bit.ly/LIsahost) |
| 美国纽约 | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 200Mbps / 不限 | 198 元/月 | [ 查看纽约不限流量](https://bit.ly/LIsahost) |
| 美国纽约 | 不限流量 Pro | 8 核 / 8GB / 120GB NVMe / 500Mbps / 不限 | 498 元/月 | [ 查看纽约不限流量](https://bit.ly/LIsahost) |
| 美国纽约 | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 600GB | 399 元/年 | [ 查看纽约年付](https://bit.ly/LIsahost) |
| 美国芝加哥 | 基础版 | 1 核 / 1GB / 20GB NVMe / 300Mbps / 3000GB | 68 元/月 | [ 查看芝加哥方案](https://bit.ly/LIsahost) |
| 美国芝加哥 | 进阶版 | 2 核 / 2GB / 40GB NVMe / 500Mbps / 8000GB | 100 元/月 | [ 查看芝加哥方案](https://bit.ly/LIsahost) |
| 香港三网优化 | 基础版 | 1 核 / 1GB / 20GB NVMe / 30Mbps / 1000GB | 88 元/月 | [ 查看香港三网方案](https://bit.ly/LIsahost) |
| 香港三网优化 | 进阶版 | 2 核 / 2GB / 40GB NVMe / 50Mbps / 2000GB | 188 元/月 | [ 查看香港三网方案](https://bit.ly/LIsahost) |
| 香港 iCable | 精简版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 2000GB | 88 元/月 | [ 查看香港 iCable](https://bit.ly/LIsahost) |
| 香港 iCable | 基础版 | 1 核 / 1GB / 20GB NVMe / 150Mbps / 4000GB | 129 元/月 | [ 查看香港 iCable](https://bit.ly/LIsahost) |
| 香港 iCable | 进阶版 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 6000GB | 299 元/月 | [ 查看香港 iCable](https://bit.ly/LIsahost) |
| 香港 HGC | 精简版 | 1 核 / 1GB / 10GB NVMe / 50Mbps / 1000GB | 99 元/月 | [ 查看香港 HGC](https://bit.ly/LIsahost) |
| 香港 HGC | 基础版 | 1 核 / 1GB / 20GB NVMe / 60Mbps / 3000GB | 129 元/月 | [ 查看香港 HGC](https://bit.ly/LIsahost) |
| 香港 HGC | 进阶版 | 2 核 / 2GB / 40GB NVMe / 100Mbps / 5000GB | 299 元/月 | [ 查看香港 HGC](https://bit.ly/LIsahost) |
| 香港 HGC | 豪华版 | 4 核 / 4GB / 80GB NVMe / 150Mbps / 10000GB | 599 元/月 | [ 查看香港 HGC](https://bit.ly/LIsahost) |
| 香港 HGC | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 50Mbps / 不限 | 899 元/月 | [ 查看香港 HGC](https://bit.ly/LIsahost) |
| 新加坡原生 IP | 基础版 | 1 核 / 1GB / 10GB NVMe / 300Mbps / 6000GB | 68 元/月 | [ 查看新加坡 VPS](https://bit.ly/LIsahost) |
| 新加坡原生 IP | 进阶版 | 2 核 / 2GB / 20GB NVMe / 500Mbps / 10000GB | 88 元/月 | [ 查看新加坡 VPS](https://bit.ly/LIsahost) |
| 新加坡原生 IP | 豪华版 | 4 核 / 4GB / 40GB NVMe / 1Gbps / 20000GB | 388 元/月 | [ 查看新加坡 VPS](https://bit.ly/LIsahost) |
| 新加坡原生 IP | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 200Mbps / 不限 | 398 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 新加坡原生 IP | 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 500Mbps / 不限 | 898 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 新加坡原生 IP | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 300Mbps / 2000GB | 466 元/年 | [ 查看新加坡年付](https://bit.ly/LIsahost) |
| 台湾 Hinet 动态 IP | 200Mbps 不限流量 | 1 核 / 1GB / 20GB NVMe / 200Mbps / 不限 | 399 元/月 | [ 查看台湾 Hinet](https://bit.ly/LIsahost) |
| 台湾 Hinet 动态 IP | 300Mbps 不限流量 | 2 核 / 2GB / 40GB NVMe / 300Mbps / 不限 | 599 元/月 | [ 查看台湾 Hinet](https://bit.ly/LIsahost) |
| 台湾 Hinet 动态 IP | 500Mbps 不限流量 | 4 核 / 4GB / 80GB NVMe / 500Mbps / 不限 | 899 元/月 | [ 查看台湾 Hinet](https://bit.ly/LIsahost) |
| 台湾原生 IP VPS | 进阶版 | 2 核 / 2GB / 20GB NVMe / 200Mbps / 5000GB | 99 元/月 | [ 查看台湾原生 IP](https://bit.ly/LIsahost) |
| 台湾原生 IP VPS | 豪华版 | 4 核 / 4GB / 40GB NVMe / 500Mbps / 20000GB | 388 元/月 | [ 查看台湾原生 IP](https://bit.ly/LIsahost) |
| 台湾原生 IP VDS | 100Mbps 不限流量 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 不限 | 299 元/月 | [ 查看台湾 VDS](https://bit.ly/LIsahost) |
| 台湾原生 IP VDS | 200Mbps 不限流量 | 2 核 / 2GB / 20GB NVMe / 200Mbps / 不限 | 599 元/月 | [ 查看台湾 VDS](https://bit.ly/LIsahost) |
| 台湾原生 IP VDS | 500Mbps 不限流量 | 4 核 / 4GB / 40GB NVMe / 500Mbps / 不限 | 1599 元/月 | [ 查看台湾 VDS](https://bit.ly/LIsahost) |
| 台湾原生 IP VPS | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 2000GB | 766 元/年 | [ 查看台湾年付](https://bit.ly/LIsahost) |
| 日本 IIJ 双 ISP | 100Mbps 固定流量版 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 3000GB | 188 元/月 | [ 查看日本 IIJ](https://bit.ly/LIsahost) |
| 日本 IIJ 双 ISP | 200Mbps 固定流量版 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 8000GB | 399 元/月 | [ 查看日本 IIJ](https://bit.ly/LIsahost) |
| 日本 IIJ 双 ISP | 300Mbps 固定流量版 | 4 核 / 4GB / 80GB NVMe / 300Mbps / 20000GB | 899 元/月 | [ 查看日本 IIJ](https://bit.ly/LIsahost) |
| 日本 IIJ 双 ISP | 100Mbps 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 100Mbps / 不限 | 1099 元/月 | [ 查看不限流量 IIJ](https://bit.ly/LIsahost) |
| 日本 IIJ 双 ISP | 200Mbps 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 200Mbps / 不限 | 1899 元/月 | [ 查看不限流量 IIJ](https://bit.ly/LIsahost) |
| 日本 IIJ 双 ISP | 特价年付流量版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 1000GB | 999 元/年 | [ 查看日本年付](https://bit.ly/LIsahost) |
| 日本 ISP 住宅 IP | 300Mbps 固定流量版 | 1 核 / 1GB / 20GB NVMe / 300Mbps / 3000GB | 169 元/月 | [ 查看日本 ISP](https://bit.ly/LIsahost) |
| 日本 ISP 住宅 IP | 500Mbps 固定流量版 | 2 核 / 2GB / 40GB NVMe / 500Mbps / 8000GB | 399 元/月 | [ 查看日本 ISP](https://bit.ly/LIsahost) |
| 日本 ISP 住宅 IP | 800Mbps 固定流量版 | 4 核 / 4GB / 80GB NVMe / 800Mbps / 20000GB | 899 元/月 | [ 查看日本 ISP](https://bit.ly/LIsahost) |
| 日本 ISP 住宅 IP | 200Mbps 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 200Mbps / 不限 | 1099 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 日本 ISP 住宅 IP | 500Mbps 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 500Mbps / 不限 | 1899 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 日本原生 IP VPS | 基础版 | 1 核 / 1GB / 10GB NVMe / 300Mbps / 3000GB | 88 元/月 | [ 查看日本原生 IP](https://bit.ly/LIsahost) |
| 日本原生 IP VPS | 进阶版 | 2 核 / 2GB / 20GB NVMe / 500Mbps / 8000GB | 158 元/月 | [ 查看日本原生 IP](https://bit.ly/LIsahost) |
| 日本原生 IP VPS | 豪华版 | 4 核 / 4GB / 40GB NVMe / 1Gbps / 20000GB | 300 元/月 | [ 查看日本原生 IP](https://bit.ly/LIsahost) |
| 日本原生 IP VPS | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 200Mbps / 不限 | 598 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 英国双 ISP 住宅 IP | 基础版 | 1 核 / 1GB / 10GB NVMe / 300Mbps / 6000GB | 68 元/月 | [ 查看英国 VPS](https://bit.ly/LIsahost) |
| 英国双 ISP 住宅 IP | 进阶版 | 2 核 / 2GB / 20GB NVMe / 500Mbps / 8000GB | 100 元/月 | [ 查看英国 VPS](https://bit.ly/LIsahost) |
| 英国双 ISP 住宅 IP | 豪华版 | 4 核 / 4GB / 40GB NVMe / 1Gbps / 20000GB | 300 元/月 | [ 查看英国 VPS](https://bit.ly/LIsahost) |
| 英国双 ISP 住宅 IP | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 300Mbps / 2000GB | 466 元/年 | [ 查看英国年付](https://bit.ly/LIsahost) |
| 韩国双 ISP 住宅 IP | 基础版 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 3000GB | 99 元/月 | [ 查看韩国 VPS](https://bit.ly/LIsahost) |
| 韩国双 ISP 住宅 IP | 进阶版 | 2 核 / 2GB / 40GB NVMe / 150Mbps / 5000GB | 188 元/月 | [ 查看韩国 VPS](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 精简版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 3000GB；IPv4+IPv6 | 68 元/月 | [ 查看德国原生 IP](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 基础版 | 1 核 / 1GB / 20GB NVMe / 150Mbps / 5000GB | 88 元/月 | [ 查看德国原生 IP](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 进阶版 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 8000GB | 158 元/月 | [ 查看德国原生 IP](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 豪华版 | 4 核 / 4GB / 80GB NVMe / 300Mbps / 15000GB | 899 元/月 | [ 查看德国原生 IP](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 50Mbps / 不限 | 698 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 100Mbps / 不限 | 1288 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 德国 9929 双栈双原生 IP | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 600GB | 499 元/年 | [ 查看德国年付](https://bit.ly/LIsahost) |
| 德国双 ISP 住宅 VDS | 100Mbps 固定流量版 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 3000GB | 169 元/月 | [ 查看德国住宅 VDS](https://bit.ly/LIsahost) |
| 德国双 ISP 住宅 VDS | 200Mbps 固定流量版 | 2 核 / 2GB / 40GB NVMe / 200Mbps / 8000GB | 399 元/月 | [ 查看德国住宅 VDS](https://bit.ly/LIsahost) |
| 德国双 ISP 住宅 VDS | 100Mbps 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 100Mbps / 不限 | 1099 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 德国双 ISP 住宅 VDS | 200Mbps 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 200Mbps / 不限 | 1899 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 德国双 ISP 住宅 VDS | 特价年付流量版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 1000GB | 1099 元/年 | [ 查看德国年付](https://bit.ly/LIsahost) |
| 越南双 ISP 住宅 IP | 基础版 | 1 核 / 1GB / 20GB NVMe / 100Mbps / 3000GB | 88 元/月 | [ 查看越南 VPS](https://bit.ly/LIsahost) |
| 越南双 ISP 住宅 IP | 进阶版 | 2 核 / 2GB / 40GB NVMe / 150Mbps / 6000GB | 129 元/月 | [ 查看越南 VPS](https://bit.ly/LIsahost) |
| 越南双 ISP 住宅 IP | 豪华版 | 4 核 / 4GB / 80GB NVMe / 200Mbps / 20000GB | 599 元/月 | [ 查看越南 VPS](https://bit.ly/LIsahost) |
| 越南双 ISP 住宅 IP | 不限流量 Lite | 2 核 / 2GB / 40GB NVMe / 100Mbps / 不限 | 899 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 越南双 ISP 住宅 IP | 不限流量 Pro | 4 核 / 4GB / 80GB NVMe / 200Mbps / 不限 | 1899 元/月 | [ 查看不限流量方案](https://bit.ly/LIsahost) |
| 越南双 ISP 住宅 IP | 特价年付版 | 1 核 / 1GB / 10GB NVMe / 100Mbps / 1000GB | 699 元/年 | [ 查看越南年付](https://bit.ly/LIsahost) |

美国 9929、4837、西雅图家庭宽带、美国 CERA、纽约、香港三网、香港 iCable、香港 HGC、新加坡、台湾、德国、日本、英国和越南的上述价格与配置均来自本次抓取的 LisaHost 官方产品页；例如美国 9929、4837、纽约、香港 HGC、英国、德国与越南页面均直接列出套餐参数和周期。

需要特别注意，**少数官网分类页存在动态加载导致的字段提取不完整**。本次没有将无法稳定核验的型号、价格或套餐 ID 用第三方资料“补齐”。这比为了让表格看起来整齐而写一个未经证实的数字更可靠。

## 几条产品线，实际差异在哪里

### 美国 9929：围绕住宅 IP 做配置分级

这是官网目前非常醒目的产品线。普通套餐价格从 **68 元/月**起，精简版给到 1 核、1GB、10GB NVMe、50Mbps、1000GB；基础版提高到 20GB、60Mbps、2000GB；进阶版为 2 核 2GB、40GB、80Mbps、4000GB；豪华版则到 4 核 4GB、80GB、100Mbps、8000GB。

真正值得注意的是不限流量档：Lite 为 **498 元/月**，Pro 为 **1288 元/月**。它们的网络速度反而不比普通档更高，Lite 是 20Mbps，Pro 是 50Mbps，差异更多体现在“不限流量”和资源配置。

换句话说，假如你的流量使用并不大，只是需要一个特定 IP 属性，那么直接上不限流量版本未必有必要。

### 美国 4837：带宽和流量给得更激进

4837 产品的基础版已经有 **300Mbps + 3000GB**，进阶版是 500Mbps + 8000GB，豪华版达到 1Gbps + 20000GB。官网还特别强调双 ISP 家宽住宅 IP。

这个系列更像是在“住宅 IP + 大带宽”方向继续往上堆配置。

### CERA：核心卖点不是便宜，而是高防

CERA 页面明确写有默认 **50G 防御**，可付费增加到 100G；官网还说明 100G 内可秒解，超过 100G 后 15 分钟解封。

所以不要把 40 元/月的 CERA 精简版理解成普通 VPS 的廉价替代品。它的主要购买理由来自线路和防御能力，而不是纯算力。

### 美国住宅 VDS：退款限制尤其值得看

这是 LisaHost 里面最应该仔细读购买规则的一类。

西雅图家庭宽带产品页面明确写着：**特殊产品，仅退网站余额**；同时产品说明要求避免垃圾邮件、批量邮件、攻击扫描、钓鱼诈骗和资源滥用，一旦发现或者被投诉，可能直接停机且不退款。

例如西雅图基础版 169 元/月，1 核 1GB、20GB NVMe、100Mbps、3000GB；200Mbps 不限流量版本则是 599 元/月、4 核 4GB、80GB NVMe。

这个限制非常具体，所以住宅 IP VDS 不应该按照普通“买个 VPS，不满意退款”的思路理解。

## 香港方案：线路和本地服务是主要卖点

香港三网线路页面写得非常具体：电信去程 CN2、联通 9929、移动 CMIN2，并强调三网回程大陆优化；基础版目前显示 **88 元/月**，1 核 1GB、20GB NVMe、30Mbps、1000GB 流量。进阶版是 188 元/月，2 核 2GB、40GB、50Mbps、2000GB。

iCable 和 HGC 则把重点转到了香港住宅 IP。

iCable 精简版 **88 元/月**，1 核 1GB、10GB NVMe、100Mbps、2000GB；基础版为 **129 元/月**，20GB、150Mbps、4000GB；进阶版为 299 元/月，2 核 2GB、40GB、200Mbps、6000GB。

HGC 精简版 **99 元/月**，基础版 129 元/月，进阶版 299 元/月，豪华版 599 元/月，另外还有不限流量 Lite。

这三条线不是简单的价格排序。三网优化、住宅 IP、本地服务解锁和香港节点位置，对不同业务的重要程度完全不同。

## 日本产品：IP 需求非常明确

日本 IIJ 产品页明确写出使用日本本土宽带运营商 IIJ 的 IP，且部分 IP 段按照 IP 提供方要求禁用 ping；官网特别说明“不能 ping 是正常的，不影响使用”。

当前固定流量版本从 **188 元/月**起，基础版 1 核 1GB、20GB NVMe、100Mbps、3000GB；进阶版 399 元/月，2 核 2GB、40GB、200Mbps、8000GB；豪华版 899 元/月，4 核 4GB、80GB、300Mbps、20000GB。不限流量 Lite 与 Pro 分别为 1099 元/月和 1899 元/月，另有 **999 元/年**的特价年付流量版。

日本 ISP 静态住宅 IP VDS 的价格结构也很接近：固定流量版本目前从 169 元/月起，不限流量 Lite 为 1099 元/月，Pro 为 1899 元/月，另有 899 元/年的年付版。

这里最重要的购买前确认项其实很简单：**你的业务到底需要日本 ISP/住宅属性，还是只需要日本节点。**

## 新加坡、台湾、德国、英国和越南

新加坡 BGP 产品官网明确提醒：它不是针对中国大陆直连做优化的网络，部分联通和移动网络表现较好，官方建议通过香港或日本中转。基础版 68 元/月，1 核 1GB、10GB NVMe、300Mbps、6000GB；进阶版 88 元/月；豪华版 388 元/月；不限流量 Lite/Pro 分别为 398 元/月和 898 元/月；年付版为 466 元/年。

台湾产品也类似。台湾 BGP 页面明确提示并非大陆直连优化网络；台湾原生 IP VPS 进阶版为 99 元/月，豪华版 388 元/月，另有 299/599/1599 元/月的 VDS 不限流量规格以及 766 元/年的年付产品。

德国是当前官网新增产品线之一。德国 9929 双栈产品把 **原生 IPv4 + 原生 IPv6**作为明显卖点，精简版 68 元/月、基础版 88 元/月、进阶版 158 元/月；豪华版 899 元/月；不限流量 Lite 698 元/月、Pro 1288 元/月；年付版 499 元/年。

英国双 ISP 住宅产品从 68 元/月起，基础、进阶、豪华分别为 1 核 1GB、2 核 2GB、4 核 4GB；官网同样提示其属于非大陆直连优化网络，建议需要时通过香港或日本中转。年付特价版为 466 元/年。

越南产品的公开规格也比较完整：基础版 88 元/月，进阶版 129 元/月，豪华版 599 元/月，不限流量 Lite 为 899 元/月、Pro 为 1899 元/月，年付版 699 元/年。

## 退款政策：不要只看“48 小时无条件退款”

LisaHost 官网首页确实把“48小时不满意无条件退款”作为服务卖点。

但产品页之间存在明显差异：

普通 VPS 类产品大量直接写 **48小时不满意，无条件退款**；例如美国 9929、4837、纽约和新加坡产品都有类似说明。

而部分 VDS、住宅 IP 产品明确写 **“特殊产品，仅退网站余额”**。西雅图住宅 VDS、台湾不限流量 VDS、日本 IIJ、德国住宅 VDS 等页面都存在这样的规则。

另外，2 元的 CN2 GIA 试用版和 CERA 试用版本身就标明 **无退款**，而且是一次性一天体验。

所以实际下单前，最好直接看你准备购买的那个具体产品页，而不是只看首页那一句“48小时退款”。

## LisaHost 的优惠码，现在应该怎么理解

这一项尤其容易被旧文章带偏。

我检索到大量 2026 年第三方文章都重复提到一个优惠码 `TS-CBP205DQJE`，并声称可以长期九折、甚至与季付九折、年付八折、两年付七折叠加。这个说法在多个 GitHub 和博客页面中反复出现。

但在我本轮核查到的 LisaHost 官方首页及当前产品价格页里，没有找到能够直接确认该优惠码当前有效的官方公开说明。

因此，**不建议把这个码直接写成“已验证当前有效优惠”**。

更现实的做法是进入订单页后再检查优惠码输入框实际是否接受。如果页面没有通过验证，就不要把第三方文章里的旧码当成当前优惠。

官网本身已经明确显示大量“限时特价”，而且不同套餐的价格已经是特价价，例如美国 CERA 精简版由 55 元标成 40 元，美国 CERA 基础版由 75 元标成 50 元；这些才是当前产品页可以直接确认的价格信息。

## 用户评价怎么看：公开数据其实很少

这一点反而很值得单独说。

我能找到的 Trustpilot 页面目前只有 **1 条评论**，页面显示评分为 **3.2/5**，这条评论发布于 2026 年 1 月 29 日，给出 1 星，并指责服务商存在诈骗问题。

问题在于，**只有 1 条公开评论的数据量太小，不能据此推断 LisaHost 整体用户满意度**。

与此同时，2026 年出现了大量正面或偏正面的第三方评测文章，但不少来自个人博客、GitHub 页面或推广性质较强的网站。有些文章声称做过延迟、IP 清洁度、流媒体解锁等测试，也有文章明确说明自己没有租用测试机，只对官方公开信息做整理。

社区讨论中也存在另一种意见。IDC Flare 2026 年的一篇用户评测质疑 LisaHost 某些所谓“住宅 IP”是否符合严格意义上的真实家庭宽带定义，并特别指出部分地区 IP 在其判断标准下更接近机房 IP。这个观点属于第三方用户的技术判断，不能当成 LisaHost 官方事实，但它确实提醒了一个重要问题：**“IP 数据库显示 ISP”与“真正的家庭宽带终端 IP”并不是完全等价的概念。**

所以，评价 LisaHost 时，比单看“好评很多”或“有人骂它”更有意义的是看你自己的业务是否能在退款窗口内正常运行。

## 哪些情况适合先从 LisaHost 的低价套餐开始

### 只是想试网络或 IP

官网的 2 元一天 CN2 GIA 试用方案很适合用来确认：

网络是否能正常访问你的目标服务、延迟是否符合业务需求、IP 是否被你的目标平台接受。

不过它本身是一天试用，而且每用户限购一次，且无退款。

### 需要美国住宅 IP，但算力要求不高

可以先从美国 9929 或 4837 的低配档看起。68 元/月附近已经可以买到 1 核 1GB 的方案，而且对应的带宽、流量和 IP 类型已经足够明确。

更重要的是，不要因为看到“住宅 IP”三个字就直接选择 500 元以上的不限流量产品。假如你的业务每月只有几百 GB 流量，普通流量套餐往往就够用。

### 真正需要大流量

这时候才应该看不限流量版本。

不过不限流量不等于“无限速度”。美国 9929 Lite 仍然只有 20Mbps，美国 4837 Lite 是 200Mbps，纽约 Lite 为 200Mbps，德国 Lite 仅 50Mbps。

所以购买不限流量前，一定要一起看 **端口带宽**。

### 做高防业务

直接看 CERA，而不是单纯按价格找普通 VPS。CERA 页面把 CN2 GIA、高防和美国原生 IP 放在同一个产品定位里。

## LisaHost 最大的购买风险，其实不是价格

价格非常透明，反而不是最容易踩坑的地方。

真正需要注意的是 **IP 属性、线路、退款条件和具体使用限制之间的组合**。

例如：

> 普通 VPS 写着 48 小时退款，不代表住宅 VDS 也一定按同样方式原路退款；部分特殊产品明确只退网站余额。

另一个容易被忽略的是，“住宅 IP”产品通常比普通 VPS 对滥用行为更敏感。西雅图住宅 VDS 页面直接禁止垃圾邮件、批量邮件、攻击扫描、钓鱼诈骗和资源滥用等行为，被投诉后可能停机且不退款。

因此，如果你的业务属于正常的网站、远程办公、程序部署、跨境业务环境、合法的数据处理等场景，选型重点应该放在网络和资源；如果业务本身容易产生 IP 投诉，那么购买前必须把服务条款和产品页限制看清楚。

## 购买 LisaHost 前，建议按这个顺序检查

第一步先决定 **地区**。美国、香港、日本、德国、新加坡等产品之间的网络方向差异很大。

第二步再决定 **IP 类型**。你需要普通原生 IP、ISP、双 ISP，还是明确标注的住宅 IP？

第三步才看 CPU、内存、SSD、带宽和流量。

第四步看 **退款规则**。尤其是产品名称里带 VDS、住宅、特殊产品、Unlimited 的，要单独确认。

第五步才看优惠。第三方网站提到的优惠码很多，但本轮没有找到官方页面对 `TS-CBP205DQJE` 的当前有效性做明确确认，因此不要把它当成确定折扣。

最后才是价格比较。

这个顺序会比单纯从“68 元/月、88 元/月”开始看套餐靠谱得多，因为 LisaHost 的产品价格差距，本质上很多时候是在为 **IP 属性和网络路线**付费，而不只是为 CPU 和内存付费。

## 常见问题

### LisaHost 有 Windows VPS 吗？

有。多条官方产品页面明确写有支持安装 Windows，例如美国 9929、美国 4837、新加坡、日本、英国、台湾等产品。

### LisaHost 是不是所有产品都有 48 小时退款？

不是。

普通产品中很常见，但部分特殊 VDS 明确只有网站余额退款，试用产品还有直接标注“无退款”的情况。

### 住宅 IP 一定比普通 VPS IP 好吗？

不能这么简单判断。

住宅 IP 的价值来自特定业务对 IP 类型的要求；普通建站、后端服务、开发环境并不会因为“住宅”二字自动获得额外价值。是否值得，取决于你的业务平台、风控规则和目标地区。

### LisaHost 的价格为什么看起来差距特别大？

因为它卖的不只是“几核几 GB”。

同一地区可能同时存在普通原生 IP、9929、4837、CN2 GIA、住宅双 ISP、高防 CERA，以及不限流量版本。比如美国 CERA 40 元/月的精简版和美国 4837 的 68 元/月基础版，价格接近，但产品定位完全不同。

### 现在适合直接买年付吗？

从价格上看，LisaHost 当前确实有大量年付特价产品，例如美国 4837 为 399 元/年、美国 9929 为 499 元/年、新加坡为 466 元/年、德国 9929 为 499 元/年、日本 IIJ 为 999 元/年。

但年付的关键不是“便宜不便宜”，而是你是否已经确认 IP、线路和业务兼容性。

对于第一次使用某条线路的人，先验证业务，再决定长期周期，通常更符合实际。

## 最后怎么理解 LisaHost

把 LisaHost 当成一家“什么都能买一点”的普通 VPS 商家，其实很容易选错。

它现在真正有辨识度的部分，是 **不同地区的原生 IP、双 ISP/住宅 IP、面向中国访问的特色线路、BGP 网络以及 CERA 高防产品**。官网产品数量很多，价格从 2 元一天的试用，到上千元/月的高规格住宅 VDS 都有。

这也意味着，LisaHost 的选购逻辑不是“哪台配置最高”，而是“我到底需要哪一种 IP、哪一条线路、多少流量，以及能不能接受对应退款限制”。

对于还没确定具体需求的人，先看低价试用或月付方案会更容易控制试错成本。

对于已经明确需要美国 9929/4837、香港三网、香港住宅、日本 IIJ、德国双栈原生 IP 或 CERA 高防的人，则应该直接围绕对应产品线比较参数，而不是拿不同类型的套餐横向比较。

[👉 进入 LisaHost 当前套餐与购买页面](https://bit.ly/LIsahost)
