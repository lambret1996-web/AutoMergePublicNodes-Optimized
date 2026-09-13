# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 06:39:37 |
| 运行耗时 | 857.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94410 |
| 去重后节点 | 25154 |
| TCP 可达 | 3000 |
| 真实可用 | 561 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25154 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.6 |
| tcp | 41.4 |
| probe | 336.5 |
| real_test | 380.5 |
| generate | 89.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57824 |
| vmess | 13513 |
| shadowsocks | 10949 |
| trojan | 9014 |
| hysteria2 | 2242 |
| http | 639 |
| shadowsocksr | 124 |
| socks | 64 |
| hysteria | 15 |
| anytls | 14 |
| tuic | 12 |

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
| 85.07 | hysteria2 | 211.2 | 510.0 | 22.89 | 0.0 | 10.0 | 13.7 | 19.48 | Au1rxx-base64 | 66.94.121.46 |
| 82.41 | shadowsocks | 196.8 | 477.7 | 23.22 | 0.0 | 10.0 | 14.21 | 19.48 | Au1rxx-base64 | 108.181.0.177 |
| 80.5 | hysteria2 | 279.1 | 787.8 | 21.32 | 0.0 | 10.0 | 13.7 | 19.48 | Au1rxx-base64 | 107.175.219.48 |
| 80.45 | shadowsocks | 230.7 | 597.5 | 22.44 | 0.0 | 10.0 | 14.21 | 18.3 | Surfboard-tg-mixed | 5.78.51.123 |
| 78.85 | vless | 199.3 | 502.1 | 23.17 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.235.43.210 |
| 78.23 | vless | 226.0 | 533.8 | 22.55 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.233.139.46 |
| 77.55 | hysteria2 | 354.0 | 734.8 | 19.58 | 0.0 | 10.0 | 13.7 | 19.48 | Au1rxx-base64 | 159.223.157.129 |
| 76.34 | shadowsocks | 290.3 | 647.8 | 21.06 | 0.0 | 10.0 | 14.21 | 18.3 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.3 | vless | 309.2 | 811.0 | 20.62 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 15.204.97.216 |
| 75.42 | vless | 347.0 | 559.4 | 19.74 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.235.38.85 |
| 75.15 | vless | 267.9 | 524.4 | 21.58 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 144.172.104.26 |
| 74.69 | shadowsocks | 303.8 | 642.8 | 20.74 | 0.0 | 10.0 | 14.21 | 18.3 | Surfboard-tg-mixed | 23.150.248.20 |
| 74.47 | shadowsocks | 283.7 | 626.8 | 21.21 | 0.0 | 10.0 | 14.21 | 19.48 | Au1rxx-base64 | 156.146.38.169 |
| 74.26 | vless | 203.0 | 488.2 | 23.08 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.64.32.103 |
| 73.73 | vless | 204.4 | 506.7 | 23.05 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 31.58.50.200 |
| 73.72 | vless | 195.6 | 487.3 | 23.25 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.64.229.170 |
| 73.46 | vless | 194.4 | 482.2 | 23.28 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.64.32.108 |
| 73.38 | vless | 197.6 | 486.0 | 23.2 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 104.18.39.218 |
| 73.36 | vless | 252.1 | 595.0 | 21.94 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 172.64.52.6 |
| 73.05 | vless | 233.5 | 627.2 | 22.37 | 0.0 | 10.0 | 6.2 | 19.48 | Au1rxx-base64 | 45.149.172.80 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.907 | 0.839 | 355 | 1728 | prefer |
| mheidari-all | 0.782 | 0.707 | 92 | 20709 | prefer |
| Surfboard-tg-mixed | 0.727 | 0.649 | 171 | 7432 | prefer |
| ermaozi | 0.684 | 0.679 | 28 | 436 | observe |
| DeltaKronecker-all | 0.467 | 0.385 | 161 | 5970 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| ermaozi-get_subscribe | 0.3 | 0.4 | 10 | 464 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 83 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8741 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6027 | observe |
| barry-far-vless | 0.255 | None | 0 | 6247 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4221 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 78 |
| geo | ClientOSError | - | 47 |
| speed | ClientOSError | - | 40 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 20 |
| speed | TimeoutError | - | 18 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | exit-country | CN | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
