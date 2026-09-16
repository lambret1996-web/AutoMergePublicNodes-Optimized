# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 00:41:27 |
| 运行耗时 | 1101.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85453 |
| 去重后节点 | 23177 |
| TCP 可达 | 3000 |
| 真实可用 | 638 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23177 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 37.9 |
| probe | 404.5 |
| real_test | 569.8 |
| generate | 80.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52710 |
| vmess | 12675 |
| shadowsocks | 9628 |
| trojan | 8308 |
| hysteria2 | 1297 |
| http | 624 |
| shadowsocksr | 123 |
| socks | 70 |
| hysteria | 11 |
| tuic | 5 |
| anytls | 2 |

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
| 83.3 | vless | 204.1 | 525.8 | 23.05 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 45.149.172.74 |
| 82.74 | vless | 228.5 | 596.8 | 22.49 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 45.149.172.80 |
| 82.55 | hysteria2 | 256.6 | 724.7 | 21.84 | 0.0 | 10.0 | 12.75 | 18.96 | Au1rxx-base64 | 107.175.219.48 |
| 82.46 | vless | 227.6 | 589.4 | 22.51 | 0.0 | 10.0 | 11.29 | 18.66 | DeltaKronecker-all | 172.233.139.46 |
| 81.36 | shadowsocks | 196.1 | 474.1 | 23.24 | 0.0 | 10.0 | 13.66 | 18.96 | Au1rxx-base64 | 108.181.0.177 |
| 80.88 | vless | 308.8 | 804.0 | 20.63 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 15.204.97.216 |
| 80.85 | shadowsocks | 239.6 | 539.7 | 22.23 | 0.0 | 10.0 | 13.66 | 18.96 | Au1rxx-base64 | 173.244.56.6 |
| 80.63 | shadowsocks | 242.3 | 549.6 | 22.17 | 0.0 | 10.0 | 13.66 | 18.96 | Au1rxx-base64 | 173.244.56.9 |
| 80.31 | vless | 203.8 | 513.9 | 23.06 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 192.3.247.109 |
| 79.4 | shadowsocks | 280.9 | 776.5 | 21.28 | 0.0 | 10.0 | 13.66 | 18.96 | Au1rxx-base64 | 192.3.247.109 |
| 78.98 | vless | 174.9 | 478.0 | 23.73 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 31.58.50.200 |
| 78.5 | vless | 195.8 | 487.2 | 23.25 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 172.235.38.85 |
| 78.33 | shadowsocks | 196.3 | 479.2 | 23.23 | 0.0 | 10.0 | 13.66 | 15.94 | mheidari-all | 108.181.118.10 |
| 78.32 | vless | 363.4 | 782.9 | 19.37 | 0.0 | 10.0 | 11.29 | 18.66 | DeltaKronecker-all | 172.67.202.235 |
| 78.17 | http | 200.7 | 501.1 | 23.13 | 0.0 | 10.0 | 12.0 | 16.04 | ermaozi | 138.199.35.210 |
| 78.08 | vless | 289.7 | 561.3 | 21.07 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 144.172.104.26 |
| 77.93 | http | 211.3 | 514.3 | 22.89 | 0.0 | 10.0 | 12.0 | 16.04 | ermaozi | 138.199.35.216 |
| 77.79 | hysteria2 | 201.2 | 511.4 | 23.12 | 0.0 | 10.0 | 12.75 | 13.92 | Surfboard-tg-mixed | 45.149.172.80 |
| 77.76 | shadowsocks | 238.8 | 574.1 | 22.25 | 0.0 | 10.0 | 13.66 | 15.94 | mheidari-all | 149.22.95.183 |
| 77.72 | vless | 207.6 | 471.0 | 22.97 | 0.0 | 10.0 | 11.29 | 18.96 | Au1rxx-base64 | 162.159.43.187 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | 0.915 | 305 | 1577 | prefer |
| Surfboard-tg-mixed | 0.863 | 0.789 | 90 | 7589 | prefer |
| ermaozi | 0.797 | 0.795 | 39 | 406 | prefer |
| mheidari-all | 0.667 | 0.588 | 119 | 16112 | observe |
| DeltaKronecker-all | 0.449 | 0.369 | 496 | 5932 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5015 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 148 | observe |
| Epodonios-all | 0.255 | None | 0 | 8039 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9195 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6098 | observe |
| barry-far-vless | 0.255 | None | 0 | 6357 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1577 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 219 |
| geo | ClientOSError | - | 58 |
| speed | TimeoutError | - | 52 |
| speed | ClientOSError | - | 38 |
| 204 | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 11 |
| 204 | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
