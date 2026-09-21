# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 00:38:45 |
| 运行耗时 | 894.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83607 |
| 去重后节点 | 23524 |
| TCP 可达 | 3000 |
| 真实可用 | 701 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23524 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.5 |
| tcp | 38.3 |
| probe | 313.6 |
| real_test | 464.1 |
| generate | 72.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49973 |
| vmess | 13545 |
| shadowsocks | 9897 |
| trojan | 8283 |
| hysteria2 | 1124 |
| http | 579 |
| shadowsocksr | 124 |
| socks | 66 |
| hysteria | 11 |
| tuic | 4 |
| anytls | 1 |

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
| 83.07 | hysteria2 | 237.7 | 553.6 | 22.28 | 0.0 | 10.0 | 13.33 | 18.46 | Au1rxx-base64 | 66.94.121.46 |
| 79.91 | http | 196.0 | 507.0 | 23.24 | 0.0 | 10.0 | 12.27 | 17.4 | ermaozi | 138.199.35.198 |
| 79.54 | shadowsocks | 251.4 | 611.2 | 21.96 | 0.0 | 10.0 | 13.12 | 18.46 | Au1rxx-base64 | 156.146.38.167 |
| 77.42 | shadowsocks | 304.8 | 765.5 | 20.72 | 0.0 | 10.0 | 13.12 | 18.46 | Au1rxx-base64 | 156.146.38.170 |
| 76.43 | shadowsocks | 258.1 | 628.1 | 21.8 | 0.0 | 10.0 | 13.12 | 18.46 | Au1rxx-base64 | 156.146.38.168 |
| 76.38 | shadowsocks | 266.8 | 559.6 | 21.6 | 0.0 | 10.0 | 13.12 | 18.46 | Au1rxx-base64 | 149.22.95.183 |
| 76.32 | vless | 328.4 | 749.9 | 20.17 | 0.0 | 10.0 | 10.22 | 18.46 | Au1rxx-base64 | 79.141.172.154 |
| 76.15 | shadowsocks | 284.8 | 638.2 | 21.19 | 0.0 | 10.0 | 13.12 | 18.46 | Au1rxx-base64 | 23.150.248.20 |
| 75.85 | vless | 198.1 | 493.9 | 23.19 | 0.0 | 10.0 | 10.22 | 18.46 | Au1rxx-base64 | 172.235.43.210 |
| 75.43 | shadowsocks | 220.7 | 552.6 | 22.67 | 0.0 | 10.0 | 13.12 | 13.64 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.23 | http | 192.7 | 489.3 | 23.32 | 0.0 | 10.0 | 12.27 | 17.4 | ermaozi | 138.199.35.216 |
| 75.05 | vless | 235.0 | 535.2 | 22.34 | 0.0 | 10.0 | 10.22 | 18.46 | Au1rxx-base64 | 31.58.50.200 |
| 75.01 | vless | 239.0 | 558.6 | 22.25 | 0.0 | 10.0 | 10.22 | 15.54 | DeltaKronecker-all | 192.3.20.155 |
| 74.49 | vless | 337.7 | 706.1 | 19.96 | 0.0 | 10.0 | 10.22 | 18.46 | Au1rxx-base64 | 138.124.60.146 |
| 74.42 | vless | 262.6 | 544.4 | 21.7 | 0.0 | 10.0 | 10.22 | 18.46 | Au1rxx-base64 | 162.159.48.32 |
| 74.21 | vless | 252.0 | 533.1 | 21.94 | 0.0 | 10.0 | 10.22 | 13.64 | Surfboard-tg-mixed | 139.64.235.225 |
| 74.05 | vless | 198.0 | 518.4 | 23.19 | 0.0 | 10.0 | 10.22 | 13.64 | Surfboard-tg-mixed | 172.235.38.85 |
| 73.92 | shadowsocks | 253.0 | 618.9 | 21.92 | 0.0 | 10.0 | 13.12 | 13.64 | Surfboard-tg-mixed | 156.146.38.169 |
| 73.84 | trojan | 222.6 | 516.0 | 22.63 | 0.0 | 10.0 | 5.25 | 18.46 | Au1rxx-base64 | 100.42.228.109 |
| 73.29 | vless | 306.6 | 397.7 | 20.68 | 0.09 | 10.0 | 10.22 | 18.46 | Au1rxx-base64 | 172.64.229.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | 0.905 | 327 | 1515 | prefer |
| ermaozi | 0.87 | 0.885 | 26 | 314 | prefer |
| Surfboard-tg-mixed | 0.703 | 0.624 | 242 | 7207 | prefer |
| DeltaKronecker-all | 0.545 | 0.465 | 409 | 6092 | observe |
| mheidari-all | 0.448 | 0.366 | 93 | 16054 | observe |
| tg-oneclickvpnkeys | 0.361 | 1.0 | 3 | 74 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| Au1rxx-clash | 0.322 | 1.0 | 1 | 1670 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7665 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8799 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5768 | observe |
| barry-far-vless | 0.255 | None | 0 | 5983 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 163 |
| geo | ClientOSError | - | 84 |
| speed | TimeoutError | - | 57 |
| speed | ClientOSError | - | 54 |
| cn-block | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyError | - | 12 |
| cn-block | TimeoutError | - | 9 |
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
