# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 12:29:14 |
| 运行耗时 | 546.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83790 |
| 去重后节点 | 23453 |
| TCP 可达 | 3000 |
| 真实可用 | 499 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23453 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 38.7 |
| probe | 242.3 |
| real_test | 178.4 |
| generate | 79.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50086 |
| vmess | 13476 |
| shadowsocks | 9922 |
| trojan | 8301 |
| hysteria2 | 1131 |
| http | 667 |
| shadowsocksr | 120 |
| socks | 71 |
| hysteria | 11 |
| tuic | 3 |
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
| 81.79 | hysteria2 | 249.8 | 692.4 | 22.0 | 0.0 | 10.0 | 12.63 | 18.26 | mheidari-all | 159.223.157.129 |
| 81.17 | shadowsocks | 243.5 | 674.7 | 22.14 | 0.0 | 10.0 | 14.27 | 18.76 | Au1rxx-base64 | 37.19.198.236 |
| 80.66 | vless | 248.3 | 704.5 | 22.03 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 79.141.172.154 |
| 80.65 | shadowsocks | 244.5 | 681.0 | 22.12 | 0.0 | 10.0 | 14.27 | 18.26 | mheidari-all | 37.19.198.244 |
| 80.37 | shadowsocks | 256.5 | 662.0 | 21.84 | 0.0 | 10.0 | 14.27 | 18.76 | Au1rxx-base64 | 38.180.135.156 |
| 79.94 | vless | 279.4 | 684.3 | 21.31 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.15 |
| 79.73 | shadowsocks | 284.1 | 797.5 | 21.2 | 0.0 | 10.0 | 14.27 | 18.26 | mheidari-all | 37.19.198.160 |
| 79.64 | vless | 292.5 | 775.8 | 21.01 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.35 |
| 79.47 | vless | 287.0 | 690.7 | 21.13 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 216.152.147.28 |
| 79.11 | vless | 315.2 | 780.5 | 20.48 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.90 |
| 78.91 | vless | 324.1 | 828.8 | 20.28 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 66.70.179.198 |
| 78.61 | vless | 337.0 | 858.2 | 19.98 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.168 |
| 78.57 | shadowsocks | 334.3 | 862.5 | 20.04 | 0.0 | 10.0 | 14.27 | 18.76 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 78.55 | shadowsocks | 227.1 | 631.9 | 22.52 | 0.0 | 10.0 | 14.27 | 18.76 | Au1rxx-base64 | 37.19.198.243 |
| 78.45 | vless | 343.9 | 928.4 | 19.82 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.16 |
| 78.22 | vless | 353.6 | 967.4 | 19.59 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.235 |
| 78.21 | vless | 354.1 | 984.3 | 19.58 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 185.95.231.156 |
| 78.07 | vless | 274.8 | 730.0 | 21.42 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.224 |
| 77.69 | vless | 376.4 | 986.3 | 19.06 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.163 |
| 77.56 | vless | 382.3 | 979.3 | 18.93 | 0.0 | 10.0 | 9.87 | 18.76 | Au1rxx-base64 | 169.40.42.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | 0.93 | 272 | 1620 | prefer |
| mheidari-all | 0.837 | 0.764 | 72 | 15979 | prefer |
| Surfboard-tg-mixed | 0.74 | 0.661 | 192 | 7118 | prefer |
| ermaozi | 0.715 | 0.708 | 48 | 365 | prefer |
| DeltaKronecker-all | 0.589 | 0.509 | 53 | 6092 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 89 | observe |
| Epodonios-all | 0.255 | None | 0 | 7603 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9126 | observe |
| barry-far-vless | 0.255 | None | 0 | 5960 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1620 | observe |
| 10ium-ScrapeCategorize-Vless | 0.226 | 0.2 | 5 | 5238 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 49 |
| 204 | TimeoutError | - | 25 |
| 204 | ProxyError | - | 21 |
| geo | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
