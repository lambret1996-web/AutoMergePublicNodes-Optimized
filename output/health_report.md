# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 05:16:44 |
| 运行耗时 | 835.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95256 |
| 去重后节点 | 26812 |
| TCP 可达 | 3000 |
| 真实可用 | 371 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26812 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 44.0 |
| probe | 302.4 |
| real_test | 441.0 |
| generate | 39.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57647 |
| vmess | 14879 |
| shadowsocks | 11467 |
| trojan | 8894 |
| hysteria2 | 1449 |
| http | 621 |
| shadowsocksr | 176 |
| socks | 76 |
| anytls | 24 |
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
| 80.27 | vless | 235.6 | 539.3 | 22.32 | 0.0 | 10.0 | 12.42 | 19.32 | mheidari-all | 216.227.161.95 |
| 80.03 | shadowsocks | 271.3 | 720.2 | 21.5 | 0.0 | 10.0 | 13.53 | 19.0 | Surfboard-tg-mixed | 37.19.198.244 |
| 80.01 | shadowsocks | 264.1 | 717.4 | 21.66 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | 37.19.198.243 |
| 80.0 | shadowsocks | 264.8 | 721.0 | 21.65 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | 37.19.198.236 |
| 79.5 | shadowsocks | 272.4 | 697.7 | 21.47 | 0.0 | 10.0 | 13.53 | 19.0 | Surfboard-tg-mixed | 140.82.63.79 |
| 78.86 | shadowsocks | 292.5 | 727.7 | 21.01 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 77.78 | hysteria2 | 308.8 | 295.3 | 20.63 | 3.93 | 8.08 | 14.32 | 18.82 | Au1rxx-base64 | open.w2m.ink |
| 77.58 | hysteria2 | 366.0 | 764.1 | 19.31 | 0.0 | 10.0 | 14.32 | 18.82 | Au1rxx-base64 | 192.255.128.123 |
| 77.35 | shadowsocks | 357.8 | 921.8 | 19.5 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | 185.156.47.97 |
| 77.2 | hysteria2 | 328.9 | 691.2 | 20.16 | 0.0 | 10.0 | 14.32 | 18.82 | Au1rxx-base64 | 66.94.121.46 |
| 76.91 | shadowsocks | 276.1 | 638.7 | 21.39 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | 156.146.38.168 |
| 76.91 | shadowsocks | 281.4 | 645.7 | 21.26 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | 156.146.38.169 |
| 76.23 | shadowsocks | 330.1 | 796.6 | 20.14 | 0.0 | 10.0 | 13.53 | 19.32 | mheidari-all | 51.222.200.165 |
| 75.82 | shadowsocks | 317.6 | 730.7 | 20.43 | 0.0 | 10.0 | 13.53 | 18.82 | Au1rxx-base64 | 108.181.57.93 |
| 75.73 | vless | 335.3 | 610.8 | 20.02 | 0.0 | 10.0 | 12.42 | 19.32 | mheidari-all | 47.251.108.158 |
| 75.71 | shadowsocks | 436.1 | 1224.4 | 17.68 | 0.0 | 10.0 | 13.53 | 19.0 | Surfboard-tg-mixed | 15.204.233.41 |
| 75.25 | shadowsocks | 240.1 | 627.2 | 22.22 | 0.0 | 10.0 | 13.53 | 19.0 | Surfboard-tg-mixed | 14.1.31.220 |
| 74.95 | hysteria2 | 402.9 | 747.1 | 18.45 | 0.0 | 9.9 | 14.32 | 19.32 | mheidari-all | 45.192.12.93 |
| 74.75 | hysteria2 | 418.0 | 857.8 | 18.1 | 0.0 | 10.0 | 14.32 | 19.0 | Surfboard-tg-mixed | 130.49.161.70 |
| 74.67 | shadowsocks | 385.3 | 907.8 | 18.86 | 0.0 | 10.0 | 13.53 | 19.32 | mheidari-all | 23.150.248.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.982 | 112 | 1437 | prefer |
| Surfboard-tg-mixed | 0.686 | 0.607 | 107 | 6916 | observe |
| ermaozi | 0.648 | 0.641 | 39 | 347 | observe |
| mheidari-all | 0.417 | 0.336 | 482 | 22305 | observe |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 5466 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7506 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9195 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5591 | observe |
| barry-far-vless | 0.255 | None | 0 | 5817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1437 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 170 |
| speed | TimeoutError | - | 84 |
| geo | ClientOSError | - | 57 |
| speed | ClientOSError | - | 22 |
| 204 | ProxyError | - | 20 |
| 204 | ProxyConnectionError | - | 10 |
| 204 | TimeoutError | - | 10 |
| cn-block | TimeoutError | - | 8 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
