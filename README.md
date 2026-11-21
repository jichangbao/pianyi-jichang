# 机场价格数据集 2026｜15 家专线机场年付、月付、不限时套餐比价

> 每月更新的翻墙机场（梯子）公开价格数据：把 15 家专线机场的套餐统一折算成「每月多少钱」和「每 G 多少钱」，方便横向比较。
> 最近更新：**2026-11-13** · 数据维护：阿K（[便宜机场](https://pianyijichang.net/)） · 数据格式：[CSV](jichang-prices.csv) / [JSON](jichang-prices.json)

## 为什么做这个数据集

机场的套餐名、计费周期、流量单位各不相同，直接看标价很难比较。这个仓库只做一件事：把官网公开价格整理成统一口径，任何人都可以拿去做比价、画图或写文章（请注明来源）。

| 字段 | 计算方式 |
| --- | --- |
| 折合月价 | 年付价格 ÷ 12 |
| 每 G 单价（月付） | 月付价格 ÷ 每月流量 |
| 每 G 单价（不限时） | 一次性价格 ÷ 总流量 |

## 年付小包：按折合月价排序

年付小包是最省钱的买法，适合每月 40–80G 的轻度用户。

| # | 机场 | 套餐 | 年付 | 每月流量 | 折合月价 |
| --- | --- | --- | --- | --- | --- |
| 1 | [无忧](https://pianyijichang.net/review/wuyou/) | MINI链接（年付） | ¥79/年 | 50G/月 | **¥6.6** |
| 2 | [唯兔云](https://pianyijichang.net/review/weitu/) | 年付限量款 | ¥79.9/年 | 45G/月 | **¥6.7** |
| 3 | [飞猫云](https://pianyijichang.net/review/feimao/) | 学生版 | ¥84/年 | 50G/月 | **¥7** |
| 4 | [二猫云](https://pianyijichang.net/review/ermao/) | 二猫年付小包 | ¥89/年 | 60G/月 | **¥7.4** |
| 5 | [Firefly](https://pianyijichang.net/review/firefly/) | 年付版 | ¥96/年 | 60G/月 | **¥8** |
| 6 | [宇宙云](https://pianyijichang.net/review/yuzhou/) | 星云年付小包 | ¥96/年 | 60G/月 | **¥8** |
| 7 | [星岛梦](https://pianyijichang.net/review/xingdaomeng/) | 贴心小包 | ¥96/年 | 60G/月 | **¥8** |
| 8 | [U1S1](https://pianyijichang.net/review/u1s1/) | 就是好用包 | ¥96/年 | 60G/月 | **¥8** |
| 9 | [sogo云](https://pianyijichang.net/review/sogo/) | 小包-年付版 | ¥98/年 | 60G/月 | **¥8.2** |
| 10 | [一翻云](https://pianyijichang.net/review/yifan/) | 年付小包 | ¥98/年 | 60G/月 | **¥8.2** |
| 11 | [飞 V](https://pianyijichang.net/review/feiv/) | 年付标准轻量版 | ¥99/年 | 65G/月 | **¥8.3** |
| 12 | [光速云](https://pianyijichang.net/review/guangsu/) | 轻量版 | ¥99/年 | 59G/月 | **¥8.3** |
| 13 | [灵动云](https://pianyijichang.net/review/lingdong/) | 穿云 | ¥99/年 | 79G/月 | **¥8.3** |
| 14 | [暮光](https://pianyijichang.net/review/muguang/) | 年付轻量版 | ¥109/年 | 70G/月 | **¥9.1** |
| 15 | [微风](https://pianyijichang.net/review/weifeng/) | 清风 | ¥137/年 | 100G/月 | **¥11.4** |

## 月付入门套餐：按每 G 单价排序

| 机场 | 套餐 | 月付 | 每月流量 | 每 G 单价 |
| --- | --- | --- | --- | --- |
| 唯兔云 | 普通版 | ¥19.9/月 | 150G/月 | ¥0.13/G |
| 一翻云 | 轻享版 | ¥20/月 | 150G/月 | ¥0.13/G |
| 微风 | 乘风 | ¥27/月 | 200G/月 | ¥0.14/G |
| 二猫云 | 白猫套餐 | ¥20/月 | 130G/月 | ¥0.15/G |
| 宇宙云 | 行星基础版 | ¥25/月 | 160G/月 | ¥0.16/G |
| 无忧 | 舒心链接 | ¥25/月 | 160G/月 | ¥0.16/G |
| sogo云 | 基础版 | ¥25/月 | 150G/月 | ¥0.17/G |
| 飞猫云 | 星耀版 | ¥25/月 | 150G/月 | ¥0.17/G |
| 暮光 | 基础版 | ¥20/月 | 120G/月 | ¥0.17/G |
| 飞 V | 入门方案 | ¥25/月 | 150G/月 | ¥0.17/G |
| Firefly | Lite | ¥25/月 | 150G/月 | ¥0.17/G |
| 光速云 | 极速版 | ¥23/月 | 138G/月 | ¥0.17/G |
| 星岛梦 | 超量150G | ¥25/月 | 150G/月 | ¥0.17/G |
| U1S1 | 普通人真够了包 | ¥20/月 | 120G/月 | ¥0.17/G |
| 灵动云 | 拂风 | ¥20/月 | 100G/月 | ¥0.20/G |

## 不限时流量包：按每 G 单价排序

| 机场 | 流量包 | 价格 | 流量 | 每 G 单价 |
| --- | --- | --- | --- | --- |
| 飞猫云 | 不限时套餐 | ¥680/一次性 | 1000G | ¥0.68/G |
| 光速云 | 不限时套餐 | ¥680/一次性 | 1000G | ¥0.68/G |
| 微风 | 信风·不限时 | ¥200/一次性 | 270G | ¥0.74/G |
| 宇宙云 | 行星不限时版 | ¥110/一次性 | 120G | ¥0.92/G |
| 二猫云 | 不限时套餐 | ¥99/一次性 | 100G | ¥0.99/G |
| sogo云 | 基础餐不限时版 | ¥120/一次性 | 120G | ¥1.00/G |
| Firefly | 不限时 | ¥100/一次性 | 100G | ¥1.00/G |
| 星岛梦 | 永久不限时100 | ¥100/一次性 | 100G | ¥1.00/G |
| 唯兔云 | 永久不限时 | ¥100/一次性 | 100G | ¥1.00/G |
| 一翻云 | 轻享不限时包 | ¥100/一次性 | 100G | ¥1.00/G |
| 无忧 | 100G 永久不限时 | ¥98/一次性 | 100G | ¥0.98/G |
| 灵动云 | 闲云（不限时） | ¥199/一次性 | 150G | ¥1.33/G |
| 飞 V | 单次买断小流量包 | ¥189/一次性 | 130G | ¥1.45/G |
| 暮光 | 不限时轻量包 | ¥219/一次性 | 150G | ¥1.46/G |

## 怎么用这份数据

| 你想做的事 | 去哪里看 |
| --- | --- |
| 按预算挑一家低价机场 | [便宜机场推荐（含优惠码实付价）](https://pianyijichang.net/pianyi-jichang-tuijian/) |
| 比较线路、地区、AI 与流媒体解锁 | [15 家机场综合对比](https://pianyijichang.net/jichang-duibi/) |
| 看速度、稳定性、售后的综合排名 | [机场排行榜](https://pianyijichang.net/jichang-paihangbang/) |
| 下载 Clash、小火箭等客户端 | [客户端下载汇总](https://pianyijichang.net/download/) |
| 想要一家长期主力 | 阿K 目前主力使用 [sogo云](https://pianyijichang.net/review/sogo/)（IPLC 专线、原生 IP，年付 ¥98） |
| 第一次用机场 | [机场是什么](https://pianyijichang.net/blog/jichang-shi-shenme/) · [订阅导入教程](https://pianyijichang.net/jiaocheng/daoru-dingyue/) |

## 数据说明

- 价格来自各机场官网公开套餐，单位人民币，以官网下单页为准；每月复核一次。
- 本仓库只整理公开信息，不提供任何代理服务，也不出售账号。
- 评分与排名规则见 [测评方法](https://pianyijichang.net/pingce-fangfa/)；发现数据有误欢迎提 Issue。
- 请遵守所在地法律法规，合理使用网络服务。

## 许可

数据以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans) 发布：可以自由使用和转载，请注明来源「便宜机场 pianyijichang.net」。
