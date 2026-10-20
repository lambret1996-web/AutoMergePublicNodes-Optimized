# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 16:39:41 |
| 运行耗时 | 586.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94292 |
| 去重后节点 | 26481 |
| TCP 可达 | 3000 |
| 真实可用 | 329 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26481 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 45.1 |
| probe | 219.4 |
| real_test | 237.3 |
| generate | 77.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56254 |
| vmess | 16826 |
| shadowsocks | 11210 |
| trojan | 8370 |
| hysteria2 | 1141 |
| http | 211 |
| shadowsocksr | 158 |
| socks | 63 |
| anytls | 36 |
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
| 78.16 | shadowsocks | 235.2 | 608.3 | 22.33 | 0.0 | 8.41 | 13.88 | 17.54 | Au1rxx-base64 | 156.146.38.167 |
| 78.09 | shadowsocks | 247.6 | 648.1 | 22.05 | 0.0 | 8.62 | 13.88 | 17.54 | Au1rxx-base64 | 156.146.38.169 |
| 74.85 | shadowsocks | 329.7 | 811.8 | 20.15 | 0.0 | 8.39 | 13.88 | 17.54 | Au1rxx-base64 | 37.19.198.160 |
| 72.87 | vless | 295.4 | 746.3 | 20.94 | 0.0 | 8.6 | 8.79 | 17.54 | Au1rxx-base64 | 162.35.126.130 |
| 72.84 | shadowsocks | 253.1 | 612.9 | 21.92 | 0.0 | 10.0 | 13.88 | 11.04 | mheidari-all | 156.146.38.170 |
| 72.79 | shadowsocks | 255.2 | 627.4 | 21.87 | 0.0 | 10.0 | 13.88 | 11.04 | mheidari-all | 156.146.38.168 |
| 71.68 | hysteria2 | 271.5 | 689.2 | 21.49 | 0.0 | 10.0 | 14.25 | 7.44 | Surfboard-tg-mixed | 129.213.91.185 |
| 71.64 | shadowsocks | 319.8 | 632.6 | 20.37 | 0.0 | 8.39 | 13.88 | 17.54 | Au1rxx-base64 | 149.22.95.183 |
| 70.83 | vless | 410.0 | 1020.6 | 18.29 | 0.0 | 8.45 | 8.79 | 17.54 | Au1rxx-base64 | 185.95.231.156 |
| 70.72 | shadowsocks | 336.0 | 329.2 | 20.0 | 2.66 | 8.38 | 13.88 | 17.54 | Au1rxx-base64 | 149.22.87.204 |
| 70.7 | vless | 280.9 | 673.0 | 21.28 | 0.0 | 8.63 | 8.79 | 17.54 | Au1rxx-base64 | 216.227.161.95 |
| 70.68 | vless | 324.2 | 718.9 | 20.27 | 0.0 | 8.45 | 8.79 | 17.54 | Au1rxx-base64 | 167.17.69.171 |
| 70.48 | shadowsocks | 310.8 | 763.9 | 20.58 | 0.0 | 10.0 | 13.88 | 11.04 | mheidari-all | 37.19.198.243 |
| 70.36 | vless | 368.3 | 863.0 | 19.25 | 0.0 | 8.6 | 8.79 | 17.54 | Au1rxx-base64 | 195.123.235.183 |
| 70.35 | vless | 283.1 | 665.1 | 21.23 | 0.0 | 8.44 | 8.79 | 17.54 | Au1rxx-base64 | 69.48.201.136 |
| 70.35 | shadowsocks | 338.8 | 335.4 | 19.94 | 2.42 | 8.38 | 13.88 | 17.54 | Au1rxx-base64 | 149.22.87.240 |
| 70.31 | shadowsocks | 292.1 | 603.5 | 21.02 | 0.0 | 8.51 | 13.88 | 17.54 | Au1rxx-base64 | 173.244.56.9 |
| 70.29 | vless | 340.5 | 775.0 | 19.9 | 0.0 | 8.46 | 8.79 | 17.54 | Au1rxx-base64 | 169.40.42.74 |
| 70.02 | trojan | 583.7 | 1606.2 | 14.27 | 0.0 | 8.42 | 12.79 | 17.54 | Au1rxx-base64 | 66.23.203.21 |
| 69.38 | shadowsocks | 294.6 | 713.9 | 20.96 | 0.0 | 8.39 | 13.88 | 17.54 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.88 | 0.809 | 68 | 23236 | prefer |
| Au1rxx-base64 | 0.834 | 0.782 | 293 | 1348 | prefer |
| DeltaKronecker-all | 0.759 | 0.692 | 26 | 3519 | prefer |
| zhangkai | 0.501 | 0.5 | 26 | 31 | observe |
| Surfboard-tg-mixed | 0.489 | 0.667 | 9 | 6911 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 7384 | observe |
| ermaozi-get_subscribe | 0.322 | 0.5 | 8 | 429 | observe |
| chromego_merge | 0.264 | 1.0 | 1 | 227 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10086 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5732 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 22 |
| speed | TimeoutError | - | 19 |
| 204 | ProxyError | - | 18 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
