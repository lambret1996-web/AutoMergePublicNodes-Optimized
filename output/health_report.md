# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 06:36:37 |
| 运行耗时 | 794.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90569 |
| 去重后节点 | 25507 |
| TCP 可达 | 3000 |
| 真实可用 | 512 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25507 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.5 |
| tcp | 40.8 |
| probe | 316.1 |
| real_test | 346.7 |
| generate | 83.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55889 |
| vmess | 13283 |
| shadowsocks | 10102 |
| trojan | 8541 |
| hysteria2 | 1869 |
| http | 668 |
| shadowsocksr | 124 |
| socks | 62 |
| hysteria | 14 |
| tuic | 9 |
| anytls | 8 |

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
| 76.95 | shadowsocks | 265.2 | 650.3 | 21.64 | 0.0 | 10.0 | 14.25 | 15.06 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.24 | vless | 254.1 | 632.7 | 21.9 | 0.0 | 9.23 | 5.69 | 18.42 | Au1rxx-base64 | 198.251.78.29 |
| 75.19 | shadowsocks | 261.7 | 653.8 | 21.72 | 0.0 | 10.0 | 14.25 | 15.06 | Surfboard-tg-mixed | 23.150.248.20 |
| 74.92 | vless | 267.1 | 695.1 | 21.6 | 0.0 | 9.21 | 5.69 | 18.42 | Au1rxx-base64 | 216.152.147.28 |
| 74.61 | shadowsocks | 260.0 | 639.9 | 21.76 | 0.0 | 9.18 | 14.25 | 18.42 | Au1rxx-base64 | 156.146.38.168 |
| 74.41 | vless | 288.3 | 722.7 | 21.1 | 0.0 | 9.2 | 5.69 | 18.42 | Au1rxx-base64 | 47.253.226.114 |
| 73.93 | vless | 301.2 | 720.7 | 20.8 | 0.0 | 9.32 | 5.69 | 18.42 | Au1rxx-base64 | 195.123.235.177 |
| 73.5 | shadowsocks | 296.8 | 611.7 | 20.91 | 0.0 | 9.06 | 14.25 | 18.42 | Au1rxx-base64 | 192.3.247.109 |
| 73.41 | vless | 321.0 | 657.5 | 20.35 | 0.0 | 9.2 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.133 |
| 72.37 | hysteria2 | 357.8 | 842.3 | 19.5 | 0.0 | 9.05 | 11.79 | 18.42 | Au1rxx-base64 | 107.175.219.48 |
| 72.3 | vless | 340.2 | 721.6 | 19.9 | 0.0 | 9.16 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.179 |
| 72.16 | vless | 337.8 | 833.7 | 19.96 | 0.0 | 9.15 | 5.69 | 18.42 | Au1rxx-base64 | 66.70.179.198 |
| 72.01 | vless | 356.2 | 904.9 | 19.53 | 0.0 | 9.16 | 5.69 | 18.42 | Au1rxx-base64 | 137.184.218.169 |
| 71.95 | shadowsocks | 383.5 | 947.9 | 18.9 | 0.0 | 10.0 | 14.25 | 15.06 | Surfboard-tg-mixed | 51.222.141.125 |
| 71.85 | vless | 360.6 | 748.2 | 19.43 | 0.0 | 9.2 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.74 |
| 71.74 | vless | 372.3 | 806.8 | 19.16 | 0.0 | 9.2 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.16 |
| 71.31 | vless | 377.7 | 938.3 | 19.03 | 0.0 | 9.17 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.75 |
| 71.13 | vless | 402.0 | 1022.0 | 18.47 | 0.0 | 9.17 | 5.69 | 18.42 | Au1rxx-base64 | 185.95.231.156 |
| 70.29 | vless | 364.3 | 906.2 | 19.34 | 0.0 | 9.22 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.173 |
| 70.01 | vless | 425.9 | 961.4 | 17.92 | 0.0 | 9.2 | 5.69 | 18.42 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.868 | 0.808 | 292 | 1549 | prefer |
| Surfboard-tg-mixed | 0.745 | 0.667 | 165 | 7543 | prefer |
| mheidari-all | 0.646 | 0.567 | 134 | 21540 | observe |
| ermaozi | 0.632 | 0.62 | 50 | 425 | observe |
| DeltaKronecker-all | 0.572 | 0.491 | 116 | 5972 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 133 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8044 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8973 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6114 | observe |
| barry-far-vless | 0.255 | None | 0 | 6333 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1549 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 68 |
| speed | TimeoutError | - | 34 |
| geo | ClientOSError | - | 33 |
| 204 | ProxyError | - | 29 |
| cn-block | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 23 |
| speed | ClientOSError | - | 17 |
| cn-block | ClientOSError | - | 15 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
