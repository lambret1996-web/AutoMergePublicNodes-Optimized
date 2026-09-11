# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-11 18:29:05 |
| 运行耗时 | 561.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83682 |
| 去重后节点 | 23281 |
| TCP 可达 | 3000 |
| 真实可用 | 370 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23281 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 40.5 |
| probe | 226.6 |
| real_test | 201.8 |
| generate | 84.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50700 |
| vmess | 12613 |
| shadowsocks | 9886 |
| trojan | 8045 |
| hysteria2 | 1640 |
| http | 599 |
| shadowsocksr | 125 |
| socks | 51 |
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
| 83.05 | vless | 204.1 | 516.3 | 23.05 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 172.235.43.210 |
| 83.0 | vless | 206.3 | 511.4 | 23.0 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 172.235.38.85 |
| 82.91 | hysteria2 | 256.8 | 589.1 | 21.83 | 0.0 | 10.0 | 14.29 | 18.98 | Au1rxx-base64 | 66.94.121.46 |
| 81.65 | vless | 264.9 | 693.5 | 21.65 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 172.233.139.46 |
| 80.6 | shadowsocks | 215.5 | 501.7 | 22.79 | 0.0 | 10.0 | 13.33 | 18.98 | Au1rxx-base64 | 108.181.118.10 |
| 79.39 | shadowsocks | 279.1 | 649.5 | 21.32 | 0.0 | 10.0 | 13.33 | 18.74 | Surfboard-tg-mixed | 173.244.56.6 |
| 79.26 | shadowsocks | 261.2 | 635.8 | 21.73 | 0.0 | 10.0 | 13.33 | 18.74 | Surfboard-tg-mixed | 156.146.38.167 |
| 79.23 | hysteria2 | 328.4 | 718.1 | 20.18 | 0.0 | 10.0 | 14.29 | 18.98 | Au1rxx-base64 | 159.223.157.129 |
| 78.97 | shadowsocks | 273.2 | 648.5 | 21.45 | 0.0 | 10.0 | 13.33 | 18.98 | Au1rxx-base64 | 156.146.38.169 |
| 77.68 | vless | 344.2 | 823.3 | 19.81 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 15.204.97.216 |
| 77.62 | vless | 322.2 | 729.9 | 20.32 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 79.141.172.154 |
| 77.39 | vless | 254.4 | 467.1 | 21.89 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 104.18.46.46 |
| 76.48 | vless | 311.4 | 641.5 | 20.57 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 31.58.50.200 |
| 76.3 | shadowsocks | 265.1 | 637.2 | 21.64 | 0.0 | 10.0 | 13.33 | 18.74 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.3 | vless | 324.5 | 692.5 | 20.27 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 188.137.243.243 |
| 76.13 | shadowsocks | 320.8 | 249.3 | 20.35 | 5.65 | 9.9 | 13.33 | 18.74 | Surfboard-tg-mixed | 45.32.16.53 |
| 76.07 | shadowsocks | 209.9 | 472.5 | 22.92 | 0.0 | 10.0 | 13.33 | 14.32 | mheidari-all | 108.181.0.177 |
| 75.1 | shadowsocks | 273.4 | 661.9 | 21.45 | 0.0 | 10.0 | 13.33 | 14.32 | mheidari-all | 156.146.38.170 |
| 73.91 | vless | 249.7 | 494.6 | 22.0 | 0.0 | 10.0 | 11.02 | 18.98 | Au1rxx-base64 | 162.159.48.32 |
| 73.81 | vless | 359.7 | 341.2 | 19.45 | 2.21 | 9.89 | 11.02 | 18.98 | Au1rxx-base64 | 13.231.19.51 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | 0.848 | 263 | 1757 | prefer |
| Surfboard-tg-mixed | 0.821 | 0.745 | 110 | 7370 | prefer |
| DeltaKronecker-all | 0.774 | 0.706 | 34 | 6070 | prefer |
| mheidari-all | 0.734 | 0.66 | 50 | 15494 | prefer |
| ermaozi | 0.418 | 0.5 | 14 | 377 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7830 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8523 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5979 | observe |
| barry-far-vless | 0.255 | None | 0 | 6192 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1757 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 26 |
| cn-block | TimeoutError | - | 21 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyConnectionError | - | 7 |
| geo | TimeoutError | - | 5 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
