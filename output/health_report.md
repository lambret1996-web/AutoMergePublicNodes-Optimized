# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 16:58:28 |
| 运行耗时 | 664.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96596 |
| 去重后节点 | 26903 |
| TCP 可达 | 3000 |
| 真实可用 | 361 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26903 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 46.0 |
| probe | 267.1 |
| real_test | 260.0 |
| generate | 85.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57438 |
| vmess | 17061 |
| shadowsocks | 11923 |
| trojan | 8548 |
| hysteria2 | 1255 |
| shadowsocksr | 161 |
| http | 110 |
| socks | 56 |
| anytls | 21 |
| hysteria | 17 |
| tuic | 6 |

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
| 81.54 | hysteria2 | 288.1 | 712.5 | 21.11 | 0.0 | 8.89 | 14.0 | 19.04 | Au1rxx-base64 | 129.213.91.185 |
| 80.09 | shadowsocks | 235.2 | 616.7 | 22.33 | 0.0 | 8.88 | 13.84 | 19.04 | Au1rxx-base64 | 156.146.38.170 |
| 79.43 | shadowsocks | 264.4 | 712.4 | 21.66 | 0.0 | 8.89 | 13.84 | 19.04 | Au1rxx-base64 | 156.146.38.169 |
| 78.84 | shadowsocks | 255.7 | 559.3 | 21.86 | 0.0 | 10.0 | 13.84 | 19.04 | Au1rxx-base64 | 173.244.56.6 |
| 76.59 | vless | 284.6 | 642.5 | 21.19 | 0.0 | 10.0 | 8.23 | 19.04 | Au1rxx-base64 | 45.63.53.81 |
| 75.27 | shadowsocks | 320.4 | 749.1 | 20.36 | 0.0 | 8.88 | 13.84 | 19.04 | Au1rxx-base64 | 37.19.198.160 |
| 75.2 | hysteria2 | 426.6 | 795.2 | 17.9 | 0.0 | 9.8 | 14.0 | 19.04 | Au1rxx-base64 | 66.94.121.46 |
| 75.17 | shadowsocks | 312.9 | 722.9 | 20.53 | 0.0 | 8.89 | 13.84 | 19.04 | Au1rxx-base64 | 37.19.198.243 |
| 74.25 | vless | 301.7 | 648.6 | 20.79 | 0.0 | 10.0 | 8.23 | 19.04 | Au1rxx-base64 | 172.245.253.16 |
| 73.72 | vless | 298.2 | 648.1 | 20.87 | 0.0 | 10.0 | 8.23 | 19.04 | Au1rxx-base64 | 23.94.251.190 |
| 73.6 | vless | 343.2 | 751.7 | 19.83 | 0.0 | 10.0 | 8.23 | 19.04 | Au1rxx-base64 | 5.34.178.120 |
| 73.37 | shadowsocks | 321.4 | 322.3 | 20.34 | 2.92 | 8.86 | 13.84 | 19.04 | Au1rxx-base64 | 149.22.87.241 |
| 73.34 | shadowsocks | 375.3 | 983.4 | 19.09 | 0.0 | 8.87 | 13.84 | 19.04 | Au1rxx-base64 | 185.215.132.9 |
| 72.9 | shadowsocks | 234.9 | 596.5 | 22.34 | 0.0 | 10.0 | 13.84 | 10.72 | mheidari-all | 156.146.38.168 |
| 72.69 | shadowsocks | 328.0 | 655.0 | 20.18 | 0.0 | 8.87 | 13.84 | 19.04 | Au1rxx-base64 | 149.22.95.183 |
| 72.54 | shadowsocks | 316.0 | 743.2 | 20.46 | 0.0 | 8.87 | 13.84 | 19.04 | Au1rxx-base64 | 185.230.230.18 |
| 72.08 | shadowsocks | 330.6 | 770.2 | 20.13 | 0.0 | 10.0 | 13.84 | 19.04 | Au1rxx-base64 | 37.19.198.244 |
| 71.8 | vless | 280.6 | 571.9 | 21.28 | 0.0 | 8.91 | 8.23 | 19.04 | Au1rxx-base64 | 195.123.240.65 |
| 71.54 | vless | 367.9 | 777.4 | 19.26 | 0.0 | 10.0 | 8.23 | 19.04 | Au1rxx-base64 | 167.17.69.171 |
| 71.02 | hysteria2 | 299.9 | 707.8 | 20.83 | 0.0 | 3.2 | 14.0 | 19.04 | Au1rxx-base64 | clash2.deep-links.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.841 | 0.781 | 237 | 1568 | prefer |
| mheidari-all | 0.818 | 0.746 | 63 | 24102 | prefer |
| DeltaKronecker-all | 0.638 | 0.559 | 145 | 4067 | observe |
| Surfboard-tg-mixed | 0.603 | 0.524 | 63 | 7070 | observe |
| zhangkai | 0.518 | 0.519 | 27 | 31 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| Epodonios-all | 0.255 | None | 0 | 7559 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10165 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5554 | observe |
| barry-far-vless | 0.255 | None | 0 | 5768 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1568 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 38 |
| 204 | ProxyError | - | 35 |
| cn-block | TimeoutError | - | 34 |
| geo | ClientOSError | - | 19 |
| geo | TimeoutError | - | 18 |
| speed | TimeoutError | - | 18 |
| speed | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
