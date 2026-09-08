# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 18:32:51 |
| 运行耗时 | 755.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 90700 |
| 去重后节点 | 25007 |
| TCP 可达 | 3000 |
| 真实可用 | 492 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25007 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.7 |
| tcp | 43.0 |
| probe | 325.4 |
| real_test | 291.0 |
| generate | 89.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56476 |
| vmess | 12321 |
| shadowsocks | 10312 |
| trojan | 8866 |
| hysteria2 | 1936 |
| http | 571 |
| shadowsocksr | 129 |
| socks | 52 |
| hysteria | 16 |
| tuic | 11 |
| anytls | 10 |

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
| 82.77 | vless | 194.9 | 491.4 | 23.27 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 38.209.125.45 |
| 82.6 | vless | 202.2 | 493.7 | 23.1 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 172.235.43.210 |
| 82.58 | vless | 202.9 | 507.5 | 23.08 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 172.235.38.85 |
| 82.34 | vless | 213.2 | 487.9 | 22.84 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 172.233.139.46 |
| 82.06 | hysteria2 | 232.6 | 540.4 | 22.39 | 0.0 | 10.0 | 11.11 | 19.58 | Au1rxx-base64 | 66.94.121.46 |
| 81.49 | vless | 249.9 | 623.3 | 21.99 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 38.244.20.160 |
| 80.72 | vless | 240.0 | 600.0 | 22.22 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 38.246.229.58 |
| 80.35 | shadowsocks | 254.2 | 599.9 | 21.89 | 0.0 | 10.0 | 13.38 | 19.58 | Au1rxx-base64 | 108.181.0.177 |
| 76.63 | vless | 233.0 | 489.2 | 22.38 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 104.18.47.113 |
| 75.35 | vless | 299.2 | 725.7 | 20.85 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 5.253.38.67 |
| 75.34 | http | 411.8 | 1147.1 | 18.25 | 0.0 | 10.0 | 12.83 | 17.26 | ermaozi | 138.199.35.216 |
| 75.25 | http | 415.3 | 1153.0 | 18.16 | 0.0 | 10.0 | 12.83 | 17.26 | ermaozi | 138.199.35.198 |
| 75.13 | vless | 287.4 | 468.9 | 21.13 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 162.159.43.187 |
| 75.0 | vless | 311.6 | 465.4 | 20.56 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 162.159.24.131 |
| 74.68 | shadowsocks | 309.5 | 778.7 | 20.61 | 0.0 | 10.0 | 13.38 | 15.66 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.58 | vless | 265.9 | 501.2 | 21.62 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 172.64.154.8 |
| 74.06 | vless | 290.0 | 416.2 | 21.06 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 162.159.45.19 |
| 73.89 | vless | 297.5 | 559.0 | 20.89 | 0.0 | 10.0 | 9.92 | 19.58 | Au1rxx-base64 | 172.64.158.146 |
| 73.42 | vless | 346.2 | 350.4 | 19.76 | 1.86 | 9.87 | 9.92 | 19.58 | Au1rxx-base64 | 13.230.222.139 |
| 73.35 | vless | 349.6 | 347.2 | 19.68 | 1.98 | 9.85 | 9.92 | 19.58 | Au1rxx-base64 | 13.231.19.51 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | 0.884 | 302 | 1657 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.707 | 140 | 7545 | prefer |
| ermaozi | 0.711 | 0.706 | 34 | 409 | prefer |
| mheidari-all | 0.585 | 0.505 | 194 | 21346 | observe |
| DeltaKronecker-all | 0.391 | 1.0 | 2 | 6097 | observe |
| tg-oneclickvpnkeys | 0.264 | 1.0 | 1 | 224 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7932 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9081 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6277 | observe |
| barry-far-vless | 0.255 | None | 0 | 6498 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 41 |
| 204 | TimeoutError | - | 40 |
| geo | ClientOSError | - | 35 |
| 204 | ProxyError | - | 21 |
| cn-block | TimeoutError | - | 21 |
| speed | TimeoutError | - | 7 |
| speed | ClientOSError | - | 7 |
| geo | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
