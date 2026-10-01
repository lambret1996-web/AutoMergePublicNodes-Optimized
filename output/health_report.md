# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 18:18:14 |
| 运行耗时 | 490.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98761 |
| 去重后节点 | 27523 |
| TCP 可达 | 3000 |
| 真实可用 | 179 |
| Verified 输出 | 179 |
| Global 输出 | 186 |
| All 输出 | 27523 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 45.2 |
| probe | 229.7 |
| real_test | 111.8 |
| generate | 94.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 61002 |
| vmess | 15429 |
| shadowsocks | 11419 |
| trojan | 8888 |
| hysteria2 | 1313 |
| http | 399 |
| shadowsocksr | 171 |
| socks | 63 |
| anytls | 53 |
| hysteria | 16 |
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
| 83.17 | hysteria2 | 251.5 | 654.9 | 21.96 | 0.0 | 10.0 | 14.29 | 18.02 | mheidari-all | 159.223.157.129 |
| 77.7 | shadowsocks | 256.3 | 710.3 | 21.84 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 37.19.198.243 |
| 76.9 | shadowsocks | 256.4 | 705.1 | 21.84 | 0.0 | 10.0 | 12.86 | 16.2 | Surfboard-tg-mixed | 37.19.198.244 |
| 76.53 | hysteria2 | 303.2 | 586.7 | 20.76 | 0.0 | 10.0 | 14.29 | 17.0 | Au1rxx-base64 | 192.255.128.123 |
| 76.5 | vless | 293.5 | 647.1 | 20.98 | 0.0 | 10.0 | 10.29 | 18.02 | mheidari-all | 216.227.161.95 |
| 76.47 | shadowsocks | 275.1 | 759.3 | 21.41 | 0.0 | 10.0 | 12.86 | 16.2 | Surfboard-tg-mixed | 198.98.53.130 |
| 75.73 | shadowsocks | 311.6 | 810.7 | 20.56 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 103.214.111.162 |
| 75.3 | shadowsocks | 255.2 | 709.9 | 21.87 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 37.19.198.160 |
| 74.74 | shadowsocks | 279.3 | 764.8 | 21.31 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 140.82.63.79 |
| 74.71 | shadowsocks | 256.0 | 714.5 | 21.85 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 37.19.198.236 |
| 74.7 | shadowsocks | 289.0 | 663.4 | 21.09 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 156.146.38.168 |
| 74.64 | shadowsocks | 292.7 | 662.2 | 21.0 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 156.146.38.170 |
| 74.58 | shadowsocks | 291.1 | 660.8 | 21.04 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 156.146.38.169 |
| 74.08 | hysteria2 | 366.8 | 1057.5 | 19.29 | 0.0 | 10.0 | 14.29 | 17.0 | Au1rxx-base64 | 129.213.91.185 |
| 73.5 | hysteria2 | 410.1 | 751.2 | 18.28 | 0.0 | 9.97 | 14.29 | 18.02 | mheidari-all | 217.60.33.215 |
| 72.62 | hysteria2 | 455.1 | 904.5 | 17.24 | 0.0 | 9.95 | 14.29 | 18.02 | mheidari-all | 91.196.32.163 |
| 72.37 | shadowsocks | 465.4 | 1006.1 | 17.01 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 15.204.246.132 |
| 72.32 | shadowsocks | 314.5 | 708.1 | 20.5 | 0.0 | 10.0 | 12.86 | 17.0 | Au1rxx-base64 | 108.181.57.93 |
| 72.06 | hysteria2 | 470.7 | 702.0 | 16.88 | 0.0 | 10.0 | 14.29 | 18.02 | mheidari-all | 45.192.12.93 |
| 71.34 | hysteria2 | 447.6 | 950.8 | 17.42 | 0.0 | 10.0 | 14.29 | 16.2 | Surfboard-tg-mixed | 130.49.161.70 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.937 | 95 | 1825 | prefer |
| Surfboard-tg-mixed | 0.886 | 0.828 | 29 | 7228 | prefer |
| zhangkai | 0.788 | 0.81 | 21 | 144 | prefer |
| mheidari-all | 0.7 | 0.623 | 77 | 23055 | prefer |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 5603 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7640 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9977 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5857 | observe |
| barry-far-vless | 0.255 | None | 0 | 6032 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4241 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1825 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| speed | TimeoutError | - | 3 |
| geo | TimeoutError | - | 3 |
| speed | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 30 | 179 | - |
| global | False | 30 | 186 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
