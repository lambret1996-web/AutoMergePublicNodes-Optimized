# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 00:41:23 |
| 运行耗时 | 1121.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89626 |
| 去重后节点 | 24571 |
| TCP 可达 | 3000 |
| 真实可用 | 591 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24571 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.4 |
| tcp | 41.6 |
| probe | 394.9 |
| real_test | 611.5 |
| generate | 68.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53171 |
| vmess | 14184 |
| shadowsocks | 11003 |
| trojan | 8964 |
| hysteria2 | 1499 |
| http | 592 |
| shadowsocksr | 127 |
| socks | 74 |
| hysteria | 8 |
| tuic | 2 |
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
| 80.97 | vless | 284.3 | 659.5 | 21.2 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 198.251.78.29 |
| 80.57 | shadowsocks | 258.9 | 632.5 | 21.78 | 0.0 | 10.0 | 13.85 | 18.94 | Au1rxx-base64 | 156.146.38.168 |
| 80.27 | shadowsocks | 246.5 | 613.4 | 22.07 | 0.0 | 10.0 | 13.85 | 18.94 | Au1rxx-base64 | 156.146.38.170 |
| 78.75 | hysteria2 | 289.6 | 579.8 | 21.07 | 0.0 | 10.0 | 13.04 | 18.94 | Au1rxx-base64 | 66.94.121.46 |
| 78.49 | vless | 314.2 | 744.4 | 20.5 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 47.253.226.114 |
| 78.46 | hysteria2 | 260.0 | 540.7 | 21.76 | 0.0 | 10.0 | 13.04 | 19.56 | mheidari-all | 45.149.172.80 |
| 78.46 | shadowsocks | 273.0 | 628.4 | 21.46 | 0.0 | 10.0 | 13.85 | 18.94 | Au1rxx-base64 | 23.150.248.20 |
| 77.92 | vless | 232.8 | 588.5 | 22.39 | 0.0 | 10.0 | 10.97 | 19.56 | mheidari-all | 88.216.57.128 |
| 77.41 | vless | 303.3 | 710.9 | 20.76 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 216.152.147.28 |
| 77.4 | shadowsocks | 294.1 | 685.1 | 20.97 | 0.0 | 10.0 | 13.85 | 18.94 | Au1rxx-base64 | 37.19.198.236 |
| 77.07 | hysteria2 | 255.9 | 526.4 | 21.85 | 0.0 | 10.0 | 13.04 | 19.56 | mheidari-all | 45.149.172.74 |
| 76.67 | vless | 324.6 | 736.8 | 20.26 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 137.184.218.169 |
| 76.46 | vless | 316.2 | 684.4 | 20.46 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 195.123.235.177 |
| 76.29 | shadowsocks | 292.9 | 642.5 | 21.0 | 0.0 | 10.0 | 13.85 | 18.94 | Au1rxx-base64 | 5.78.51.123 |
| 76.23 | vless | 334.6 | 701.8 | 20.03 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 169.40.42.133 |
| 76.12 | vless | 296.3 | 590.8 | 20.92 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 172.235.43.210 |
| 76.02 | vless | 353.6 | 813.0 | 19.59 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 169.40.42.89 |
| 76.0 | hysteria2 | 250.0 | 586.0 | 21.99 | 0.0 | 10.0 | 13.04 | 18.94 | Au1rxx-base64 | 108.59.244.158 |
| 75.94 | vless | 299.5 | 549.9 | 20.84 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 144.172.104.26 |
| 75.94 | vless | 339.2 | 667.9 | 19.93 | 0.0 | 10.0 | 10.97 | 18.94 | Au1rxx-base64 | 198.200.42.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | 0.928 | 293 | 1705 | prefer |
| Surfboard-tg-mixed | 0.763 | 0.687 | 99 | 7464 | prefer |
| ermaozi | 0.558 | 0.818 | 11 | 353 | observe |
| mheidari-all | 0.49 | 0.409 | 181 | 18096 | observe |
| DeltaKronecker-all | 0.42 | 0.34 | 480 | 6081 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4234 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 140 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7947 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9078 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5964 | observe |
| barry-far-vless | 0.255 | None | 0 | 6148 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 2484 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1705 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 245 |
| geo | ClientOSError | - | 80 |
| speed | TimeoutError | - | 65 |
| speed | ClientOSError | - | 48 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 10 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
