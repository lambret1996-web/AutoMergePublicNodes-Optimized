# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 12:29:34 |
| 运行耗时 | 542.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 88011 |
| 去重后节点 | 25187 |
| TCP 可达 | 3000 |
| 真实可用 | 493 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25187 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 41.9 |
| probe | 206.2 |
| real_test | 192.1 |
| generate | 96.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52735 |
| vmess | 13851 |
| shadowsocks | 10575 |
| trojan | 8711 |
| hysteria2 | 1272 |
| http | 656 |
| shadowsocksr | 127 |
| socks | 67 |
| hysteria | 9 |
| tuic | 4 |
| anytls | 4 |

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
| 80.38 | shadowsocks | 243.1 | 614.4 | 22.15 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 156.146.38.169 |
| 80.17 | shadowsocks | 252.4 | 626.4 | 21.94 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 156.146.38.167 |
| 80.03 | shadowsocks | 258.3 | 636.1 | 21.8 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 156.146.38.170 |
| 79.84 | shadowsocks | 249.4 | 618.2 | 22.0 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 156.146.38.168 |
| 78.9 | vless | 283.9 | 708.0 | 21.21 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 79.141.172.154 |
| 78.65 | shadowsocks | 291.3 | 708.7 | 21.03 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 37.19.198.236 |
| 78.57 | vless | 297.8 | 744.0 | 20.88 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 216.152.147.28 |
| 78.08 | shadowsocks | 299.1 | 716.5 | 20.85 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 37.19.198.160 |
| 78.05 | vless | 320.3 | 740.6 | 20.36 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 198.251.78.29 |
| 77.81 | hysteria2 | 297.4 | 658.2 | 20.89 | 0.0 | 10.0 | 13.33 | 18.68 | Au1rxx-base64 | 66.94.121.46 |
| 76.97 | shadowsocks | 298.9 | 717.6 | 20.86 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 37.19.198.243 |
| 75.38 | shadowsocks | 351.1 | 924.9 | 19.65 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 75.12 | vless | 338.1 | 784.7 | 19.95 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 169.40.42.184 |
| 75.09 | shadowsocks | 298.3 | 624.1 | 20.87 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 149.22.95.183 |
| 74.38 | shadowsocks | 300.8 | 612.0 | 20.82 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 173.244.56.9 |
| 74.32 | hysteria2 | 348.1 | 869.7 | 19.72 | 0.0 | 10.0 | 13.33 | 12.5 | mheidari-all | 159.223.157.129 |
| 74.05 | vless | 357.1 | 794.9 | 19.51 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 169.40.42.173 |
| 73.7 | vless | 341.2 | 802.7 | 19.88 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 169.40.42.133 |
| 73.63 | shadowsocks | 314.1 | 733.2 | 20.51 | 0.0 | 10.0 | 13.55 | 18.68 | Au1rxx-base64 | 108.181.57.93 |
| 73.27 | vless | 386.2 | 934.5 | 18.84 | 0.0 | 10.0 | 9.01 | 18.68 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | 0.884 | 327 | 1571 | prefer |
| ermaozi | 0.75 | 0.745 | 51 | 358 | prefer |
| Surfboard-tg-mixed | 0.671 | 0.592 | 213 | 7474 | observe |
| mheidari-all | 0.492 | 0.41 | 83 | 19088 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| roosterkid-openproxylist-v2ray | 0.317 | 1.0 | 2 | 150 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 387 | observe |
| DeltaKronecker-all | 0.263 | 0.25 | 8 | 6421 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7699 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9271 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6006 | observe |
| barry-far-vless | 0.255 | None | 0 | 5996 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1571 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 47 |
| cn-block | ClientOSError | - | 34 |
| 204 | TimeoutError | - | 22 |
| 204 | ProxyError | - | 20 |
| geo | TimeoutError | - | 19 |
| speed | ClientOSError | - | 16 |
| speed | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 13 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
