# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 23:18:20 |
| 运行耗时 | 489.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97528 |
| 去重后节点 | 27020 |
| TCP 可达 | 3000 |
| 真实可用 | 429 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27020 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 45.3 |
| probe | 216.7 |
| real_test | 148.3 |
| generate | 71.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59921 |
| vmess | 14922 |
| shadowsocks | 11415 |
| trojan | 8882 |
| hysteria2 | 1459 |
| http | 635 |
| shadowsocksr | 170 |
| socks | 77 |
| anytls | 24 |
| hysteria | 15 |
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
| 81.88 | vless | 204.5 | 532.6 | 23.04 | 0.0 | 10.0 | 11.3 | 17.54 | Au1rxx-base64 | 172.235.38.85 |
| 81.63 | vless | 203.0 | 520.9 | 23.08 | 0.0 | 9.71 | 11.3 | 17.54 | Au1rxx-base64 | 172.233.139.46 |
| 81.15 | shadowsocks | 204.7 | 541.0 | 23.04 | 0.0 | 10.0 | 12.97 | 19.14 | mheidari-all | 216.105.168.18 |
| 80.93 | shadowsocks | 192.6 | 513.9 | 23.32 | 0.0 | 10.0 | 12.97 | 19.14 | mheidari-all | 192.3.247.109 |
| 80.72 | vless | 242.7 | 641.7 | 22.16 | 0.0 | 9.72 | 11.3 | 17.54 | Au1rxx-base64 | 172.235.43.210 |
| 80.56 | vless | 251.8 | 610.6 | 21.95 | 0.0 | 9.77 | 11.3 | 17.54 | Au1rxx-base64 | 137.175.82.40 |
| 80.02 | hysteria2 | 299.5 | 823.8 | 20.84 | 0.0 | 9.69 | 12.95 | 17.54 | Au1rxx-base64 | 192.255.128.123 |
| 79.52 | hysteria2 | 265.5 | 632.2 | 21.63 | 0.0 | 10.0 | 12.95 | 17.54 | Au1rxx-base64 | 66.94.121.46 |
| 79.08 | vless | 220.2 | 520.0 | 22.68 | 0.0 | 10.0 | 11.3 | 19.14 | mheidari-all | 47.251.108.158 |
| 78.96 | shadowsocks | 218.1 | 529.8 | 22.73 | 0.0 | 9.72 | 12.97 | 17.54 | Au1rxx-base64 | 173.244.56.9 |
| 78.82 | shadowsocks | 203.4 | 488.7 | 23.07 | 0.0 | 9.74 | 12.97 | 17.54 | Au1rxx-base64 | 108.181.118.10 |
| 78.52 | vless | 220.0 | 508.9 | 22.68 | 0.0 | 10.0 | 11.3 | 17.54 | Au1rxx-base64 | 173.249.207.28 |
| 78.43 | shadowsocks | 266.2 | 647.0 | 21.62 | 0.0 | 10.0 | 12.97 | 19.14 | mheidari-all | 156.146.38.170 |
| 78.36 | shadowsocks | 201.7 | 479.1 | 23.11 | 0.0 | 10.0 | 12.97 | 16.78 | Surfboard-tg-mixed | 108.181.0.177 |
| 77.96 | vless | 338.3 | 840.9 | 19.95 | 0.0 | 9.74 | 11.3 | 17.54 | Au1rxx-base64 | 23.95.222.127 |
| 77.55 | vless | 281.2 | 617.4 | 21.27 | 0.0 | 10.0 | 11.3 | 17.54 | Au1rxx-base64 | 15.204.97.216 |
| 77.3 | shadowsocks | 258.0 | 625.7 | 21.81 | 0.0 | 10.0 | 12.97 | 16.78 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.55 | vless | 230.1 | 492.8 | 22.45 | 0.0 | 9.76 | 11.3 | 17.54 | Au1rxx-base64 | 104.18.46.234 |
| 76.03 | vless | 327.0 | 745.9 | 20.21 | 0.0 | 9.72 | 11.3 | 17.54 | Au1rxx-base64 | 79.141.172.154 |
| 76.02 | shadowsocks | 259.4 | 625.9 | 21.77 | 0.0 | 10.0 | 12.97 | 16.78 | Surfboard-tg-mixed | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.992 | 0.927 | 55 | 7142 | prefer |
| Au1rxx-base64 | 0.936 | 0.871 | 310 | 1674 | prefer |
| mheidari-all | 0.907 | 0.833 | 108 | 22856 | prefer |
| ermaozi | 0.565 | 0.556 | 27 | 344 | observe |
| DeltaKronecker-all | 0.335 | 1.0 | 1 | 5428 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 121 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7535 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9706 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5799 | observe |
| barry-far-vless | 0.255 | None | 0 | 6027 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4237 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 28 |
| 204 | ProxyError | - | 11 |
| cn-block | TimeoutError | - | 8 |
| 204 | ProxyConnectionError | - | 6 |
| speed | TimeoutError | - | 6 |
| 204 | TimeoutError | - | 6 |
| geo | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
