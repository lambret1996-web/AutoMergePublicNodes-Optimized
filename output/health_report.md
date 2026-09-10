# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 00:33:52 |
| 运行耗时 | 662.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83955 |
| 去重后节点 | 21995 |
| TCP 可达 | 3000 |
| 真实可用 | 504 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21995 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 36.6 |
| probe | 235.5 |
| real_test | 306.8 |
| generate | 75.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51432 |
| vmess | 12078 |
| shadowsocks | 9995 |
| trojan | 8059 |
| hysteria2 | 1641 |
| http | 554 |
| shadowsocksr | 126 |
| socks | 52 |
| hysteria | 8 |
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
| 83.41 | vless | 194.8 | 486.7 | 23.27 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 172.233.139.46 |
| 83.13 | vless | 206.7 | 520.3 | 22.99 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 172.235.38.85 |
| 81.87 | shadowsocks | 201.7 | 473.9 | 23.11 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 108.181.0.177 |
| 81.57 | shadowsocks | 236.1 | 515.0 | 22.31 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 173.244.56.6 |
| 81.42 | shadowsocks | 242.8 | 590.6 | 22.16 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 149.22.95.183 |
| 80.61 | vless | 315.7 | 818.1 | 20.47 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 15.204.97.216 |
| 80.5 | vless | 190.7 | 510.5 | 23.36 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 31.58.50.200 |
| 80.28 | shadowsocks | 282.3 | 664.3 | 21.24 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 173.244.56.9 |
| 77.61 | vless | 445.1 | 1205.8 | 17.47 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 51.81.203.63 |
| 77.16 | vless | 248.8 | 600.7 | 22.02 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 38.244.20.152 |
| 76.68 | vless | 240.1 | 567.1 | 22.22 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 38.246.229.58 |
| 76.5 | shadowsocks | 302.2 | 674.7 | 20.78 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 156.146.38.168 |
| 76.46 | shadowsocks | 297.0 | 671.9 | 20.9 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 156.146.38.169 |
| 76.46 | shadowsocks | 299.7 | 668.4 | 20.84 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 156.146.38.167 |
| 76.17 | shadowsocks | 292.8 | 637.9 | 21.0 | 0.0 | 10.0 | 13.8 | 19.46 | Au1rxx-base64 | 156.146.38.170 |
| 75.62 | vless | 315.4 | 739.5 | 20.48 | 0.0 | 10.0 | 10.68 | 19.46 | Au1rxx-base64 | 38.209.125.45 |
| 75.08 | vless | 253.6 | 287.9 | 21.91 | 4.2 | 9.91 | 10.68 | 15.34 | Surfboard-tg-mixed | 31.76.91.72 |
| 74.69 | vless | 337.2 | 340.7 | 19.97 | 2.22 | 9.88 | 10.68 | 19.46 | Au1rxx-base64 | 18.183.215.124 |
| 74.68 | vless | 336.3 | 340.0 | 19.99 | 2.25 | 9.86 | 10.68 | 19.46 | Au1rxx-base64 | 13.231.19.51 |
| 74.55 | vless | 336.6 | 343.3 | 19.99 | 2.12 | 9.86 | 10.68 | 19.46 | Au1rxx-base64 | 3.112.47.207 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | 0.93 | 284 | 1529 | prefer |
| Surfboard-tg-mixed | 0.872 | 0.795 | 200 | 7448 | prefer |
| ermaozi | 0.731 | 0.731 | 26 | 410 | prefer |
| mheidari-all | 0.695 | 0.619 | 63 | 16401 | observe |
| DeltaKronecker-all | 0.535 | 0.452 | 42 | 5187 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 147 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8855 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6108 | observe |
| barry-far-vless | 0.255 | None | 0 | 6329 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4247 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1529 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 28 |
| speed | TimeoutError | - | 22 |
| geo | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| 204 | ProxyError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
