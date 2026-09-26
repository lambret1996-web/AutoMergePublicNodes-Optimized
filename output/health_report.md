# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 04:58:56 |
| 运行耗时 | 1085.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96648 |
| 去重后节点 | 26495 |
| TCP 可达 | 3000 |
| 真实可用 | 516 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26495 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 43.4 |
| probe | 355.5 |
| real_test | 524.6 |
| generate | 154.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58916 |
| vmess | 15125 |
| shadowsocks | 11186 |
| trojan | 8917 |
| hysteria2 | 1536 |
| http | 638 |
| shadowsocksr | 168 |
| socks | 101 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 14 |

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
| 82.24 | vless | 220.0 | 597.3 | 22.69 | 0.0 | 8.54 | 11.67 | 19.34 | Au1rxx-base64 | 195.211.98.43 |
| 81.4 | vless | 257.6 | 646.2 | 21.82 | 0.0 | 8.57 | 11.67 | 19.34 | Au1rxx-base64 | 198.251.78.29 |
| 81.17 | vless | 267.3 | 703.0 | 21.59 | 0.0 | 8.57 | 11.67 | 19.34 | Au1rxx-base64 | 79.141.172.154 |
| 80.56 | shadowsocks | 254.0 | 631.2 | 21.9 | 0.0 | 10.0 | 13.32 | 19.34 | Au1rxx-base64 | 156.146.38.169 |
| 79.27 | shadowsocks | 252.4 | 629.1 | 21.93 | 0.0 | 10.0 | 13.32 | 18.02 | mheidari-all | 156.146.38.170 |
| 79.23 | vless | 311.3 | 761.9 | 20.57 | 0.0 | 8.74 | 11.67 | 19.34 | Au1rxx-base64 | 195.123.235.177 |
| 79.22 | shadowsocks | 254.9 | 635.8 | 21.88 | 0.0 | 10.0 | 13.32 | 18.02 | mheidari-all | 156.146.38.168 |
| 79.0 | vless | 319.7 | 792.0 | 20.38 | 0.0 | 8.6 | 11.67 | 19.34 | Au1rxx-base64 | 169.40.42.35 |
| 78.99 | vless | 362.6 | 924.6 | 19.38 | 0.0 | 8.6 | 11.67 | 19.34 | Au1rxx-base64 | 169.40.42.15 |
| 78.58 | shadowsocks | 279.9 | 722.3 | 21.3 | 0.0 | 8.62 | 13.32 | 19.34 | Au1rxx-base64 | 37.19.198.243 |
| 78.29 | vless | 306.9 | 771.7 | 20.67 | 0.0 | 8.61 | 11.67 | 19.34 | Au1rxx-base64 | 38.77.133.202 |
| 78.1 | vless | 317.4 | 704.4 | 20.43 | 0.0 | 8.64 | 11.67 | 19.34 | Au1rxx-base64 | 169.40.42.16 |
| 78.1 | vless | 393.6 | 906.1 | 18.67 | 0.0 | 8.64 | 11.67 | 19.34 | Au1rxx-base64 | 169.40.42.173 |
| 78.08 | vless | 367.7 | 951.9 | 19.27 | 0.0 | 8.64 | 11.67 | 19.34 | Au1rxx-base64 | 185.95.231.233 |
| 77.86 | shadowsocks | 270.3 | 643.7 | 21.52 | 0.0 | 10.0 | 13.32 | 18.02 | mheidari-all | 23.150.248.20 |
| 77.7 | vless | 332.2 | 784.8 | 20.09 | 0.0 | 8.57 | 11.67 | 19.34 | Au1rxx-base64 | 169.40.42.235 |
| 77.68 | vless | 384.9 | 965.9 | 18.87 | 0.0 | 8.6 | 11.67 | 19.34 | Au1rxx-base64 | 130.107.73.148 |
| 77.34 | vless | 300.2 | 764.8 | 20.83 | 0.0 | 10.0 | 11.67 | 19.34 | Au1rxx-base64 | 162.35.96.15 |
| 77.21 | vless | 334.7 | 785.9 | 20.03 | 0.0 | 8.66 | 11.67 | 19.34 | Au1rxx-base64 | 66.70.179.198 |
| 77.18 | vless | 285.4 | 723.5 | 21.17 | 0.0 | 10.0 | 11.67 | 19.34 | Au1rxx-base64 | 47.253.226.114 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.901 | 0.838 | 272 | 1634 | prefer |
| Surfboard-tg-mixed | 0.866 | 0.794 | 68 | 7217 | prefer |
| mheidari-all | 0.425 | 0.345 | 632 | 22526 | observe |
| ermaozi | 0.357 | 0.333 | 33 | 352 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| ermaozi-get_subscribe | 0.267 | 0.286 | 14 | 375 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7682 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8923 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5837 | observe |
| barry-far-vless | 0.255 | None | 0 | 6063 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4304 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1634 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 202 |
| speed | TimeoutError | - | 90 |
| cn-block | ClientOSError | - | 57 |
| geo | ClientOSError | - | 48 |
| 204 | ProxyError | - | 45 |
| 204 | TimeoutError | - | 22 |
| speed | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 21 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
