# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 16:59:32 |
| 运行耗时 | 566.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 96135 |
| 去重后节点 | 26661 |
| TCP 可达 | 3000 |
| 真实可用 | 344 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26661 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 44.2 |
| probe | 235.7 |
| real_test | 186.0 |
| generate | 91.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58744 |
| vmess | 14609 |
| shadowsocks | 11292 |
| trojan | 9175 |
| hysteria2 | 1454 |
| http | 574 |
| shadowsocksr | 170 |
| socks | 69 |
| anytls | 25 |
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
| 81.17 | vless | 221.3 | 568.6 | 22.65 | 0.0 | 10.0 | 10.5 | 18.02 | Au1rxx-base64 | 51.81.203.63 |
| 80.59 | vless | 246.6 | 661.9 | 22.07 | 0.0 | 10.0 | 10.5 | 18.02 | Au1rxx-base64 | 5.78.159.214 |
| 80.26 | vless | 239.6 | 537.5 | 22.23 | 0.0 | 10.0 | 10.5 | 18.02 | Au1rxx-base64 | 137.175.82.40 |
| 79.52 | shadowsocks | 217.0 | 582.1 | 22.75 | 0.0 | 10.0 | 12.75 | 18.02 | Au1rxx-base64 | 149.22.95.183 |
| 78.31 | vless | 215.3 | 559.4 | 22.79 | 0.0 | 10.0 | 10.5 | 18.02 | Au1rxx-base64 | 15.204.97.216 |
| 78.17 | vless | 261.7 | 565.8 | 21.72 | 0.0 | 10.0 | 10.5 | 18.02 | Au1rxx-base64 | 172.235.43.210 |
| 77.9 | hysteria2 | 233.7 | 279.2 | 22.37 | 4.53 | 6.66 | 12.86 | 18.02 | Au1rxx-base64 | open.w2m.ink |
| 77.22 | vless | 260.7 | 559.9 | 21.74 | 0.0 | 8.87 | 10.5 | 18.02 | Au1rxx-base64 | 192.3.247.109 |
| 75.97 | vless | 230.2 | 586.3 | 22.45 | 0.0 | 10.0 | 10.5 | 18.02 | Au1rxx-base64 | 15.204.97.206 |
| 75.85 | shadowsocks | 197.6 | 525.3 | 23.2 | 0.0 | 10.0 | 12.75 | 14.4 | Surfboard-tg-mixed | 5.78.51.123 |
| 74.89 | shadowsocks | 259.5 | 272.6 | 21.77 | 4.78 | 8.49 | 12.75 | 18.02 | Au1rxx-base64 | 149.22.87.241 |
| 74.22 | hysteria2 | 267.2 | 548.7 | 21.59 | 0.0 | 10.0 | 12.86 | 18.02 | Au1rxx-base64 | 192.255.128.123 |
| 73.01 | vless | 358.8 | 298.7 | 19.47 | 3.8 | 8.51 | 10.5 | 18.02 | Au1rxx-base64 | 43.133.11.187 |
| 72.71 | shadowsocks | 275.2 | 320.5 | 21.41 | 2.98 | 8.5 | 12.75 | 18.02 | Au1rxx-base64 | 149.22.87.204 |
| 72.46 | shadowsocks | 250.9 | 573.2 | 21.97 | 0.0 | 10.0 | 12.75 | 18.02 | Au1rxx-base64 | 173.234.25.93 |
| 72.27 | vless | 321.7 | 342.0 | 20.33 | 2.17 | 8.59 | 10.5 | 18.02 | Au1rxx-base64 | 18.183.215.124 |
| 71.97 | shadowsocks | 293.6 | 681.4 | 20.98 | 0.0 | 10.0 | 12.75 | 18.02 | Au1rxx-base64 | 153.75.232.60 |
| 71.79 | shadowsocks | 350.0 | 774.7 | 19.68 | 0.0 | 10.0 | 12.75 | 18.02 | Au1rxx-base64 | 23.150.248.20 |
| 71.54 | vless | 278.2 | 573.3 | 21.34 | 0.0 | 8.87 | 10.5 | 18.02 | Au1rxx-base64 | 195.123.240.65 |
| 71.12 | shadowsocks | 314.7 | 669.0 | 20.49 | 0.0 | 8.85 | 12.75 | 18.02 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.895 | 0.827 | 52 | 22413 | prefer |
| Au1rxx-base64 | 0.838 | 0.775 | 307 | 1601 | prefer |
| Surfboard-tg-mixed | 0.794 | 0.722 | 54 | 7109 | prefer |
| ermaozi | 0.57 | 0.562 | 32 | 289 | observe |
| DeltaKronecker-all | 0.465 | 0.714 | 7 | 5466 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7600 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9194 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5703 | observe |
| barry-far-vless | 0.255 | None | 0 | 5938 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4277 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1601 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| geo | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 15 |
| speed | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 9 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
