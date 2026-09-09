# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 00:43:03 |
| 运行耗时 | 915.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85335 |
| 去重后节点 | 22916 |
| TCP 可达 | 3000 |
| 真实可用 | 576 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22916 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.4 |
| tcp | 37.5 |
| probe | 308.8 |
| real_test | 483.3 |
| generate | 78.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52698 |
| vmess | 11909 |
| shadowsocks | 9910 |
| trojan | 8375 |
| hysteria2 | 1655 |
| http | 569 |
| shadowsocksr | 128 |
| socks | 69 |
| hysteria | 11 |
| tuic | 8 |
| anytls | 3 |

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
| 81.04 | shadowsocks | 229.5 | 593.9 | 22.46 | 0.0 | 10.0 | 13.62 | 18.96 | Au1rxx-base64 | 198.98.53.130 |
| 81.02 | vless | 247.6 | 616.4 | 22.05 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 195.123.235.177 |
| 80.82 | vless | 256.1 | 644.1 | 21.85 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.224 |
| 80.56 | shadowsocks | 250.6 | 670.4 | 21.98 | 0.0 | 10.0 | 13.62 | 18.96 | Au1rxx-base64 | 37.19.198.244 |
| 80.38 | vless | 259.6 | 647.7 | 21.77 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.74 |
| 79.98 | vless | 292.4 | 720.5 | 21.01 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 66.70.179.198 |
| 79.98 | vless | 292.4 | 628.8 | 21.01 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.52 |
| 79.75 | hysteria2 | 247.5 | 657.4 | 22.05 | 0.0 | 10.0 | 13.12 | 15.68 | Surfboard-tg-mixed | 159.223.157.129 |
| 79.64 | vless | 276.5 | 699.2 | 21.38 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.229 |
| 79.63 | vless | 307.6 | 680.4 | 20.66 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.104 |
| 78.93 | vless | 337.6 | 882.6 | 19.96 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.75 |
| 78.92 | vless | 338.1 | 828.4 | 19.95 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.235 |
| 78.84 | vless | 255.4 | 700.5 | 21.87 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 47.253.226.114 |
| 78.62 | vless | 351.0 | 883.2 | 19.65 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.182 |
| 78.36 | vless | 362.3 | 843.6 | 19.39 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.179 |
| 78.32 | shadowsocks | 325.8 | 919.2 | 20.24 | 0.0 | 10.0 | 13.62 | 18.96 | Au1rxx-base64 | 15.204.246.189 |
| 78.21 | vless | 368.9 | 860.1 | 19.24 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.223 |
| 78.11 | vless | 308.5 | 668.6 | 20.64 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.90 |
| 77.9 | vless | 364.4 | 910.1 | 19.34 | 0.0 | 10.0 | 10.01 | 18.96 | Au1rxx-base64 | 169.40.42.231 |
| 77.81 | shadowsocks | 279.3 | 642.6 | 21.31 | 0.0 | 10.0 | 13.62 | 18.96 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | 0.906 | 267 | 1704 | prefer |
| Surfboard-tg-mixed | 0.875 | 0.798 | 213 | 7518 | prefer |
| ermaozi | 0.655 | 0.647 | 34 | 409 | observe |
| mheidari-all | 0.644 | 0.564 | 179 | 16624 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| DeltaKronecker-all | 0.276 | 0.193 | 207 | 6097 | observe |
| Epodonios-all | 0.255 | None | 0 | 7966 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8721 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6168 | observe |
| barry-far-vless | 0.255 | None | 0 | 6313 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1704 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 140 |
| geo | ClientOSError | - | 54 |
| speed | TimeoutError | - | 52 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 7 |
| 204 | ProxyConnectionError | - | 5 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
