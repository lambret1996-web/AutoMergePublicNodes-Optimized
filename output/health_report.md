# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 18:27:56 |
| 运行耗时 | 593.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83333 |
| 去重后节点 | 23378 |
| TCP 可达 | 3000 |
| 真实可用 | 465 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23378 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 38.0 |
| probe | 259.6 |
| real_test | 204.5 |
| generate | 83.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50020 |
| vmess | 13354 |
| shadowsocks | 9877 |
| trojan | 8255 |
| hysteria2 | 1047 |
| http | 577 |
| shadowsocksr | 115 |
| socks | 73 |
| hysteria | 11 |
| tuic | 3 |
| anytls | 1 |

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
| 82.33 | vless | 248.3 | 653.5 | 22.03 | 0.0 | 9.78 | 10.68 | 19.84 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 82.24 | vless | 261.6 | 690.7 | 21.72 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 79.141.172.154 |
| 81.77 | vless | 282.0 | 746.0 | 21.25 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.232 |
| 81.45 | vless | 296.0 | 669.7 | 20.93 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.15 |
| 81.39 | vless | 298.6 | 666.5 | 20.87 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.163 |
| 81.34 | vless | 300.4 | 774.9 | 20.82 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 66.70.179.198 |
| 81.14 | vless | 309.2 | 825.7 | 20.62 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.223 |
| 80.98 | shadowsocks | 267.9 | 745.5 | 21.58 | 0.0 | 10.0 | 13.56 | 19.84 | Au1rxx-base64 | 37.19.198.236 |
| 80.94 | shadowsocks | 269.3 | 746.4 | 21.54 | 0.0 | 10.0 | 13.56 | 19.84 | Au1rxx-base64 | 37.19.198.160 |
| 80.69 | shadowsocks | 280.3 | 784.5 | 21.29 | 0.0 | 10.0 | 13.56 | 19.84 | Au1rxx-base64 | 37.19.198.244 |
| 80.57 | vless | 334.0 | 846.5 | 20.05 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.89 |
| 80.48 | vless | 294.4 | 733.2 | 20.96 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 195.211.98.43 |
| 80.43 | vless | 338.8 | 919.7 | 19.94 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.90 |
| 80.39 | vless | 341.7 | 912.5 | 19.87 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.95 |
| 80.35 | hysteria2 | 283.8 | 782.5 | 21.21 | 0.0 | 10.0 | 13.5 | 16.74 | mheidari-all | 159.223.157.129 |
| 80.34 | vless | 292.7 | 703.6 | 21.0 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 167.17.69.171 |
| 80.24 | vless | 333.2 | 847.3 | 20.07 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.202 |
| 80.23 | vless | 348.6 | 970.6 | 19.71 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 185.95.231.156 |
| 80.09 | vless | 272.0 | 724.4 | 21.48 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.212 |
| 79.82 | vless | 366.2 | 862.7 | 19.3 | 0.0 | 10.0 | 10.68 | 19.84 | Au1rxx-base64 | 169.40.42.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.923 | 0.864 | 286 | 1556 | prefer |
| ermaozi | 0.87 | 0.885 | 26 | 314 | prefer |
| DeltaKronecker-all | 0.777 | 0.71 | 31 | 6092 | prefer |
| mheidari-all | 0.775 | 0.702 | 57 | 15889 | prefer |
| Surfboard-tg-mixed | 0.682 | 0.603 | 214 | 7161 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 59 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7593 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9013 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5710 | observe |
| barry-far-vless | 0.255 | None | 0 | 5918 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1556 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 40 |
| geo | ClientOSError | - | 31 |
| geo | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 19 |
| cn-block | ClientOSError | - | 15 |
| 204 | ProxyError | - | 12 |
| speed | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 6 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
