# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 00:44:23 |
| 运行耗时 | 1182.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94116 |
| 去重后节点 | 25341 |
| TCP 可达 | 3000 |
| 真实可用 | 670 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25341 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.4 |
| tcp | 42.7 |
| probe | 389.5 |
| real_test | 656.7 |
| generate | 84.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57471 |
| vmess | 13645 |
| shadowsocks | 11038 |
| trojan | 8934 |
| hysteria2 | 2189 |
| http | 613 |
| shadowsocksr | 124 |
| socks | 62 |
| hysteria | 14 |
| anytls | 14 |
| tuic | 12 |

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
| 80.83 | hysteria2 | 261.3 | 555.0 | 21.73 | 0.0 | 10.0 | 13.97 | 18.44 | Au1rxx-base64 | 66.94.121.46 |
| 80.41 | shadowsocks | 241.5 | 592.5 | 22.19 | 0.0 | 10.0 | 13.48 | 18.74 | mheidari-all | 156.146.38.170 |
| 80.16 | vless | 260.2 | 669.3 | 21.75 | 0.0 | 9.35 | 10.62 | 18.44 | Au1rxx-base64 | 216.152.147.28 |
| 79.78 | shadowsocks | 268.5 | 670.2 | 21.56 | 0.0 | 10.0 | 13.48 | 18.74 | mheidari-all | 37.19.198.243 |
| 79.67 | hysteria2 | 284.4 | 641.7 | 21.19 | 0.0 | 10.0 | 13.97 | 18.44 | Au1rxx-base64 | 159.223.157.129 |
| 79.31 | vless | 297.0 | 748.5 | 20.9 | 0.0 | 9.35 | 10.62 | 18.44 | Au1rxx-base64 | 47.253.226.114 |
| 78.3 | shadowsocks | 289.1 | 720.5 | 21.08 | 0.0 | 10.0 | 13.48 | 18.74 | mheidari-all | 156.146.38.168 |
| 78.29 | vless | 282.2 | 663.6 | 21.25 | 0.0 | 9.38 | 10.62 | 18.44 | Au1rxx-base64 | 195.123.235.177 |
| 77.93 | vless | 384.7 | 868.3 | 18.87 | 0.0 | 10.0 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.184 |
| 77.84 | vless | 377.3 | 959.4 | 19.04 | 0.0 | 10.0 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.168 |
| 77.8 | vless | 364.0 | 925.5 | 19.35 | 0.0 | 9.39 | 10.62 | 18.44 | Au1rxx-base64 | 185.95.231.156 |
| 77.72 | vless | 310.8 | 726.9 | 20.58 | 0.0 | 10.0 | 10.62 | 18.74 | mheidari-all | 2.24.124.64 |
| 77.72 | vless | 393.1 | 896.1 | 18.68 | 0.0 | 10.0 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.179 |
| 77.71 | vless | 382.1 | 974.1 | 18.93 | 0.0 | 10.0 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.15 |
| 77.6 | vless | 358.7 | 876.4 | 19.47 | 0.0 | 9.43 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.202 |
| 77.57 | vless | 348.2 | 883.4 | 19.72 | 0.0 | 9.43 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.225 |
| 77.42 | vless | 323.3 | 799.9 | 20.29 | 0.0 | 10.0 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.173 |
| 77.4 | shadowsocks | 308.0 | 795.0 | 20.65 | 0.0 | 9.33 | 13.48 | 18.44 | Au1rxx-base64 | 15.204.247.206 |
| 77.4 | vless | 402.1 | 930.6 | 18.47 | 0.0 | 10.0 | 10.62 | 18.44 | Au1rxx-base64 | 169.40.42.229 |
| 77.31 | shadowsocks | 319.2 | 808.7 | 20.39 | 0.0 | 10.0 | 13.48 | 18.44 | Au1rxx-base64 | 142.4.216.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | 0.911 | 361 | 1631 | prefer |
| Surfboard-tg-mixed | 0.915 | 0.843 | 83 | 7440 | prefer |
| DeltaKronecker-all | 0.43 | 0.348 | 264 | 5970 | observe |
| mheidari-all | 0.358 | 0.277 | 614 | 20520 | observe |
| ermaozi | 0.338 | 0.316 | 19 | 393 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 141 | observe |
| Epodonios-all | 0.255 | None | 0 | 7839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8833 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6133 | observe |
| barry-far-vless | 0.255 | None | 0 | 6210 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1631 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 228 |
| geo | ClientOSError | - | 128 |
| speed | TimeoutError | - | 110 |
| speed | ClientOSError | - | 97 |
| cn-block | ClientOSError | - | 65 |
| 204 | ProxyError | - | 17 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 6 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
