# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 18:28:50 |
| 运行耗时 | 484.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 97372 |
| 去重后节点 | 26673 |
| TCP 可达 | 3000 |
| 真实可用 | 404 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26673 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 43.7 |
| probe | 194.8 |
| real_test | 164.9 |
| generate | 73.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60014 |
| vmess | 14745 |
| shadowsocks | 11171 |
| trojan | 8989 |
| hysteria2 | 1535 |
| http | 612 |
| shadowsocksr | 174 |
| socks | 81 |
| anytls | 25 |
| hysteria | 18 |
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
| 80.74 | shadowsocks | 253.5 | 625.3 | 21.91 | 0.0 | 9.64 | 13.82 | 19.86 | Au1rxx-base64 | 156.146.38.169 |
| 77.82 | shadowsocks | 269.3 | 599.6 | 21.54 | 0.0 | 9.69 | 13.82 | 19.86 | Au1rxx-base64 | 23.150.248.20 |
| 77.67 | vless | 287.9 | 667.6 | 21.11 | 0.0 | 9.65 | 9.57 | 19.86 | Au1rxx-base64 | 198.251.78.29 |
| 77.55 | vless | 370.2 | 976.6 | 19.21 | 0.0 | 9.68 | 9.57 | 19.86 | Au1rxx-base64 | 195.211.98.43 |
| 77.42 | shadowsocks | 347.7 | 834.0 | 19.73 | 0.0 | 10.0 | 13.82 | 19.86 | Au1rxx-base64 | 198.98.53.130 |
| 77.17 | shadowsocks | 320.3 | 772.8 | 20.36 | 0.0 | 9.82 | 13.82 | 19.86 | Au1rxx-base64 | 37.19.198.244 |
| 76.26 | shadowsocks | 300.9 | 621.5 | 20.81 | 0.0 | 9.82 | 13.82 | 19.86 | Au1rxx-base64 | 173.244.56.6 |
| 74.95 | shadowsocks | 319.0 | 651.3 | 20.39 | 0.0 | 9.82 | 13.82 | 19.86 | Au1rxx-base64 | 149.22.95.183 |
| 74.93 | vless | 407.5 | 958.1 | 18.34 | 0.0 | 9.57 | 9.57 | 19.86 | Au1rxx-base64 | 23.132.28.51 |
| 74.76 | vless | 303.1 | 593.2 | 20.76 | 0.0 | 9.59 | 9.57 | 19.86 | Au1rxx-base64 | 172.235.43.210 |
| 74.71 | hysteria2 | 356.0 | 807.3 | 19.54 | 0.0 | 9.68 | 13.12 | 19.86 | Au1rxx-base64 | 66.94.121.46 |
| 73.77 | vless | 381.5 | 721.2 | 18.95 | 0.0 | 9.6 | 9.57 | 19.86 | Au1rxx-base64 | 169.40.42.182 |
| 73.62 | vless | 427.7 | 1022.3 | 17.88 | 0.0 | 9.63 | 9.57 | 19.86 | Au1rxx-base64 | 169.40.42.168 |
| 73.6 | vless | 376.2 | 764.9 | 19.07 | 0.0 | 9.62 | 9.57 | 19.86 | Au1rxx-base64 | 169.40.42.163 |
| 73.57 | vless | 464.2 | 1159.5 | 17.03 | 0.0 | 9.63 | 9.57 | 19.86 | Au1rxx-base64 | 130.107.73.148 |
| 73.51 | vless | 357.1 | 656.4 | 19.51 | 0.0 | 9.67 | 9.57 | 19.86 | Au1rxx-base64 | 104.18.47.113 |
| 73.44 | vless | 398.6 | 951.2 | 18.55 | 0.0 | 9.64 | 9.57 | 19.86 | Au1rxx-base64 | 169.40.42.16 |
| 72.5 | vless | 439.4 | 930.6 | 17.61 | 0.0 | 9.63 | 9.57 | 19.86 | Au1rxx-base64 | 169.40.42.15 |
| 72.39 | shadowsocks | 369.5 | 932.6 | 19.22 | 0.0 | 10.0 | 13.82 | 16.02 | Surfboard-tg-mixed | 37.19.198.243 |
| 72.25 | vless | 442.9 | 1045.8 | 17.52 | 0.0 | 9.65 | 9.57 | 19.86 | Au1rxx-base64 | 185.95.231.233 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.953 | 0.889 | 270 | 1665 | prefer |
| mheidari-all | 0.769 | 0.693 | 101 | 22490 | prefer |
| ermaozi | 0.754 | 0.759 | 29 | 291 | prefer |
| Surfboard-tg-mixed | 0.648 | 0.569 | 123 | 7072 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4332 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6471 | observe |
| Epodonios-all | 0.255 | None | 0 | 7607 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9166 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5711 | observe |
| barry-far-vless | 0.255 | None | 0 | 6042 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1665 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 36 |
| cn-block | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 17 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
