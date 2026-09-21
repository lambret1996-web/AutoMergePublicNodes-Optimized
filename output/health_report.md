# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 18:27:17 |
| 运行耗时 | 489.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85428 |
| 去重后节点 | 23571 |
| TCP 可达 | 3000 |
| 真实可用 | 417 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23571 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 38.5 |
| probe | 209.1 |
| real_test | 209.7 |
| generate | 23.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51790 |
| vmess | 13629 |
| shadowsocks | 9685 |
| trojan | 8402 |
| hysteria2 | 1063 |
| http | 632 |
| shadowsocksr | 131 |
| socks | 77 |
| hysteria | 11 |
| tuic | 4 |
| anytls | 4 |

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
| 81.95 | hysteria2 | 298.9 | 816.6 | 20.86 | 0.0 | 10.0 | 13.33 | 18.86 | Au1rxx-base64 | 159.223.157.129 |
| 81.02 | vless | 261.7 | 640.1 | 21.72 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 195.211.98.43 |
| 80.57 | vless | 281.0 | 700.5 | 21.27 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 66.70.179.198 |
| 80.35 | vless | 290.8 | 640.9 | 21.05 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.104 |
| 80.26 | vless | 294.3 | 780.0 | 20.96 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.90 |
| 80.16 | vless | 298.7 | 799.8 | 20.86 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.179 |
| 79.12 | vless | 343.7 | 932.1 | 19.82 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.202 |
| 79.02 | vless | 348.0 | 937.7 | 19.72 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.163 |
| 79.0 | vless | 349.0 | 838.0 | 19.7 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.212 |
| 78.85 | vless | 355.5 | 974.6 | 19.55 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.232 |
| 78.83 | vless | 356.3 | 969.3 | 19.53 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.173 |
| 78.63 | shadowsocks | 248.4 | 647.5 | 22.03 | 0.0 | 10.0 | 13.5 | 17.6 | DeltaKronecker-all | 38.180.135.156 |
| 78.61 | vless | 365.8 | 1056.4 | 19.31 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 34.85.179.6 |
| 78.59 | vless | 362.5 | 928.1 | 19.39 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 209.200.246.148 |
| 78.48 | vless | 371.3 | 931.7 | 19.18 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.35 |
| 78.28 | vless | 380.0 | 900.5 | 18.98 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 169.40.42.182 |
| 77.85 | vless | 344.5 | 814.4 | 19.8 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 198.251.78.29 |
| 77.85 | vless | 361.8 | 976.1 | 19.4 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 185.95.231.156 |
| 77.75 | shadowsocks | 254.3 | 703.8 | 21.89 | 0.0 | 10.0 | 13.5 | 16.36 | mheidari-all | 37.19.198.160 |
| 77.73 | vless | 263.3 | 655.8 | 21.68 | 0.0 | 10.0 | 10.44 | 18.86 | Au1rxx-base64 | 138.124.60.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | 0.846 | 273 | 1766 | prefer |
| mheidari-all | 0.834 | 0.764 | 55 | 16282 | prefer |
| DeltaKronecker-all | 0.637 | 0.558 | 208 | 6181 | observe |
| Surfboard-tg-mixed | 0.622 | 0.545 | 22 | 7273 | observe |
| ermaozi | 0.533 | 0.52 | 25 | 350 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 123 | observe |
| Epodonios-all | 0.255 | None | 0 | 7695 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9453 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5859 | observe |
| barry-far-vless | 0.255 | None | 0 | 6075 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 41 |
| geo | TimeoutError | - | 34 |
| 204 | ProxyError | - | 26 |
| geo | ClientOSError | - | 25 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| speed | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
