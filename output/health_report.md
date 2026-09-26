# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 16:22:36 |
| 运行耗时 | 499.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96925 |
| 去重后节点 | 26334 |
| TCP 可达 | 3000 |
| 真实可用 | 379 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26334 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 42.8 |
| probe | 205.4 |
| real_test | 163.8 |
| generate | 81.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58929 |
| vmess | 15338 |
| shadowsocks | 11307 |
| trojan | 8923 |
| hysteria2 | 1517 |
| http | 609 |
| shadowsocksr | 173 |
| socks | 78 |
| anytls | 25 |
| hysteria | 15 |
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
| 79.81 | shadowsocks | 243.3 | 613.3 | 22.15 | 0.0 | 9.87 | 12.95 | 18.84 | Au1rxx-base64 | 156.146.38.168 |
| 79.67 | vless | 277.2 | 664.0 | 21.36 | 0.0 | 9.82 | 9.65 | 18.84 | Au1rxx-base64 | 198.251.78.29 |
| 78.25 | shadowsocks | 313.7 | 761.7 | 20.52 | 0.0 | 9.96 | 12.95 | 18.84 | Au1rxx-base64 | 37.19.198.243 |
| 77.58 | vless | 288.9 | 729.8 | 21.09 | 0.0 | 9.86 | 9.65 | 18.84 | Au1rxx-base64 | 79.141.172.154 |
| 76.75 | shadowsocks | 353.6 | 933.2 | 19.59 | 0.0 | 9.87 | 12.95 | 18.84 | Au1rxx-base64 | 185.156.47.97 |
| 75.52 | vless | 368.2 | 765.4 | 19.26 | 0.0 | 9.86 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.225 |
| 75.48 | vless | 358.6 | 786.2 | 19.48 | 0.0 | 9.83 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.173 |
| 75.44 | shadowsocks | 255.1 | 631.7 | 21.87 | 0.0 | 10.0 | 12.95 | 14.62 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.03 | vless | 340.2 | 676.9 | 19.9 | 0.0 | 9.84 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.89 |
| 74.76 | shadowsocks | 263.1 | 604.4 | 21.69 | 0.0 | 10.0 | 12.95 | 14.62 | Surfboard-tg-mixed | 23.150.248.20 |
| 74.76 | vless | 292.6 | 589.4 | 21.0 | 0.0 | 9.81 | 9.65 | 18.84 | Au1rxx-base64 | 172.235.43.210 |
| 74.37 | vless | 341.7 | 749.7 | 19.87 | 0.0 | 9.84 | 9.65 | 18.84 | Au1rxx-base64 | 5.78.159.214 |
| 74.21 | shadowsocks | 326.0 | 615.4 | 20.23 | 0.0 | 9.98 | 12.95 | 18.84 | Au1rxx-base64 | 149.22.95.183 |
| 74.19 | vless | 348.3 | 792.9 | 19.72 | 0.0 | 9.86 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.75 |
| 74.14 | shadowsocks | 265.4 | 605.6 | 21.63 | 0.0 | 10.0 | 12.95 | 14.62 | Surfboard-tg-mixed | 198.98.53.130 |
| 73.73 | vless | 451.8 | 997.0 | 17.32 | 0.0 | 9.84 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.212 |
| 73.45 | shadowsocks | 294.3 | 610.2 | 20.97 | 0.0 | 9.96 | 12.95 | 18.84 | Au1rxx-base64 | 173.244.56.6 |
| 73.38 | vless | 432.3 | 957.2 | 17.77 | 0.0 | 9.86 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.104 |
| 73.16 | vless | 355.8 | 696.4 | 19.54 | 0.0 | 9.81 | 9.65 | 18.84 | Au1rxx-base64 | 137.175.82.40 |
| 73.14 | vless | 464.3 | 1007.4 | 17.03 | 0.0 | 9.83 | 9.65 | 18.84 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | 0.899 | 268 | 1642 | prefer |
| Surfboard-tg-mixed | 0.816 | 0.741 | 108 | 7263 | prefer |
| mheidari-all | 0.781 | 0.708 | 65 | 22551 | prefer |
| ermaozi | 0.433 | 0.444 | 18 | 296 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7742 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9122 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6056 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1642 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 39 |
| 204 | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 3 |
| speed | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
