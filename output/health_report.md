# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-05 04:50:23 |
| 运行耗时 | 875.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98824 |
| 去重后节点 | 27506 |
| TCP 可达 | 3000 |
| 真实可用 | 539 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27506 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.7 |
| probe | 296.7 |
| real_test | 447.6 |
| generate | 74.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59300 |
| vmess | 15515 |
| shadowsocks | 11405 |
| trojan | 10312 |
| hysteria2 | 1365 |
| http | 623 |
| shadowsocksr | 170 |
| socks | 68 |
| anytls | 30 |
| tuic | 19 |
| hysteria | 17 |

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
| 82.92 | vless | 273.9 | 733.9 | 21.44 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.212 |
| 82.66 | vless | 284.9 | 720.8 | 21.18 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 66.70.179.198 |
| 82.65 | vless | 285.5 | 714.8 | 21.17 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.104 |
| 82.35 | vless | 298.5 | 827.7 | 20.87 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 159.89.87.21 |
| 82.06 | hysteria2 | 258.5 | 669.0 | 21.79 | 0.0 | 10.0 | 13.33 | 19.44 | Au1rxx-base64 | 129.213.91.185 |
| 81.33 | vless | 342.6 | 885.6 | 19.85 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 137.184.218.169 |
| 81.08 | vless | 278.6 | 682.9 | 21.33 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.173 |
| 80.96 | vless | 358.6 | 976.9 | 19.48 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.89 |
| 80.87 | vless | 362.2 | 951.6 | 19.39 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 2.24.124.64 |
| 80.57 | vless | 286.5 | 701.6 | 21.15 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.232 |
| 80.56 | vless | 246.2 | 692.6 | 22.08 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 47.253.226.114 |
| 79.63 | hysteria2 | 318.9 | 837.3 | 20.4 | 0.0 | 10.0 | 13.33 | 17.0 | mheidari-all | 159.223.157.129 |
| 79.05 | vless | 225.0 | 589.0 | 22.57 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 172.86.105.222 |
| 79.05 | vless | 225.2 | 598.8 | 22.57 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 195.123.235.177 |
| 79.0 | vless | 226.9 | 595.1 | 22.52 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 172.86.111.135 |
| 78.76 | vless | 373.0 | 901.0 | 19.14 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.231 |
| 78.54 | vless | 353.4 | 989.8 | 19.6 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 185.95.231.156 |
| 78.0 | vless | 343.4 | 867.0 | 19.83 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.163 |
| 77.98 | vless | 299.0 | 801.1 | 20.86 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.35 |
| 77.92 | vless | 347.0 | 873.5 | 19.74 | 0.0 | 10.0 | 12.04 | 19.44 | Au1rxx-base64 | 169.40.42.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.892 | 371 | 1883 | prefer |
| Surfboard-tg-mixed | 0.858 | 0.8 | 25 | 7178 | prefer |
| ermaozi | 0.497 | 0.468 | 62 | 694 | observe |
| mheidari-all | 0.417 | 0.336 | 461 | 23195 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7673 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9258 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5736 | observe |
| barry-far-vless | 0.255 | None | 0 | 6057 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4365 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.25 | None | 0 | 1883 | observe |
| DeltaKronecker-all | 0.249 | 0.2 | 10 | 5267 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 160 |
| speed | TimeoutError | - | 78 |
| 204 | ProxyError | - | 54 |
| geo | ClientOSError | - | 37 |
| cn-block | TimeoutError | - | 18 |
| 204 | ProxyConnectionError | - | 16 |
| speed | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
