# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 05:15:55 |
| 运行耗时 | 889.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 95804 |
| 去重后节点 | 26622 |
| TCP 可达 | 3000 |
| 真实可用 | 531 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26622 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.7 |
| tcp | 43.6 |
| probe | 305.6 |
| real_test | 458.0 |
| generate | 74.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58208 |
| vmess | 14891 |
| shadowsocks | 11298 |
| trojan | 9002 |
| hysteria2 | 1434 |
| http | 677 |
| shadowsocksr | 167 |
| socks | 79 |
| anytls | 26 |
| hysteria | 15 |
| tuic | 7 |

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
| 82.71 | vless | 262.6 | 657.0 | 21.7 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 198.251.78.29 |
| 82.64 | vless | 265.7 | 704.2 | 21.63 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 79.141.172.154 |
| 81.64 | vless | 308.7 | 779.1 | 20.63 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 38.77.133.202 |
| 80.66 | vless | 347.9 | 758.4 | 19.72 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.225 |
| 80.48 | vless | 301.6 | 724.9 | 20.8 | 0.0 | 9.56 | 11.77 | 19.24 | Au1rxx-base64 | 66.70.179.198 |
| 79.75 | vless | 390.2 | 1018.3 | 18.74 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 185.95.231.233 |
| 79.64 | vless | 385.2 | 936.8 | 18.86 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.223 |
| 79.41 | vless | 315.0 | 778.9 | 20.49 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.89 |
| 79.23 | shadowsocks | 318.5 | 822.6 | 20.4 | 0.0 | 10.0 | 13.59 | 19.24 | Au1rxx-base64 | 142.4.216.225 |
| 79.08 | vless | 419.5 | 960.5 | 18.07 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.95 |
| 79.0 | vless | 422.8 | 987.6 | 17.99 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.235 |
| 78.35 | shadowsocks | 335.2 | 928.7 | 20.02 | 0.0 | 10.0 | 13.59 | 19.24 | Au1rxx-base64 | 185.156.47.97 |
| 78.29 | vless | 382.2 | 941.1 | 18.93 | 0.0 | 9.59 | 11.77 | 19.24 | Au1rxx-base64 | 209.200.246.148 |
| 77.77 | shadowsocks | 324.3 | 898.1 | 20.27 | 0.0 | 9.17 | 13.59 | 19.24 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 77.42 | shadowsocks | 282.8 | 733.8 | 21.23 | 0.0 | 10.0 | 13.59 | 16.6 | mheidari-all | 37.19.198.160 |
| 77.41 | shadowsocks | 283.2 | 737.7 | 21.22 | 0.0 | 10.0 | 13.59 | 16.6 | mheidari-all | 37.19.198.244 |
| 77.11 | vless | 292.5 | 739.9 | 21.01 | 0.0 | 9.59 | 11.77 | 19.24 | Au1rxx-base64 | 162.35.96.15 |
| 76.99 | vless | 298.2 | 751.5 | 20.87 | 0.0 | 9.61 | 11.77 | 19.24 | Au1rxx-base64 | 162.35.96.18 |
| 76.99 | vless | 327.1 | 816.7 | 20.21 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.16 |
| 76.95 | vless | 432.3 | 1002.0 | 17.77 | 0.0 | 10.0 | 11.77 | 19.24 | Au1rxx-base64 | 169.40.42.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.937 | 0.878 | 279 | 1536 | prefer |
| Surfboard-tg-mixed | 0.792 | 0.715 | 130 | 7113 | prefer |
| ermaozi | 0.719 | 0.719 | 32 | 338 | prefer |
| mheidari-all | 0.406 | 0.325 | 504 | 22408 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 66 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7583 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8902 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5686 | observe |
| barry-far-vless | 0.255 | None | 0 | 5907 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1536 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 177 |
| speed | TimeoutError | - | 75 |
| geo | ClientOSError | - | 60 |
| speed | ClientOSError | - | 36 |
| 204 | TimeoutError | - | 22 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 15 |
| 204 | ProxyConnectionError | - | 8 |
| 204 | ClientOSError | - | 5 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
