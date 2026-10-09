# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 18:18:08 |
| 运行耗时 | 761.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98340 |
| 去重后节点 | 27594 |
| TCP 可达 | 3000 |
| 真实可用 | 426 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27594 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.4 |
| tcp | 47.8 |
| probe | 300.3 |
| real_test | 317.3 |
| generate | 89.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57745 |
| vmess | 15603 |
| shadowsocks | 11950 |
| trojan | 10821 |
| hysteria2 | 1473 |
| http | 437 |
| shadowsocksr | 170 |
| socks | 81 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 13 |

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
| 83.09 | hysteria2 | 284.4 | 713.8 | 21.19 | 0.0 | 10.0 | 14.44 | 19.5 | Au1rxx-base64 | 129.213.91.185 |
| 81.09 | shadowsocks | 246.6 | 613.0 | 22.07 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 156.146.38.169 |
| 80.95 | shadowsocks | 246.3 | 631.3 | 22.08 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 156.146.38.167 |
| 80.72 | shadowsocks | 262.4 | 636.8 | 21.7 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 156.146.38.170 |
| 79.21 | hysteria2 | 306.5 | 326.1 | 20.68 | 2.77 | 9.54 | 14.44 | 19.5 | Au1rxx-base64 | 158.101.148.79 |
| 79.01 | shadowsocks | 304.2 | 743.4 | 20.74 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 37.19.198.160 |
| 78.15 | shadowsocks | 304.6 | 736.2 | 20.73 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 37.19.198.243 |
| 78.12 | shadowsocks | 309.7 | 742.5 | 20.61 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 37.19.198.236 |
| 77.68 | shadowsocks | 303.5 | 750.8 | 20.75 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 37.19.198.244 |
| 77.18 | hysteria2 | 307.6 | 347.6 | 20.66 | 1.97 | 8.38 | 14.44 | 19.5 | Au1rxx-base64 | open.2ml.bid |
| 76.42 | shadowsocks | 376.6 | 949.7 | 19.06 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 15.204.233.41 |
| 75.76 | shadowsocks | 305.3 | 648.4 | 20.71 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 149.22.95.183 |
| 75.12 | shadowsocks | 340.7 | 779.8 | 19.89 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 5.78.51.123 |
| 73.56 | shadowsocks | 325.4 | 665.2 | 20.24 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 173.244.56.6 |
| 73.38 | shadowsocks | 335.2 | 331.4 | 20.02 | 2.57 | 9.57 | 13.52 | 19.5 | Au1rxx-base64 | 149.22.87.204 |
| 73.36 | shadowsocks | 344.8 | 659.9 | 19.8 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 173.244.56.9 |
| 73.23 | hysteria2 | 456.1 | 676.9 | 17.22 | 0.0 | 9.69 | 14.44 | 19.5 | Au1rxx-base64 | 62.210.124.146 |
| 73.22 | vless | 270.8 | 542.5 | 21.51 | 0.0 | 10.0 | 6.08 | 19.5 | Au1rxx-base64 | 47.251.108.158 |
| 72.98 | vless | 332.5 | 749.4 | 20.08 | 0.0 | 10.0 | 6.08 | 19.5 | Au1rxx-base64 | 159.89.87.21 |
| 72.76 | shadowsocks | 415.8 | 1001.4 | 18.15 | 0.0 | 10.0 | 13.52 | 19.5 | Au1rxx-base64 | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.945 | 0.873 | 347 | 1840 | prefer |
| mheidari-all | 0.894 | 0.829 | 41 | 23183 | prefer |
| Surfboard-tg-mixed | 0.605 | 0.525 | 99 | 7121 | observe |
| DeltaKronecker-all | 0.418 | 0.375 | 16 | 5154 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7589 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10106 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |
| barry-far-vless | 0.255 | None | 0 | 5819 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1840 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 43 |
| 204 | TimeoutError | - | 38 |
| cn-block | TimeoutError | - | 21 |
| geo | ClientOSError | - | 11 |
| speed | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| geo | TimeoutError | - | 5 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
