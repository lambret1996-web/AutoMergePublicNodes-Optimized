# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 18:28:05 |
| 运行耗时 | 563.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 95109 |
| 去重后节点 | 25430 |
| TCP 可达 | 3000 |
| 真实可用 | 448 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25430 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.4 |
| tcp | 43.6 |
| probe | 222.7 |
| real_test | 212.3 |
| generate | 77.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58526 |
| vmess | 13617 |
| shadowsocks | 11065 |
| trojan | 8776 |
| hysteria2 | 2283 |
| http | 613 |
| shadowsocksr | 126 |
| socks | 60 |
| hysteria | 17 |
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
| 80.48 | hysteria2 | 284.4 | 683.3 | 21.19 | 0.0 | 10.0 | 13.12 | 17.74 | Au1rxx-base64 | 159.223.157.129 |
| 80.12 | shadowsocks | 254.6 | 623.3 | 21.88 | 0.0 | 10.0 | 13.74 | 18.96 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.76 | shadowsocks | 268.5 | 622.3 | 21.56 | 0.0 | 10.0 | 13.74 | 18.96 | Surfboard-tg-mixed | 23.150.248.20 |
| 78.74 | hysteria2 | 268.5 | 523.3 | 21.56 | 0.0 | 10.0 | 13.12 | 17.74 | Au1rxx-base64 | 66.94.121.46 |
| 78.63 | shadowsocks | 243.8 | 628.2 | 22.13 | 0.0 | 10.0 | 13.74 | 17.74 | Au1rxx-base64 | 156.146.38.170 |
| 78.63 | shadowsocks | 284.2 | 683.0 | 21.2 | 0.0 | 10.0 | 13.74 | 17.74 | Au1rxx-base64 | 37.19.198.160 |
| 77.6 | vless | 279.2 | 694.8 | 21.31 | 0.0 | 9.9 | 8.65 | 17.74 | Au1rxx-base64 | 79.141.172.154 |
| 77.11 | shadowsocks | 288.7 | 683.4 | 21.1 | 0.0 | 9.86 | 13.74 | 17.74 | Au1rxx-base64 | 37.19.198.236 |
| 75.4 | vless | 307.9 | 728.9 | 20.65 | 0.0 | 10.0 | 8.65 | 18.96 | Surfboard-tg-mixed | 47.89.186.170 |
| 75.02 | vless | 311.8 | 740.2 | 20.56 | 0.0 | 10.0 | 8.65 | 17.74 | Au1rxx-base64 | 47.253.226.114 |
| 74.69 | shadowsocks | 354.6 | 868.2 | 19.57 | 0.0 | 9.86 | 13.74 | 17.74 | Au1rxx-base64 | 15.204.247.206 |
| 74.12 | shadowsocks | 319.8 | 719.4 | 20.37 | 0.0 | 10.0 | 13.74 | 18.96 | Surfboard-tg-mixed | 5.78.51.123 |
| 73.94 | trojan | 244.6 | 598.0 | 22.12 | 0.0 | 10.0 | 13.5 | 11.32 | mheidari-all | 64.94.95.115 |
| 73.53 | hysteria2 | 357.7 | 849.2 | 19.5 | 0.0 | 9.8 | 13.12 | 17.74 | Au1rxx-base64 | 107.175.219.48 |
| 73.1 | vless | 330.5 | 692.7 | 20.13 | 0.0 | 9.87 | 8.65 | 17.74 | Au1rxx-base64 | 169.40.42.235 |
| 72.93 | shadowsocks | 309.6 | 596.8 | 20.61 | 0.0 | 9.86 | 13.74 | 17.74 | Au1rxx-base64 | 173.244.56.9 |
| 72.82 | trojan | 261.8 | 636.5 | 21.72 | 0.0 | 10.0 | 13.5 | 11.32 | mheidari-all | 64.94.95.117 |
| 72.8 | shadowsocks | 291.4 | 541.4 | 21.03 | 0.0 | 9.86 | 13.74 | 17.74 | Au1rxx-base64 | 108.181.118.10 |
| 72.78 | shadowsocks | 250.8 | 610.7 | 21.97 | 0.0 | 10.0 | 13.74 | 11.32 | mheidari-all | 156.146.38.168 |
| 72.68 | shadowsocks | 426.2 | 995.1 | 17.91 | 0.0 | 10.0 | 13.74 | 18.96 | Surfboard-tg-mixed | 142.4.216.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | 0.834 | 301 | 1740 | prefer |
| Surfboard-tg-mixed | 0.796 | 0.719 | 146 | 7573 | prefer |
| ermaozi | 0.637 | 0.629 | 35 | 382 | observe |
| mheidari-all | 0.489 | 0.407 | 162 | 20529 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4222 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5301 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| Epodonios-all | 0.255 | None | 0 | 8071 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9137 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6175 | observe |
| barry-far-vless | 0.255 | None | 0 | 6393 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1740 | observe |
| DeltaKronecker-all | 0.226 | 0.2 | 5 | 5892 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 66 |
| cn-block | ClientOSError | - | 44 |
| speed | ClientOSError | - | 30 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 10 |
| speed | TimeoutError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | exit-country | CN | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
