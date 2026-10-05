# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-05 20:29:01 |
| 运行耗时 | 566.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98500 |
| 去重后节点 | 27364 |
| TCP 可达 | 3000 |
| 真实可用 | 450 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27364 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.5 |
| tcp | 46.4 |
| probe | 257.0 |
| real_test | 172.3 |
| generate | 81.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58535 |
| vmess | 15742 |
| shadowsocks | 11612 |
| trojan | 10256 |
| hysteria2 | 1398 |
| http | 635 |
| shadowsocksr | 169 |
| socks | 89 |
| anytls | 27 |
| tuic | 20 |
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
| 80.73 | shadowsocks | 257.9 | 709.0 | 21.81 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 37.19.198.244 |
| 80.59 | shadowsocks | 263.8 | 725.1 | 21.67 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 37.19.198.236 |
| 80.37 | shadowsocks | 251.9 | 648.6 | 21.95 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 140.82.63.79 |
| 80.06 | hysteria2 | 373.0 | 1089.8 | 19.14 | 0.0 | 10.0 | 13.12 | 19.3 | Au1rxx-base64 | 129.213.91.185 |
| 78.41 | shadowsocks | 285.6 | 655.9 | 21.17 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 156.146.38.167 |
| 77.5 | shadowsocks | 285.6 | 660.3 | 21.17 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 156.146.38.170 |
| 77.41 | shadowsocks | 287.9 | 658.8 | 21.11 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 77.22 | vless | 292.1 | 727.8 | 21.02 | 0.0 | 10.0 | 6.9 | 19.3 | Au1rxx-base64 | 66.70.179.198 |
| 77.19 | vless | 293.2 | 728.8 | 20.99 | 0.0 | 10.0 | 6.9 | 19.3 | Au1rxx-base64 | 2.24.124.64 |
| 76.84 | shadowsocks | 289.0 | 673.9 | 21.09 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 76.71 | shadowsocks | 409.8 | 1092.5 | 18.29 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 185.156.47.97 |
| 76.6 | shadowsocks | 328.3 | 938.5 | 20.18 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 15.204.233.41 |
| 76.46 | shadowsocks | 314.9 | 809.2 | 20.49 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 66.23.204.210 |
| 76.17 | vless | 337.1 | 903.4 | 19.97 | 0.0 | 10.0 | 6.9 | 19.3 | Au1rxx-base64 | 185.95.231.156 |
| 75.82 | shadowsocks | 253.8 | 708.2 | 21.9 | 0.0 | 10.0 | 13.62 | 19.3 | Au1rxx-base64 | 37.19.198.160 |
| 75.18 | hysteria2 | 339.3 | 340.9 | 19.92 | 2.21 | 8.78 | 13.12 | 19.3 | Au1rxx-base64 | open.w2m.ink |
| 73.86 | shadowsocks | 352.5 | 908.9 | 19.62 | 0.0 | 8.55 | 13.62 | 19.3 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 73.73 | vless | 288.9 | 647.7 | 21.09 | 0.0 | 10.0 | 6.9 | 19.3 | Au1rxx-base64 | 169.40.42.182 |
| 73.38 | vless | 263.6 | 691.6 | 21.68 | 0.0 | 10.0 | 6.9 | 19.3 | Au1rxx-base64 | 162.159.0.169 |
| 73.21 | vless | 281.8 | 709.1 | 21.26 | 0.0 | 10.0 | 6.9 | 19.3 | Au1rxx-base64 | 104.18.39.218 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.968 | 0.897 | 319 | 1855 | prefer |
| mheidari-all | 0.924 | 0.86 | 43 | 23179 | prefer |
| Surfboard-tg-mixed | 0.832 | 0.758 | 99 | 7145 | prefer |
| ermaozi | 0.584 | 0.557 | 70 | 701 | observe |
| DeltaKronecker-all | 0.58 | 0.5 | 20 | 5300 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5111 | observe |
| Epodonios-all | 0.255 | None | 0 | 7624 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9342 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5642 | observe |
| barry-far-vless | 0.255 | None | 0 | 5930 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 32 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 14 |
| geo | ClientOSError | - | 9 |
| speed | TimeoutError | - | 8 |
| speed | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 1 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
