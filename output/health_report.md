# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 12:46:56 |
| 运行耗时 | 575.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96889 |
| 去重后节点 | 26973 |
| TCP 可达 | 3000 |
| 真实可用 | 453 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26973 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.6 |
| tcp | 45.1 |
| probe | 257.0 |
| real_test | 177.2 |
| generate | 88.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59097 |
| vmess | 14821 |
| shadowsocks | 11447 |
| trojan | 9244 |
| hysteria2 | 1406 |
| http | 583 |
| shadowsocksr | 165 |
| socks | 79 |
| anytls | 24 |
| hysteria | 15 |
| tuic | 8 |

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
| 81.57 | hysteria2 | 249.2 | 552.9 | 22.01 | 0.0 | 10.0 | 13.93 | 17.5 | Au1rxx-base64 | 192.255.128.123 |
| 78.27 | shadowsocks | 241.9 | 596.1 | 22.18 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 156.146.38.168 |
| 78.07 | shadowsocks | 250.5 | 622.1 | 21.98 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 156.146.38.170 |
| 78.04 | shadowsocks | 251.7 | 636.3 | 21.95 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 156.146.38.167 |
| 76.87 | shadowsocks | 302.3 | 778.8 | 20.78 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.37 | shadowsocks | 311.2 | 765.8 | 20.57 | 0.0 | 8.69 | 14.29 | 17.5 | Au1rxx-base64 | 37.19.198.244 |
| 76.02 | shadowsocks | 304.9 | 742.2 | 20.72 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 37.19.198.243 |
| 74.05 | vless | 282.9 | 659.7 | 21.23 | 0.0 | 8.67 | 6.65 | 17.5 | Au1rxx-base64 | 198.251.78.29 |
| 73.92 | vless | 287.6 | 724.9 | 21.12 | 0.0 | 8.65 | 6.65 | 17.5 | Au1rxx-base64 | 79.141.172.154 |
| 73.87 | shadowsocks | 323.0 | 806.1 | 20.3 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 37.19.198.160 |
| 73.85 | shadowsocks | 315.6 | 725.4 | 20.47 | 0.0 | 10.0 | 14.29 | 17.5 | Au1rxx-base64 | 173.244.56.9 |
| 73.67 | shadowsocks | 270.3 | 573.2 | 21.52 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 5.78.51.123 |
| 73.49 | shadowsocks | 306.6 | 752.1 | 20.68 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 140.82.63.79 |
| 73.32 | shadowsocks | 432.8 | 1170.7 | 17.76 | 0.0 | 8.27 | 14.29 | 17.5 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 73.11 | hysteria2 | 330.5 | 282.7 | 20.13 | 4.4 | 7.22 | 13.93 | 17.5 | Au1rxx-base64 | open.2ml.bid |
| 72.94 | shadowsocks | 274.1 | 638.8 | 21.43 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 198.98.53.130 |
| 72.56 | shadowsocks | 335.8 | 321.4 | 20.0 | 2.95 | 9.64 | 14.29 | 17.5 | Au1rxx-base64 | 149.22.87.204 |
| 72.11 | hysteria2 | 399.2 | 728.1 | 18.54 | 0.0 | 9.88 | 13.93 | 17.5 | Au1rxx-base64 | 62.210.124.146 |
| 72.02 | shadowsocks | 301.3 | 744.0 | 20.8 | 0.0 | 8.73 | 14.29 | 17.5 | Au1rxx-base64 | 47.90.153.88 |
| 71.57 | shadowsocks | 334.8 | 649.8 | 20.03 | 0.0 | 10.0 | 14.29 | 15.8 | Surfboard-tg-mixed | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.965 | 0.9 | 50 | 22883 | prefer |
| Au1rxx-base64 | 0.916 | 0.854 | 335 | 1598 | prefer |
| ermaozi | 0.769 | 0.774 | 31 | 291 | prefer |
| Surfboard-tg-mixed | 0.749 | 0.672 | 137 | 7053 | prefer |
| DeltaKronecker-all | 0.45 | 0.5 | 12 | 5528 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| Epodonios-all | 0.255 | None | 0 | 7502 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9548 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5690 | observe |
| barry-far-vless | 0.255 | None | 0 | 5869 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1598 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 27 |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 14 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| geo | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42638: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
