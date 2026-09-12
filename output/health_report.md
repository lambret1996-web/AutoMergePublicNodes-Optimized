# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 06:33:29 |
| 运行耗时 | 781.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83310 |
| 去重后节点 | 22807 |
| TCP 可达 | 3000 |
| 真实可用 | 500 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22807 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 37.7 |
| probe | 293.6 |
| real_test | 362.6 |
| generate | 79.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50404 |
| vmess | 12626 |
| shadowsocks | 9750 |
| trojan | 8057 |
| hysteria2 | 1642 |
| http | 634 |
| shadowsocksr | 120 |
| socks | 52 |
| tuic | 12 |
| hysteria | 11 |
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
| 82.84 | vless | 186.6 | 490.1 | 23.46 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 31.58.50.200 |
| 82.51 | vless | 200.9 | 485.9 | 23.13 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 172.235.38.85 |
| 82.22 | vless | 213.4 | 524.2 | 22.84 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 172.235.43.210 |
| 81.17 | shadowsocks | 270.0 | 674.5 | 21.53 | 0.0 | 10.0 | 13.96 | 19.68 | Au1rxx-base64 | 173.244.56.6 |
| 80.33 | shadowsocks | 199.9 | 478.0 | 23.15 | 0.0 | 10.0 | 13.96 | 17.72 | mheidari-all | 108.181.118.10 |
| 80.23 | shadowsocks | 204.3 | 494.5 | 23.05 | 0.0 | 10.0 | 13.96 | 17.72 | mheidari-all | 108.181.0.177 |
| 79.83 | shadowsocks | 243.1 | 580.8 | 22.15 | 0.0 | 10.0 | 13.96 | 17.72 | mheidari-all | 149.22.95.183 |
| 79.77 | vless | 319.3 | 845.7 | 20.39 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 15.204.97.216 |
| 79.39 | vless | 200.3 | 491.9 | 23.14 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 172.233.139.46 |
| 77.94 | vless | 203.9 | 455.1 | 23.06 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 108.162.198.178 |
| 76.3 | shadowsocks | 335.1 | 786.3 | 20.02 | 0.0 | 10.0 | 13.96 | 19.68 | Au1rxx-base64 | 156.146.38.170 |
| 75.74 | shadowsocks | 314.6 | 643.2 | 20.49 | 0.0 | 10.0 | 13.96 | 19.68 | Au1rxx-base64 | 23.150.248.20 |
| 75.7 | vless | 353.0 | 775.8 | 19.61 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 79.141.172.154 |
| 75.48 | shadowsocks | 291.1 | 651.7 | 21.04 | 0.0 | 10.0 | 13.96 | 17.72 | mheidari-all | 156.146.38.169 |
| 75.32 | vless | 247.9 | 248.0 | 22.04 | 5.7 | 9.85 | 9.7 | 14.78 | Surfboard-tg-mixed | 31.76.91.72 |
| 75.12 | vless | 304.1 | 743.4 | 20.74 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 150.241.102.181 |
| 75.02 | vless | 209.4 | 476.2 | 22.93 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 172.64.42.85 |
| 74.98 | vless | 258.6 | 406.8 | 21.79 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 162.159.24.131 |
| 74.98 | shadowsocks | 337.1 | 330.6 | 19.98 | 2.6 | 9.91 | 13.96 | 19.68 | Au1rxx-base64 | 84.247.155.196 |
| 74.7 | vless | 276.6 | 550.6 | 21.38 | 0.0 | 10.0 | 9.7 | 19.68 | Au1rxx-base64 | 144.172.104.26 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.925 | 0.861 | 294 | 1683 | prefer |
| Surfboard-tg-mixed | 0.805 | 0.729 | 140 | 7232 | prefer |
| mheidari-all | 0.714 | 0.636 | 99 | 15597 | prefer |
| ermaozi | 0.617 | 0.606 | 33 | 434 | observe |
| DeltaKronecker-all | 0.356 | 0.274 | 208 | 6070 | observe |
| ermaozi-get_subscribe | 0.283 | 0.333 | 12 | 459 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7720 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8713 | observe |
| barry-far-vless | 0.255 | None | 0 | 6107 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4207 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1683 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| tg-oneclickvpnkeys | 0.215 | 0.5 | 2 | 197 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 101 |
| geo | ClientOSError | - | 57 |
| speed | ClientOSError | - | 32 |
| 204 | ProxyError | - | 27 |
| speed | TimeoutError | - | 22 |
| cn-block | ClientOSError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
