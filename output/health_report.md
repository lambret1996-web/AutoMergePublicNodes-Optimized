# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 18:46:03 |
| 运行耗时 | 623.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98112 |
| 去重后节点 | 27346 |
| TCP 可达 | 3000 |
| 真实可用 | 386 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27346 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.4 |
| geo | 1.5 |
| tcp | 46.8 |
| probe | 304.1 |
| real_test | 172.2 |
| generate | 90.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57801 |
| vmess | 15555 |
| shadowsocks | 11596 |
| trojan | 10746 |
| hysteria2 | 1488 |
| http | 610 |
| shadowsocksr | 161 |
| socks | 95 |
| anytls | 34 |
| hysteria | 17 |
| tuic | 9 |

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
| 82.59 | hysteria2 | 240.7 | 279.6 | 22.21 | 4.52 | 9.39 | 14.0 | 19.3 | Au1rxx-base64 | open.w2m.ink |
| 81.15 | shadowsocks | 213.5 | 531.2 | 22.84 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 108.181.0.177 |
| 81.05 | shadowsocks | 217.5 | 524.8 | 22.74 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 108.181.118.10 |
| 80.76 | shadowsocks | 251.8 | 611.2 | 21.95 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 149.22.95.183 |
| 79.95 | hysteria2 | 266.7 | 264.0 | 21.6 | 5.1 | 7.96 | 14.0 | 19.3 | Au1rxx-base64 | open.2ml.bid |
| 79.81 | trojan | 289.4 | 696.1 | 21.08 | 0.0 | 10.0 | 11.93 | 19.3 | Au1rxx-base64 | 34.220.15.24 |
| 78.47 | vless | 175.1 | 465.1 | 23.72 | 0.0 | 10.0 | 5.45 | 19.3 | Au1rxx-base64 | 47.251.108.158 |
| 77.51 | vless | 216.6 | 600.9 | 22.76 | 0.0 | 10.0 | 5.45 | 19.3 | Au1rxx-base64 | 137.175.82.40 |
| 77.44 | hysteria2 | 347.1 | 761.3 | 19.74 | 0.0 | 10.0 | 14.0 | 19.3 | Au1rxx-base64 | 129.213.91.185 |
| 77.1 | vless | 234.3 | 576.2 | 22.35 | 0.0 | 10.0 | 5.45 | 19.3 | Au1rxx-base64 | 15.204.97.216 |
| 76.92 | shadowsocks | 297.2 | 664.9 | 20.9 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 156.146.38.170 |
| 76.92 | shadowsocks | 302.6 | 581.6 | 20.77 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 173.244.56.9 |
| 76.83 | vless | 246.0 | 653.3 | 22.08 | 0.0 | 10.0 | 5.45 | 19.3 | Au1rxx-base64 | 107.173.237.146 |
| 76.65 | shadowsocks | 288.5 | 651.8 | 21.1 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 156.146.38.167 |
| 76.23 | vless | 228.7 | 552.6 | 22.48 | 0.0 | 10.0 | 5.45 | 19.3 | Au1rxx-base64 | 15.204.97.197 |
| 76.23 | shadowsocks | 298.8 | 671.6 | 20.86 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 74.5 | shadowsocks | 297.6 | 669.6 | 20.89 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 173.244.56.6 |
| 74.23 | vless | 228.9 | 500.8 | 22.48 | 0.0 | 10.0 | 5.45 | 19.3 | Au1rxx-base64 | 154.12.38.202 |
| 73.71 | shadowsocks | 295.9 | 654.9 | 20.93 | 0.0 | 10.0 | 13.51 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 73.55 | trojan | 332.9 | 335.8 | 20.07 | 2.41 | 9.93 | 11.93 | 19.3 | Au1rxx-base64 | 54.238.153.132 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | 0.888 | 303 | 1823 | prefer |
| mheidari-all | 0.948 | 0.882 | 51 | 23074 | prefer |
| Surfboard-tg-mixed | 0.633 | 0.554 | 83 | 7069 | observe |
| ermaozi | 0.593 | 0.571 | 28 | 664 | observe |
| DeltaKronecker-all | 0.474 | 0.467 | 15 | 5344 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7546 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9241 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5616 | observe |
| barry-far-vless | 0.255 | None | 0 | 5859 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 30 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 16 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 8 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |
| geo | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
