# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 00:40:37 |
| 运行耗时 | 971.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 89876 |
| 去重后节点 | 25286 |
| TCP 可达 | 3000 |
| 真实可用 | 612 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25286 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.5 |
| tcp | 42.1 |
| probe | 347.8 |
| real_test | 497.7 |
| generate | 75.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53384 |
| vmess | 14334 |
| shadowsocks | 11255 |
| trojan | 8831 |
| hysteria2 | 1277 |
| http | 576 |
| shadowsocksr | 127 |
| socks | 72 |
| hysteria | 10 |
| tuic | 5 |
| anytls | 5 |

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
| 82.01 | hysteria2 | 291.4 | 745.4 | 21.03 | 0.0 | 10.0 | 13.42 | 18.66 | Au1rxx-base64 | 159.223.157.129 |
| 80.76 | vless | 257.4 | 645.1 | 21.82 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 198.251.78.29 |
| 80.72 | vless | 259.3 | 687.8 | 21.78 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 79.141.172.154 |
| 79.04 | shadowsocks | 296.4 | 753.0 | 20.92 | 0.0 | 10.0 | 13.46 | 18.66 | Au1rxx-base64 | 156.146.38.168 |
| 79.03 | vless | 332.2 | 896.9 | 20.09 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 216.152.147.28 |
| 78.58 | vless | 310.0 | 706.5 | 20.6 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.90 |
| 78.46 | vless | 285.9 | 658.7 | 21.16 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 138.124.60.146 |
| 78.25 | vless | 293.1 | 609.6 | 20.99 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 195.123.235.177 |
| 78.16 | vless | 369.7 | 766.2 | 19.22 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.133 |
| 78.13 | vless | 332.8 | 819.5 | 20.07 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 66.70.179.198 |
| 77.9 | vless | 368.0 | 940.1 | 19.26 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.229 |
| 77.61 | shadowsocks | 336.5 | 929.8 | 19.99 | 0.0 | 10.0 | 13.46 | 18.66 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 77.53 | vless | 396.7 | 897.8 | 18.59 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.179 |
| 77.42 | vless | 328.1 | 746.1 | 20.18 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.95 |
| 76.74 | shadowsocks | 247.9 | 619.9 | 22.04 | 0.0 | 10.0 | 13.46 | 15.24 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.73 | vless | 406.2 | 1067.4 | 18.38 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 185.95.231.156 |
| 76.65 | vless | 304.3 | 680.0 | 20.73 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.223 |
| 76.62 | shadowsocks | 253.1 | 619.2 | 21.92 | 0.0 | 10.0 | 13.46 | 15.24 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.52 | vless | 224.7 | 616.1 | 22.58 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 195.211.98.43 |
| 76.35 | vless | 331.0 | 747.5 | 20.12 | 0.0 | 10.0 | 10.28 | 18.66 | Au1rxx-base64 | 169.40.42.15 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.921 | 0.86 | 300 | 1577 | prefer |
| ermaozi | 0.885 | 0.909 | 22 | 250 | prefer |
| Surfboard-tg-mixed | 0.708 | 0.629 | 267 | 7112 | prefer |
| mheidari-all | 0.423 | 0.343 | 429 | 18979 | observe |
| DeltaKronecker-all | 0.385 | 0.298 | 57 | 6421 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7571 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8803 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5640 | observe |
| barry-far-vless | 0.255 | None | 0 | 5853 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3625 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 172 |
| speed | TimeoutError | - | 110 |
| geo | ClientOSError | - | 83 |
| speed | ClientOSError | - | 30 |
| cn-block | ClientOSError | - | 29 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 10 |
| 204 | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
