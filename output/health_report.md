# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 12:32:56 |
| 运行耗时 | 651.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 86898 |
| 去重后节点 | 24190 |
| TCP 可达 | 3000 |
| 真实可用 | 425 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24190 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 40.8 |
| probe | 277.2 |
| real_test | 243.7 |
| generate | 81.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51546 |
| vmess | 14008 |
| shadowsocks | 10464 |
| trojan | 8663 |
| hysteria2 | 1384 |
| http | 627 |
| shadowsocksr | 120 |
| socks | 74 |
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
| 80.25 | hysteria2 | 323.4 | 841.2 | 20.29 | 0.0 | 10.0 | 13.04 | 18.02 | Au1rxx-base64 | 159.223.157.129 |
| 79.22 | hysteria2 | 265.8 | 560.0 | 21.63 | 0.0 | 10.0 | 13.04 | 18.02 | Au1rxx-base64 | 66.94.121.46 |
| 78.21 | vless | 260.2 | 678.2 | 21.75 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 216.152.147.28 |
| 77.69 | vless | 282.8 | 719.2 | 21.23 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 79.141.172.154 |
| 76.37 | vless | 330.9 | 811.8 | 20.12 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 66.70.179.198 |
| 75.51 | shadowsocks | 254.6 | 623.6 | 21.88 | 0.0 | 10.0 | 13.97 | 13.66 | Surfboard-tg-mixed | 156.146.38.168 |
| 75.44 | shadowsocks | 257.6 | 634.0 | 21.81 | 0.0 | 10.0 | 13.97 | 13.66 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.29 | shadowsocks | 409.6 | 1103.4 | 18.3 | 0.0 | 10.0 | 13.97 | 18.02 | Au1rxx-base64 | 15.204.247.206 |
| 75.26 | shadowsocks | 271.0 | 686.3 | 21.51 | 0.0 | 10.0 | 13.97 | 13.78 | mheidari-all | 37.19.198.236 |
| 75.25 | shadowsocks | 271.1 | 684.3 | 21.5 | 0.0 | 10.0 | 13.97 | 13.78 | mheidari-all | 37.19.198.243 |
| 75.16 | vless | 361.8 | 905.5 | 19.4 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 169.40.42.225 |
| 75.05 | vless | 364.9 | 915.7 | 19.33 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 169.40.42.75 |
| 75.0 | vless | 387.6 | 938.7 | 18.8 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 169.40.42.179 |
| 74.9 | vless | 385.9 | 997.6 | 18.85 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 185.95.231.156 |
| 74.83 | shadowsocks | 472.6 | 1273.2 | 16.84 | 0.0 | 10.0 | 13.97 | 18.02 | Au1rxx-base64 | 156.146.38.169 |
| 74.67 | shadowsocks | 263.4 | 653.5 | 21.68 | 0.0 | 10.0 | 13.97 | 18.02 | Au1rxx-base64 | 37.19.198.244 |
| 74.61 | vless | 416.0 | 931.7 | 18.15 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 169.40.42.229 |
| 74.28 | shadowsocks | 434.7 | 1071.9 | 17.72 | 0.0 | 10.0 | 13.97 | 18.02 | Au1rxx-base64 | 38.180.135.156 |
| 74.18 | vless | 330.7 | 747.4 | 20.12 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 169.40.42.74 |
| 73.9 | vless | 437.4 | 1019.5 | 17.65 | 0.0 | 10.0 | 8.44 | 18.02 | Au1rxx-base64 | 169.40.42.95 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.905 | 0.836 | 55 | 16008 | prefer |
| Au1rxx-base64 | 0.899 | 0.835 | 266 | 1663 | prefer |
| ermaozi | 0.73 | 0.722 | 54 | 396 | prefer |
| Surfboard-tg-mixed | 0.693 | 0.615 | 135 | 7408 | observe |
| DeltaKronecker-all | 0.629 | 0.551 | 49 | 5931 | observe |
| ermaozi-get_subscribe | 0.337 | 0.304 | 23 | 431 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 129 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7867 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8874 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5925 | observe |
| barry-far-vless | 0.255 | None | 0 | 6149 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4179 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 35 |
| geo | ClientOSError | - | 30 |
| 204 | TimeoutError | - | 22 |
| speed | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 14 |
| geo | TimeoutError | - | 8 |
| 204 | ProxyConnectionError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
