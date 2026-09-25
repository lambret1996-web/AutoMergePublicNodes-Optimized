# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 04:52:17 |
| 运行耗时 | 926.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97833 |
| 去重后节点 | 26571 |
| TCP 可达 | 3000 |
| 真实可用 | 457 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26571 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 44.2 |
| probe | 348.7 |
| real_test | 438.1 |
| generate | 89.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59370 |
| vmess | 15073 |
| shadowsocks | 11808 |
| trojan | 8997 |
| hysteria2 | 1640 |
| http | 649 |
| shadowsocksr | 175 |
| socks | 74 |
| anytls | 24 |
| hysteria | 16 |
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
| 83.83 | vless | 223.8 | 535.0 | 22.6 | 0.0 | 10.0 | 12.09 | 19.44 | Au1rxx-base64 | 195.123.240.65 |
| 83.08 | vless | 220.6 | 500.9 | 22.67 | 0.0 | 8.88 | 12.09 | 19.44 | Au1rxx-base64 | 172.235.43.210 |
| 81.65 | vless | 205.5 | 529.8 | 23.02 | 0.0 | 10.0 | 12.09 | 16.54 | mheidari-all | 172.233.139.46 |
| 80.49 | vless | 275.8 | 609.4 | 21.39 | 0.0 | 10.0 | 12.09 | 19.44 | Au1rxx-base64 | 15.204.97.216 |
| 80.33 | shadowsocks | 225.5 | 532.6 | 22.56 | 0.0 | 8.91 | 13.42 | 19.44 | Au1rxx-base64 | 173.244.56.6 |
| 78.9 | shadowsocks | 187.5 | 490.7 | 23.44 | 0.0 | 10.0 | 13.42 | 16.54 | mheidari-all | 192.3.247.109 |
| 78.7 | shadowsocks | 222.6 | 548.4 | 22.62 | 0.0 | 8.88 | 13.42 | 19.44 | Au1rxx-base64 | 173.244.56.9 |
| 78.5 | shadowsocks | 231.5 | 579.4 | 22.42 | 0.0 | 10.0 | 13.42 | 17.16 | Surfboard-tg-mixed | 108.181.118.10 |
| 78.47 | shadowsocks | 258.9 | 627.3 | 21.79 | 0.0 | 8.87 | 13.42 | 19.44 | Au1rxx-base64 | 156.146.38.167 |
| 78.4 | shadowsocks | 235.8 | 597.8 | 22.32 | 0.0 | 10.0 | 13.42 | 17.16 | Surfboard-tg-mixed | 108.181.0.177 |
| 78.13 | hysteria2 | 321.9 | 721.2 | 20.33 | 0.0 | 10.0 | 14.25 | 19.44 | Au1rxx-base64 | 159.223.157.129 |
| 78.12 | vless | 331.4 | 764.1 | 20.11 | 0.0 | 8.88 | 12.09 | 19.44 | Au1rxx-base64 | 79.141.172.154 |
| 77.6 | hysteria2 | 253.8 | 255.2 | 21.9 | 5.43 | 8.84 | 14.25 | 19.44 | Au1rxx-base64 | 43.167.208.94 |
| 77.53 | shadowsocks | 261.7 | 632.9 | 21.72 | 0.0 | 10.0 | 13.42 | 17.16 | Surfboard-tg-mixed | 156.146.38.169 |
| 77.24 | vless | 406.5 | 1011.9 | 18.37 | 0.0 | 8.9 | 12.09 | 19.44 | Au1rxx-base64 | 5.78.159.214 |
| 77.12 | shadowsocks | 263.5 | 647.0 | 21.68 | 0.0 | 10.0 | 13.42 | 17.16 | Surfboard-tg-mixed | 156.146.38.168 |
| 77.07 | hysteria2 | 299.6 | 208.5 | 20.84 | 7.18 | 7.17 | 14.25 | 19.44 | Au1rxx-base64 | hk01.kfc-520.com |
| 76.55 | vless | 224.6 | 526.4 | 22.58 | 0.0 | 8.94 | 12.09 | 19.44 | Au1rxx-base64 | 172.64.32.108 |
| 76.5 | shadowsocks | 346.0 | 890.7 | 19.77 | 0.0 | 8.87 | 13.42 | 19.44 | Au1rxx-base64 | 156.146.38.170 |
| 76.49 | shadowsocks | 273.1 | 642.8 | 21.46 | 0.0 | 10.0 | 13.42 | 17.16 | Surfboard-tg-mixed | 5.78.51.123 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | 0.899 | 267 | 1701 | prefer |
| Surfboard-tg-mixed | 0.749 | 0.671 | 164 | 7399 | prefer |
| ermaozi | 0.643 | 0.64 | 25 | 338 | observe |
| ermaozi-get_subscribe | 0.38 | 0.8 | 5 | 359 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4405 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 5845 | observe |
| mheidari-all | 0.272 | 0.191 | 440 | 22554 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7876 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9018 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5862 | observe |
| barry-far-vless | 0.255 | None | 0 | 6091 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1701 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 160 |
| speed | TimeoutError | - | 68 |
| cn-block | ClientOSError | - | 63 |
| geo | ClientOSError | - | 47 |
| 204 | ProxyError | - | 36 |
| 204 | TimeoutError | - | 30 |
| speed | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 22 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
