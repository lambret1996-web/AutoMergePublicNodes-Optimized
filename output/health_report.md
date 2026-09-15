# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 12:32:09 |
| 运行耗时 | 621.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90388 |
| 去重后节点 | 25595 |
| TCP 可达 | 3000 |
| 真实可用 | 438 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25595 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.5 |
| tcp | 42.9 |
| probe | 261.0 |
| real_test | 235.6 |
| generate | 74.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55726 |
| vmess | 13071 |
| shadowsocks | 10073 |
| trojan | 8813 |
| hysteria2 | 1825 |
| http | 667 |
| shadowsocksr | 128 |
| socks | 56 |
| hysteria | 14 |
| anytls | 8 |
| tuic | 7 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 77.14 | shadowsocks | 273.1 | 609.1 | 21.46 | 0.0 | 10.0 | 13.86 | 17.36 | Au1rxx-base64 | 198.98.53.130 |
| 76.91 | vless | 283.9 | 656.0 | 21.21 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 198.251.78.29 |
| 76.02 | hysteria2 | 285.4 | 680.4 | 21.17 | 0.0 | 10.0 | 13.04 | 12.92 | mheidari-all | 159.223.157.129 |
| 75.5 | shadowsocks | 251.2 | 611.9 | 21.96 | 0.0 | 10.0 | 13.86 | 17.36 | Au1rxx-base64 | 156.146.38.168 |
| 75.05 | hysteria2 | 333.7 | 742.6 | 20.05 | 0.0 | 10.0 | 13.04 | 17.36 | Au1rxx-base64 | 107.175.219.48 |
| 74.76 | shadowsocks | 244.8 | 601.3 | 22.11 | 0.0 | 10.0 | 13.86 | 14.9 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.63 | shadowsocks | 256.1 | 620.9 | 21.85 | 0.0 | 10.0 | 13.86 | 12.92 | mheidari-all | 156.146.38.170 |
| 74.51 | vless | 356.8 | 528.3 | 19.52 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 38.180.242.205 |
| 73.84 | vless | 305.3 | 663.3 | 20.71 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 195.123.235.177 |
| 72.2 | vless | 307.0 | 573.1 | 20.67 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 150.241.102.181 |
| 72.03 | shadowsocks | 282.2 | 675.0 | 21.25 | 0.0 | 10.0 | 13.86 | 12.92 | mheidari-all | 37.19.198.244 |
| 71.99 | vless | 334.7 | 775.7 | 20.03 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 216.152.147.28 |
| 71.6 | vless | 307.0 | 596.1 | 20.67 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 192.3.247.109 |
| 71.58 | shadowsocks | 328.4 | 733.0 | 20.18 | 0.0 | 10.0 | 13.86 | 17.36 | Au1rxx-base64 | 108.181.57.93 |
| 71.42 | vless | 323.6 | 658.3 | 20.29 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 45.149.172.80 |
| 71.18 | vless | 364.0 | 708.7 | 19.35 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 169.40.42.89 |
| 71.09 | vless | 357.7 | 811.3 | 19.5 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 169.40.42.235 |
| 71.0 | shadowsocks | 366.9 | 946.1 | 19.28 | 0.0 | 10.0 | 13.86 | 17.36 | Au1rxx-base64 | 166.88.130.218 |
| 70.89 | vless | 412.9 | 993.5 | 18.22 | 0.0 | 10.0 | 8.63 | 17.36 | Au1rxx-base64 | 169.40.42.202 |
| 70.87 | shadowsocks | 306.8 | 554.5 | 20.68 | 0.0 | 10.0 | 13.86 | 17.36 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.909 | 0.854 | 308 | 1440 | prefer |
| Surfboard-tg-mixed | 0.727 | 0.649 | 131 | 7608 | prefer |
| ermaozi | 0.67 | 0.66 | 47 | 425 | observe |
| mheidari-all | 0.66 | 0.581 | 86 | 21594 | observe |
| DeltaKronecker-all | 0.53 | 0.7 | 10 | 5932 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 148 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8076 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8760 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6177 | observe |
| barry-far-vless | 0.255 | None | 0 | 6401 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| Au1rxx-clash | 0.233 | None | 0 | 1440 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 41 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 16 |
| speed | ClientOSError | - | 12 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
