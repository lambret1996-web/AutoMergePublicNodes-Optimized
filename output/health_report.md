# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 21:34:01 |
| 运行耗时 | 478.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97228 |
| 去重后节点 | 26475 |
| TCP 可达 | 3000 |
| 真实可用 | 403 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26475 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 43.7 |
| probe | 204.5 |
| real_test | 149.0 |
| generate | 75.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59627 |
| vmess | 15074 |
| shadowsocks | 11211 |
| trojan | 8869 |
| hysteria2 | 1553 |
| http | 576 |
| shadowsocksr | 169 |
| socks | 96 |
| anytls | 27 |
| hysteria | 15 |
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
| 79.0 | vless | 269.7 | 649.6 | 21.53 | 0.0 | 8.58 | 10.55 | 18.34 | Au1rxx-base64 | 195.211.98.43 |
| 78.76 | vless | 281.4 | 713.4 | 21.26 | 0.0 | 8.61 | 10.55 | 18.34 | Au1rxx-base64 | 79.141.172.154 |
| 78.61 | vless | 286.5 | 680.0 | 21.15 | 0.0 | 8.57 | 10.55 | 18.34 | Au1rxx-base64 | 198.251.78.29 |
| 78.39 | shadowsocks | 246.0 | 610.7 | 22.08 | 0.0 | 8.65 | 13.32 | 18.34 | Au1rxx-base64 | 156.146.38.168 |
| 76.66 | shadowsocks | 253.8 | 632.8 | 21.9 | 0.0 | 10.0 | 13.32 | 15.44 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.55 | shadowsocks | 258.5 | 645.5 | 21.79 | 0.0 | 10.0 | 13.32 | 15.44 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.5 | shadowsocks | 274.6 | 641.1 | 21.42 | 0.0 | 8.57 | 13.32 | 18.34 | Au1rxx-base64 | 23.150.248.20 |
| 76.38 | hysteria2 | 283.4 | 275.1 | 21.22 | 4.69 | 7.13 | 12.63 | 18.34 | Au1rxx-base64 | open.w2m.ink |
| 75.38 | shadowsocks | 338.9 | 883.1 | 19.93 | 0.0 | 8.59 | 13.32 | 18.34 | Au1rxx-base64 | 185.156.47.97 |
| 75.21 | shadowsocks | 259.8 | 641.3 | 21.76 | 0.0 | 10.0 | 13.32 | 14.46 | mheidari-all | 156.146.38.170 |
| 74.48 | shadowsocks | 311.9 | 759.6 | 20.56 | 0.0 | 10.0 | 13.32 | 15.44 | Surfboard-tg-mixed | 37.19.198.243 |
| 74.39 | vless | 363.0 | 736.6 | 19.37 | 0.0 | 8.61 | 10.55 | 18.34 | Au1rxx-base64 | 169.40.42.104 |
| 73.37 | vless | 300.0 | 617.7 | 20.83 | 0.0 | 10.0 | 10.55 | 15.44 | Surfboard-tg-mixed | 172.235.38.85 |
| 73.22 | vless | 307.5 | 631.6 | 20.66 | 0.0 | 8.57 | 10.55 | 18.34 | Au1rxx-base64 | 172.235.43.210 |
| 73.18 | vless | 431.4 | 1079.5 | 17.79 | 0.0 | 8.61 | 10.55 | 18.34 | Au1rxx-base64 | 185.95.231.233 |
| 73.05 | shadowsocks | 332.7 | 797.1 | 20.08 | 0.0 | 8.59 | 13.32 | 18.34 | Au1rxx-base64 | 198.98.53.130 |
| 72.68 | vless | 343.9 | 780.5 | 19.82 | 0.0 | 8.58 | 10.55 | 18.34 | Au1rxx-base64 | 66.70.179.198 |
| 72.63 | vless | 333.5 | 642.0 | 20.06 | 0.0 | 8.63 | 10.55 | 18.34 | Au1rxx-base64 | 195.123.240.65 |
| 72.63 | vless | 393.7 | 855.3 | 18.67 | 0.0 | 8.6 | 10.55 | 18.34 | Au1rxx-base64 | 169.40.42.179 |
| 72.57 | vless | 325.3 | 702.3 | 20.25 | 0.0 | 8.59 | 10.55 | 18.34 | Au1rxx-base64 | 169.40.42.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | 0.903 | 248 | 1671 | prefer |
| mheidari-all | 0.901 | 0.829 | 82 | 22345 | prefer |
| Surfboard-tg-mixed | 0.774 | 0.697 | 122 | 7370 | prefer |
| ermaozi | 0.698 | 0.697 | 33 | 304 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 5452 | observe |
| ermaozi-get_subscribe | 0.268 | 1.0 | 1 | 314 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7740 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9253 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5959 | observe |
| barry-far-vless | 0.255 | None | 0 | 6190 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4304 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1701 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 15 |
| speed | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
