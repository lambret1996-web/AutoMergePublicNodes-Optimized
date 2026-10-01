# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 11:52:23 |
| 运行耗时 | 590.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98651 |
| 去重后节点 | 27372 |
| TCP 可达 | 3000 |
| 真实可用 | 430 |
| Verified 输出 | 30 |
| Global 输出 | 30 |
| All 输出 | 27372 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.5 |
| tcp | 45.3 |
| probe | 282.2 |
| real_test | 172.1 |
| generate | 80.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60510 |
| vmess | 15581 |
| shadowsocks | 11407 |
| trojan | 8949 |
| hysteria2 | 1368 |
| http | 532 |
| shadowsocksr | 174 |
| socks | 66 |
| anytls | 40 |
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
| 78.52 | shadowsocks | 252.9 | 701.8 | 21.92 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 37.19.198.244 |
| 78.34 | shadowsocks | 260.8 | 719.7 | 21.74 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 37.19.198.160 |
| 77.6 | shadowsocks | 293.0 | 821.8 | 21.0 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 37.19.198.243 |
| 76.99 | shadowsocks | 297.5 | 782.3 | 20.89 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 140.82.63.79 |
| 76.93 | vless | 231.9 | 620.8 | 22.41 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 195.123.235.177 |
| 76.16 | shadowsocks | 354.8 | 994.0 | 19.56 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 198.98.53.130 |
| 75.76 | shadowsocks | 281.4 | 648.2 | 21.26 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 156.146.38.168 |
| 75.65 | shadowsocks | 355.5 | 965.4 | 19.55 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 15.204.247.206 |
| 75.47 | shadowsocks | 363.2 | 975.6 | 19.37 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 51.222.200.165 |
| 75.42 | shadowsocks | 285.5 | 662.4 | 21.17 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 156.146.38.170 |
| 75.28 | vless | 303.2 | 768.1 | 20.76 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 66.70.179.198 |
| 75.18 | shadowsocks | 282.1 | 644.8 | 21.25 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 156.146.38.169 |
| 75.11 | hysteria2 | 341.5 | 741.1 | 19.87 | 0.0 | 10.0 | 12.69 | 17.42 | Au1rxx-base64 | 192.255.128.123 |
| 74.96 | vless | 317.0 | 877.4 | 20.44 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 137.184.218.169 |
| 74.7 | shadowsocks | 310.1 | 804.6 | 20.6 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 199.60.101.12 |
| 74.66 | vless | 330.0 | 758.6 | 20.14 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 169.40.42.163 |
| 74.15 | vless | 299.5 | 683.2 | 20.84 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 169.40.42.90 |
| 74.11 | vless | 285.9 | 690.8 | 21.16 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 167.17.69.171 |
| 74.02 | vless | 297.1 | 673.5 | 20.9 | 0.0 | 10.0 | 7.1 | 17.42 | Au1rxx-base64 | 198.251.78.29 |
| 73.81 | shadowsocks | 434.9 | 1110.2 | 17.71 | 0.0 | 10.0 | 13.18 | 17.42 | Au1rxx-base64 | 103.214.111.162 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | 0.955 | 22 | 588 | prefer |
| mheidari-all | 0.901 | 0.831 | 65 | 23162 | prefer |
| Au1rxx-base64 | 0.85 | 0.781 | 310 | 1767 | prefer |
| Surfboard-tg-mixed | 0.81 | 0.734 | 124 | 7144 | prefer |
| DeltaKronecker-all | 0.78 | 0.714 | 28 | 5603 | prefer |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 81 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9494 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5788 | observe |
| barry-far-vless | 0.255 | None | 0 | 6050 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4241 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 50 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 10 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 30 | - |
| global | False | 300 | 30 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
