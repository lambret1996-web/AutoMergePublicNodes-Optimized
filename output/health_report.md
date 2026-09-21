# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 12:29:23 |
| 运行耗时 | 516.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84518 |
| 去重后节点 | 23404 |
| TCP 可达 | 3000 |
| 真实可用 | 501 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23404 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 38.7 |
| probe | 180.9 |
| real_test | 215.7 |
| generate | 75.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51058 |
| vmess | 13400 |
| shadowsocks | 9659 |
| trojan | 8406 |
| hysteria2 | 1117 |
| http | 638 |
| shadowsocksr | 146 |
| socks | 77 |
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
| 82.34 | hysteria2 | 296.6 | 732.6 | 20.91 | 0.0 | 10.0 | 14.17 | 18.36 | mheidari-all | 159.223.157.129 |
| 79.56 | shadowsocks | 253.4 | 598.8 | 21.91 | 0.0 | 10.0 | 13.95 | 18.2 | Au1rxx-base64 | 23.150.248.20 |
| 77.94 | vless | 271.8 | 656.9 | 21.49 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 195.211.98.43 |
| 77.4 | vless | 294.8 | 715.7 | 20.95 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 79.141.172.154 |
| 76.42 | shadowsocks | 314.0 | 748.3 | 20.51 | 0.0 | 10.0 | 13.95 | 18.36 | mheidari-all | 37.19.198.236 |
| 75.82 | shadowsocks | 317.9 | 760.9 | 20.42 | 0.0 | 10.0 | 13.95 | 18.36 | mheidari-all | 37.19.198.244 |
| 74.6 | shadowsocks | 320.8 | 685.2 | 20.35 | 0.0 | 10.0 | 13.95 | 18.36 | mheidari-all | 149.22.95.183 |
| 74.32 | shadowsocks | 371.4 | 879.8 | 19.18 | 0.0 | 10.0 | 13.95 | 18.2 | Au1rxx-base64 | 142.4.216.225 |
| 72.68 | shadowsocks | 316.5 | 753.9 | 20.45 | 0.0 | 10.0 | 13.95 | 18.36 | mheidari-all | 37.19.198.160 |
| 72.38 | shadowsocks | 317.2 | 762.5 | 20.43 | 0.0 | 10.0 | 13.95 | 13.28 | Surfboard-tg-mixed | 37.19.198.243 |
| 72.23 | hysteria2 | 385.2 | 667.9 | 18.86 | 0.0 | 9.13 | 14.17 | 18.2 | Au1rxx-base64 | 66.94.121.46 |
| 71.98 | shadowsocks | 364.7 | 959.3 | 19.33 | 0.0 | 10.0 | 13.95 | 18.2 | Au1rxx-base64 | 185.156.47.97 |
| 71.79 | shadowsocks | 258.4 | 647.3 | 21.8 | 0.0 | 10.0 | 13.95 | 18.36 | mheidari-all | 156.146.38.168 |
| 71.69 | hysteria2 | 460.4 | 899.4 | 17.12 | 0.0 | 9.84 | 14.17 | 18.2 | Au1rxx-base64 | 62.210.124.146 |
| 71.5 | vless | 340.3 | 768.6 | 19.9 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 162.159.48.32 |
| 71.18 | vless | 330.5 | 638.6 | 20.13 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 15.204.97.216 |
| 70.99 | vless | 426.7 | 1037.3 | 17.9 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 169.40.42.212 |
| 70.98 | vless | 467.3 | 1075.7 | 16.96 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 169.40.42.16 |
| 70.97 | vless | 379.1 | 918.6 | 19.0 | 0.0 | 10.0 | 8.25 | 18.2 | Au1rxx-base64 | 169.40.42.224 |
| 70.95 | hysteria2 | 432.4 | 769.4 | 17.77 | 0.0 | 9.72 | 14.17 | 18.2 | Au1rxx-base64 | 45.192.12.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | 0.88 | 275 | 1649 | prefer |
| DeltaKronecker-all | 0.88 | 0.814 | 43 | 6181 | prefer |
| mheidari-all | 0.818 | 0.744 | 78 | 16192 | prefer |
| ermaozi | 0.746 | 0.744 | 39 | 355 | prefer |
| Surfboard-tg-mixed | 0.705 | 0.626 | 214 | 7246 | prefer |
| tg-oneclickvpnkeys | 0.273 | 0.667 | 3 | 108 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5290 | observe |
| Epodonios-all | 0.255 | None | 0 | 7697 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8900 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5845 | observe |
| barry-far-vless | 0.255 | None | 0 | 6062 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 32 |
| geo | TimeoutError | - | 23 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 15 |
| speed | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 13 |
| speed | TimeoutError | - | 12 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
