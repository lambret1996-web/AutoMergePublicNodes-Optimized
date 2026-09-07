# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 18:25:33 |
| 运行耗时 | 316.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 89152 |
| 去重后节点 | 25044 |
| TCP 可达 | 3000 |
| 真实可用 | 511 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25044 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.4 |
| tcp | 41.5 |
| probe | 94.3 |
| real_test | 129.7 |
| generate | 42.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55518 |
| vmess | 12341 |
| shadowsocks | 10483 |
| trojan | 8684 |
| hysteria2 | 1765 |
| http | 139 |
| shadowsocksr | 132 |
| socks | 47 |
| hysteria | 16 |
| anytls | 16 |
| tuic | 11 |

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
| 84.78 | hysteria2 | 243.0 | 654.6 | 22.15 | 0.0 | 10.0 | 13.85 | 19.88 | Au1rxx-base64 | 159.223.157.129 |
| 82.08 | vless | 263.0 | 661.8 | 21.69 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.212 |
| 81.75 | shadowsocks | 242.7 | 640.8 | 22.16 | 0.0 | 10.0 | 13.71 | 19.88 | Au1rxx-base64 | 37.19.198.160 |
| 81.74 | vless | 277.7 | 695.9 | 21.35 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.16 |
| 81.12 | vless | 277.8 | 640.1 | 21.35 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.231 |
| 80.73 | vless | 321.2 | 787.2 | 20.34 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 66.70.179.198 |
| 80.68 | vless | 323.4 | 849.8 | 20.29 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.35 |
| 80.36 | vless | 337.2 | 893.1 | 19.97 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.75 |
| 80.08 | vless | 349.6 | 807.1 | 19.69 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.168 |
| 79.78 | vless | 362.2 | 892.3 | 19.39 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.202 |
| 79.67 | vless | 361.1 | 949.4 | 19.42 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.223 |
| 79.48 | vless | 272.1 | 636.7 | 21.48 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.232 |
| 79.43 | shadowsocks | 256.4 | 693.6 | 21.84 | 0.0 | 10.0 | 13.71 | 19.88 | Au1rxx-base64 | 37.19.198.236 |
| 79.36 | shadowsocks | 324.5 | 823.7 | 20.27 | 0.0 | 10.0 | 13.71 | 19.88 | Au1rxx-base64 | 38.180.135.156 |
| 79.36 | vless | 362.4 | 831.6 | 19.39 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.95 |
| 78.85 | shadowsocks | 252.0 | 667.4 | 21.94 | 0.0 | 10.0 | 13.71 | 17.2 | Surfboard-tg-mixed | 198.98.53.130 |
| 78.35 | hysteria2 | 311.5 | 607.6 | 20.57 | 0.0 | 10.0 | 13.85 | 19.88 | Au1rxx-base64 | 66.94.121.46 |
| 77.54 | vless | 377.6 | 934.2 | 19.04 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 216.152.147.28 |
| 77.53 | shadowsocks | 314.2 | 751.6 | 20.51 | 0.0 | 10.0 | 13.71 | 19.88 | Au1rxx-base64 | 156.146.38.168 |
| 77.43 | vless | 384.3 | 921.1 | 18.88 | 0.0 | 10.0 | 10.51 | 19.88 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | 0.93 | 316 | 1785 | prefer |
| zhangkai | 0.875 | 0.905 | 21 | 144 | prefer |
| Surfboard-tg-mixed | 0.83 | 0.753 | 154 | 7406 | prefer |
| mheidari-all | 0.603 | 0.524 | 147 | 21150 | observe |
| tg-oneclickvpnkeys | 0.329 | 0.571 | 7 | 196 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 6417 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7870 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8564 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6099 | observe |
| barry-far-vless | 0.255 | None | 0 | 6314 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4218 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1785 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 39 |
| cn-block | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 8 |
| speed | TimeoutError | - | 8 |
| speed | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
