# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 12:31:18 |
| 运行耗时 | 586.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91808 |
| 去重后节点 | 25278 |
| TCP 可达 | 3000 |
| 真实可用 | 468 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25278 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 43.3 |
| probe | 247.3 |
| real_test | 212.0 |
| generate | 75.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54078 |
| vmess | 14803 |
| shadowsocks | 11151 |
| trojan | 9270 |
| hysteria2 | 1603 |
| http | 634 |
| shadowsocksr | 142 |
| socks | 81 |
| anytls | 21 |
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
| 79.04 | hysteria2 | 301.3 | 724.9 | 20.8 | 0.0 | 8.64 | 13.64 | 18.24 | Au1rxx-base64 | 159.223.157.129 |
| 77.26 | vless | 265.9 | 663.3 | 21.62 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 195.211.98.43 |
| 75.48 | vless | 298.7 | 723.6 | 20.86 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 79.141.172.154 |
| 74.58 | shadowsocks | 335.9 | 894.8 | 20.0 | 0.0 | 10.0 | 14.03 | 18.24 | Au1rxx-base64 | 185.156.47.97 |
| 74.29 | shadowsocks | 395.1 | 1016.3 | 18.63 | 0.0 | 10.0 | 14.03 | 18.24 | Au1rxx-base64 | 15.204.247.206 |
| 74.1 | vless | 377.0 | 904.7 | 19.05 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 34.85.179.6 |
| 71.94 | shadowsocks | 312.8 | 742.0 | 20.54 | 0.0 | 10.0 | 14.03 | 13.28 | Surfboard-tg-mixed | 37.19.198.243 |
| 71.68 | vless | 384.2 | 906.8 | 18.88 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 130.107.73.148 |
| 71.37 | shadowsocks | 399.7 | 940.1 | 18.53 | 0.0 | 8.67 | 14.03 | 18.24 | Au1rxx-base64 | 108.181.57.93 |
| 71.26 | shadowsocks | 280.1 | 661.2 | 21.29 | 0.0 | 10.0 | 14.03 | 13.28 | Surfboard-tg-mixed | 198.98.53.130 |
| 70.96 | vless | 323.9 | 615.0 | 20.28 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 195.123.240.65 |
| 70.95 | shadowsocks | 299.6 | 792.6 | 20.84 | 0.0 | 10.0 | 14.03 | 18.24 | Au1rxx-base64 | 156.146.38.167 |
| 70.95 | vless | 438.2 | 880.1 | 17.64 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 169.40.42.231 |
| 70.74 | shadowsocks | 262.8 | 630.4 | 21.69 | 0.0 | 10.0 | 14.03 | 9.52 | mheidari-all | 23.150.248.20 |
| 70.67 | vless | 414.4 | 867.3 | 18.18 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 169.40.42.182 |
| 70.62 | vless | 401.2 | 955.2 | 18.49 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 169.40.42.184 |
| 70.31 | vless | 423.2 | 862.9 | 17.98 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 169.40.42.52 |
| 70.1 | hysteria2 | 446.6 | 777.1 | 17.44 | 0.0 | 8.35 | 13.64 | 18.24 | Au1rxx-base64 | 45.192.12.93 |
| 70.03 | vless | 454.6 | 1111.5 | 17.25 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 185.95.231.156 |
| 69.64 | vless | 317.0 | 686.0 | 20.44 | 0.0 | 10.0 | 7.4 | 18.24 | Au1rxx-base64 | 138.124.60.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.951 | 0.888 | 278 | 1630 | prefer |
| ermaozi | 0.689 | 0.682 | 44 | 369 | observe |
| Surfboard-tg-mixed | 0.58 | 0.5 | 154 | 7157 | observe |
| mheidari-all | 0.513 | 0.433 | 245 | 19835 | observe |
| DeltaKronecker-all | 0.372 | 0.444 | 9 | 6324 | observe |
| ermaozi-get_subscribe | 0.309 | 0.6 | 5 | 393 | observe |
| xiaoji235-airport-v2ray-all | 0.259 | 0.333 | 3 | 4242 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4915 | observe |
| Epodonios-all | 0.255 | None | 0 | 7611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9025 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5792 | observe |
| barry-far-vless | 0.255 | None | 0 | 5817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 62 |
| cn-block | ClientOSError | - | 56 |
| speed | ClientOSError | - | 43 |
| 204 | TimeoutError | - | 31 |
| 204 | ProxyError | - | 24 |
| speed | TimeoutError | - | 14 |
| geo | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
