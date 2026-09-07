# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 13:42:46 |
| 运行耗时 | 326.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94662 |
| 去重后节点 | 24969 |
| TCP 可达 | 3000 |
| 真实可用 | 586 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24969 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 41.2 |
| probe | 88.0 |
| real_test | 143.9 |
| generate | 45.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59113 |
| vmess | 12785 |
| shadowsocks | 11103 |
| trojan | 9187 |
| hysteria2 | 2088 |
| http | 138 |
| shadowsocksr | 130 |
| socks | 61 |
| anytls | 22 |
| hysteria | 21 |
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
| 84.15 | hysteria2 | 244.2 | 661.5 | 22.13 | 0.0 | 9.16 | 14.42 | 19.54 | Au1rxx-base64 | 159.223.157.129 |
| 83.25 | vless | 249.9 | 633.4 | 21.99 | 0.0 | 9.25 | 12.47 | 19.54 | Au1rxx-base64 | 195.123.235.177 |
| 82.17 | vless | 329.2 | 833.4 | 20.16 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 66.70.179.198 |
| 81.91 | vless | 340.5 | 797.6 | 19.9 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 167.17.69.171 |
| 81.7 | vless | 349.4 | 944.3 | 19.69 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 185.95.231.156 |
| 81.47 | vless | 359.2 | 818.4 | 19.46 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.52 |
| 81.38 | vless | 363.1 | 884.6 | 19.37 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.231 |
| 80.88 | shadowsocks | 258.8 | 694.5 | 21.79 | 0.0 | 10.0 | 13.55 | 19.54 | Au1rxx-base64 | 37.19.198.244 |
| 80.65 | vless | 370.1 | 860.1 | 19.21 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.182 |
| 80.52 | vless | 393.2 | 1053.8 | 18.68 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.184 |
| 80.5 | vless | 289.2 | 619.8 | 21.08 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.35 |
| 80.27 | vless | 265.2 | 674.7 | 21.64 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.163 |
| 80.11 | vless | 321.9 | 780.0 | 20.33 | 0.0 | 9.09 | 12.47 | 19.54 | Au1rxx-base64 | 158.69.112.254 |
| 79.45 | vless | 390.4 | 1002.6 | 18.74 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.212 |
| 79.25 | vless | 428.1 | 1094.8 | 17.87 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.95 |
| 78.63 | vless | 352.0 | 879.8 | 19.63 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.202 |
| 78.61 | vless | 451.4 | 1107.6 | 17.33 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.104 |
| 78.34 | vless | 375.3 | 856.9 | 19.09 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.168 |
| 78.27 | vless | 445.4 | 708.7 | 17.47 | 0.0 | 10.0 | 12.47 | 19.54 | Au1rxx-base64 | 169.40.42.229 |
| 78.13 | hysteria2 | 294.6 | 588.5 | 20.96 | 0.0 | 8.95 | 14.42 | 19.54 | Au1rxx-base64 | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | 0.926 | 323 | 1785 | prefer |
| zhangkai | 0.886 | 0.913 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.86 | 0.784 | 171 | 7247 | prefer |
| mheidari-all | 0.618 | 0.538 | 234 | 21631 | observe |
| tg-oneclickvpnkeys | 0.364 | 1.0 | 3 | 151 | observe |
| 10ium-HighSpeed | 0.345 | 1.0 | 2 | 839 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5750 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6417 | observe |
| Epodonios-all | 0.255 | None | 0 | 7707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8440 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 45 |
| geo | ClientOSError | - | 36 |
| 204 | TimeoutError | - | 36 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 11 |
| geo | TimeoutError | - | 8 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyConnectionError | - | 2 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48510: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 30 | 300 | - |
| global | False | 30 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
