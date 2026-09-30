# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 05:30:18 |
| 运行耗时 | 901.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96719 |
| 去重后节点 | 27034 |
| TCP 可达 | 3000 |
| 真实可用 | 480 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27034 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 45.9 |
| probe | 346.1 |
| real_test | 458.3 |
| generate | 44.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58490 |
| vmess | 15172 |
| shadowsocks | 11339 |
| trojan | 9322 |
| hysteria2 | 1452 |
| http | 643 |
| shadowsocksr | 166 |
| socks | 75 |
| anytls | 37 |
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
| 83.25 | hysteria2 | 199.5 | 515.8 | 23.16 | 0.0 | 8.96 | 13.85 | 18.28 | Au1rxx-base64 | 192.255.128.123 |
| 81.97 | vless | 196.7 | 507.4 | 23.23 | 0.0 | 8.98 | 11.48 | 18.28 | Au1rxx-base64 | 172.235.43.210 |
| 81.94 | vless | 204.2 | 532.6 | 23.05 | 0.0 | 9.13 | 11.48 | 18.28 | Au1rxx-base64 | 172.233.139.46 |
| 81.91 | vless | 205.7 | 526.4 | 23.02 | 0.0 | 9.13 | 11.48 | 18.28 | Au1rxx-base64 | 192.3.247.109 |
| 81.24 | vless | 216.4 | 514.4 | 22.77 | 0.0 | 10.0 | 11.48 | 17.92 | mheidari-all | 47.251.108.158 |
| 80.58 | vless | 258.2 | 636.4 | 21.8 | 0.0 | 9.02 | 11.48 | 18.28 | Au1rxx-base64 | 137.175.82.40 |
| 80.52 | shadowsocks | 217.1 | 501.5 | 22.75 | 0.0 | 10.0 | 14.35 | 17.92 | mheidari-all | 192.3.247.109 |
| 80.34 | shadowsocks | 195.5 | 477.9 | 23.25 | 0.0 | 8.96 | 14.35 | 18.28 | Au1rxx-base64 | 108.181.118.10 |
| 79.46 | shadowsocks | 255.4 | 626.0 | 21.87 | 0.0 | 8.96 | 14.35 | 18.28 | Au1rxx-base64 | 156.146.38.170 |
| 79.38 | shadowsocks | 258.9 | 636.4 | 21.79 | 0.0 | 8.96 | 14.35 | 18.28 | Au1rxx-base64 | 156.146.38.168 |
| 79.37 | shadowsocks | 259.1 | 625.4 | 21.78 | 0.0 | 8.96 | 14.35 | 18.28 | Au1rxx-base64 | 156.146.38.167 |
| 79.34 | shadowsocks | 259.8 | 639.9 | 21.76 | 0.0 | 8.95 | 14.35 | 18.28 | Au1rxx-base64 | 156.146.38.169 |
| 78.49 | hysteria2 | 234.1 | 240.0 | 22.36 | 6.0 | 4.92 | 13.85 | 18.28 | Au1rxx-base64 | open.w2m.ink |
| 78.34 | vless | 272.0 | 605.5 | 21.48 | 0.0 | 9.13 | 11.48 | 18.28 | Au1rxx-base64 | 15.204.97.216 |
| 77.64 | vless | 295.1 | 661.6 | 20.95 | 0.0 | 10.0 | 11.48 | 17.92 | mheidari-all | 216.227.161.95 |
| 77.29 | shadowsocks | 217.9 | 538.1 | 22.73 | 0.0 | 8.93 | 14.35 | 18.28 | Au1rxx-base64 | 173.244.56.6 |
| 77.09 | vless | 213.7 | 497.0 | 22.83 | 0.0 | 9.0 | 11.48 | 18.28 | Au1rxx-base64 | 104.18.34.14 |
| 76.79 | trojan | 204.6 | 527.4 | 23.04 | 0.0 | 8.97 | 10.0 | 18.28 | Au1rxx-base64 | 192.236.151.43 |
| 76.13 | hysteria2 | 323.5 | 719.6 | 20.29 | 0.0 | 9.09 | 13.85 | 18.28 | Au1rxx-base64 | 159.223.157.129 |
| 75.77 | vless | 270.5 | 632.0 | 21.52 | 0.0 | 8.99 | 11.48 | 18.28 | Au1rxx-base64 | 172.64.229.2 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.853 | 0.788 | 293 | 1657 | prefer |
| ermaozi | 0.83 | 0.828 | 58 | 335 | prefer |
| Surfboard-tg-mixed | 0.825 | 0.755 | 53 | 7024 | prefer |
| DeltaKronecker-all | 0.503 | 0.583 | 12 | 5528 | observe |
| mheidari-all | 0.393 | 0.313 | 467 | 22586 | observe |
| ermaozi-get_subscribe | 0.38 | 0.8 | 5 | 353 | observe |
| tg-oneclickvpnkeys | 0.361 | 1.0 | 3 | 74 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| Epodonios-all | 0.255 | None | 0 | 7591 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9348 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5656 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 157 |
| speed | TimeoutError | - | 76 |
| speed | ClientOSError | - | 67 |
| geo | ClientOSError | - | 40 |
| 204 | ProxyError | - | 27 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
