# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 06:34:45 |
| 运行耗时 | 743.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96782 |
| 去重后节点 | 26365 |
| TCP 可达 | 3000 |
| 真实可用 | 470 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26365 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 42.8 |
| probe | 279.3 |
| real_test | 335.5 |
| generate | 77.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59396 |
| vmess | 14923 |
| shadowsocks | 11198 |
| trojan | 8737 |
| hysteria2 | 1566 |
| http | 649 |
| shadowsocksr | 174 |
| socks | 88 |
| anytls | 24 |
| hysteria | 19 |
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
| 79.67 | hysteria2 | 301.2 | 758.6 | 20.8 | 0.0 | 9.09 | 13.7 | 17.08 | Au1rxx-base64 | 66.94.121.46 |
| 75.45 | shadowsocks | 236.5 | 597.1 | 22.3 | 0.0 | 10.0 | 14.17 | 13.48 | Surfboard-tg-mixed | 108.181.0.177 |
| 75.29 | trojan | 188.7 | 477.8 | 23.41 | 0.0 | 9.21 | 8.09 | 17.08 | Au1rxx-base64 | 100.42.228.109 |
| 75.23 | vless | 203.0 | 528.5 | 23.08 | 0.0 | 9.11 | 5.96 | 17.08 | Au1rxx-base64 | 172.235.43.210 |
| 75.21 | http | 201.6 | 511.5 | 23.11 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.211 |
| 75.18 | http | 202.9 | 510.8 | 23.08 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.220 |
| 75.17 | http | 203.5 | 520.6 | 23.07 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.213 |
| 75.14 | http | 204.8 | 528.7 | 23.04 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.198 |
| 75.1 | http | 206.2 | 525.5 | 23.0 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.206 |
| 75.09 | http | 206.7 | 524.5 | 22.99 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.207 |
| 75.09 | http | 206.8 | 535.5 | 22.99 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.204 |
| 75.09 | http | 206.8 | 528.4 | 22.99 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.214 |
| 74.75 | vless | 236.4 | 580.5 | 22.31 | 0.0 | 9.4 | 5.96 | 17.08 | Au1rxx-base64 | 15.204.97.216 |
| 74.46 | shadowsocks | 240.7 | 561.8 | 22.21 | 0.0 | 9.02 | 14.17 | 17.08 | Au1rxx-base64 | 173.244.56.9 |
| 73.75 | shadowsocks | 329.8 | 777.4 | 20.14 | 0.0 | 9.2 | 14.17 | 17.08 | Au1rxx-base64 | 156.146.38.169 |
| 73.69 | shadowsocks | 195.3 | 512.6 | 23.26 | 0.0 | 10.0 | 14.17 | 10.76 | mheidari-all | 192.3.247.109 |
| 73.41 | http | 211.1 | 526.1 | 22.89 | 0.0 | 10.0 | 10.0 | 15.1 | ermaozi | 138.199.35.203 |
| 72.93 | shadowsocks | 297.0 | 663.2 | 20.9 | 0.0 | 9.02 | 14.17 | 17.08 | Au1rxx-base64 | 156.146.38.168 |
| 72.82 | shadowsocks | 343.8 | 818.3 | 19.82 | 0.0 | 9.02 | 14.17 | 17.08 | Au1rxx-base64 | 156.146.38.167 |
| 72.56 | hysteria2 | 433.0 | 986.2 | 17.75 | 0.0 | 9.08 | 13.7 | 17.08 | Au1rxx-base64 | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | 0.804 | 301 | 1591 | prefer |
| ermaozi | 0.743 | 0.737 | 57 | 346 | prefer |
| Surfboard-tg-mixed | 0.549 | 0.469 | 224 | 7168 | observe |
| mheidari-all | 0.392 | 0.311 | 235 | 22274 | observe |
| DeltaKronecker-all | 0.332 | 0.286 | 14 | 6324 | observe |
| ermaozi-get_subscribe | 0.296 | 0.4 | 10 | 372 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7633 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8897 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5836 | observe |
| barry-far-vless | 0.255 | None | 0 | 6054 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4187 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 88 |
| speed | ClientOSError | - | 71 |
| geo | ClientOSError | - | 47 |
| speed | TimeoutError | - | 47 |
| cn-block | ClientOSError | - | 36 |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyError | - | 25 |
| cn-block | TimeoutError | - | 21 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
