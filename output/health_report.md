# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 18:27:18 |
| 运行耗时 | 529.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 87959 |
| 去重后节点 | 25367 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25367 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 41.5 |
| probe | 228.8 |
| real_test | 176.8 |
| generate | 76.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53304 |
| vmess | 13690 |
| shadowsocks | 10476 |
| trojan | 8502 |
| hysteria2 | 1205 |
| http | 575 |
| shadowsocksr | 128 |
| socks | 62 |
| hysteria | 9 |
| tuic | 4 |
| anytls | 4 |

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
| 80.82 | vless | 241.8 | 678.4 | 22.18 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 79.141.172.154 |
| 79.75 | vless | 288.0 | 710.0 | 21.11 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.224 |
| 79.4 | vless | 303.1 | 679.2 | 20.76 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.89 |
| 79.34 | vless | 297.0 | 729.1 | 20.9 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.90 |
| 79.28 | vless | 308.3 | 795.4 | 20.64 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 66.70.179.198 |
| 79.05 | vless | 318.4 | 793.2 | 20.41 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.163 |
| 78.92 | shadowsocks | 309.3 | 863.0 | 20.62 | 0.0 | 10.0 | 13.42 | 18.88 | Au1rxx-base64 | 198.98.53.130 |
| 78.74 | vless | 318.4 | 790.2 | 20.41 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.74 |
| 78.53 | vless | 340.6 | 792.8 | 19.89 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.168 |
| 78.17 | vless | 356.2 | 841.3 | 19.53 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.182 |
| 77.95 | vless | 365.6 | 912.4 | 19.31 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.95 |
| 77.94 | vless | 366.1 | 883.9 | 19.3 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.232 |
| 77.91 | vless | 367.6 | 937.8 | 19.27 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 216.152.147.28 |
| 77.87 | vless | 369.2 | 777.7 | 19.23 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.35 |
| 77.85 | vless | 370.1 | 933.5 | 19.21 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.52 |
| 77.68 | vless | 377.3 | 912.3 | 19.04 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.225 |
| 77.47 | vless | 386.4 | 1002.4 | 18.83 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.202 |
| 77.45 | vless | 384.7 | 923.6 | 18.87 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.179 |
| 77.06 | vless | 404.5 | 1034.3 | 18.42 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 209.200.246.148 |
| 76.73 | vless | 336.7 | 915.3 | 19.98 | 0.0 | 10.0 | 9.76 | 18.88 | Au1rxx-base64 | 169.40.42.223 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | 0.869 | 298 | 1650 | prefer |
| ermaozi | 0.862 | 0.88 | 25 | 250 | prefer |
| Surfboard-tg-mixed | 0.762 | 0.684 | 177 | 7303 | prefer |
| mheidari-all | 0.65 | 0.571 | 147 | 19206 | observe |
| DeltaKronecker-all | 0.557 | 1.0 | 6 | 6421 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9224 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5863 | observe |
| barry-far-vless | 0.255 | None | 0 | 6115 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1651 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| ermaozi-get_subscribe | 0.22 | 0.5 | 2 | 316 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 41 |
| cn-block | ClientOSError | - | 33 |
| 204 | TimeoutError | - | 26 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 11 |
| geo | TimeoutError | - | 11 |
| 204 | ProxyError | - | 10 |
| speed | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
