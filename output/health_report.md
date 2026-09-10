# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 06:34:51 |
| 运行耗时 | 728.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87973 |
| 去重后节点 | 23200 |
| TCP 可达 | 3000 |
| 真实可用 | 543 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23200 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 40.4 |
| probe | 285.6 |
| real_test | 314.6 |
| generate | 80.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53569 |
| vmess | 12675 |
| shadowsocks | 10624 |
| trojan | 8448 |
| hysteria2 | 1762 |
| http | 685 |
| shadowsocksr | 125 |
| socks | 59 |
| hysteria | 12 |
| tuic | 9 |
| anytls | 5 |

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
| 82.3 | shadowsocks | 214.4 | 532.8 | 22.81 | 0.0 | 9.59 | 14.14 | 19.76 | Au1rxx-base64 | 173.244.56.9 |
| 81.55 | vless | 239.3 | 545.3 | 22.24 | 0.0 | 9.58 | 10.73 | 19.76 | Au1rxx-base64 | 31.58.50.200 |
| 81.52 | shadowsocks | 257.6 | 623.1 | 21.82 | 0.0 | 9.8 | 14.14 | 19.76 | Au1rxx-base64 | 156.146.38.167 |
| 81.41 | shadowsocks | 253.1 | 620.7 | 21.92 | 0.0 | 9.59 | 14.14 | 19.76 | Au1rxx-base64 | 173.244.56.6 |
| 81.23 | shadowsocks | 257.1 | 647.9 | 21.83 | 0.0 | 10.0 | 14.14 | 19.76 | Au1rxx-base64 | 108.181.118.10 |
| 81.2 | shadowsocks | 262.3 | 637.7 | 21.71 | 0.0 | 9.59 | 14.14 | 19.76 | Au1rxx-base64 | 156.146.38.170 |
| 80.82 | trojan | 206.8 | 527.1 | 22.99 | 0.0 | 8.32 | 12.75 | 19.76 | Au1rxx-base64 | us01.duotg.top |
| 80.33 | vless | 239.8 | 558.6 | 22.23 | 0.0 | 9.61 | 10.73 | 19.76 | Au1rxx-base64 | 38.246.229.58 |
| 80.11 | shadowsocks | 285.8 | 632.0 | 21.16 | 0.0 | 9.8 | 14.14 | 19.76 | Au1rxx-base64 | 23.150.248.20 |
| 79.14 | trojan | 207.6 | 523.5 | 22.97 | 0.0 | 9.66 | 12.75 | 19.76 | Au1rxx-base64 | 107.150.105.84 |
| 78.85 | shadowsocks | 260.3 | 634.6 | 21.75 | 0.0 | 10.0 | 14.14 | 17.44 | Surfboard-tg-mixed | 156.146.38.169 |
| 78.36 | vless | 346.4 | 839.5 | 19.76 | 0.0 | 9.83 | 10.73 | 19.76 | Au1rxx-base64 | 15.204.97.216 |
| 77.51 | shadowsocks | 289.4 | 626.6 | 21.08 | 0.0 | 9.69 | 14.14 | 19.76 | Au1rxx-base64 | 149.22.95.183 |
| 76.69 | vless | 292.4 | 273.7 | 21.01 | 4.74 | 9.81 | 10.73 | 17.44 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.18 | shadowsocks | 222.0 | 496.8 | 22.64 | 0.0 | 10.0 | 14.14 | 13.9 | mheidari-all | 108.181.0.177 |
| 75.82 | vless | 330.8 | 753.9 | 20.12 | 0.0 | 9.58 | 10.73 | 19.76 | Au1rxx-base64 | 79.141.172.154 |
| 75.59 | http | 195.1 | 484.3 | 23.26 | 0.0 | 10.0 | 10.71 | 14.62 | ermaozi | 138.199.35.198 |
| 75.5 | vless | 331.4 | 331.8 | 20.11 | 2.56 | 9.81 | 10.73 | 19.76 | Au1rxx-base64 | 130.12.102.62 |
| 75.44 | http | 201.7 | 496.8 | 23.11 | 0.0 | 10.0 | 10.71 | 14.62 | ermaozi | 138.199.35.216 |
| 75.34 | http | 205.8 | 496.8 | 23.01 | 0.0 | 10.0 | 10.71 | 14.62 | ermaozi | 138.199.35.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.953 | 0.888 | 277 | 1684 | prefer |
| Surfboard-tg-mixed | 0.85 | 0.773 | 181 | 7346 | prefer |
| ermaozi | 0.768 | 0.759 | 54 | 449 | prefer |
| DeltaKronecker-all | 0.725 | 0.655 | 29 | 5187 | prefer |
| mheidari-all | 0.725 | 0.647 | 139 | 16259 | prefer |
| xiaoji235-airport-v2ray-all | 0.465 | 0.714 | 7 | 3508 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7921 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8976 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5990 | observe |
| barry-far-vless | 0.255 | None | 0 | 6344 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1684 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 31 |
| 204 | ProxyError | - | 22 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 16 |
| geo | TimeoutError | - | 16 |
| cn-block | ClientOSError | - | 13 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
