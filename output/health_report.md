# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 06:30:27 |
| 运行耗时 | 584.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87431 |
| 去重后节点 | 25200 |
| TCP 可达 | 3000 |
| 真实可用 | 529 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25200 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.7 |
| tcp | 41.8 |
| probe | 200.0 |
| real_test | 256.5 |
| generate | 77.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52028 |
| vmess | 13999 |
| shadowsocks | 10763 |
| trojan | 8658 |
| hysteria2 | 1104 |
| http | 666 |
| shadowsocksr | 121 |
| socks | 73 |
| hysteria | 12 |
| tuic | 4 |
| anytls | 3 |

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
| 83.47 | hysteria2 | 243.3 | 659.9 | 22.15 | 0.0 | 10.0 | 14.0 | 18.42 | Au1rxx-base64 | 159.223.157.129 |
| 80.77 | shadowsocks | 236.4 | 634.3 | 22.3 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 37.19.198.244 |
| 80.63 | shadowsocks | 242.9 | 657.4 | 22.16 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 37.19.198.160 |
| 80.47 | shadowsocks | 249.7 | 677.5 | 22.0 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 37.19.198.236 |
| 78.14 | shadowsocks | 328.7 | 836.4 | 20.17 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 38.180.135.156 |
| 77.77 | shadowsocks | 281.3 | 653.6 | 21.27 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 156.146.38.167 |
| 77.74 | shadowsocks | 285.0 | 669.7 | 21.18 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 156.146.38.170 |
| 77.62 | shadowsocks | 298.5 | 712.7 | 20.87 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 156.146.38.169 |
| 77.54 | vless | 237.3 | 608.1 | 22.28 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 195.123.235.177 |
| 77.47 | shadowsocks | 301.4 | 717.4 | 20.8 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 108.181.57.93 |
| 77.47 | shadowsocks | 357.4 | 998.3 | 19.5 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 15.204.247.206 |
| 77.21 | vless | 251.7 | 694.7 | 21.95 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 79.141.172.154 |
| 77.18 | shadowsocks | 347.6 | 894.3 | 19.73 | 0.0 | 9.84 | 14.05 | 18.42 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 76.88 | vless | 266.0 | 707.5 | 21.62 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 137.184.218.169 |
| 76.66 | shadowsocks | 414.2 | 1159.7 | 18.19 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 198.98.53.130 |
| 76.27 | vless | 292.5 | 761.9 | 21.01 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 169.40.42.133 |
| 76.17 | vless | 296.7 | 721.2 | 20.91 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 169.40.42.75 |
| 76.05 | vless | 301.9 | 787.7 | 20.79 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 169.40.42.184 |
| 75.97 | vless | 305.2 | 722.4 | 20.71 | 0.0 | 10.0 | 6.84 | 18.42 | Au1rxx-base64 | 169.40.42.173 |
| 75.94 | shadowsocks | 289.2 | 623.3 | 21.08 | 0.0 | 10.0 | 14.05 | 18.42 | Au1rxx-base64 | 23.150.248.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | 0.874 | 341 | 1653 | prefer |
| mheidari-all | 0.913 | 0.853 | 34 | 15978 | prefer |
| ermaozi | 0.778 | 0.774 | 53 | 365 | prefer |
| Surfboard-tg-mixed | 0.701 | 0.622 | 196 | 7138 | prefer |
| DeltaKronecker-all | 0.537 | 0.456 | 79 | 6421 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| xiaoji235-airport-v2ray-all | 0.3 | 0.4 | 5 | 3625 | observe |
| Epodonios-all | 0.255 | None | 0 | 7601 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8785 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5908 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1653 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 53 |
| geo | ClientOSError | - | 31 |
| speed | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 10 |
| speed | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
