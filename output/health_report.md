# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 06:35:00 |
| 运行耗时 | 729.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 86343 |
| 去重后节点 | 24246 |
| TCP 可达 | 3000 |
| 真实可用 | 493 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24246 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 40.6 |
| probe | 273.9 |
| real_test | 332.2 |
| generate | 75.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51671 |
| vmess | 13583 |
| shadowsocks | 10290 |
| trojan | 8561 |
| hysteria2 | 1404 |
| http | 626 |
| shadowsocksr | 125 |
| socks | 71 |
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
| 82.31 | shadowsocks | 234.1 | 631.1 | 22.36 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 37.19.198.236 |
| 82.22 | shadowsocks | 237.8 | 641.8 | 22.27 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 37.19.198.243 |
| 81.28 | shadowsocks | 257.1 | 652.5 | 21.83 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 38.180.135.156 |
| 79.75 | shadowsocks | 275.5 | 635.9 | 21.4 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 156.146.38.168 |
| 78.64 | vless | 249.5 | 694.6 | 22.0 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 79.141.172.154 |
| 78.53 | hysteria2 | 299.5 | 584.1 | 20.85 | 0.0 | 10.0 | 13.2 | 19.88 | Au1rxx-base64 | 66.94.121.46 |
| 78.49 | vless | 256.2 | 701.9 | 21.85 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 47.253.226.114 |
| 78.05 | vless | 275.0 | 643.9 | 21.41 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.179 |
| 77.76 | vless | 287.5 | 629.9 | 21.12 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.89 |
| 77.75 | vless | 272.2 | 701.7 | 21.48 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.104 |
| 77.64 | vless | 292.8 | 630.8 | 21.0 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.15 |
| 77.46 | vless | 280.1 | 669.2 | 21.29 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 216.152.147.28 |
| 77.23 | shadowsocks | 432.0 | 1093.2 | 17.78 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 15.204.246.132 |
| 77.21 | vless | 311.4 | 840.3 | 20.57 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 137.184.218.169 |
| 77.17 | shadowsocks | 391.2 | 1039.0 | 18.72 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 51.222.155.113 |
| 77.07 | vless | 291.2 | 623.7 | 21.04 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.232 |
| 76.99 | vless | 320.9 | 731.3 | 20.35 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.16 |
| 76.95 | shadowsocks | 249.6 | 673.0 | 22.0 | 0.0 | 10.0 | 14.07 | 19.88 | Au1rxx-base64 | 37.19.198.244 |
| 76.81 | vless | 325.2 | 812.7 | 20.25 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 66.70.179.198 |
| 76.64 | vless | 335.9 | 592.6 | 20.0 | 0.0 | 10.0 | 6.76 | 19.88 | Au1rxx-base64 | 169.40.42.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | 0.839 | 274 | 1590 | prefer |
| ermaozi | 0.745 | 0.737 | 57 | 396 | prefer |
| mheidari-all | 0.689 | 0.612 | 85 | 17792 | observe |
| Surfboard-tg-mixed | 0.683 | 0.604 | 212 | 7408 | observe |
| DeltaKronecker-all | 0.442 | 0.359 | 92 | 6081 | observe |
| ermaozi-get_subscribe | 0.365 | 0.333 | 21 | 431 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7876 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8898 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5925 | observe |
| barry-far-vless | 0.255 | None | 0 | 6158 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4179 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1590 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 77 |
| geo | ClientOSError | - | 38 |
| 204 | ProxyError | - | 37 |
| speed | TimeoutError | - | 29 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 11 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
