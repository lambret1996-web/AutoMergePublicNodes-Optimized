# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 06:33:38 |
| 运行耗时 | 716.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83214 |
| 去重后节点 | 22880 |
| TCP 可达 | 3000 |
| 真实可用 | 481 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22880 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.6 |
| tcp | 38.5 |
| probe | 280.9 |
| real_test | 313.3 |
| generate | 77.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49472 |
| vmess | 13207 |
| shadowsocks | 10171 |
| trojan | 8164 |
| hysteria2 | 1336 |
| http | 649 |
| shadowsocksr | 130 |
| socks | 71 |
| hysteria | 8 |
| anytls | 4 |
| tuic | 2 |

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
| 82.36 | shadowsocks | 213.2 | 544.3 | 22.84 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 173.244.56.9 |
| 82.3 | shadowsocks | 194.4 | 503.4 | 23.28 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 108.181.118.10 |
| 82.16 | hysteria2 | 253.2 | 579.3 | 21.92 | 0.0 | 10.0 | 13.75 | 19.28 | Au1rxx-base64 | 66.94.121.46 |
| 81.02 | shadowsocks | 249.8 | 634.9 | 22.0 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 108.181.0.177 |
| 80.73 | shadowsocks | 259.7 | 626.5 | 21.77 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 156.146.38.167 |
| 79.5 | vless | 193.9 | 487.0 | 23.29 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 45.149.172.80 |
| 78.73 | hysteria2 | 329.5 | 703.8 | 20.15 | 0.0 | 10.0 | 13.75 | 19.28 | Au1rxx-base64 | 159.223.157.129 |
| 78.69 | vless | 228.8 | 557.4 | 22.48 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 198.200.42.129 |
| 75.6 | shadowsocks | 267.8 | 736.7 | 21.58 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 129.146.167.237 |
| 75.33 | vless | 237.6 | 542.9 | 22.28 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 31.58.50.200 |
| 75.13 | shadowsocks | 259.6 | 636.6 | 21.77 | 0.0 | 10.0 | 14.24 | 13.12 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.79 | shadowsocks | 340.2 | 728.3 | 19.9 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 37.19.198.236 |
| 74.18 | shadowsocks | 516.1 | 1448.8 | 15.83 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 173.244.56.6 |
| 73.71 | vless | 221.0 | 504.3 | 22.66 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 172.64.158.146 |
| 73.1 | vless | 358.4 | 854.4 | 19.48 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 15.204.97.216 |
| 73.01 | vless | 279.8 | 485.5 | 21.3 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 172.64.32.108 |
| 72.71 | shadowsocks | 378.5 | 797.4 | 19.02 | 0.0 | 10.0 | 14.24 | 19.28 | Au1rxx-base64 | 108.181.57.93 |
| 72.52 | vless | 300.9 | 456.0 | 20.81 | 0.0 | 10.0 | 6.93 | 19.28 | Au1rxx-base64 | 104.21.70.21 |
| 72.17 | http | 339.9 | 935.7 | 19.91 | 0.0 | 10.0 | 10.42 | 14.84 | ermaozi | 138.199.35.201 |
| 72.15 | http | 341.0 | 934.2 | 19.89 | 0.0 | 10.0 | 10.42 | 14.84 | ermaozi | 138.199.35.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.899 | 0.838 | 297 | 1561 | prefer |
| ermaozi | 0.765 | 0.761 | 46 | 378 | prefer |
| Surfboard-tg-mixed | 0.691 | 0.612 | 209 | 7282 | observe |
| DeltaKronecker-all | 0.586 | 0.506 | 85 | 5931 | observe |
| mheidari-all | 0.519 | 0.436 | 55 | 15863 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| 10ium-ScrapeCategorize-Vless | 0.287 | 0.5 | 2 | 5076 | observe |
| Epodonios-all | 0.255 | None | 0 | 7742 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8726 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5769 | observe |
| barry-far-vless | 0.255 | None | 0 | 5988 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1561 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 70 |
| speed | TimeoutError | - | 36 |
| geo | ClientOSError | - | 30 |
| 204 | ProxyError | - | 18 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
