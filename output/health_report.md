# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 00:36:54 |
| 运行耗时 | 740.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83456 |
| 去重后节点 | 22993 |
| TCP 可达 | 3000 |
| 真实可用 | 514 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22993 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 39.6 |
| probe | 285.3 |
| real_test | 329.1 |
| generate | 80.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50723 |
| vmess | 12321 |
| shadowsocks | 9816 |
| trojan | 8117 |
| hysteria2 | 1705 |
| http | 568 |
| shadowsocksr | 129 |
| socks | 53 |
| tuic | 12 |
| hysteria | 8 |
| anytls | 4 |

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
| 80.76 | shadowsocks | 228.5 | 541.2 | 22.49 | 0.0 | 10.0 | 13.87 | 18.4 | Au1rxx-base64 | 173.244.56.6 |
| 80.24 | hysteria2 | 246.9 | 572.0 | 22.06 | 0.0 | 10.0 | 11.74 | 18.4 | Au1rxx-base64 | 66.94.121.46 |
| 78.1 | vless | 199.5 | 484.4 | 23.16 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 104.194.74.73 |
| 77.99 | vless | 204.3 | 500.8 | 23.05 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 172.236.233.59 |
| 77.87 | shadowsocks | 206.5 | 492.5 | 23.0 | 0.0 | 10.0 | 13.87 | 15.5 | Surfboard-tg-mixed | 108.181.118.10 |
| 77.57 | vless | 265.5 | 662.4 | 21.63 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 107.173.237.146 |
| 76.14 | shadowsocks | 302.5 | 757.6 | 20.77 | 0.0 | 10.0 | 13.87 | 15.5 | Surfboard-tg-mixed | 173.244.56.9 |
| 75.92 | shadowsocks | 199.9 | 535.7 | 23.15 | 0.0 | 10.0 | 13.87 | 18.4 | Au1rxx-base64 | 129.146.122.135 |
| 75.77 | vless | 300.3 | 767.5 | 20.83 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 38.209.125.45 |
| 75.77 | vless | 323.9 | 737.1 | 20.28 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 79.141.172.154 |
| 75.2 | vless | 238.5 | 615.0 | 22.26 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 216.36.124.176 |
| 74.93 | vless | 246.7 | 564.0 | 22.07 | 0.0 | 10.0 | 9.54 | 18.4 | Au1rxx-base64 | 31.58.50.200 |
| 74.0 | vless | 254.5 | 312.4 | 21.89 | 3.28 | 9.92 | 9.54 | 15.5 | Surfboard-tg-mixed | 31.76.91.72 |
| 73.3 | shadowsocks | 278.8 | 278.0 | 21.32 | 4.58 | 9.9 | 13.87 | 15.5 | Surfboard-tg-mixed | 45.32.16.53 |
| 73.18 | shadowsocks | 299.2 | 747.6 | 20.85 | 0.0 | 10.0 | 13.87 | 15.5 | Surfboard-tg-mixed | 156.146.38.167 |
| 72.71 | http | 413.1 | 1159.3 | 18.22 | 0.0 | 10.0 | 11.79 | 15.7 | ermaozi | 138.199.35.216 |
| 72.7 | http | 413.1 | 1153.2 | 18.21 | 0.0 | 10.0 | 11.79 | 15.7 | ermaozi | 138.199.35.198 |
| 72.66 | shadowsocks | 286.3 | 630.6 | 21.15 | 0.0 | 10.0 | 13.87 | 15.5 | Surfboard-tg-mixed | 23.150.248.20 |
| 72.65 | shadowsocks | 265.6 | 648.4 | 21.63 | 0.0 | 10.0 | 13.87 | 11.48 | mheidari-all | 156.146.38.170 |
| 72.32 | shadowsocks | 262.2 | 638.8 | 21.71 | 0.0 | 10.0 | 13.87 | 11.48 | mheidari-all | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.955 | 0.895 | 296 | 1552 | prefer |
| Surfboard-tg-mixed | 0.832 | 0.755 | 204 | 7329 | prefer |
| ermaozi | 0.824 | 0.833 | 24 | 405 | prefer |
| mheidari-all | 0.571 | 0.49 | 104 | 15770 | observe |
| DeltaKronecker-all | 0.419 | 0.333 | 57 | 5853 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 7698 | observe |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 165 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8841 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5926 | observe |
| barry-far-vless | 0.255 | None | 0 | 6066 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1552 | observe |
| ninja-vless | 0.232 | 0.25 | 4 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 41 |
| geo | TimeoutError | - | 41 |
| speed | TimeoutError | - | 40 |
| speed | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyError | - | 8 |
| 204 | TimeoutError | - | 8 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
