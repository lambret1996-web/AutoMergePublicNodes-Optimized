# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 00:34:11 |
| 运行耗时 | 666.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83057 |
| 去重后节点 | 23305 |
| TCP 可达 | 3000 |
| 真实可用 | 507 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23305 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 39.5 |
| probe | 238.1 |
| real_test | 295.1 |
| generate | 85.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50107 |
| vmess | 12658 |
| shadowsocks | 9771 |
| trojan | 8010 |
| hysteria2 | 1704 |
| http | 599 |
| shadowsocksr | 131 |
| socks | 54 |
| tuic | 12 |
| hysteria | 9 |
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
| 81.97 | vless | 203.0 | 499.9 | 23.08 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 172.235.43.210 |
| 81.84 | vless | 208.4 | 508.5 | 22.95 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 172.236.233.59 |
| 81.82 | vless | 209.6 | 537.2 | 22.93 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 172.235.38.85 |
| 81.75 | vless | 212.6 | 540.6 | 22.86 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 172.233.139.46 |
| 81.73 | vless | 211.0 | 544.8 | 22.89 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 107.173.237.146 |
| 81.49 | vless | 223.7 | 492.1 | 22.6 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 31.58.50.200 |
| 80.38 | vless | 228.6 | 587.5 | 22.49 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 38.209.125.45 |
| 79.56 | vless | 307.0 | 801.0 | 20.67 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 15.204.97.216 |
| 78.64 | shadowsocks | 188.6 | 492.6 | 23.41 | 0.0 | 10.0 | 13.81 | 16.42 | Surfboard-tg-mixed | 216.105.168.18 |
| 77.81 | trojan | 200.7 | 516.0 | 23.13 | 0.0 | 8.5 | 10.86 | 18.32 | Au1rxx-base64 | us01.duotg.top |
| 77.36 | shadowsocks | 222.5 | 521.0 | 22.63 | 0.0 | 10.0 | 13.81 | 16.42 | Surfboard-tg-mixed | 5.78.51.123 |
| 77.25 | shadowsocks | 195.0 | 470.9 | 23.26 | 0.0 | 10.0 | 13.81 | 14.68 | mheidari-all | 108.181.0.177 |
| 77.22 | vless | 255.5 | 538.6 | 21.86 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 144.172.104.26 |
| 77.21 | hysteria2 | 216.1 | 555.7 | 22.77 | 0.0 | 10.0 | 13.75 | 18.32 | Au1rxx-base64 | 66.94.121.46 |
| 77.18 | trojan | 206.5 | 525.5 | 23.0 | 0.0 | 10.0 | 10.86 | 18.32 | Au1rxx-base64 | 107.150.105.84 |
| 76.8 | shadowsocks | 214.4 | 538.4 | 22.81 | 0.0 | 10.0 | 13.81 | 14.68 | mheidari-all | 108.181.118.10 |
| 76.8 | vless | 247.5 | 297.4 | 22.05 | 3.85 | 9.94 | 10.57 | 16.42 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.47 | vless | 257.1 | 504.8 | 21.83 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 162.159.0.53 |
| 76.42 | hysteria2 | 348.1 | 736.7 | 19.72 | 0.0 | 10.0 | 13.75 | 18.32 | Au1rxx-base64 | 159.223.157.129 |
| 76.25 | vless | 255.4 | 552.0 | 21.86 | 0.0 | 10.0 | 10.57 | 18.32 | Au1rxx-base64 | 172.64.52.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | 0.923 | 297 | 1613 | prefer |
| mheidari-all | 0.886 | 0.817 | 60 | 15581 | prefer |
| Surfboard-tg-mixed | 0.739 | 0.66 | 209 | 7263 | prefer |
| ermaozi | 0.409 | 0.467 | 15 | 377 | observe |
| DeltaKronecker-all | 0.382 | 0.298 | 124 | 6070 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 194 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7719 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8492 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5889 | observe |
| barry-far-vless | 0.255 | None | 0 | 6106 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 77 |
| geo | ClientOSError | - | 48 |
| 204 | ProxyError | - | 18 |
| speed | ClientOSError | - | 17 |
| cn-block | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 10 |
| speed | TimeoutError | - | 8 |
| 204 | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
