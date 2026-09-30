# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 12:35:50 |
| 运行耗时 | 689.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96416 |
| 去重后节点 | 26887 |
| TCP 可达 | 3000 |
| 真实可用 | 453 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26887 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 45.4 |
| probe | 327.0 |
| real_test | 220.6 |
| generate | 87.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58476 |
| vmess | 15247 |
| shadowsocks | 11267 |
| trojan | 9053 |
| hysteria2 | 1431 |
| http | 639 |
| shadowsocksr | 171 |
| socks | 72 |
| anytls | 37 |
| hysteria | 15 |
| tuic | 8 |

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
| 82.55 | hysteria2 | 199.4 | 489.3 | 23.16 | 0.0 | 10.0 | 13.33 | 17.06 | Au1rxx-base64 | 192.255.128.123 |
| 78.87 | http | 220.0 | 556.0 | 22.69 | 0.0 | 10.0 | 12.58 | 16.6 | ermaozi | 138.199.35.216 |
| 78.81 | shadowsocks | 211.6 | 523.4 | 22.88 | 0.0 | 10.0 | 13.37 | 17.06 | Au1rxx-base64 | 108.181.0.177 |
| 78.75 | http | 224.9 | 559.6 | 22.57 | 0.0 | 10.0 | 12.58 | 16.6 | ermaozi | 138.199.35.215 |
| 78.74 | http | 225.6 | 535.8 | 22.56 | 0.0 | 10.0 | 12.58 | 16.6 | ermaozi | 138.199.35.214 |
| 78.41 | shadowsocks | 204.7 | 517.6 | 23.04 | 0.0 | 10.0 | 13.37 | 16.5 | Surfboard-tg-mixed | 192.3.247.109 |
| 77.45 | shadowsocks | 205.7 | 549.5 | 23.02 | 0.0 | 10.0 | 13.37 | 17.06 | Au1rxx-base64 | 173.244.56.6 |
| 77.14 | shadowsocks | 264.1 | 642.0 | 21.66 | 0.0 | 10.0 | 13.37 | 16.5 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.13 | shadowsocks | 263.5 | 639.5 | 21.68 | 0.0 | 10.0 | 13.37 | 17.06 | Au1rxx-base64 | 156.146.38.167 |
| 77.11 | shadowsocks | 269.2 | 636.9 | 21.55 | 0.0 | 10.0 | 13.37 | 17.06 | Au1rxx-base64 | 156.146.38.170 |
| 76.6 | http | 231.4 | 576.3 | 22.42 | 0.0 | 10.0 | 12.58 | 16.6 | ermaozi | 138.199.35.207 |
| 76.09 | vless | 197.0 | 515.8 | 23.22 | 0.0 | 10.0 | 5.81 | 17.06 | Au1rxx-base64 | 172.235.43.210 |
| 75.98 | vless | 201.4 | 524.8 | 23.11 | 0.0 | 10.0 | 5.81 | 17.06 | Au1rxx-base64 | 172.233.139.46 |
| 75.77 | vless | 210.7 | 533.1 | 22.9 | 0.0 | 10.0 | 5.81 | 17.06 | Au1rxx-base64 | 195.123.240.65 |
| 75.51 | vless | 191.5 | 503.9 | 23.35 | 0.0 | 10.0 | 5.81 | 17.06 | Au1rxx-base64 | 192.3.247.109 |
| 75.46 | vless | 200.0 | 520.4 | 23.15 | 0.0 | 10.0 | 5.81 | 16.5 | Surfboard-tg-mixed | 172.235.38.85 |
| 75.37 | shadowsocks | 301.5 | 739.0 | 20.8 | 0.0 | 10.0 | 13.37 | 16.5 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.34 | http | 199.6 | 497.8 | 23.16 | 0.0 | 10.0 | 12.58 | 16.6 | ermaozi | 107.167.18.122 |
| 75.12 | trojan | 203.9 | 517.9 | 23.06 | 0.0 | 10.0 | 7.5 | 17.06 | Au1rxx-base64 | 192.236.151.43 |
| 74.83 | vless | 251.4 | 609.6 | 21.96 | 0.0 | 10.0 | 5.81 | 17.06 | Au1rxx-base64 | 137.175.82.40 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.872 | 0.804 | 46 | 22755 | prefer |
| Au1rxx-base64 | 0.855 | 0.786 | 281 | 1752 | prefer |
| ermaozi | 0.817 | 0.815 | 54 | 335 | prefer |
| Surfboard-tg-mixed | 0.622 | 0.542 | 118 | 6952 | observe |
| DeltaKronecker-all | 0.592 | 0.512 | 162 | 5434 | observe |
| tg-oneclickvpnkeys | 0.361 | 1.0 | 3 | 68 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 353 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7458 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9148 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5632 | observe |
| barry-far-vless | 0.255 | None | 0 | 5879 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 74 |
| 204 | TimeoutError | - | 34 |
| 204 | ProxyError | - | 21 |
| speed | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 21 |
| geo | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 15 |
| geo | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
