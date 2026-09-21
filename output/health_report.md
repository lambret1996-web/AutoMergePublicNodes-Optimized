# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 06:35:56 |
| 运行耗时 | 699.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84788 |
| 去重后节点 | 23352 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23352 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 39.0 |
| probe | 231.3 |
| real_test | 347.4 |
| generate | 76.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50830 |
| vmess | 13686 |
| shadowsocks | 9780 |
| trojan | 8469 |
| hysteria2 | 1139 |
| http | 639 |
| shadowsocksr | 149 |
| socks | 79 |
| hysteria | 8 |
| anytls | 5 |
| tuic | 4 |

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
| 81.81 | shadowsocks | 242.9 | 621.2 | 22.15 | 0.0 | 10.0 | 14.4 | 19.26 | Au1rxx-base64 | 156.146.38.168 |
| 80.1 | hysteria2 | 271.2 | 580.0 | 21.5 | 0.0 | 9.86 | 13.5 | 19.26 | Au1rxx-base64 | 66.94.121.46 |
| 79.46 | shadowsocks | 266.5 | 620.3 | 21.61 | 0.0 | 10.0 | 14.4 | 19.26 | Au1rxx-base64 | 23.150.248.20 |
| 78.16 | vless | 310.7 | 762.4 | 20.59 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 195.211.98.43 |
| 77.29 | vless | 312.2 | 699.7 | 20.55 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 216.152.147.28 |
| 76.74 | vless | 291.1 | 701.6 | 21.04 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 79.141.172.154 |
| 76.63 | vless | 325.7 | 766.0 | 20.24 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 47.253.226.114 |
| 76.3 | shadowsocks | 256.3 | 640.8 | 21.84 | 0.0 | 10.0 | 14.4 | 14.06 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.58 | vless | 301.6 | 651.5 | 20.8 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 195.123.235.177 |
| 75.48 | vless | 341.0 | 761.6 | 19.88 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 169.40.42.16 |
| 75.23 | shadowsocks | 417.1 | 1056.1 | 18.12 | 0.0 | 10.0 | 14.4 | 19.26 | Au1rxx-base64 | 15.204.247.206 |
| 74.59 | vless | 318.3 | 688.5 | 20.41 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 138.124.60.146 |
| 74.3 | shadowsocks | 432.6 | 1091.3 | 17.76 | 0.0 | 10.0 | 14.4 | 19.26 | Au1rxx-base64 | 15.204.246.132 |
| 74.01 | vless | 363.5 | 686.1 | 19.36 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 169.40.42.89 |
| 73.95 | vless | 320.4 | 673.5 | 20.36 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 169.40.42.90 |
| 73.9 | shadowsocks | 296.4 | 693.2 | 20.92 | 0.0 | 10.0 | 14.4 | 14.06 | Surfboard-tg-mixed | 37.19.198.243 |
| 73.86 | vless | 337.8 | 674.4 | 19.96 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 169.40.42.163 |
| 73.86 | vless | 347.5 | 685.6 | 19.73 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 169.40.42.15 |
| 73.6 | vless | 389.0 | 942.7 | 18.77 | 0.0 | 10.0 | 8.31 | 19.26 | Au1rxx-base64 | 169.40.42.223 |
| 73.47 | hysteria2 | 401.5 | 742.4 | 18.48 | 0.0 | 9.83 | 13.5 | 19.26 | Au1rxx-base64 | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.918 | 0.857 | 35 | 16285 | prefer |
| Au1rxx-base64 | 0.91 | 0.843 | 325 | 1727 | prefer |
| ermaozi | 0.697 | 0.692 | 39 | 355 | observe |
| Surfboard-tg-mixed | 0.664 | 0.585 | 301 | 7246 | observe |
| DeltaKronecker-all | 0.448 | 0.367 | 150 | 6092 | observe |
| tg-oneclickvpnkeys | 0.404 | 1.0 | 4 | 92 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7661 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9052 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5845 | observe |
| barry-far-vless | 0.255 | None | 0 | 6061 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1727 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 104 |
| geo | ClientOSError | - | 51 |
| speed | TimeoutError | - | 38 |
| 204 | TimeoutError | - | 33 |
| speed | ClientOSError | - | 23 |
| 204 | ProxyError | - | 19 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 12 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
