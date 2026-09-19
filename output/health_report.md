# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 00:34:12 |
| 运行耗时 | 657.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84075 |
| 去重后节点 | 23209 |
| TCP 可达 | 3000 |
| 真实可用 | 550 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23209 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.4 |
| tcp | 39.2 |
| probe | 253.5 |
| real_test | 329.4 |
| generate | 25.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50489 |
| vmess | 13372 |
| shadowsocks | 9931 |
| trojan | 8223 |
| hysteria2 | 1271 |
| http | 587 |
| shadowsocksr | 123 |
| socks | 62 |
| hysteria | 8 |
| anytls | 7 |
| tuic | 2 |

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
| 80.64 | vless | 203.1 | 512.4 | 23.08 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 172.235.43.210 |
| 80.53 | vless | 207.7 | 489.3 | 22.97 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 45.149.172.74 |
| 78.79 | shadowsocks | 261.1 | 634.6 | 21.73 | 0.0 | 10.0 | 12.82 | 18.24 | Au1rxx-base64 | 156.146.38.169 |
| 78.78 | shadowsocks | 252.7 | 611.5 | 21.93 | 0.0 | 10.0 | 12.82 | 18.24 | Au1rxx-base64 | 156.146.38.170 |
| 78.52 | hysteria2 | 329.6 | 704.8 | 20.15 | 0.0 | 10.0 | 14.29 | 18.24 | Au1rxx-base64 | 159.223.157.129 |
| 77.86 | trojan | 240.2 | 555.5 | 22.22 | 0.0 | 10.0 | 10.91 | 18.24 | Au1rxx-base64 | 100.42.228.109 |
| 76.66 | http | 196.1 | 507.1 | 23.24 | 0.0 | 10.0 | 9.86 | 16.56 | ermaozi | 138.199.35.198 |
| 76.22 | hysteria2 | 390.8 | 783.1 | 18.73 | 0.0 | 9.88 | 14.29 | 18.24 | Au1rxx-base64 | 66.94.121.46 |
| 75.68 | vless | 199.6 | 507.9 | 23.16 | 0.0 | 10.0 | 9.32 | 14.2 | Surfboard-tg-mixed | 172.235.38.85 |
| 75.56 | http | 200.3 | 521.5 | 23.14 | 0.0 | 10.0 | 9.86 | 16.56 | ermaozi | 138.199.35.216 |
| 75.39 | vless | 235.1 | 544.0 | 22.33 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 162.159.43.187 |
| 75.24 | vless | 220.2 | 551.1 | 22.68 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 195.123.240.65 |
| 74.94 | vless | 233.3 | 535.8 | 22.38 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 31.58.50.200 |
| 74.87 | shadowsocks | 285.2 | 639.1 | 21.17 | 0.0 | 10.0 | 12.82 | 18.24 | Au1rxx-base64 | 23.150.248.20 |
| 74.81 | shadowsocks | 255.0 | 622.1 | 21.88 | 0.0 | 10.0 | 12.82 | 14.2 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.76 | shadowsocks | 281.2 | 612.0 | 21.27 | 0.0 | 10.0 | 12.82 | 18.24 | Au1rxx-base64 | 149.22.95.183 |
| 74.65 | vless | 267.2 | 456.3 | 21.59 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 104.18.46.46 |
| 74.51 | vless | 356.3 | 845.4 | 19.53 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 15.204.97.216 |
| 74.5 | vless | 222.6 | 488.8 | 22.63 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 104.18.39.218 |
| 74.04 | vless | 293.8 | 455.7 | 20.98 | 0.0 | 10.0 | 9.32 | 18.24 | Au1rxx-base64 | 172.64.229.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | 0.906 | 319 | 1773 | prefer |
| ermaozi | 0.821 | 0.833 | 24 | 325 | prefer |
| Surfboard-tg-mixed | 0.743 | 0.664 | 244 | 7329 | prefer |
| mheidari-all | 0.553 | 0.473 | 129 | 15908 | observe |
| roosterkid-openproxylist-v2ray | 0.483 | 1.0 | 6 | 150 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| DeltaKronecker-all | 0.269 | 0.176 | 51 | 6040 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8782 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5896 | observe |
| barry-far-vless | 0.255 | None | 0 | 6111 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1774 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 87 |
| speed | TimeoutError | - | 51 |
| geo | ClientOSError | - | 27 |
| speed | ClientOSError | - | 20 |
| 204 | ProxyError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
