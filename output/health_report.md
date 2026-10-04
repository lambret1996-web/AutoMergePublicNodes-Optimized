# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 05:01:21 |
| 运行耗时 | 821.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99156 |
| 去重后节点 | 27380 |
| TCP 可达 | 3000 |
| 真实可用 | 469 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27380 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 47.7 |
| probe | 286.1 |
| real_test | 403.4 |
| generate | 75.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59947 |
| vmess | 15637 |
| shadowsocks | 11510 |
| trojan | 9602 |
| hysteria2 | 1654 |
| http | 521 |
| shadowsocksr | 166 |
| socks | 69 |
| anytls | 27 |
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
| 79.67 | shadowsocks | 243.4 | 628.7 | 22.14 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 156.146.38.169 |
| 78.86 | http | 246.9 | 554.3 | 22.06 | 0.0 | 10.0 | 13.2 | 18.12 | ermaozi | 138.199.35.198 |
| 78.79 | vless | 271.8 | 596.9 | 21.49 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 15.204.97.216 |
| 78.76 | shadowsocks | 239.5 | 615.0 | 22.23 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 156.146.38.167 |
| 78.49 | vless | 279.0 | 596.3 | 21.32 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 195.123.240.65 |
| 78.41 | vless | 265.4 | 557.1 | 21.63 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 172.233.139.46 |
| 78.32 | vless | 273.3 | 594.2 | 21.45 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 172.235.43.210 |
| 76.96 | vless | 329.4 | 748.8 | 20.15 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 107.173.237.146 |
| 76.69 | vless | 340.5 | 795.6 | 19.9 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 172.235.38.85 |
| 75.66 | shadowsocks | 268.6 | 569.3 | 21.56 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 173.244.56.6 |
| 75.35 | shadowsocks | 245.4 | 628.5 | 22.1 | 0.0 | 10.0 | 13.15 | 14.1 | mheidari-all | 156.146.38.170 |
| 75.0 | shadowsocks | 292.2 | 705.6 | 21.01 | 0.0 | 10.0 | 13.15 | 15.92 | Surfboard-tg-mixed | 5.78.51.123 |
| 74.45 | vless | 368.4 | 778.0 | 19.25 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 66.70.179.198 |
| 74.21 | hysteria2 | 324.2 | 742.7 | 20.27 | 0.0 | 10.0 | 13.24 | 14.1 | mheidari-all | 159.223.157.129 |
| 74.13 | vless | 308.7 | 665.3 | 20.63 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 38.246.229.58 |
| 73.92 | shadowsocks | 337.2 | 773.5 | 19.97 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 37.19.198.243 |
| 73.41 | vless | 343.1 | 698.2 | 19.84 | 0.0 | 10.0 | 11.63 | 18.38 | Au1rxx-base64 | 137.175.82.40 |
| 73.38 | shadowsocks | 274.5 | 587.0 | 21.42 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 173.244.56.9 |
| 73.22 | shadowsocks | 342.9 | 820.3 | 19.84 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 103.214.109.197 |
| 73.21 | shadowsocks | 325.6 | 729.4 | 20.24 | 0.0 | 10.0 | 13.15 | 18.38 | Au1rxx-base64 | 140.82.63.79 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | 0.911 | 293 | 1797 | prefer |
| ermaozi | 0.949 | 0.958 | 24 | 646 | prefer |
| Surfboard-tg-mixed | 0.849 | 0.773 | 154 | 7318 | prefer |
| ermaozi-get_subscribe | 0.331 | 1.0 | 2 | 505 | observe |
| mheidari-all | 0.291 | 0.209 | 277 | 23371 | observe |
| Epodonios-all | 0.255 | None | 0 | 7797 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9371 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6122 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4285 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1797 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 150 |
| speed | TimeoutError | - | 63 |
| geo | ClientOSError | - | 27 |
| 204 | TimeoutError | - | 19 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 10 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
