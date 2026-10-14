# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 16:56:21 |
| 运行耗时 | 727.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98394 |
| 去重后节点 | 27299 |
| TCP 可达 | 3000 |
| 真实可用 | 362 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27299 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 48.4 |
| probe | 298.7 |
| real_test | 298.3 |
| generate | 75.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58410 |
| vmess | 16289 |
| shadowsocks | 11771 |
| trojan | 9944 |
| hysteria2 | 1290 |
| http | 410 |
| shadowsocksr | 166 |
| socks | 65 |
| anytls | 25 |
| hysteria | 18 |
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
| 82.35 | hysteria2 | 287.0 | 719.7 | 21.13 | 0.0 | 10.0 | 13.64 | 19.08 | Au1rxx-base64 | 129.213.91.185 |
| 81.44 | shadowsocks | 252.4 | 638.7 | 21.94 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 156.146.38.167 |
| 79.42 | shadowsocks | 290.7 | 745.1 | 21.05 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 156.146.38.169 |
| 79.17 | shadowsocks | 310.3 | 746.0 | 20.6 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 37.19.198.160 |
| 78.44 | shadowsocks | 314.8 | 765.9 | 20.49 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 37.19.198.236 |
| 77.57 | hysteria2 | 311.5 | 640.3 | 20.57 | 0.0 | 9.73 | 13.64 | 19.08 | Au1rxx-base64 | 66.94.121.46 |
| 75.45 | shadowsocks | 329.8 | 662.7 | 20.14 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 149.22.95.183 |
| 75.0 | vless | 277.9 | 540.7 | 21.34 | 0.0 | 10.0 | 8.77 | 19.08 | Au1rxx-base64 | 47.251.108.158 |
| 74.96 | shadowsocks | 346.9 | 659.7 | 19.75 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 173.244.56.9 |
| 74.64 | shadowsocks | 305.2 | 577.5 | 20.71 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 173.244.56.6 |
| 74.15 | shadowsocks | 399.9 | 993.7 | 18.52 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 64.74.163.67 |
| 73.93 | shadowsocks | 294.9 | 699.7 | 20.95 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 140.82.63.79 |
| 72.94 | shadowsocks | 448.9 | 961.1 | 17.39 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 51.222.136.236 |
| 72.74 | vless | 290.4 | 586.6 | 21.06 | 0.0 | 10.0 | 8.77 | 19.08 | Au1rxx-base64 | 45.32.69.110 |
| 72.71 | vless | 286.3 | 640.1 | 21.15 | 0.0 | 8.21 | 8.77 | 19.08 | Au1rxx-base64 | uspanel.unixzone.us |
| 72.62 | shadowsocks | 320.0 | 755.8 | 20.37 | 0.0 | 10.0 | 14.42 | 19.08 | Au1rxx-base64 | 37.19.198.243 |
| 72.62 | vless | 364.1 | 739.1 | 19.35 | 0.0 | 10.0 | 8.77 | 19.08 | Au1rxx-base64 | 154.29.145.196 |
| 72.5 | shadowsocks | 298.1 | 747.6 | 20.88 | 0.0 | 10.0 | 14.42 | 11.2 | mheidari-all | 156.146.38.170 |
| 72.36 | vless | 348.2 | 842.2 | 19.72 | 0.0 | 10.0 | 8.77 | 19.08 | Au1rxx-base64 | 69.48.201.136 |
| 71.92 | trojan | 458.3 | 1205.9 | 17.17 | 0.0 | 10.0 | 13.67 | 19.08 | Au1rxx-base64 | 66.23.203.21 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.928 | 0.864 | 44 | 23968 | prefer |
| Au1rxx-base64 | 0.871 | 0.801 | 287 | 1780 | prefer |
| Surfboard-tg-mixed | 0.663 | 0.585 | 94 | 7210 | observe |
| DeltaKronecker-all | 0.647 | 0.571 | 28 | 4803 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7543 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1780 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 30 |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyError | - | 15 |
| speed | TimeoutError | - | 10 |
| geo | ClientOSError | - | 9 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| geo | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| cn-block | status | 530 | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
