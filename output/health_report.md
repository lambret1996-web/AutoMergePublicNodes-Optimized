# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 06:34:47 |
| 运行耗时 | 732.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 86181 |
| 去重后节点 | 22674 |
| TCP 可达 | 3000 |
| 真实可用 | 550 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22674 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 38.5 |
| probe | 299.7 |
| real_test | 309.6 |
| generate | 76.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53274 |
| vmess | 12034 |
| shadowsocks | 9985 |
| trojan | 8391 |
| hysteria2 | 1638 |
| http | 638 |
| shadowsocksr | 127 |
| socks | 75 |
| hysteria | 9 |
| tuic | 8 |
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
| 80.4 | hysteria2 | 279.3 | 660.7 | 21.31 | 0.0 | 10.0 | 13.42 | 17.5 | Surfboard-tg-mixed | 159.223.157.129 |
| 79.41 | shadowsocks | 245.4 | 562.6 | 22.1 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.22 | shadowsocks | 250.5 | 647.2 | 21.98 | 0.0 | 8.38 | 13.81 | 19.44 | Au1rxx-base64 | 156.146.38.169 |
| 79.15 | shadowsocks | 256.4 | 649.1 | 21.84 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 156.146.38.170 |
| 78.44 | shadowsocks | 265.6 | 635.9 | 21.63 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.26 | vless | 306.2 | 739.2 | 20.69 | 0.0 | 8.4 | 7.77 | 19.44 | Au1rxx-base64 | 216.152.147.28 |
| 75.74 | shadowsocks | 311.0 | 734.5 | 20.58 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 37.19.198.243 |
| 73.71 | shadowsocks | 287.7 | 536.0 | 21.12 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 108.181.0.177 |
| 73.6 | shadowsocks | 302.8 | 631.0 | 20.77 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 149.22.95.183 |
| 73.39 | shadowsocks | 397.8 | 917.5 | 18.57 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 38.180.135.156 |
| 73.21 | shadowsocks | 369.6 | 877.7 | 19.22 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 198.98.53.130 |
| 72.95 | trojan | 320.1 | 599.1 | 20.37 | 0.0 | 8.58 | 12.86 | 19.44 | Au1rxx-base64 | 100.42.228.109 |
| 72.74 | vless | 306.8 | 665.6 | 20.68 | 0.0 | 8.47 | 7.77 | 19.44 | Au1rxx-base64 | 195.123.235.177 |
| 72.5 | vless | 348.6 | 699.6 | 19.71 | 0.0 | 8.45 | 7.77 | 19.44 | Au1rxx-base64 | 169.40.42.223 |
| 72.32 | shadowsocks | 366.6 | 808.7 | 19.29 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 51.222.12.127 |
| 72.29 | vless | 311.8 | 695.3 | 20.56 | 0.0 | 10.0 | 7.77 | 17.5 | Surfboard-tg-mixed | 184.107.106.68 |
| 72.26 | vless | 295.1 | 557.1 | 20.95 | 0.0 | 8.36 | 7.77 | 19.44 | Au1rxx-base64 | 172.235.38.85 |
| 72.23 | shadowsocks | 430.9 | 1118.2 | 17.8 | 0.0 | 10.0 | 13.81 | 17.5 | Surfboard-tg-mixed | 15.204.246.108 |
| 72.12 | shadowsocks | 315.9 | 747.7 | 20.47 | 0.0 | 10.0 | 13.81 | 12.88 | mheidari-all | 37.19.198.160 |
| 71.78 | shadowsocks | 295.8 | 720.0 | 20.93 | 0.0 | 10.0 | 13.81 | 12.88 | mheidari-all | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | 0.839 | 279 | 1690 | prefer |
| Surfboard-tg-mixed | 0.875 | 0.798 | 183 | 7520 | prefer |
| mheidari-all | 0.824 | 0.748 | 131 | 16820 | prefer |
| ermaozi | 0.721 | 0.712 | 52 | 442 | prefer |
| ermaozi-get_subscribe | 0.664 | 0.684 | 19 | 473 | observe |
| DeltaKronecker-all | 0.621 | 0.543 | 35 | 6097 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 180 | observe |
| Epodonios-all | 0.255 | None | 0 | 7969 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8998 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6208 | observe |
| barry-far-vless | 0.255 | None | 0 | 6433 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 30 |
| cn-block | ClientOSError | - | 28 |
| 204 | ProxyError | - | 25 |
| speed | TimeoutError | - | 21 |
| geo | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 6 |
| geo | ProxyError | - | 6 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
