# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 16:41:10 |
| 运行耗时 | 668.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 100051 |
| 去重后节点 | 27882 |
| TCP 可达 | 3000 |
| 真实可用 | 368 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27882 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 48.1 |
| probe | 270.3 |
| real_test | 255.5 |
| generate | 85.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59036 |
| vmess | 16501 |
| shadowsocks | 11998 |
| trojan | 10370 |
| hysteria2 | 1209 |
| http | 660 |
| shadowsocksr | 170 |
| socks | 57 |
| anytls | 27 |
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
| 83.33 | hysteria2 | 252.7 | 686.5 | 21.93 | 0.0 | 10.0 | 14.06 | 18.84 | Au1rxx-base64 | 129.213.91.185 |
| 79.53 | vless | 260.9 | 687.0 | 21.74 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 167.17.69.171 |
| 79.22 | vless | 260.5 | 627.4 | 21.75 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 195.211.98.43 |
| 79.16 | vless | 276.7 | 715.2 | 21.37 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 159.89.87.21 |
| 78.96 | vless | 242.3 | 646.6 | 22.17 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 147.45.60.160 |
| 78.61 | vless | 282.6 | 697.1 | 21.24 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 66.70.179.198 |
| 77.89 | vless | 331.8 | 919.2 | 20.1 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 185.95.231.156 |
| 77.62 | shadowsocks | 257.4 | 721.1 | 21.82 | 0.0 | 10.0 | 13.96 | 18.84 | Au1rxx-base64 | 37.19.198.243 |
| 77.4 | shadowsocks | 287.8 | 644.3 | 21.12 | 0.0 | 10.0 | 13.96 | 18.84 | Au1rxx-base64 | 156.146.38.167 |
| 76.97 | vless | 257.6 | 698.2 | 21.81 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 137.184.218.169 |
| 76.08 | vless | 280.3 | 738.3 | 21.29 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 195.123.235.183 |
| 74.35 | trojan | 526.3 | 1471.6 | 15.6 | 0.0 | 10.0 | 12.91 | 18.84 | Au1rxx-base64 | 69.164.240.85 |
| 73.59 | vless | 323.1 | 898.8 | 20.3 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 104.243.33.154 |
| 73.01 | shadowsocks | 277.4 | 639.4 | 21.36 | 0.0 | 10.0 | 13.96 | 18.84 | Au1rxx-base64 | 156.146.38.168 |
| 72.92 | vless | 295.3 | 668.4 | 20.94 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 69.48.201.136 |
| 72.85 | vless | 290.2 | 646.1 | 21.06 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 104.21.70.22 |
| 72.41 | shadowsocks | 373.7 | 966.9 | 19.13 | 0.0 | 10.0 | 13.96 | 18.84 | Au1rxx-base64 | 51.222.136.236 |
| 71.98 | vless | 389.4 | 888.7 | 18.76 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 216.227.161.95 |
| 71.87 | vless | 255.1 | 662.9 | 21.87 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 71.27 | vless | 367.4 | 714.7 | 19.27 | 0.0 | 10.0 | 8.95 | 18.84 | Au1rxx-base64 | 178.17.57.33 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | 0.801 | 417 | 1767 | prefer |
| mheidari-all | 0.555 | 0.529 | 17 | 24080 | observe |
| Surfboard-tg-mixed | 0.352 | 0.5 | 6 | 7281 | observe |
| ermaozi | 0.298 | 0.265 | 68 | 659 | observe |
| ermaozi-get_subscribe | 0.289 | 0.667 | 3 | 519 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7794 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10074 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5707 | observe |
| barry-far-vless | 0.255 | None | 0 | 5961 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 38 |
| 204 | TimeoutError | - | 27 |
| 204 | ProxyConnectionError | - | 21 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 8 |
| geo | ClientOSError | - | 7 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
