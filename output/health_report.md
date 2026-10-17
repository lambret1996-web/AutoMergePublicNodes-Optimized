# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 03:39:33 |
| 运行耗时 | 867.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99741 |
| 去重后节点 | 27733 |
| TCP 可达 | 3000 |
| 真实可用 | 612 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27733 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.7 |
| tcp | 49.4 |
| probe | 322.8 |
| real_test | 385.0 |
| generate | 99.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58474 |
| vmess | 16652 |
| shadowsocks | 12106 |
| trojan | 10173 |
| hysteria2 | 1340 |
| http | 717 |
| shadowsocksr | 168 |
| socks | 62 |
| anytls | 26 |
| hysteria | 17 |
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
| 78.76 | hysteria2 | 296.7 | 723.5 | 20.91 | 0.0 | 9.06 | 13.85 | 16.44 | Au1rxx-base64 | 129.213.91.185 |
| 75.67 | vless | 277.5 | 672.2 | 21.35 | 0.0 | 8.69 | 9.19 | 16.44 | Au1rxx-base64 | 147.45.60.160 |
| 75.59 | vless | 237.3 | 524.6 | 22.28 | 0.0 | 10.0 | 9.19 | 16.44 | Au1rxx-base64 | 47.251.108.158 |
| 74.14 | shadowsocks | 245.2 | 629.4 | 22.1 | 0.0 | 8.77 | 12.83 | 16.44 | Au1rxx-base64 | 156.146.38.168 |
| 73.0 | shadowsocks | 244.3 | 627.3 | 22.12 | 0.0 | 8.61 | 12.83 | 16.44 | Au1rxx-base64 | 156.146.38.170 |
| 72.46 | shadowsocks | 242.0 | 616.8 | 22.18 | 0.0 | 8.59 | 12.83 | 16.44 | Au1rxx-base64 | 156.146.38.167 |
| 72.27 | hysteria2 | 354.4 | 732.8 | 19.57 | 0.0 | 9.83 | 13.85 | 16.44 | Au1rxx-base64 | 66.94.121.46 |
| 72.24 | shadowsocks | 270.1 | 567.5 | 21.53 | 0.0 | 8.67 | 12.83 | 16.44 | Au1rxx-base64 | 173.244.56.9 |
| 72.19 | vless | 293.1 | 656.0 | 20.99 | 0.0 | 8.81 | 9.19 | 16.44 | Au1rxx-base64 | 195.211.98.43 |
| 71.86 | shadowsocks | 274.4 | 583.2 | 21.43 | 0.0 | 8.61 | 12.83 | 16.44 | Au1rxx-base64 | 173.244.56.6 |
| 71.42 | shadowsocks | 349.3 | 256.0 | 19.69 | 5.4 | 8.57 | 12.83 | 16.44 | Au1rxx-base64 | 149.22.87.241 |
| 71.29 | shadowsocks | 238.7 | 614.4 | 22.25 | 0.0 | 8.77 | 12.83 | 16.44 | Au1rxx-base64 | 156.146.38.169 |
| 70.8 | shadowsocks | 308.8 | 312.2 | 20.63 | 3.29 | 9.08 | 12.83 | 16.44 | Au1rxx-base64 | 149.22.87.240 |
| 70.65 | shadowsocks | 338.0 | 777.7 | 19.95 | 0.0 | 8.59 | 12.83 | 16.44 | Au1rxx-base64 | 37.19.198.244 |
| 70.59 | vless | 272.6 | 577.2 | 21.47 | 0.0 | 8.8 | 9.19 | 16.44 | Au1rxx-base64 | 154.29.159.211 |
| 70.56 | vless | 312.6 | 657.9 | 20.54 | 0.0 | 8.8 | 9.19 | 16.44 | Au1rxx-base64 | 154.9.241.170 |
| 70.56 | shadowsocks | 341.7 | 778.7 | 19.87 | 0.0 | 8.59 | 12.83 | 16.44 | Au1rxx-base64 | 37.19.198.243 |
| 70.38 | vless | 249.1 | 554.1 | 22.01 | 0.0 | 8.81 | 9.19 | 16.44 | Au1rxx-base64 | 45.63.53.81 |
| 70.04 | shadowsocks | 339.5 | 779.9 | 19.92 | 0.0 | 8.59 | 12.83 | 16.44 | Au1rxx-base64 | 37.19.198.160 |
| 69.5 | vless | 358.2 | 759.6 | 19.49 | 0.0 | 8.76 | 9.19 | 16.44 | Au1rxx-base64 | 195.123.235.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.949 | 0.871 | 533 | 1993 | prefer |
| Surfboard-tg-mixed | 0.668 | 0.591 | 66 | 7128 | observe |
| mheidari-all | 0.56 | 0.478 | 23 | 24092 | observe |
| DeltaKronecker-all | 0.503 | 0.422 | 154 | 4946 | observe |
| ermaozi | 0.491 | 0.462 | 52 | 702 | observe |
| ninja-vless | 0.438 | 0.8 | 5 | 1791 | observe |
| ermaozi-get_subscribe | 0.382 | 1.0 | 3 | 601 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5024 | observe |
| tg-Farah_VPN | 0.263 | 1.0 | 1 | 200 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| Epodonios-all | 0.255 | None | 0 | 7692 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10039 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5602 | observe |
| barry-far-vless | 0.255 | None | 0 | 5847 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 51 |
| 204 | ProxyError | - | 40 |
| geo | ClientOSError | - | 38 |
| speed | ClientOSError | - | 29 |
| speed | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 7 |
| speed | ProxyError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
