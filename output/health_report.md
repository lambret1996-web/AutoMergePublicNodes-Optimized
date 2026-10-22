# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 03:54:21 |
| 运行耗时 | 687.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 91 |
| 原始节点 | 96952 |
| 去重后节点 | 27034 |
| TCP 可达 | 3000 |
| 真实可用 | 418 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27034 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 16.2 |
| geo | 1.7 |
| tcp | 44.9 |
| probe | 230.1 |
| real_test | 304.8 |
| generate | 89.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57679 |
| vmess | 17005 |
| shadowsocks | 12096 |
| trojan | 8433 |
| hysteria2 | 1279 |
| http | 194 |
| shadowsocksr | 167 |
| socks | 55 |
| anytls | 21 |
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
| 79.83 | hysteria2 | 264.6 | 645.4 | 21.65 | 0.0 | 10.0 | 12.86 | 16.82 | Au1rxx-base64 | 129.213.91.185 |
| 78.35 | hysteria2 | 279.5 | 255.1 | 21.31 | 5.43 | 9.63 | 12.86 | 16.82 | Au1rxx-base64 | 45.32.10.7 |
| 77.71 | shadowsocks | 236.1 | 619.1 | 22.31 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 156.146.38.168 |
| 77.27 | shadowsocks | 245.4 | 630.4 | 22.1 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 156.146.38.170 |
| 77.23 | hysteria2 | 279.5 | 270.0 | 21.31 | 4.87 | 9.07 | 12.86 | 16.82 | Au1rxx-base64 | vp3.yysyy.online |
| 77.18 | shadowsocks | 259.2 | 631.3 | 21.78 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 156.146.38.169 |
| 76.46 | shadowsocks | 289.0 | 711.8 | 21.09 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 37.19.198.243 |
| 75.99 | shadowsocks | 304.4 | 764.7 | 20.73 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 37.19.198.160 |
| 75.5 | vless | 341.7 | 729.7 | 19.87 | 0.0 | 10.0 | 9.27 | 16.36 | mheidari-all | 172.245.253.16 |
| 75.05 | vless | 310.3 | 718.2 | 20.6 | 0.0 | 10.0 | 9.27 | 16.82 | Au1rxx-base64 | 159.89.87.21 |
| 74.75 | hysteria2 | 279.8 | 646.0 | 21.3 | 0.0 | 10.0 | 12.86 | 16.82 | Au1rxx-base64 | clash2.deep-links.com |
| 74.75 | shadowsocks | 311.1 | 772.3 | 20.58 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 37.19.198.236 |
| 73.66 | vless | 395.5 | 985.6 | 18.62 | 0.0 | 10.0 | 9.27 | 16.82 | Au1rxx-base64 | 185.95.231.156 |
| 73.62 | shadowsocks | 304.4 | 745.0 | 20.73 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 37.19.198.244 |
| 73.14 | vless | 291.1 | 565.6 | 21.04 | 0.0 | 10.0 | 9.27 | 16.82 | Au1rxx-base64 | 144.202.126.147 |
| 72.96 | vless | 276.9 | 654.3 | 21.37 | 0.0 | 10.0 | 9.27 | 16.82 | Au1rxx-base64 | 69.48.201.136 |
| 72.65 | vless | 287.7 | 572.0 | 21.12 | 0.0 | 10.0 | 9.27 | 16.82 | Au1rxx-base64 | 45.32.69.110 |
| 72.45 | shadowsocks | 247.6 | 613.0 | 22.05 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 156.146.38.167 |
| 72.1 | trojan | 340.0 | 859.8 | 19.91 | 0.0 | 10.0 | 8.37 | 16.82 | Au1rxx-base64 | 66.23.203.21 |
| 72.03 | shadowsocks | 319.9 | 671.5 | 20.37 | 0.0 | 10.0 | 12.58 | 16.82 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.942 | 0.88 | 292 | 1599 | prefer |
| Surfboard-tg-mixed | 0.887 | 0.941 | 17 | 7097 | prefer |
| mheidari-all | 0.609 | 0.529 | 221 | 24252 | observe |
| zhangkai | 0.609 | 0.667 | 18 | 31 | observe |
| DeltaKronecker-all | 0.384 | 0.286 | 21 | 4067 | observe |
| ermaozi-get_subscribe | 0.335 | 0.303 | 33 | 523 | observe |
| Epodonios-all | 0.255 | None | 0 | 7591 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10125 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5559 | observe |
| barry-far-vless | 0.255 | None | 0 | 5773 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1599 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 69 |
| speed | ClientOSError | - | 25 |
| geo | ClientOSError | - | 21 |
| 204 | ProxyError | - | 20 |
| speed | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 8 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
