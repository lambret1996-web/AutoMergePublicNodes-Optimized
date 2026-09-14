# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 18:29:33 |
| 运行耗时 | 598.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84821 |
| 去重后节点 | 22987 |
| TCP 可达 | 3000 |
| 真实可用 | 412 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22987 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 38.3 |
| probe | 272.5 |
| real_test | 212.3 |
| generate | 68.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51718 |
| vmess | 13000 |
| shadowsocks | 9735 |
| trojan | 8015 |
| hysteria2 | 1538 |
| http | 593 |
| shadowsocksr | 127 |
| socks | 57 |
| anytls | 16 |
| hysteria | 11 |
| tuic | 11 |

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
| 81.63 | shadowsocks | 237.3 | 593.1 | 22.29 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 156.146.38.167 |
| 80.41 | hysteria2 | 281.6 | 689.2 | 21.26 | 0.0 | 10.0 | 11.67 | 18.92 | Au1rxx-base64 | 159.223.157.129 |
| 80.1 | shadowsocks | 258.7 | 635.2 | 21.79 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 156.146.38.170 |
| 79.63 | shadowsocks | 276.1 | 679.0 | 21.39 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 23.150.248.20 |
| 77.45 | vless | 311.0 | 739.3 | 20.58 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 47.253.226.114 |
| 76.33 | vless | 305.0 | 565.2 | 20.72 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 144.172.104.26 |
| 75.76 | shadowsocks | 282.0 | 593.8 | 21.25 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 173.244.56.6 |
| 75.75 | vless | 312.7 | 678.9 | 20.54 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 195.123.235.177 |
| 75.38 | vless | 381.1 | 875.7 | 18.96 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 169.40.42.104 |
| 75.05 | shadowsocks | 293.1 | 590.2 | 20.99 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 173.244.56.9 |
| 75.0 | hysteria2 | 358.1 | 862.9 | 19.49 | 0.0 | 10.0 | 11.67 | 18.92 | Au1rxx-base64 | 107.175.219.48 |
| 74.99 | shadowsocks | 343.3 | 747.8 | 19.83 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 108.181.57.93 |
| 74.93 | vless | 364.9 | 738.6 | 19.33 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 45.149.172.80 |
| 74.79 | vless | 352.6 | 774.6 | 19.62 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 169.40.42.224 |
| 74.61 | vless | 345.5 | 665.8 | 19.78 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 169.40.42.173 |
| 74.6 | shadowsocks | 326.6 | 651.6 | 20.22 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 108.181.118.10 |
| 74.55 | vless | 317.0 | 713.6 | 20.44 | 0.0 | 9.77 | 10.48 | 18.92 | Au1rxx-base64 | lizca2.footballfantasyforum.com |
| 74.55 | vless | 410.0 | 987.5 | 18.29 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 185.95.231.156 |
| 74.47 | vless | 356.5 | 686.8 | 19.53 | 0.0 | 10.0 | 10.48 | 18.92 | Au1rxx-base64 | 169.40.42.133 |
| 74.33 | shadowsocks | 281.2 | 562.8 | 21.27 | 0.0 | 10.0 | 14.42 | 18.92 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | 0.935 | 293 | 1619 | prefer |
| mheidari-all | 0.8 | 0.729 | 48 | 15899 | prefer |
| DeltaKronecker-all | 0.734 | 0.722 | 18 | 5972 | prefer |
| Surfboard-tg-mixed | 0.702 | 0.624 | 109 | 7482 | prefer |
| ermaozi | 0.61 | 0.6 | 35 | 393 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 149 | observe |
| Epodonios-all | 0.255 | None | 0 | 7933 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9209 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6061 | observe |
| barry-far-vless | 0.255 | None | 0 | 6293 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1619 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 24 |
| 204 | TimeoutError | - | 22 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 4 |
| speed | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | TimeoutError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
