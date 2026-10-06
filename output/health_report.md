# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 18:13:04 |
| 运行耗时 | 611.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97513 |
| 去重后节点 | 27042 |
| TCP 可达 | 3000 |
| 真实可用 | 448 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27042 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.3 |
| tcp | 45.5 |
| probe | 285.2 |
| real_test | 191.4 |
| generate | 80.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57314 |
| vmess | 15946 |
| shadowsocks | 11669 |
| trojan | 10123 |
| hysteria2 | 1419 |
| http | 717 |
| shadowsocksr | 172 |
| socks | 92 |
| anytls | 36 |
| hysteria | 17 |
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
| 84.23 | hysteria2 | 273.3 | 783.1 | 21.45 | 0.0 | 10.0 | 14.32 | 19.96 | Au1rxx-base64 | 129.213.91.185 |
| 81.51 | shadowsocks | 259.5 | 716.7 | 21.77 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 37.19.198.236 |
| 79.8 | shadowsocks | 311.7 | 815.4 | 20.56 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 140.82.63.79 |
| 79.44 | hysteria2 | 334.1 | 280.4 | 20.04 | 4.49 | 8.83 | 14.32 | 19.96 | Au1rxx-base64 | open.2ml.bid |
| 78.65 | shadowsocks | 253.4 | 692.8 | 21.91 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 37.19.198.160 |
| 77.64 | vless | 289.4 | 718.0 | 21.08 | 0.0 | 10.0 | 6.6 | 19.96 | Au1rxx-base64 | 66.70.179.198 |
| 77.54 | shadowsocks | 323.1 | 907.5 | 20.3 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 15.204.247.206 |
| 77.53 | shadowsocks | 325.9 | 778.2 | 20.23 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 156.146.38.167 |
| 77.16 | vless | 310.1 | 854.3 | 20.6 | 0.0 | 10.0 | 6.6 | 19.96 | Au1rxx-base64 | 159.89.87.21 |
| 76.96 | shadowsocks | 308.9 | 697.1 | 20.63 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 108.181.57.93 |
| 76.22 | vless | 350.6 | 976.6 | 19.66 | 0.0 | 10.0 | 6.6 | 19.96 | Au1rxx-base64 | 185.95.231.156 |
| 75.93 | vless | 363.1 | 947.0 | 19.37 | 0.0 | 10.0 | 6.6 | 19.96 | Au1rxx-base64 | 2.24.124.64 |
| 75.73 | shadowsocks | 333.7 | 821.0 | 20.05 | 0.0 | 10.0 | 13.78 | 16.4 | Surfboard-tg-mixed | 66.23.204.210 |
| 75.18 | vless | 390.6 | 788.7 | 18.74 | 0.0 | 10.0 | 6.6 | 19.96 | Au1rxx-base64 | 137.184.218.169 |
| 74.3 | shadowsocks | 281.4 | 652.4 | 21.26 | 0.0 | 10.0 | 13.78 | 16.4 | Surfboard-tg-mixed | 156.146.38.169 |
| 73.77 | shadowsocks | 347.3 | 673.8 | 19.74 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 149.22.95.183 |
| 73.39 | shadowsocks | 340.8 | 638.0 | 19.89 | 0.0 | 10.0 | 13.78 | 19.96 | Au1rxx-base64 | 108.181.118.10 |
| 73.27 | hysteria2 | 339.7 | 321.0 | 19.91 | 2.96 | 9.23 | 14.32 | 19.96 | Au1rxx-base64 | 158.101.148.79 |
| 72.33 | vless | 324.2 | 637.6 | 20.27 | 0.0 | 10.0 | 6.6 | 19.96 | Au1rxx-base64 | 172.64.53.55 |
| 72.26 | hysteria2 | 298.6 | 832.1 | 20.86 | 0.0 | 10.0 | 14.32 | 8.18 | mheidari-all | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | 0.893 | 309 | 1828 | prefer |
| mheidari-all | 0.864 | 0.796 | 49 | 23142 | prefer |
| Surfboard-tg-mixed | 0.772 | 0.695 | 128 | 7117 | prefer |
| ermaozi | 0.528 | 0.5 | 80 | 708 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 4889 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7535 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9111 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5711 | observe |
| barry-far-vless | 0.255 | None | 0 | 5822 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4373 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1828 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 49 |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 22 |
| speed | ClientOSError | - | 8 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
