# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 06:34:45 |
| 运行耗时 | 793.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83435 |
| 去重后节点 | 22871 |
| TCP 可达 | 3000 |
| 真实可用 | 445 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22871 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.5 |
| tcp | 39.5 |
| probe | 295.5 |
| real_test | 358.9 |
| generate | 89.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50653 |
| vmess | 12534 |
| shadowsocks | 9758 |
| trojan | 8012 |
| hysteria2 | 1622 |
| http | 649 |
| shadowsocksr | 128 |
| socks | 57 |
| tuic | 12 |
| hysteria | 8 |
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
| 82.48 | hysteria2 | 266.0 | 670.4 | 21.62 | 0.0 | 10.0 | 12.86 | 19.1 | Au1rxx-base64 | 159.223.157.129 |
| 81.76 | shadowsocks | 245.1 | 613.7 | 22.1 | 0.0 | 10.0 | 14.56 | 19.1 | Au1rxx-base64 | 198.98.53.130 |
| 81.55 | shadowsocks | 254.4 | 621.0 | 21.89 | 0.0 | 10.0 | 14.56 | 19.1 | Au1rxx-base64 | 156.146.38.167 |
| 81.02 | shadowsocks | 277.4 | 707.4 | 21.36 | 0.0 | 10.0 | 14.56 | 19.1 | Au1rxx-base64 | 37.19.198.243 |
| 80.1 | shadowsocks | 317.1 | 826.5 | 20.44 | 0.0 | 10.0 | 14.56 | 19.1 | Au1rxx-base64 | 37.19.198.160 |
| 79.65 | vless | 280.7 | 671.3 | 21.28 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.75 |
| 79.42 | vless | 290.5 | 736.7 | 21.05 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 47.253.226.114 |
| 79.12 | vless | 272.4 | 632.7 | 21.47 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 195.123.235.177 |
| 79.04 | vless | 306.9 | 757.0 | 20.67 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.235 |
| 78.91 | vless | 312.6 | 730.2 | 20.54 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.225 |
| 78.64 | shadowsocks | 273.9 | 698.3 | 21.44 | 0.0 | 10.0 | 14.56 | 16.64 | Surfboard-tg-mixed | 37.19.198.244 |
| 78.49 | vless | 331.0 | 890.3 | 20.12 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 216.152.147.28 |
| 78.43 | vless | 295.4 | 714.5 | 20.94 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.229 |
| 78.35 | vless | 250.4 | 646.1 | 21.98 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 188.137.243.243 |
| 78.01 | shadowsocks | 385.9 | 986.9 | 18.85 | 0.0 | 10.0 | 14.56 | 19.1 | Au1rxx-base64 | 15.204.247.206 |
| 77.98 | vless | 336.2 | 841.9 | 19.99 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.202 |
| 77.82 | vless | 330.6 | 805.3 | 20.13 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 66.70.179.198 |
| 77.56 | vless | 371.2 | 884.8 | 19.19 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.173 |
| 77.28 | vless | 366.9 | 929.6 | 19.28 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.168 |
| 77.2 | vless | 369.4 | 887.1 | 19.23 | 0.0 | 10.0 | 9.27 | 19.1 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | 0.839 | 273 | 1703 | prefer |
| ermaozi | 0.817 | 0.814 | 43 | 431 | prefer |
| Surfboard-tg-mixed | 0.74 | 0.662 | 157 | 7301 | prefer |
| mheidari-all | 0.58 | 0.5 | 100 | 15749 | observe |
| DeltaKronecker-all | 0.376 | 0.291 | 79 | 5853 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4223 | observe |
| ermaozi-get_subscribe | 0.273 | 1.0 | 1 | 461 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 169 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7765 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8509 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6130 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 59 |
| geo | ClientOSError | - | 42 |
| speed | TimeoutError | - | 40 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | ClientOSError | - | 3 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
