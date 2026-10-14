# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 04:11:03 |
| 运行耗时 | 842.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98589 |
| 去重后节点 | 27425 |
| TCP 可达 | 3000 |
| 真实可用 | 469 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27425 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 47.2 |
| probe | 308.7 |
| real_test | 388.5 |
| generate | 88.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58021 |
| vmess | 16099 |
| shadowsocks | 11896 |
| trojan | 10493 |
| hysteria2 | 1310 |
| http | 486 |
| shadowsocksr | 165 |
| socks | 70 |
| anytls | 25 |
| hysteria | 18 |
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
| 84.74 | vless | 198.3 | 503.1 | 23.19 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 144.202.126.147 |
| 84.74 | hysteria2 | 223.5 | 227.8 | 22.6 | 6.46 | 9.94 | 12.86 | 19.62 | Au1rxx-base64 | 45.32.10.7 |
| 84.44 | vless | 211.0 | 505.1 | 22.89 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 154.29.145.196 |
| 84.18 | vless | 222.3 | 544.1 | 22.63 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 195.123.240.65 |
| 84.13 | vless | 224.5 | 526.4 | 22.58 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 154.9.241.170 |
| 83.31 | vless | 172.8 | 456.2 | 23.78 | 0.0 | 10.0 | 11.93 | 17.6 | mheidari-all | 47.251.108.158 |
| 82.65 | vless | 287.5 | 683.1 | 21.12 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 154.12.38.159 |
| 81.6 | vless | 319.1 | 672.8 | 20.39 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 95.111.212.241 |
| 81.57 | trojan | 253.4 | 596.0 | 21.91 | 0.0 | 9.78 | 12.76 | 19.62 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 81.49 | vless | 209.2 | 508.0 | 22.94 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 45.32.69.110 |
| 81.23 | shadowsocks | 229.2 | 543.3 | 22.47 | 0.0 | 10.0 | 13.14 | 19.62 | Au1rxx-base64 | 173.244.56.9 |
| 81.16 | shadowsocks | 232.3 | 550.1 | 22.4 | 0.0 | 10.0 | 13.14 | 19.62 | Au1rxx-base64 | 173.244.56.6 |
| 80.4 | vless | 228.2 | 494.0 | 22.49 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 154.40.55.185 |
| 79.23 | vless | 220.3 | 590.5 | 22.68 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 140.82.50.205 |
| 78.81 | vless | 395.5 | 1008.2 | 18.62 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 51.81.203.63 |
| 77.43 | hysteria2 | 346.0 | 762.0 | 19.77 | 0.0 | 10.0 | 12.86 | 19.62 | Au1rxx-base64 | 129.213.91.185 |
| 77.4 | shadowsocks | 272.7 | 281.7 | 21.47 | 4.44 | 9.94 | 13.14 | 19.62 | Au1rxx-base64 | 149.22.87.204 |
| 77.07 | vless | 293.2 | 691.3 | 20.99 | 0.0 | 10.0 | 11.93 | 19.62 | Au1rxx-base64 | 44.248.233.99 |
| 76.81 | vless | 327.5 | 332.6 | 20.2 | 2.53 | 9.94 | 11.93 | 19.62 | Au1rxx-base64 | 142.91.108.25 |
| 76.69 | vless | 313.2 | 758.2 | 20.53 | 0.0 | 4.61 | 11.93 | 19.62 | Au1rxx-base64 | tk1.high-speed-test-56424.me |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | 0.886 | 350 | 1771 | prefer |
| Surfboard-tg-mixed | 0.609 | 0.75 | 12 | 7113 | observe |
| mheidari-all | 0.56 | 0.48 | 248 | 24076 | observe |
| zhangkai | 0.494 | 0.875 | 8 | 144 | observe |
| ermaozi-get_subscribe | 0.466 | 0.439 | 41 | 598 | observe |
| DeltaKronecker-all | 0.45 | 0.5 | 12 | 5076 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7613 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9824 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5621 | observe |
| barry-far-vless | 0.255 | None | 0 | 5866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1771 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 88 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyError | - | 23 |
| geo | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 15 |
| 204 | ProxyConnectionError | - | 10 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
