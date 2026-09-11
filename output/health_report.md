# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 12:32:39 |
| 运行耗时 | 620.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84160 |
| 去重后节点 | 23261 |
| TCP 可达 | 3000 |
| 真实可用 | 435 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23261 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 40.4 |
| probe | 225.0 |
| real_test | 272.4 |
| generate | 75.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51188 |
| vmess | 12371 |
| shadowsocks | 10004 |
| trojan | 8073 |
| hysteria2 | 1667 |
| http | 648 |
| shadowsocksr | 132 |
| socks | 55 |
| tuic | 12 |
| hysteria | 8 |
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
| 81.07 | hysteria2 | 237.8 | 551.6 | 22.27 | 0.0 | 9.72 | 12.0 | 18.08 | Au1rxx-base64 | 66.94.121.46 |
| 80.71 | shadowsocks | 216.4 | 545.4 | 22.77 | 0.0 | 10.0 | 13.86 | 18.08 | Au1rxx-base64 | 173.244.56.9 |
| 79.82 | vless | 203.4 | 500.6 | 23.07 | 0.0 | 10.0 | 8.67 | 18.08 | Au1rxx-base64 | 172.235.38.85 |
| 79.74 | shadowsocks | 258.3 | 619.6 | 21.8 | 0.0 | 10.0 | 13.86 | 18.08 | Au1rxx-base64 | 156.146.38.170 |
| 79.13 | shadowsocks | 264.2 | 644.0 | 21.66 | 0.0 | 10.0 | 13.86 | 18.08 | Au1rxx-base64 | 156.146.38.168 |
| 77.25 | vless | 227.9 | 524.2 | 22.5 | 0.0 | 10.0 | 8.67 | 18.08 | Au1rxx-base64 | 216.36.124.176 |
| 77.18 | shadowsocks | 205.4 | 502.1 | 23.02 | 0.0 | 10.0 | 13.86 | 14.8 | Surfboard-tg-mixed | 108.181.118.10 |
| 76.4 | hysteria2 | 323.3 | 713.4 | 20.29 | 0.0 | 10.0 | 12.0 | 18.08 | Au1rxx-base64 | 159.223.157.129 |
| 75.93 | http | 227.0 | 572.0 | 22.52 | 0.0 | 10.0 | 12.07 | 16.34 | ermaozi | 138.199.35.207 |
| 75.47 | vless | 202.6 | 501.1 | 23.09 | 0.0 | 10.0 | 8.67 | 18.08 | Au1rxx-base64 | 172.235.43.210 |
| 75.44 | vless | 203.5 | 510.8 | 23.07 | 0.0 | 10.0 | 8.67 | 18.08 | Au1rxx-base64 | 172.233.139.46 |
| 75.09 | shadowsocks | 300.2 | 753.0 | 20.83 | 0.0 | 10.0 | 13.86 | 14.8 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.99 | shadowsocks | 216.9 | 548.0 | 22.76 | 0.0 | 10.0 | 13.86 | 18.08 | Au1rxx-base64 | 173.244.56.6 |
| 74.98 | http | 268.3 | 481.8 | 21.57 | 0.0 | 10.0 | 12.07 | 16.34 | ermaozi | 138.199.35.195 |
| 73.42 | shadowsocks | 243.1 | 550.3 | 22.15 | 0.0 | 10.0 | 13.86 | 14.8 | Surfboard-tg-mixed | 5.78.51.123 |
| 73.4 | http | 206.7 | 536.0 | 22.99 | 0.0 | 10.0 | 12.07 | 16.34 | ermaozi | 138.199.35.200 |
| 73.11 | shadowsocks | 261.3 | 639.6 | 21.73 | 0.0 | 10.0 | 13.86 | 11.6 | mheidari-all | 156.146.38.169 |
| 73.11 | vless | 263.6 | 570.0 | 21.68 | 0.0 | 10.0 | 8.67 | 18.08 | Au1rxx-base64 | 31.58.50.200 |
| 73.05 | http | 222.1 | 561.7 | 22.64 | 0.0 | 10.0 | 12.07 | 16.34 | ermaozi | 138.199.35.206 |
| 72.83 | shadowsocks | 336.1 | 698.1 | 20.0 | 0.0 | 10.0 | 13.86 | 18.08 | Au1rxx-base64 | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.949 | 0.881 | 268 | 1774 | prefer |
| Surfboard-tg-mixed | 0.937 | 0.864 | 103 | 7422 | prefer |
| ermaozi | 0.722 | 0.714 | 42 | 431 | prefer |
| mheidari-all | 0.716 | 0.642 | 53 | 15701 | prefer |
| DeltaKronecker-all | 0.686 | 0.609 | 69 | 6070 | observe |
| ermaozi-get_subscribe | 0.273 | 1.0 | 1 | 461 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 199 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7889 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8530 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5995 | observe |
| barry-far-vless | 0.255 | None | 0 | 6213 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 33 |
| speed | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| geo | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
