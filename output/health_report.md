# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 00:40:39 |
| 运行耗时 | 1066.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 92055 |
| 去重后节点 | 25204 |
| TCP 可达 | 3000 |
| 真实可用 | 597 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25204 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 3.0 |
| tcp | 42.1 |
| probe | 352.9 |
| real_test | 576.9 |
| generate | 84.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54381 |
| vmess | 14905 |
| shadowsocks | 11089 |
| trojan | 9222 |
| hysteria2 | 1566 |
| http | 627 |
| shadowsocksr | 140 |
| socks | 80 |
| anytls | 20 |
| hysteria | 17 |
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
| 82.33 | hysteria2 | 204.4 | 561.7 | 23.05 | 0.0 | 10.0 | 12.0 | 18.28 | Au1rxx-base64 | 66.94.121.46 |
| 81.01 | vless | 212.6 | 556.1 | 22.86 | 0.0 | 10.0 | 9.87 | 18.28 | Au1rxx-base64 | 15.204.97.216 |
| 78.27 | vless | 232.5 | 529.5 | 22.4 | 0.0 | 10.0 | 9.87 | 16.68 | mheidari-all | 47.251.108.158 |
| 77.91 | vless | 300.9 | 788.9 | 20.81 | 0.0 | 8.95 | 9.87 | 18.28 | Au1rxx-base64 | 34.19.91.203 |
| 75.22 | vless | 419.7 | 1117.3 | 18.06 | 0.0 | 9.01 | 9.87 | 18.28 | Au1rxx-base64 | 51.81.203.63 |
| 75.13 | vless | 259.8 | 560.9 | 21.76 | 0.0 | 9.02 | 9.87 | 18.28 | Au1rxx-base64 | 195.123.240.65 |
| 75.11 | vless | 258.0 | 563.8 | 21.81 | 0.0 | 10.0 | 9.87 | 16.68 | mheidari-all | 172.233.139.46 |
| 74.78 | shadowsocks | 280.5 | 601.3 | 21.28 | 0.0 | 10.0 | 13.97 | 16.68 | mheidari-all | 108.181.118.10 |
| 73.08 | vless | 273.8 | 604.1 | 21.44 | 0.0 | 8.95 | 9.87 | 18.28 | Au1rxx-base64 | 31.58.50.200 |
| 73.04 | hysteria2 | 344.3 | 741.8 | 19.81 | 0.0 | 10.0 | 12.0 | 16.68 | mheidari-all | 159.223.157.129 |
| 72.97 | vless | 261.3 | 568.3 | 21.73 | 0.0 | 8.95 | 9.87 | 18.28 | Au1rxx-base64 | 172.235.43.210 |
| 72.94 | vless | 284.1 | 663.5 | 21.2 | 0.0 | 8.59 | 9.87 | 18.28 | Au1rxx-base64 | usanbnode.jumpernode.online |
| 72.83 | shadowsocks | 317.4 | 663.9 | 20.43 | 0.0 | 10.0 | 13.97 | 16.68 | mheidari-all | 156.146.38.170 |
| 72.1 | vless | 354.3 | 693.6 | 19.58 | 0.0 | 9.08 | 9.87 | 18.28 | Au1rxx-base64 | 195.211.98.43 |
| 71.49 | vless | 357.5 | 688.5 | 19.5 | 0.0 | 9.01 | 9.87 | 18.28 | Au1rxx-base64 | 5.78.159.97 |
| 71.47 | shadowsocks | 352.8 | 740.4 | 19.61 | 0.0 | 10.0 | 13.97 | 16.68 | mheidari-all | 23.150.248.20 |
| 71.25 | vless | 349.4 | 383.4 | 19.69 | 0.62 | 10.0 | 9.87 | 18.28 | Au1rxx-base64 | 46.250.250.149 |
| 70.8 | vless | 385.3 | 759.4 | 18.86 | 0.0 | 9.0 | 9.87 | 18.28 | Au1rxx-base64 | 198.251.78.29 |
| 70.53 | vless | 280.6 | 420.3 | 21.28 | 0.0 | 10.0 | 9.87 | 16.68 | mheidari-all | 31.43.179.137 |
| 70.47 | vless | 350.1 | 424.2 | 19.67 | 0.0 | 10.0 | 9.87 | 18.28 | Au1rxx-base64 | 18.183.215.124 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | 0.819 | 271 | 1696 | prefer |
| Surfboard-tg-mixed | 0.866 | 0.793 | 82 | 7121 | prefer |
| ermaozi | 0.698 | 0.694 | 36 | 350 | observe |
| mheidari-all | 0.518 | 0.437 | 407 | 20197 | observe |
| DeltaKronecker-all | 0.315 | 0.234 | 440 | 6181 | observe |
| 10ium-ScrapeCategorize-Vless | 0.272 | 0.286 | 7 | 5290 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 377 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7569 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8704 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5672 | observe |
| barry-far-vless | 0.255 | None | 0 | 5885 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1697 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 234 |
| geo | ClientOSError | - | 127 |
| speed | ClientOSError | - | 97 |
| speed | TimeoutError | - | 75 |
| cn-block | ClientOSError | - | 59 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
