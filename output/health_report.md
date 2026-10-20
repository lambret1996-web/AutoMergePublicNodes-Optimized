# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 04:02:17 |
| 运行耗时 | 572.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94707 |
| 去重后节点 | 26190 |
| TCP 可达 | 3000 |
| 真实可用 | 339 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26190 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 44.2 |
| probe | 210.6 |
| real_test | 226.1 |
| generate | 82.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56636 |
| vmess | 17052 |
| shadowsocks | 11243 |
| trojan | 7994 |
| hysteria2 | 1214 |
| http | 276 |
| shadowsocksr | 168 |
| socks | 67 |
| anytls | 34 |
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
| 80.7 | hysteria2 | 247.7 | 685.5 | 22.04 | 0.0 | 10.0 | 13.12 | 17.04 | Au1rxx-base64 | 129.213.91.185 |
| 78.91 | vless | 277.5 | 704.9 | 21.36 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 66.70.179.198 |
| 77.5 | vless | 338.1 | 859.2 | 19.95 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.229 |
| 77.15 | vless | 353.2 | 903.3 | 19.6 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.235 |
| 77.06 | vless | 308.8 | 743.3 | 20.63 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 5.34.178.120 |
| 76.57 | shadowsocks | 255.4 | 709.1 | 21.87 | 0.0 | 9.05 | 12.61 | 17.04 | Au1rxx-base64 | 37.19.198.243 |
| 76.57 | vless | 378.5 | 1056.0 | 19.02 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 185.95.231.156 |
| 76.49 | vless | 338.2 | 923.8 | 19.95 | 0.0 | 8.99 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.35 |
| 76.27 | vless | 346.6 | 891.9 | 19.75 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 209.200.246.148 |
| 76.24 | vless | 262.8 | 633.0 | 21.69 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 195.211.98.43 |
| 75.94 | vless | 364.1 | 1001.2 | 19.35 | 0.0 | 9.04 | 10.51 | 17.04 | Au1rxx-base64 | 167.17.69.171 |
| 75.8 | hysteria2 | 310.1 | 287.7 | 20.6 | 4.21 | 8.94 | 13.12 | 17.04 | Au1rxx-base64 | 45.32.10.7 |
| 75.79 | vless | 368.7 | 950.0 | 19.24 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.163 |
| 75.65 | vless | 378.2 | 922.4 | 19.02 | 0.0 | 9.08 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.231 |
| 75.02 | vless | 364.2 | 992.4 | 19.35 | 0.0 | 10.0 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.104 |
| 74.37 | shadowsocks | 260.8 | 709.0 | 21.74 | 0.0 | 10.0 | 12.61 | 14.02 | mheidari-all | 37.19.198.160 |
| 74.3 | shadowsocks | 283.3 | 650.0 | 21.22 | 0.0 | 10.0 | 12.61 | 17.04 | Au1rxx-base64 | 156.146.38.169 |
| 73.84 | vless | 365.6 | 888.5 | 19.31 | 0.0 | 9.08 | 10.51 | 17.04 | Au1rxx-base64 | 169.40.42.168 |
| 73.44 | shadowsocks | 280.9 | 647.8 | 21.27 | 0.0 | 8.97 | 12.61 | 17.04 | Au1rxx-base64 | 156.146.38.167 |
| 73.43 | shadowsocks | 255.8 | 713.7 | 21.86 | 0.0 | 8.92 | 12.61 | 17.04 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.877 | 0.822 | 309 | 1424 | prefer |
| zhangkai | 0.705 | 0.929 | 14 | 27 | prefer |
| mheidari-all | 0.552 | 0.472 | 106 | 23317 | observe |
| DeltaKronecker-all | 0.432 | 0.429 | 14 | 3294 | observe |
| ermaozi-get_subscribe | 0.395 | 0.367 | 30 | 510 | observe |
| Surfboard-tg-mixed | 0.372 | 0.444 | 9 | 6911 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7516 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10161 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5797 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 33 |
| 204 | ProxyError | - | 27 |
| speed | TimeoutError | - | 17 |
| speed | ClientOSError | - | 15 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| geo | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| speed | ClientPayloadError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
