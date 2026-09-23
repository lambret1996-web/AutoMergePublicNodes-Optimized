# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 00:38:50 |
| 运行耗时 | 1019.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 88330 |
| 去重后节点 | 25503 |
| TCP 可达 | 3000 |
| 真实可用 | 564 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25503 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.4 |
| tcp | 43.3 |
| probe | 354.4 |
| real_test | 585.6 |
| generate | 27.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52691 |
| vmess | 14474 |
| shadowsocks | 10544 |
| trojan | 8383 |
| hysteria2 | 1384 |
| http | 584 |
| shadowsocksr | 156 |
| socks | 83 |
| hysteria | 14 |
| anytls | 11 |
| tuic | 6 |

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
| 81.61 | hysteria2 | 257.9 | 706.5 | 21.81 | 0.0 | 10.0 | 13.5 | 17.4 | Au1rxx-base64 | 159.223.157.129 |
| 79.42 | shadowsocks | 225.9 | 596.0 | 22.55 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 198.98.53.130 |
| 78.56 | shadowsocks | 263.1 | 713.9 | 21.69 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 37.19.198.160 |
| 78.46 | shadowsocks | 267.3 | 723.4 | 21.59 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 37.19.198.244 |
| 77.95 | shadowsocks | 289.5 | 796.3 | 21.08 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 37.19.198.243 |
| 77.86 | vless | 247.1 | 700.2 | 22.06 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 79.141.172.154 |
| 76.91 | vless | 288.1 | 681.6 | 21.11 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.15 |
| 76.51 | vless | 305.1 | 681.8 | 20.71 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.163 |
| 76.4 | shadowsocks | 334.9 | 901.5 | 20.03 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 38.180.135.156 |
| 76.26 | vless | 316.1 | 773.7 | 20.46 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 66.70.179.198 |
| 76.18 | vless | 319.5 | 857.7 | 20.38 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 137.184.218.169 |
| 76.03 | vless | 326.2 | 858.0 | 20.23 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.133 |
| 75.81 | vless | 321.0 | 849.9 | 20.35 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.89 |
| 75.62 | shadowsocks | 390.1 | 1060.1 | 18.75 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 142.4.216.225 |
| 75.61 | vless | 344.2 | 855.0 | 19.81 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.104 |
| 75.58 | vless | 345.6 | 855.2 | 19.78 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.173 |
| 75.57 | shadowsocks | 370.6 | 969.3 | 19.2 | 0.0 | 10.0 | 13.47 | 17.4 | Au1rxx-base64 | 51.222.200.165 |
| 75.53 | vless | 347.8 | 982.6 | 19.73 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 34.85.179.6 |
| 75.18 | vless | 332.1 | 752.8 | 20.09 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 169.40.42.231 |
| 74.86 | vless | 309.2 | 751.3 | 20.62 | 0.0 | 10.0 | 8.4 | 17.4 | Au1rxx-base64 | 195.211.98.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.854 | 0.787 | 296 | 1717 | prefer |
| ermaozi | 0.755 | 0.759 | 29 | 325 | prefer |
| Surfboard-tg-mixed | 0.674 | 0.6 | 30 | 7168 | observe |
| mheidari-all | 0.538 | 0.458 | 142 | 16262 | observe |
| xiaoji235-airport-v2ray-all | 0.515 | 0.5 | 16 | 4242 | observe |
| DeltaKronecker-all | 0.424 | 0.343 | 615 | 6324 | observe |
| 10ium-ScrapeCategorize-Vless | 0.305 | 0.3 | 10 | 4915 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| Epodonios-all | 0.255 | None | 0 | 7638 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8904 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5836 | observe |
| barry-far-vless | 0.255 | None | 0 | 6057 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4252 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 282 |
| speed | ClientOSError | - | 112 |
| geo | ClientOSError | - | 84 |
| speed | TimeoutError | - | 49 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:38638: bind: address already in use | - | 1 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
