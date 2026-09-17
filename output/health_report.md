# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-17 18:29:33 |
| 运行耗时 | 570.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84303 |
| 去重后节点 | 23020 |
| TCP 可达 | 3000 |
| 真实可用 | 384 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23020 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 37.3 |
| probe | 217.5 |
| real_test | 215.8 |
| generate | 91.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50687 |
| vmess | 13179 |
| shadowsocks | 10089 |
| trojan | 8101 |
| hysteria2 | 1439 |
| http | 596 |
| shadowsocksr | 126 |
| socks | 74 |
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
| 82.83 | hysteria2 | 240.6 | 556.4 | 22.21 | 0.0 | 10.0 | 13.64 | 17.98 | Au1rxx-base64 | 66.94.121.46 |
| 81.05 | vless | 200.8 | 508.6 | 23.13 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 172.235.43.210 |
| 79.9 | shadowsocks | 218.6 | 514.4 | 22.72 | 0.0 | 10.0 | 13.08 | 18.1 | mheidari-all | 149.22.95.183 |
| 79.83 | shadowsocks | 216.5 | 550.8 | 22.77 | 0.0 | 10.0 | 13.08 | 17.98 | Au1rxx-base64 | 173.244.56.9 |
| 79.74 | shadowsocks | 225.5 | 566.3 | 22.56 | 0.0 | 10.0 | 13.08 | 18.1 | mheidari-all | 173.244.56.6 |
| 77.02 | vless | 261.3 | 528.5 | 21.73 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 144.172.104.26 |
| 76.12 | vless | 197.9 | 488.4 | 23.2 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 31.58.50.200 |
| 75.22 | hysteria2 | 360.0 | 727.1 | 19.44 | 0.0 | 10.0 | 13.64 | 18.1 | mheidari-all | 159.223.157.129 |
| 75.2 | vless | 276.2 | 374.9 | 21.38 | 0.94 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 172.64.229.170 |
| 74.7 | vless | 207.0 | 514.0 | 22.99 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 104.18.46.234 |
| 74.49 | vless | 289.6 | 430.8 | 21.07 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 172.64.52.6 |
| 73.43 | vless | 244.8 | 593.4 | 22.11 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 162.159.0.169 |
| 73.21 | shadowsocks | 248.2 | 648.5 | 22.03 | 0.0 | 10.0 | 13.08 | 17.98 | Au1rxx-base64 | 5.78.51.123 |
| 73.02 | vless | 305.1 | 393.6 | 20.71 | 0.24 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 172.64.154.8 |
| 72.59 | shadowsocks | 297.3 | 354.4 | 20.9 | 1.71 | 9.92 | 13.08 | 18.1 | mheidari-all | 149.22.87.204 |
| 72.56 | vless | 303.9 | 361.0 | 20.74 | 1.46 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 104.18.46.46 |
| 72.11 | vless | 238.1 | 465.4 | 22.27 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 162.159.48.32 |
| 71.94 | vless | 378.4 | 990.6 | 19.02 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 15.204.97.206 |
| 71.69 | vless | 233.1 | 591.7 | 22.38 | 0.0 | 10.0 | 9.94 | 17.98 | Au1rxx-base64 | 172.64.42.85 |
| 71.69 | shadowsocks | 337.0 | 704.6 | 19.98 | 0.0 | 10.0 | 13.08 | 17.98 | Au1rxx-base64 | 23.150.248.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | 0.882 | 263 | 1620 | prefer |
| mheidari-all | 0.712 | 0.636 | 55 | 15839 | prefer |
| ermaozi | 0.711 | 0.71 | 31 | 357 | prefer |
| Surfboard-tg-mixed | 0.683 | 0.605 | 124 | 7430 | observe |
| DeltaKronecker-all | 0.628 | 0.552 | 29 | 5931 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4261 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5093 | observe |
| Epodonios-all | 0.255 | None | 0 | 7888 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9061 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5904 | observe |
| barry-far-vless | 0.255 | None | 0 | 6129 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1620 | observe |
| ermaozi-get_subscribe | 0.234 | 0.4 | 5 | 361 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 31 |
| 204 | ProxyError | - | 22 |
| geo | ClientOSError | - | 15 |
| geo | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| cn-block | TimeoutError | - | 11 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47988: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
