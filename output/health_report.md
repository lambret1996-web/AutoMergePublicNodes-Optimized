# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 05:22:21 |
| 运行耗时 | 1109.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98041 |
| 去重后节点 | 27746 |
| TCP 可达 | 3000 |
| 真实可用 | 534 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27746 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 46.5 |
| probe | 393.7 |
| real_test | 572.3 |
| generate | 89.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57647 |
| vmess | 15603 |
| shadowsocks | 12056 |
| trojan | 10515 |
| hysteria2 | 1416 |
| http | 480 |
| shadowsocksr | 174 |
| socks | 90 |
| anytls | 31 |
| hysteria | 17 |
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
| 80.92 | hysteria2 | 239.3 | 695.0 | 22.24 | 0.0 | 10.0 | 12.0 | 18.18 | Au1rxx-base64 | 129.213.91.185 |
| 80.46 | vless | 255.8 | 702.7 | 21.86 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 159.89.87.21 |
| 79.91 | vless | 279.2 | 704.9 | 21.31 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 66.70.179.198 |
| 79.33 | vless | 304.3 | 815.6 | 20.73 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 169.40.42.89 |
| 78.96 | vless | 262.4 | 691.2 | 21.7 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 169.40.42.231 |
| 78.69 | vless | 266.8 | 653.3 | 21.6 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 169.40.42.232 |
| 78.49 | vless | 340.8 | 886.9 | 19.89 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 2.24.124.64 |
| 78.49 | vless | 340.8 | 924.4 | 19.89 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 169.40.42.173 |
| 78.45 | shadowsocks | 253.3 | 709.5 | 21.92 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 37.19.198.236 |
| 78.42 | vless | 343.9 | 962.1 | 19.82 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 185.95.231.156 |
| 78.39 | shadowsocks | 255.8 | 715.0 | 21.86 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 37.19.198.243 |
| 78.34 | shadowsocks | 257.8 | 720.9 | 21.81 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 37.19.198.244 |
| 78.32 | shadowsocks | 258.5 | 725.2 | 21.79 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 37.19.198.160 |
| 78.31 | vless | 348.4 | 950.9 | 19.71 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 169.40.42.182 |
| 78.06 | shadowsocks | 248.4 | 648.2 | 22.03 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 140.82.63.79 |
| 77.79 | vless | 291.0 | 661.4 | 21.04 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 169.40.42.90 |
| 76.83 | vless | 345.1 | 902.6 | 19.79 | 0.0 | 10.0 | 10.42 | 16.74 | mheidari-all | 167.17.69.171 |
| 76.2 | vless | 439.7 | 1169.7 | 17.6 | 0.0 | 10.0 | 10.42 | 18.18 | Au1rxx-base64 | 209.200.246.148 |
| 75.95 | shadowsocks | 284.5 | 662.0 | 21.19 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 156.146.38.168 |
| 75.87 | shadowsocks | 278.3 | 644.5 | 21.33 | 0.0 | 10.0 | 12.35 | 18.18 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | 0.906 | 363 | 1761 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.727 | 0.656 | 32 | 7069 | prefer |
| ermaozi-get_subscribe | 0.62 | 0.6 | 50 | 607 | observe |
| DeltaKronecker-all | 0.563 | 0.562 | 16 | 5197 | observe |
| mheidari-all | 0.369 | 0.288 | 417 | 23125 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7569 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5581 | observe |
| barry-far-vless | 0.255 | None | 0 | 5823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.251 | 0.333 | 3 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 177 |
| speed | TimeoutError | - | 69 |
| geo | ClientOSError | - | 36 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
