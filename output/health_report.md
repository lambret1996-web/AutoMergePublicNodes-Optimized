# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 03:48:59 |
| 运行耗时 | 855.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99761 |
| 去重后节点 | 27953 |
| TCP 可达 | 3000 |
| 真实可用 | 498 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27953 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 49.3 |
| probe | 284.2 |
| real_test | 434.4 |
| generate | 80.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58950 |
| vmess | 16452 |
| shadowsocks | 11830 |
| trojan | 10318 |
| hysteria2 | 1225 |
| http | 713 |
| shadowsocksr | 166 |
| socks | 59 |
| anytls | 25 |
| hysteria | 17 |
| tuic | 6 |

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
| 79.79 | shadowsocks | 216.4 | 528.6 | 22.77 | 0.0 | 10.0 | 13.62 | 17.4 | Au1rxx-base64 | 173.244.56.6 |
| 76.98 | hysteria2 | 181.2 | 491.6 | 23.58 | 0.0 | 10.0 | 12.0 | 17.4 | Au1rxx-base64 | 179.255.104.98 |
| 76.22 | shadowsocks | 284.9 | 434.2 | 21.18 | 0.0 | 8.52 | 13.62 | 17.4 | Au1rxx-base64 | 103.11.76.248 |
| 75.63 | vless | 264.6 | 510.6 | 21.65 | 0.0 | 8.46 | 10.18 | 17.4 | Au1rxx-base64 | 95.111.212.241 |
| 75.57 | vless | 206.6 | 526.0 | 22.99 | 0.0 | 10.0 | 10.18 | 17.4 | Au1rxx-base64 | 154.29.159.211 |
| 74.24 | vless | 201.9 | 503.7 | 23.1 | 0.0 | 8.56 | 10.18 | 17.4 | Au1rxx-base64 | 216.234.140.15 |
| 74.06 | vless | 216.0 | 502.5 | 22.78 | 0.0 | 10.0 | 10.18 | 11.1 | mheidari-all | 47.251.108.158 |
| 73.79 | hysteria2 | 322.8 | 750.3 | 20.3 | 0.0 | 8.6 | 12.0 | 17.4 | Au1rxx-base64 | 129.213.91.185 |
| 73.35 | shadowsocks | 342.6 | 878.0 | 19.85 | 0.0 | 8.41 | 13.62 | 17.4 | Au1rxx-base64 | 156.146.38.167 |
| 73.25 | shadowsocks | 300.1 | 757.1 | 20.83 | 0.0 | 8.4 | 13.62 | 17.4 | Au1rxx-base64 | 156.146.38.168 |
| 73.21 | trojan | 307.0 | 801.2 | 20.67 | 0.0 | 8.58 | 14.56 | 17.4 | Au1rxx-base64 | 107.149.159.190 |
| 72.99 | vless | 296.7 | 613.0 | 20.91 | 0.0 | 8.5 | 10.18 | 17.4 | Au1rxx-base64 | 44.248.233.99 |
| 72.61 | vless | 225.9 | 498.6 | 22.55 | 0.0 | 8.58 | 10.18 | 17.4 | Au1rxx-base64 | 172.66.47.45 |
| 72.51 | vless | 247.7 | 511.8 | 22.04 | 0.0 | 10.0 | 10.18 | 17.4 | Au1rxx-base64 | 8.47.69.6 |
| 72.32 | shadowsocks | 254.2 | 621.1 | 21.89 | 0.0 | 8.41 | 13.62 | 17.4 | Au1rxx-base64 | 156.146.38.170 |
| 71.86 | vless | 270.7 | 670.1 | 21.51 | 0.0 | 10.0 | 10.18 | 17.4 | Au1rxx-base64 | 172.66.44.211 |
| 71.73 | vless | 329.5 | 725.1 | 20.15 | 0.0 | 7.55 | 10.18 | 17.4 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 71.58 | trojan | 356.9 | 327.7 | 19.52 | 2.71 | 8.41 | 14.56 | 17.4 | Au1rxx-base64 | 108.61.186.37 |
| 71.2 | shadowsocks | 300.8 | 336.4 | 20.81 | 2.38 | 8.39 | 13.62 | 17.4 | Au1rxx-base64 | 149.22.87.241 |
| 71.18 | shadowsocks | 312.9 | 330.6 | 20.53 | 2.6 | 8.39 | 13.62 | 17.4 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.838 | 0.759 | 557 | 1991 | prefer |
| ermaozi | 0.687 | 0.667 | 42 | 693 | observe |
| Surfboard-tg-mixed | 0.349 | 0.667 | 3 | 7135 | observe |
| mheidari-all | 0.337 | 0.255 | 165 | 23985 | observe |
| DeltaKronecker-all | 0.305 | 0.3 | 10 | 5147 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 7647 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9903 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5628 | observe |
| barry-far-vless | 0.255 | None | 0 | 5878 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 106 |
| speed | TimeoutError | - | 39 |
| speed | ClientOSError | - | 34 |
| 204 | TimeoutError | - | 25 |
| 204 | ProxyError | - | 21 |
| geo | ClientOSError | - | 20 |
| cn-block | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 11 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ClientPayloadError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
