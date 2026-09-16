# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 18:29:47 |
| 运行耗时 | 608.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89351 |
| 去重后节点 | 24450 |
| TCP 可达 | 3000 |
| 真实可用 | 388 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24450 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 42.3 |
| probe | 283.3 |
| real_test | 202.2 |
| generate | 72.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53168 |
| vmess | 14213 |
| shadowsocks | 10604 |
| trojan | 9099 |
| hysteria2 | 1477 |
| http | 592 |
| shadowsocksr | 127 |
| socks | 59 |
| hysteria | 8 |
| tuic | 2 |
| anytls | 2 |

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
| 81.26 | hysteria2 | 257.4 | 576.2 | 21.82 | 0.0 | 10.0 | 13.64 | 18.72 | Au1rxx-base64 | 66.94.121.46 |
| 80.97 | vless | 274.1 | 646.4 | 21.43 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 198.251.78.29 |
| 77.53 | shadowsocks | 247.6 | 614.3 | 22.05 | 0.0 | 10.0 | 13.82 | 16.16 | Surfboard-tg-mixed | 23.150.248.20 |
| 77.15 | hysteria2 | 284.9 | 698.2 | 21.18 | 0.0 | 10.0 | 13.64 | 15.22 | mheidari-all | 159.223.157.129 |
| 76.86 | shadowsocks | 282.6 | 629.3 | 21.24 | 0.0 | 10.0 | 13.82 | 18.72 | Au1rxx-base64 | 198.98.53.130 |
| 76.63 | vless | 297.3 | 559.0 | 20.9 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 144.172.104.26 |
| 76.6 | vless | 302.5 | 648.4 | 20.78 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 195.123.235.177 |
| 76.54 | vless | 302.7 | 711.8 | 20.77 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 216.152.147.28 |
| 76.06 | shadowsocks | 273.6 | 579.7 | 21.44 | 0.0 | 10.0 | 13.82 | 18.72 | Au1rxx-base64 | 5.78.51.123 |
| 75.46 | vless | 375.6 | 912.2 | 19.08 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 137.184.218.169 |
| 75.09 | vless | 349.5 | 689.6 | 19.69 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 169.40.42.133 |
| 74.81 | shadowsocks | 313.8 | 598.9 | 20.51 | 0.0 | 10.0 | 13.82 | 18.72 | Au1rxx-base64 | 149.22.95.183 |
| 74.52 | vless | 289.5 | 572.4 | 21.08 | 0.0 | 10.0 | 10.82 | 16.84 | DeltaKronecker-all | 47.251.108.158 |
| 74.43 | vless | 374.5 | 815.3 | 19.11 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 169.40.42.182 |
| 74.43 | vless | 405.8 | 897.0 | 18.38 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 169.40.42.225 |
| 74.31 | vless | 390.1 | 842.9 | 18.75 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 66.70.179.198 |
| 74.29 | vless | 381.4 | 770.2 | 18.95 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 169.40.42.16 |
| 74.21 | vless | 295.6 | 619.3 | 20.93 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 172.235.43.210 |
| 74.15 | vless | 426.9 | 932.3 | 17.9 | 0.0 | 10.0 | 10.82 | 18.72 | Au1rxx-base64 | 169.40.42.179 |
| 73.74 | shadowsocks | 303.3 | 543.8 | 20.76 | 0.0 | 10.0 | 13.82 | 18.72 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.978 | 0.912 | 57 | 17820 | prefer |
| Au1rxx-base64 | 0.947 | 0.884 | 241 | 1665 | prefer |
| DeltaKronecker-all | 0.741 | 0.664 | 110 | 6081 | prefer |
| Surfboard-tg-mixed | 0.642 | 0.563 | 71 | 7470 | observe |
| ermaozi | 0.49 | 0.667 | 12 | 353 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4234 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 7938 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9095 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6195 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1665 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 27 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 14 |
| 204 | TimeoutError | - | 12 |
| geo | TimeoutError | - | 12 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
