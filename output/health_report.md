# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 13:12:24 |
| 运行耗时 | 220.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94669 |
| 去重后节点 | 24972 |
| TCP 可达 | 1000 |
| 真实可用 | 396 |
| Verified 输出 | 30 |
| Global 输出 | 30 |
| All 输出 | 24972 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 41.9 |
| probe | 35.8 |
| real_test | 108.3 |
| generate | 28.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59130 |
| vmess | 12783 |
| shadowsocks | 11092 |
| trojan | 9192 |
| hysteria2 | 2086 |
| http | 138 |
| shadowsocksr | 130 |
| socks | 61 |
| anytls | 22 |
| hysteria | 21 |
| tuic | 14 |

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
| 84.03 | hysteria2 | 239.9 | 557.6 | 22.23 | 0.0 | 9.18 | 14.38 | 19.66 | Au1rxx-base64 | 66.94.121.46 |
| 82.15 | vless | 256.7 | 637.3 | 21.83 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 172.233.139.46 |
| 81.85 | vless | 269.8 | 672.7 | 21.53 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 172.235.43.210 |
| 80.8 | shadowsocks | 300.1 | 704.6 | 20.83 | 0.0 | 10.0 | 14.31 | 19.66 | Au1rxx-base64 | 173.244.56.9 |
| 78.46 | vless | 222.1 | 510.0 | 22.64 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 104.18.46.234 |
| 78.41 | vless | 418.5 | 1143.8 | 18.09 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 172.235.38.85 |
| 77.94 | vless | 244.5 | 454.7 | 22.12 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 172.64.229.170 |
| 77.63 | shadowsocks | 199.5 | 488.7 | 23.16 | 0.0 | 10.0 | 14.31 | 19.66 | Au1rxx-base64 | 108.181.0.177 |
| 77.15 | vless | 278.6 | 468.2 | 21.33 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 172.64.32.108 |
| 76.67 | vless | 218.6 | 517.9 | 22.72 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 23.94.227.94 |
| 76.59 | shadowsocks | 262.6 | 642.6 | 21.7 | 0.0 | 10.0 | 14.31 | 19.66 | Au1rxx-base64 | 156.146.38.167 |
| 75.96 | shadowsocks | 293.0 | 705.1 | 20.99 | 0.0 | 10.0 | 14.31 | 19.66 | Au1rxx-base64 | 173.244.56.6 |
| 75.96 | trojan | 315.4 | 726.4 | 20.48 | 0.0 | 9.27 | 12.0 | 19.66 | Au1rxx-base64 | 64.94.95.114 |
| 75.91 | trojan | 312.0 | 706.8 | 20.56 | 0.0 | 9.19 | 12.0 | 19.66 | Au1rxx-base64 | 64.94.95.118 |
| 75.66 | vless | 220.4 | 525.0 | 22.68 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 188.114.97.6 |
| 75.54 | shadowsocks | 262.0 | 633.8 | 21.71 | 0.0 | 10.0 | 14.31 | 19.66 | Au1rxx-base64 | 156.146.38.169 |
| 75.4 | vless | 294.6 | 459.5 | 20.96 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 162.159.43.187 |
| 75.28 | trojan | 372.6 | 826.0 | 19.15 | 0.0 | 10.0 | 12.0 | 19.66 | Au1rxx-base64 | 64.94.95.115 |
| 75.22 | vless | 270.6 | 449.0 | 21.51 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 104.18.39.218 |
| 75.13 | vless | 560.2 | 1559.8 | 14.81 | 0.0 | 10.0 | 10.66 | 19.66 | Au1rxx-base64 | 38.246.229.58 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.908 | 327 | 1788 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.67 | 91 | 7247 | prefer |
| mheidari-all | 0.734 | 0.857 | 14 | 21631 | prefer |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 151 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6417 | observe |
| Epodonios-all | 0.255 | None | 0 | 7707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8440 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5750 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 10 |
| geo | ClientOSError | - | 10 |
| geo | TimeoutError | - | 6 |
| speed | ClientOSError | - | 4 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | True | 30 | 30 | 30.0 |
| global | True | 30 | 30 | 30.0 |

---

此文件由 `core.report.write_health_report()` 自动生成。
