# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 12:29:51 |
| 运行耗时 | 589.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83273 |
| 去重后节点 | 22846 |
| TCP 可达 | 3000 |
| 真实可用 | 472 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22846 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 38.5 |
| probe | 231.8 |
| real_test | 233.2 |
| generate | 78.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50356 |
| vmess | 12639 |
| shadowsocks | 9819 |
| trojan | 7886 |
| hysteria2 | 1736 |
| http | 634 |
| shadowsocksr | 128 |
| socks | 52 |
| hysteria | 11 |
| tuic | 10 |
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
| 80.84 | shadowsocks | 236.7 | 605.1 | 22.3 | 0.0 | 10.0 | 14.04 | 18.5 | Au1rxx-base64 | 198.98.53.130 |
| 80.4 | shadowsocks | 255.6 | 689.3 | 21.86 | 0.0 | 10.0 | 14.04 | 18.5 | Au1rxx-base64 | 37.19.198.243 |
| 78.74 | vless | 238.9 | 613.7 | 22.25 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 195.123.235.177 |
| 78.45 | vless | 251.3 | 691.8 | 21.96 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 79.141.172.154 |
| 78.33 | vless | 256.7 | 698.7 | 21.84 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 47.253.226.114 |
| 78.29 | vless | 258.3 | 649.8 | 21.8 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 169.40.42.74 |
| 77.8 | vless | 279.5 | 661.2 | 21.31 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 169.40.42.184 |
| 77.7 | vless | 283.7 | 734.4 | 21.21 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 169.40.42.179 |
| 77.58 | shadowsocks | 287.4 | 660.3 | 21.12 | 0.0 | 10.0 | 14.04 | 18.5 | Au1rxx-base64 | 156.146.38.170 |
| 77.45 | shadowsocks | 361.5 | 930.0 | 19.41 | 0.0 | 10.0 | 14.04 | 18.5 | Au1rxx-base64 | 51.222.155.113 |
| 77.0 | vless | 313.8 | 843.3 | 20.51 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 137.184.218.169 |
| 76.55 | shadowsocks | 400.4 | 1139.4 | 18.51 | 0.0 | 10.0 | 14.04 | 18.5 | Au1rxx-base64 | 15.204.247.206 |
| 76.45 | shadowsocks | 370.9 | 949.7 | 19.19 | 0.0 | 10.0 | 14.04 | 18.5 | Au1rxx-base64 | 51.222.200.165 |
| 76.36 | shadowsocks | 304.8 | 763.0 | 20.72 | 0.0 | 10.0 | 14.04 | 16.1 | Surfboard-tg-mixed | 51.222.141.125 |
| 76.3 | shadowsocks | 307.5 | 827.1 | 20.66 | 0.0 | 10.0 | 14.04 | 16.1 | Surfboard-tg-mixed | 38.180.135.156 |
| 76.15 | shadowsocks | 257.1 | 681.0 | 21.83 | 0.0 | 10.0 | 14.04 | 14.28 | mheidari-all | 37.19.198.244 |
| 76.08 | shadowsocks | 260.1 | 680.1 | 21.76 | 0.0 | 10.0 | 14.04 | 14.28 | mheidari-all | 37.19.198.160 |
| 75.78 | vless | 362.7 | 835.0 | 19.38 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 169.40.42.16 |
| 75.65 | hysteria2 | 358.9 | 802.5 | 19.47 | 0.0 | 10.0 | 13.0 | 14.28 | mheidari-all | 159.223.157.129 |
| 75.59 | vless | 375.0 | 943.3 | 19.1 | 0.0 | 10.0 | 7.99 | 18.5 | Au1rxx-base64 | 169.40.42.75 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.917 | 0.855 | 289 | 1613 | prefer |
| DeltaKronecker-all | 0.853 | 0.786 | 42 | 5970 | prefer |
| Surfboard-tg-mixed | 0.792 | 0.715 | 144 | 7286 | prefer |
| mheidari-all | 0.696 | 0.619 | 84 | 15747 | observe |
| ermaozi | 0.633 | 0.62 | 50 | 434 | observe |
| ermaozi-get_subscribe | 0.327 | 0.385 | 13 | 459 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7695 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8771 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5895 | observe |
| barry-far-vless | 0.255 | None | 0 | 6084 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4207 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1613 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 46 |
| 204 | ProxyError | - | 27 |
| speed | ClientOSError | - | 15 |
| speed | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| 204 | ProxyConnectionError | - | 9 |
| geo | TimeoutError | - | 8 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
