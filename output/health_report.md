# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 17:44:59 |
| 运行耗时 | 555.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98390 |
| 去重后节点 | 27135 |
| TCP 可达 | 3000 |
| 真实可用 | 414 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27135 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.2 |
| tcp | 46.7 |
| probe | 227.2 |
| real_test | 200.5 |
| generate | 74.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60432 |
| vmess | 15311 |
| shadowsocks | 11540 |
| trojan | 8825 |
| hysteria2 | 1455 |
| http | 523 |
| shadowsocksr | 174 |
| socks | 66 |
| anytls | 40 |
| hysteria | 17 |
| tuic | 7 |

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
| 84.05 | hysteria2 | 253.8 | 691.1 | 21.9 | 0.0 | 10.0 | 13.93 | 19.32 | Au1rxx-base64 | 159.223.157.129 |
| 80.69 | shadowsocks | 256.4 | 704.6 | 21.84 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 37.19.198.160 |
| 80.59 | shadowsocks | 260.8 | 729.6 | 21.74 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 37.19.198.244 |
| 80.13 | shadowsocks | 280.8 | 788.3 | 21.28 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 37.19.198.243 |
| 79.0 | hysteria2 | 295.4 | 593.1 | 20.94 | 0.0 | 10.0 | 13.93 | 19.32 | Au1rxx-base64 | 192.255.128.123 |
| 78.98 | vless | 240.4 | 689.3 | 22.21 | 0.0 | 10.0 | 7.45 | 19.32 | Au1rxx-base64 | 79.141.172.154 |
| 78.85 | shadowsocks | 314.2 | 836.2 | 20.5 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 140.82.63.79 |
| 77.9 | vless | 287.1 | 723.3 | 21.13 | 0.0 | 10.0 | 7.45 | 19.32 | Au1rxx-base64 | 2.24.124.64 |
| 77.26 | shadowsocks | 286.6 | 654.8 | 21.14 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 156.146.38.170 |
| 76.23 | shadowsocks | 233.1 | 631.5 | 22.38 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 198.98.53.130 |
| 75.97 | hysteria2 | 357.1 | 321.6 | 19.51 | 2.94 | 8.76 | 13.93 | 19.32 | Au1rxx-base64 | open.2ml.bid |
| 75.28 | hysteria2 | 350.1 | 607.4 | 19.67 | 0.0 | 9.98 | 13.93 | 19.32 | Au1rxx-base64 | 66.94.121.46 |
| 74.84 | shadowsocks | 282.5 | 655.1 | 21.24 | 0.0 | 10.0 | 13.53 | 16.36 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.35 | shadowsocks | 364.7 | 897.3 | 19.34 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 108.181.57.93 |
| 74.13 | shadowsocks | 307.1 | 585.1 | 20.67 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 173.234.25.90 |
| 74.04 | vless | 259.7 | 709.7 | 21.77 | 0.0 | 10.0 | 7.45 | 19.32 | Au1rxx-base64 | 162.35.96.18 |
| 73.97 | shadowsocks | 340.7 | 822.4 | 19.89 | 0.0 | 10.0 | 13.53 | 19.32 | Au1rxx-base64 | 66.23.201.172 |
| 73.85 | vless | 267.8 | 716.5 | 21.58 | 0.0 | 10.0 | 7.45 | 19.32 | Au1rxx-base64 | 162.35.96.22 |
| 73.53 | vless | 365.4 | 808.3 | 19.32 | 0.0 | 10.0 | 7.45 | 19.32 | Au1rxx-base64 | 169.40.42.182 |
| 73.03 | vless | 281.6 | 696.4 | 21.26 | 0.0 | 10.0 | 7.45 | 19.32 | Au1rxx-base64 | 23.95.76.164 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.948 | 0.958 | 24 | 620 | prefer |
| Au1rxx-base64 | 0.918 | 0.85 | 307 | 1750 | prefer |
| mheidari-all | 0.826 | 0.754 | 57 | 22996 | prefer |
| Surfboard-tg-mixed | 0.769 | 0.692 | 117 | 7244 | prefer |
| DeltaKronecker-all | 0.389 | 0.385 | 13 | 4981 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7739 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9417 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5909 | observe |
| barry-far-vless | 0.255 | None | 0 | 6150 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 31 |
| cn-block | TimeoutError | - | 21 |
| speed | TimeoutError | - | 14 |
| 204 | ProxyError | - | 10 |
| geo | TimeoutError | - | 9 |
| geo | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
