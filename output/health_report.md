# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 17:07:41 |
| 运行耗时 | 511.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 97082 |
| 去重后节点 | 26416 |
| TCP 可达 | 3000 |
| 真实可用 | 396 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26416 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.5 |
| tcp | 43.2 |
| probe | 218.6 |
| real_test | 163.2 |
| generate | 78.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59642 |
| vmess | 14750 |
| shadowsocks | 11244 |
| trojan | 9033 |
| hysteria2 | 1568 |
| http | 551 |
| shadowsocksr | 173 |
| socks | 74 |
| anytls | 22 |
| hysteria | 18 |
| tuic | 7 |

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
| 77.48 | shadowsocks | 307.5 | 832.5 | 20.66 | 0.0 | 8.33 | 13.61 | 18.88 | Au1rxx-base64 | 198.98.53.130 |
| 76.42 | shadowsocks | 270.7 | 720.2 | 21.51 | 0.0 | 10.0 | 13.61 | 15.3 | Surfboard-tg-mixed | 37.19.198.243 |
| 76.0 | shadowsocks | 349.8 | 894.7 | 19.68 | 0.0 | 8.33 | 13.61 | 18.88 | Au1rxx-base64 | 38.180.135.156 |
| 75.36 | vless | 371.1 | 936.0 | 19.19 | 0.0 | 8.37 | 8.92 | 18.88 | Au1rxx-base64 | 23.132.28.51 |
| 75.3 | vless | 298.3 | 764.0 | 20.87 | 0.0 | 8.34 | 8.92 | 18.88 | Au1rxx-base64 | 169.40.42.95 |
| 75.24 | vless | 376.7 | 995.5 | 19.06 | 0.0 | 8.38 | 8.92 | 18.88 | Au1rxx-base64 | 185.95.231.156 |
| 74.94 | vless | 337.2 | 814.8 | 19.97 | 0.0 | 8.36 | 8.92 | 18.88 | Au1rxx-base64 | 195.211.98.43 |
| 74.72 | vless | 370.6 | 933.7 | 19.2 | 0.0 | 8.37 | 8.92 | 18.88 | Au1rxx-base64 | 66.70.179.198 |
| 74.11 | vless | 427.3 | 1152.8 | 17.89 | 0.0 | 8.42 | 8.92 | 18.88 | Au1rxx-base64 | 185.95.231.233 |
| 74.03 | vless | 244.8 | 620.4 | 22.11 | 0.0 | 10.0 | 8.92 | 18.88 | Au1rxx-base64 | 195.123.235.177 |
| 73.29 | vless | 459.3 | 1124.2 | 17.15 | 0.0 | 8.34 | 8.92 | 18.88 | Au1rxx-base64 | 169.40.42.89 |
| 73.06 | shadowsocks | 294.7 | 680.1 | 20.96 | 0.0 | 10.0 | 13.61 | 15.3 | Surfboard-tg-mixed | 156.146.38.169 |
| 72.98 | vless | 279.8 | 732.3 | 21.3 | 0.0 | 8.38 | 8.92 | 18.88 | Au1rxx-base64 | 162.35.96.21 |
| 72.95 | vless | 280.9 | 747.1 | 21.27 | 0.0 | 8.38 | 8.92 | 18.88 | Au1rxx-base64 | 162.35.96.22 |
| 72.83 | vless | 286.4 | 753.6 | 21.15 | 0.0 | 8.38 | 8.92 | 18.88 | Au1rxx-base64 | 162.35.96.15 |
| 72.75 | vless | 487.2 | 1284.4 | 16.5 | 0.0 | 8.45 | 8.92 | 18.88 | Au1rxx-base64 | 169.40.42.184 |
| 72.61 | shadowsocks | 281.7 | 650.6 | 21.26 | 0.0 | 8.43 | 13.61 | 18.88 | Au1rxx-base64 | 156.146.38.167 |
| 72.49 | vless | 496.7 | 1231.3 | 16.28 | 0.0 | 8.41 | 8.92 | 18.88 | Au1rxx-base64 | 169.40.42.16 |
| 72.24 | hysteria2 | 398.8 | 746.6 | 18.55 | 0.0 | 8.31 | 13.33 | 18.88 | Au1rxx-base64 | 45.192.12.93 |
| 72.2 | vless | 458.1 | 1127.1 | 17.17 | 0.0 | 8.56 | 8.92 | 18.88 | Au1rxx-base64 | 209.200.246.148 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.922 | 257 | 1697 | prefer |
| mheidari-all | 0.826 | 0.754 | 65 | 22258 | prefer |
| Surfboard-tg-mixed | 0.815 | 0.739 | 111 | 7421 | prefer |
| ermaozi | 0.679 | 0.676 | 34 | 298 | observe |
| tg-oneclickvpnkeys | 0.315 | 1.0 | 2 | 85 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 5845 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7498 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9120 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5991 | observe |
| barry-far-vless | 0.255 | None | 0 | 5901 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4305 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ermaozi-get_subscribe | 0.252 | 0.5 | 4 | 304 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 17 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 13 |
| 204 | ClientOSError | - | 6 |
| geo | TimeoutError | - | 6 |
| speed | TimeoutError | - | 4 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
