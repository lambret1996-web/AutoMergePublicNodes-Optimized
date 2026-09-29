# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 05:41:35 |
| 运行耗时 | 840.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96798 |
| 去重后节点 | 27003 |
| TCP 可达 | 3000 |
| 真实可用 | 550 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27003 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.7 |
| tcp | 44.7 |
| probe | 299.3 |
| real_test | 413.5 |
| generate | 75.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59486 |
| vmess | 14856 |
| shadowsocks | 11297 |
| trojan | 8877 |
| hysteria2 | 1344 |
| http | 643 |
| shadowsocksr | 170 |
| socks | 78 |
| anytls | 24 |
| hysteria | 15 |
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
| 81.88 | shadowsocks | 251.0 | 624.3 | 21.97 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 156.146.38.170 |
| 81.88 | shadowsocks | 251.0 | 617.0 | 21.97 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 156.146.38.169 |
| 81.79 | vless | 290.1 | 733.2 | 21.06 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 47.90.153.88 |
| 81.49 | vless | 303.0 | 743.6 | 20.76 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 169.40.42.35 |
| 81.48 | vless | 291.8 | 691.9 | 21.02 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 159.89.87.21 |
| 81.08 | shadowsocks | 285.3 | 735.1 | 21.17 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 37.19.198.244 |
| 80.69 | shadowsocks | 259.0 | 645.5 | 21.78 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 156.146.38.167 |
| 80.61 | vless | 322.4 | 740.1 | 20.32 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 169.40.42.89 |
| 80.5 | vless | 308.9 | 751.8 | 20.63 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 66.70.179.198 |
| 80.5 | vless | 345.8 | 868.7 | 19.77 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 169.40.42.202 |
| 80.42 | vless | 339.5 | 790.5 | 19.92 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 169.40.42.212 |
| 80.35 | hysteria2 | 257.0 | 558.6 | 21.83 | 0.0 | 9.03 | 14.42 | 18.72 | Au1rxx-base64 | 192.255.128.123 |
| 80.33 | shadowsocks | 257.0 | 646.0 | 21.83 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 156.146.38.168 |
| 79.91 | shadowsocks | 335.8 | 888.9 | 20.0 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 37.19.198.243 |
| 79.88 | vless | 372.9 | 829.1 | 19.15 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 169.40.42.16 |
| 79.87 | vless | 341.3 | 859.1 | 19.88 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 169.40.42.224 |
| 79.64 | shadowsocks | 276.5 | 686.7 | 21.38 | 0.0 | 10.0 | 14.07 | 19.84 | Surfboard-tg-mixed | 140.82.63.79 |
| 79.59 | vless | 390.6 | 780.0 | 18.74 | 0.0 | 10.0 | 12.01 | 19.84 | Surfboard-tg-mixed | 104.21.88.201 |
| 79.49 | shadowsocks | 280.6 | 722.7 | 21.28 | 0.0 | 10.0 | 14.07 | 18.14 | mheidari-all | 37.19.198.236 |
| 79.2 | vless | 383.0 | 1006.6 | 18.91 | 0.0 | 10.0 | 12.01 | 18.72 | Au1rxx-base64 | 185.95.231.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.875 | 0.812 | 351 | 1609 | prefer |
| Surfboard-tg-mixed | 0.79 | 0.712 | 208 | 7005 | prefer |
| ermaozi | 0.757 | 0.758 | 33 | 354 | prefer |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 5428 | observe |
| mheidari-all | 0.332 | 0.251 | 327 | 22589 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| ermaozi-get_subscribe | 0.308 | 0.6 | 5 | 367 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 121 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9567 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5633 | observe |
| barry-far-vless | 0.255 | None | 0 | 6028 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4237 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 131 |
| speed | TimeoutError | - | 74 |
| speed | ClientOSError | - | 70 |
| geo | ClientOSError | - | 49 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
