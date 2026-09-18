# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 18:31:22 |
| 运行耗时 | 739.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 86644 |
| 去重后节点 | 25073 |
| TCP 可达 | 3000 |
| 真实可用 | 416 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25073 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 16.6 |
| geo | 1.5 |
| tcp | 41.4 |
| probe | 327.3 |
| real_test | 259.6 |
| generate | 92.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51754 |
| vmess | 13643 |
| shadowsocks | 10526 |
| trojan | 8568 |
| hysteria2 | 1340 |
| http | 588 |
| shadowsocksr | 128 |
| socks | 73 |
| anytls | 11 |
| hysteria | 10 |
| tuic | 3 |

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
| 81.24 | hysteria2 | 280.7 | 613.9 | 21.28 | 0.0 | 10.0 | 14.21 | 18.28 | Au1rxx-base64 | 66.94.121.46 |
| 80.78 | shadowsocks | 265.3 | 536.5 | 21.64 | 0.0 | 10.0 | 13.76 | 19.38 | mheidari-all | 173.244.56.9 |
| 80.22 | shadowsocks | 289.4 | 740.8 | 21.08 | 0.0 | 10.0 | 13.76 | 19.38 | mheidari-all | 173.244.56.6 |
| 79.82 | vless | 223.5 | 590.2 | 22.6 | 0.0 | 10.0 | 8.94 | 18.28 | Au1rxx-base64 | 172.235.43.210 |
| 79.3 | hysteria2 | 250.8 | 468.4 | 21.97 | 0.0 | 10.0 | 14.21 | 19.38 | mheidari-all | 45.149.172.80 |
| 78.32 | hysteria2 | 330.0 | 736.1 | 20.14 | 0.0 | 10.0 | 14.21 | 18.28 | Au1rxx-base64 | 159.223.157.129 |
| 78.27 | hysteria2 | 242.1 | 465.0 | 22.17 | 0.0 | 10.0 | 14.21 | 19.38 | mheidari-all | 45.149.172.74 |
| 76.49 | shadowsocks | 204.9 | 533.8 | 23.03 | 0.0 | 10.0 | 13.76 | 15.12 | Surfboard-tg-mixed | 108.181.118.10 |
| 76.16 | shadowsocks | 259.0 | 509.4 | 21.78 | 0.0 | 10.0 | 13.76 | 15.12 | Surfboard-tg-mixed | 108.181.0.177 |
| 76.1 | vless | 251.8 | 556.2 | 21.95 | 0.0 | 10.0 | 8.94 | 18.28 | Au1rxx-base64 | 31.58.50.200 |
| 74.94 | vless | 240.0 | 516.3 | 22.22 | 0.0 | 10.0 | 8.94 | 18.28 | Au1rxx-base64 | 104.18.46.46 |
| 74.73 | shadowsocks | 281.8 | 611.2 | 21.26 | 0.0 | 10.0 | 13.76 | 18.28 | Au1rxx-base64 | 149.22.95.183 |
| 74.67 | shadowsocks | 253.7 | 609.5 | 21.91 | 0.0 | 10.0 | 13.76 | 15.12 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.08 | vless | 334.2 | 752.8 | 20.04 | 0.0 | 10.0 | 8.94 | 18.28 | Au1rxx-base64 | 79.141.172.154 |
| 73.87 | vless | 280.2 | 635.1 | 21.29 | 0.0 | 10.0 | 8.94 | 15.12 | Surfboard-tg-mixed | 88.216.57.128 |
| 73.66 | vless | 362.4 | 870.0 | 19.39 | 0.0 | 10.0 | 8.94 | 18.28 | Au1rxx-base64 | 15.204.97.216 |
| 73.55 | http | 257.8 | 644.9 | 21.81 | 0.0 | 10.0 | 11.41 | 15.08 | ermaozi | 138.199.35.198 |
| 73.38 | shadowsocks | 296.0 | 633.8 | 20.93 | 0.0 | 10.0 | 13.76 | 15.12 | Surfboard-tg-mixed | 23.150.248.20 |
| 73.31 | http | 257.2 | 649.0 | 21.82 | 0.0 | 10.0 | 11.41 | 15.08 | ermaozi | 138.199.35.216 |
| 73.15 | shadowsocks | 358.9 | 760.9 | 19.47 | 0.0 | 10.0 | 13.76 | 19.38 | mheidari-all | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | 0.851 | 282 | 1594 | prefer |
| ermaozi | 0.828 | 0.84 | 25 | 325 | prefer |
| Surfboard-tg-mixed | 0.71 | 0.633 | 98 | 7175 | prefer |
| mheidari-all | 0.618 | 0.538 | 169 | 19611 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5076 | observe |
| Epodonios-all | 0.255 | None | 0 | 7628 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8673 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5700 | observe |
| barry-far-vless | 0.255 | None | 0 | 5915 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1594 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 43 |
| cn-block | ClientOSError | - | 28 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 22 |
| speed | ClientOSError | - | 17 |
| geo | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 14 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
