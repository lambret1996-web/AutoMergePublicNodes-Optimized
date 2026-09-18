# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 00:42:50 |
| 运行耗时 | 1170.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84592 |
| 去重后节点 | 23112 |
| TCP 可达 | 3000 |
| 真实可用 | 643 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23112 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 38.3 |
| probe | 422.2 |
| real_test | 622.3 |
| generate | 79.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51032 |
| vmess | 13129 |
| shadowsocks | 10145 |
| trojan | 8191 |
| hysteria2 | 1296 |
| http | 597 |
| shadowsocksr | 126 |
| socks | 64 |
| hysteria | 8 |
| tuic | 2 |
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
| 82.65 | vless | 202.4 | 506.0 | 23.09 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 45.149.172.74 |
| 82.41 | vless | 212.7 | 509.9 | 22.85 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 198.200.42.129 |
| 81.12 | hysteria2 | 239.9 | 540.4 | 22.22 | 0.0 | 10.0 | 12.75 | 18.88 | Au1rxx-base64 | 66.94.121.46 |
| 80.78 | vless | 197.0 | 489.7 | 23.22 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 45.149.172.80 |
| 80.75 | shadowsocks | 214.4 | 546.0 | 22.81 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 173.244.56.9 |
| 80.22 | shadowsocks | 237.5 | 569.8 | 22.28 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 173.244.56.6 |
| 79.96 | shadowsocks | 227.2 | 607.4 | 22.52 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 108.181.0.177 |
| 79.67 | shadowsocks | 239.5 | 596.0 | 22.23 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 108.181.118.10 |
| 78.96 | shadowsocks | 262.9 | 641.8 | 21.69 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 156.146.38.170 |
| 78.58 | shadowsocks | 289.7 | 723.3 | 21.07 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 156.146.38.169 |
| 77.4 | hysteria2 | 331.0 | 726.8 | 20.12 | 0.0 | 10.0 | 12.75 | 18.88 | Au1rxx-base64 | 159.223.157.129 |
| 77.03 | vless | 251.0 | 507.0 | 21.97 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 104.18.34.14 |
| 76.76 | vless | 361.2 | 865.4 | 19.42 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 15.204.97.216 |
| 76.3 | vless | 293.4 | 463.6 | 20.99 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 172.64.53.55 |
| 75.06 | shadowsocks | 280.6 | 586.8 | 21.28 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 149.22.95.183 |
| 74.03 | http | 198.3 | 505.9 | 23.19 | 0.0 | 10.0 | 9.62 | 14.22 | ermaozi | 138.199.35.198 |
| 73.8 | shadowsocks | 252.7 | 613.0 | 21.93 | 0.0 | 10.0 | 13.06 | 13.66 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.79 | vless | 293.5 | 568.5 | 20.98 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 162.159.39.218 |
| 73.34 | vless | 381.1 | 799.4 | 18.96 | 0.0 | 10.0 | 10.68 | 18.88 | Au1rxx-base64 | 47.253.226.114 |
| 72.97 | shadowsocks | 342.6 | 729.8 | 19.85 | 0.0 | 10.0 | 13.06 | 18.88 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | 0.9 | 290 | 1671 | prefer |
| ermaozi | 0.742 | 0.742 | 31 | 357 | prefer |
| Surfboard-tg-mixed | 0.656 | 0.576 | 229 | 7509 | observe |
| mheidari-all | 0.535 | 0.455 | 99 | 16000 | observe |
| DeltaKronecker-all | 0.439 | 0.358 | 497 | 5931 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4261 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7969 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8923 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5961 | observe |
| barry-far-vless | 0.255 | None | 0 | 6183 | observe |
| ermaozi-get_subscribe | 0.254 | 0.5 | 4 | 361 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1671 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 221 |
| speed | ClientOSError | - | 81 |
| geo | ClientOSError | - | 81 |
| speed | TimeoutError | - | 64 |
| 204 | ProxyError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
