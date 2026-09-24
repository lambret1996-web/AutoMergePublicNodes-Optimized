# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 00:43:14 |
| 运行耗时 | 1203.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 96715 |
| 去重后节点 | 26644 |
| TCP 可达 | 3000 |
| 真实可用 | 562 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26644 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.6 |
| tcp | 42.7 |
| probe | 394.7 |
| real_test | 677.0 |
| generate | 80.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59318 |
| vmess | 14657 |
| shadowsocks | 11208 |
| trojan | 9172 |
| hysteria2 | 1453 |
| http | 601 |
| shadowsocksr | 170 |
| socks | 85 |
| anytls | 25 |
| hysteria | 18 |
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
| 84.62 | hysteria2 | 230.4 | 578.6 | 22.44 | 0.0 | 10.0 | 14.12 | 19.06 | Au1rxx-base64 | 66.94.121.46 |
| 80.57 | vless | 239.7 | 632.7 | 22.23 | 0.0 | 8.88 | 10.4 | 19.06 | Au1rxx-base64 | 172.235.43.210 |
| 79.76 | shadowsocks | 265.5 | 637.4 | 21.63 | 0.0 | 10.0 | 13.07 | 19.06 | Au1rxx-base64 | 173.244.56.6 |
| 79.01 | vless | 355.6 | 954.6 | 19.55 | 0.0 | 10.0 | 10.4 | 19.06 | Au1rxx-base64 | 5.78.159.214 |
| 78.91 | vless | 200.7 | 511.5 | 23.13 | 0.0 | 10.0 | 10.4 | 15.38 | mheidari-all | 172.233.139.46 |
| 78.17 | shadowsocks | 334.1 | 856.6 | 20.04 | 0.0 | 10.0 | 13.07 | 19.06 | Au1rxx-base64 | 149.22.95.183 |
| 77.29 | vless | 297.3 | 781.5 | 20.9 | 0.0 | 8.93 | 10.4 | 19.06 | Au1rxx-base64 | 5.78.139.175 |
| 76.56 | shadowsocks | 223.5 | 538.7 | 22.61 | 0.0 | 10.0 | 13.07 | 15.38 | mheidari-all | 108.181.118.10 |
| 75.29 | shadowsocks | 278.2 | 765.4 | 21.34 | 0.0 | 10.0 | 13.07 | 15.38 | mheidari-all | 192.3.247.109 |
| 75.08 | shadowsocks | 294.6 | 662.9 | 20.96 | 0.0 | 9.0 | 13.07 | 19.06 | Au1rxx-base64 | 156.146.38.169 |
| 74.97 | shadowsocks | 292.2 | 660.6 | 21.02 | 0.0 | 8.86 | 13.07 | 19.06 | Au1rxx-base64 | 156.146.38.168 |
| 74.47 | vless | 286.1 | 738.5 | 21.16 | 0.0 | 8.85 | 10.4 | 19.06 | Au1rxx-base64 | 5.78.28.48 |
| 74.17 | vless | 489.9 | 1286.2 | 16.44 | 0.0 | 8.92 | 10.4 | 19.06 | Au1rxx-base64 | 51.81.203.63 |
| 74.01 | vless | 303.7 | 817.6 | 20.75 | 0.0 | 8.8 | 10.4 | 19.06 | Au1rxx-base64 | 31.58.50.200 |
| 73.69 | http | 254.8 | 657.0 | 21.88 | 0.0 | 10.0 | 9.73 | 15.08 | ermaozi | 138.199.35.198 |
| 73.55 | http | 260.8 | 686.2 | 21.74 | 0.0 | 10.0 | 9.73 | 15.08 | ermaozi | 138.199.35.207 |
| 73.44 | vless | 240.8 | 484.5 | 22.2 | 0.0 | 9.03 | 10.4 | 19.06 | Au1rxx-base64 | 172.64.158.146 |
| 73.2 | vless | 352.5 | 721.8 | 19.62 | 0.0 | 8.88 | 10.4 | 19.06 | Au1rxx-base64 | 195.211.98.43 |
| 72.67 | shadowsocks | 241.1 | 559.9 | 22.2 | 0.0 | 10.0 | 13.07 | 12.96 | Surfboard-tg-mixed | 173.244.56.9 |
| 72.62 | vless | 256.4 | 715.8 | 21.84 | 0.0 | 10.0 | 10.4 | 15.38 | mheidari-all | 47.251.108.158 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | 0.895 | 267 | 1634 | prefer |
| ermaozi | 0.793 | 0.8 | 30 | 291 | prefer |
| Surfboard-tg-mixed | 0.774 | 0.7 | 70 | 7099 | prefer |
| mheidari-all | 0.393 | 0.312 | 781 | 22311 | observe |
| roosterkid-openproxylist-v2ray | 0.317 | 1.0 | 2 | 149 | observe |
| DeltaKronecker-all | 0.298 | 0.273 | 11 | 6471 | observe |
| Epodonios-all | 0.255 | None | 0 | 7561 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8878 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5948 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1634 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 266 |
| speed | TimeoutError | - | 130 |
| geo | ClientOSError | - | 60 |
| speed | ClientOSError | - | 54 |
| cn-block | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 15 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
