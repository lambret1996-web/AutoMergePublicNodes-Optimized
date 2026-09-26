# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 11:22:55 |
| 运行耗时 | 591.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96784 |
| 去重后节点 | 26417 |
| TCP 可达 | 3000 |
| 真实可用 | 369 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26417 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.5 |
| tcp | 43.6 |
| probe | 283.7 |
| real_test | 174.5 |
| generate | 80.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58833 |
| vmess | 15182 |
| shadowsocks | 11225 |
| trojan | 8968 |
| hysteria2 | 1571 |
| http | 672 |
| shadowsocksr | 176 |
| socks | 98 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 12 |

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
| 79.54 | shadowsocks | 218.7 | 549.9 | 22.72 | 0.0 | 9.02 | 13.78 | 18.02 | Au1rxx-base64 | 173.244.56.9 |
| 78.65 | shadowsocks | 247.5 | 603.1 | 22.05 | 0.0 | 10.0 | 13.78 | 17.32 | Surfboard-tg-mixed | 108.181.0.177 |
| 78.25 | shadowsocks | 230.3 | 535.7 | 22.45 | 0.0 | 10.0 | 13.78 | 18.02 | Au1rxx-base64 | 173.244.56.6 |
| 77.49 | shadowsocks | 265.0 | 629.6 | 21.64 | 0.0 | 10.0 | 13.78 | 17.32 | Surfboard-tg-mixed | 5.78.51.123 |
| 76.4 | vless | 202.2 | 534.6 | 23.1 | 0.0 | 10.0 | 5.98 | 17.32 | Surfboard-tg-mixed | 172.235.38.85 |
| 76.18 | vless | 192.5 | 505.7 | 23.32 | 0.0 | 8.86 | 5.98 | 18.02 | Au1rxx-base64 | 172.235.43.210 |
| 76.08 | hysteria2 | 261.5 | 598.7 | 21.72 | 0.0 | 9.04 | 12.5 | 18.02 | Au1rxx-base64 | 66.94.121.46 |
| 75.47 | vless | 229.1 | 538.2 | 22.47 | 0.0 | 9.0 | 5.98 | 18.02 | Au1rxx-base64 | 195.123.240.65 |
| 73.53 | shadowsocks | 372.6 | 872.7 | 19.15 | 0.0 | 10.0 | 13.78 | 18.02 | Au1rxx-base64 | 149.22.95.183 |
| 73.48 | vless | 223.7 | 583.7 | 22.6 | 0.0 | 8.88 | 5.98 | 18.02 | Au1rxx-base64 | 38.244.20.25 |
| 72.9 | vless | 217.2 | 511.6 | 22.75 | 0.0 | 8.86 | 5.98 | 18.02 | Au1rxx-base64 | 137.175.82.40 |
| 72.46 | shadowsocks | 325.3 | 664.8 | 20.25 | 0.0 | 10.0 | 13.78 | 17.32 | Surfboard-tg-mixed | 198.98.53.130 |
| 72.23 | shadowsocks | 303.3 | 352.7 | 20.76 | 1.77 | 9.91 | 13.78 | 17.32 | Surfboard-tg-mixed | 149.22.87.240 |
| 72.03 | shadowsocks | 303.3 | 352.1 | 20.76 | 1.8 | 9.06 | 13.78 | 18.02 | Au1rxx-base64 | 149.22.87.204 |
| 71.85 | vless | 328.6 | 786.0 | 20.17 | 0.0 | 10.0 | 5.98 | 17.32 | Surfboard-tg-mixed | 5.78.159.214 |
| 71.33 | shadowsocks | 366.9 | 807.8 | 19.29 | 0.0 | 9.06 | 13.78 | 18.02 | Au1rxx-base64 | 37.19.198.243 |
| 71.27 | vless | 217.7 | 516.8 | 22.74 | 0.0 | 9.03 | 5.98 | 18.02 | Au1rxx-base64 | 172.64.32.103 |
| 70.42 | vless | 326.8 | 751.8 | 20.21 | 0.0 | 8.86 | 5.98 | 18.02 | Au1rxx-base64 | 79.141.172.154 |
| 70.37 | hysteria2 | 375.2 | 668.6 | 19.09 | 0.0 | 7.76 | 12.5 | 18.02 | Au1rxx-base64 | open.w2m.ink |
| 70.35 | shadowsocks | 365.3 | 806.5 | 19.32 | 0.0 | 8.97 | 13.78 | 18.02 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.942 | 0.879 | 231 | 1660 | prefer |
| Surfboard-tg-mixed | 0.731 | 0.654 | 127 | 7247 | prefer |
| mheidari-all | 0.657 | 0.578 | 102 | 22392 | observe |
| ermaozi | 0.477 | 0.462 | 39 | 352 | observe |
| DeltaKronecker-all | 0.421 | 0.667 | 6 | 5512 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7713 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8992 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5840 | observe |
| barry-far-vless | 0.255 | None | 0 | 6071 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 33 |
| 204 | ProxyError | - | 25 |
| cn-block | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 14 |
| geo | TimeoutError | - | 14 |
| speed | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| geo | ClientOSError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
