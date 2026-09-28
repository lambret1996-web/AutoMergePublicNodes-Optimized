# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 13:46:01 |
| 运行耗时 | 561.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96149 |
| 去重后节点 | 26790 |
| TCP 可达 | 3000 |
| 真实可用 | 455 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26790 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 44.9 |
| probe | 218.3 |
| real_test | 197.1 |
| generate | 92.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58658 |
| vmess | 14816 |
| shadowsocks | 11428 |
| trojan | 8867 |
| hysteria2 | 1473 |
| http | 617 |
| shadowsocksr | 169 |
| socks | 74 |
| anytls | 24 |
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
| 81.53 | shadowsocks | 253.4 | 705.5 | 21.91 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.89 | shadowsocks | 324.4 | 915.8 | 20.27 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 78.55 | shadowsocks | 360.5 | 996.2 | 19.43 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 15.204.233.41 |
| 78.36 | hysteria2 | 295.8 | 601.1 | 20.93 | 0.0 | 8.72 | 13.85 | 20.0 | Au1rxx-base64 | 192.255.128.123 |
| 77.71 | shadowsocks | 284.0 | 660.7 | 21.2 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 76.78 | shadowsocks | 282.9 | 646.7 | 21.23 | 0.0 | 8.85 | 13.62 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 75.96 | hysteria2 | 390.7 | 741.6 | 18.73 | 0.0 | 9.97 | 13.85 | 20.0 | Au1rxx-base64 | 217.60.33.215 |
| 75.91 | shadowsocks | 338.7 | 978.1 | 19.94 | 0.0 | 8.85 | 13.62 | 20.0 | Au1rxx-base64 | 15.204.247.206 |
| 75.36 | hysteria2 | 375.4 | 760.0 | 19.09 | 0.0 | 10.0 | 13.85 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 75.35 | vless | 246.5 | 692.3 | 22.07 | 0.0 | 10.0 | 4.28 | 20.0 | Au1rxx-base64 | 47.90.153.88 |
| 75.34 | vless | 238.9 | 681.0 | 22.25 | 0.0 | 8.81 | 4.28 | 20.0 | Au1rxx-base64 | 79.141.172.154 |
| 75.24 | shadowsocks | 256.9 | 712.9 | 21.83 | 0.0 | 8.79 | 13.62 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 74.59 | shadowsocks | 413.8 | 1170.9 | 18.2 | 0.0 | 8.77 | 13.62 | 20.0 | Au1rxx-base64 | 198.98.53.130 |
| 74.16 | vless | 290.1 | 736.6 | 21.06 | 0.0 | 8.82 | 4.28 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 73.99 | vless | 348.6 | 971.0 | 19.71 | 0.0 | 10.0 | 4.28 | 20.0 | Au1rxx-base64 | 159.89.87.21 |
| 73.91 | shadowsocks | 550.2 | 1465.3 | 15.04 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 15.235.75.71 |
| 73.42 | shadowsocks | 338.0 | 758.2 | 19.95 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 73.36 | shadowsocks | 309.1 | 781.7 | 20.62 | 0.0 | 8.76 | 13.62 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 73.34 | vless | 323.6 | 821.6 | 20.29 | 0.0 | 8.77 | 4.28 | 20.0 | Au1rxx-base64 | 195.211.98.43 |
| 73.23 | vless | 328.5 | 834.4 | 20.17 | 0.0 | 8.78 | 4.28 | 20.0 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.957 | 0.891 | 55 | 22474 | prefer |
| Au1rxx-base64 | 0.877 | 0.812 | 313 | 1677 | prefer |
| Surfboard-tg-mixed | 0.839 | 0.763 | 139 | 7046 | prefer |
| ermaozi | 0.693 | 0.686 | 51 | 344 | observe |
| DeltaKronecker-all | 0.53 | 0.7 | 10 | 5428 | observe |
| tg-oneclickvpnkeys | 0.315 | 1.0 | 2 | 94 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7414 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9420 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5638 | observe |
| barry-far-vless | 0.255 | None | 0 | 5752 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| 204 | ProxyError | - | 20 |
| 204 | TimeoutError | - | 20 |
| speed | ClientOSError | - | 19 |
| geo | TimeoutError | - | 14 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
