# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 12:32:08 |
| 运行耗时 | 553.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84799 |
| 去重后节点 | 23007 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23007 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 38.0 |
| probe | 228.8 |
| real_test | 202.6 |
| generate | 75.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51960 |
| vmess | 12817 |
| shadowsocks | 9695 |
| trojan | 7960 |
| hysteria2 | 1522 |
| http | 638 |
| shadowsocksr | 126 |
| socks | 53 |
| tuic | 14 |
| hysteria | 11 |
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
| 81.32 | vless | 197.0 | 505.2 | 23.22 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 172.235.43.210 |
| 80.77 | shadowsocks | 198.5 | 526.1 | 23.18 | 0.0 | 10.0 | 13.41 | 18.68 | Au1rxx-base64 | 192.3.247.109 |
| 80.63 | vless | 226.9 | 514.1 | 22.53 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 150.241.102.181 |
| 80.16 | shadowsocks | 246.7 | 645.3 | 22.07 | 0.0 | 10.0 | 13.41 | 18.68 | Au1rxx-base64 | 173.244.56.9 |
| 79.71 | shadowsocks | 254.4 | 624.1 | 21.89 | 0.0 | 10.0 | 13.41 | 18.68 | Au1rxx-base64 | 156.146.38.168 |
| 79.03 | vless | 209.4 | 538.3 | 22.93 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 192.3.247.109 |
| 78.75 | shadowsocks | 286.0 | 735.7 | 21.16 | 0.0 | 10.0 | 13.41 | 18.68 | Au1rxx-base64 | 108.181.118.10 |
| 77.04 | vless | 209.9 | 511.0 | 22.92 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 45.149.172.80 |
| 76.41 | vless | 225.5 | 522.7 | 22.56 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 104.18.39.218 |
| 76.36 | vless | 343.2 | 811.7 | 19.83 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 15.204.97.216 |
| 76.12 | shadowsocks | 269.7 | 740.0 | 21.53 | 0.0 | 10.0 | 13.41 | 18.68 | Au1rxx-base64 | 129.146.118.11 |
| 75.61 | hysteria2 | 556.8 | 1563.4 | 14.89 | 0.0 | 10.0 | 13.04 | 18.68 | Au1rxx-base64 | 107.175.219.48 |
| 75.44 | vless | 234.8 | 605.0 | 22.34 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 38.244.20.41 |
| 75.4 | vless | 258.3 | 592.3 | 21.8 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 162.159.0.169 |
| 75.39 | vless | 333.6 | 752.6 | 20.06 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 79.141.172.154 |
| 75.32 | vless | 261.5 | 503.0 | 21.72 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 104.21.70.21 |
| 74.99 | shadowsocks | 286.1 | 686.8 | 21.16 | 0.0 | 10.0 | 13.41 | 15.36 | Surfboard-tg-mixed | 5.78.51.123 |
| 74.48 | shadowsocks | 210.1 | 485.9 | 22.91 | 0.0 | 10.0 | 13.41 | 12.66 | mheidari-all | 108.181.0.177 |
| 74.48 | vless | 297.8 | 440.5 | 20.88 | 0.0 | 10.0 | 9.42 | 18.68 | Au1rxx-base64 | 172.64.158.146 |
| 73.72 | shadowsocks | 264.9 | 638.2 | 21.65 | 0.0 | 10.0 | 13.41 | 12.66 | mheidari-all | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.946 | 0.882 | 288 | 1668 | prefer |
| Surfboard-tg-mixed | 0.793 | 0.717 | 113 | 7478 | prefer |
| mheidari-all | 0.789 | 0.717 | 53 | 15903 | prefer |
| ermaozi | 0.728 | 0.72 | 50 | 417 | prefer |
| ermaozi-get_subscribe | 0.579 | 0.611 | 18 | 444 | observe |
| DeltaKronecker-all | 0.57 | 0.489 | 47 | 5972 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9127 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6074 | observe |
| barry-far-vless | 0.255 | None | 0 | 6310 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 34 |
| 204 | ProxyError | - | 22 |
| speed | ClientOSError | - | 17 |
| cn-block | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| geo | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40774: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
