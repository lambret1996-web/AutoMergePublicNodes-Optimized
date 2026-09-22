# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 18:30:20 |
| 运行耗时 | 557.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 87981 |
| 去重后节点 | 25371 |
| TCP 可达 | 3000 |
| 真实可用 | 393 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25371 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.4 |
| tcp | 43.3 |
| probe | 245.7 |
| real_test | 182.4 |
| generate | 77.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52163 |
| vmess | 14567 |
| shadowsocks | 10492 |
| trojan | 8630 |
| hysteria2 | 1291 |
| http | 581 |
| shadowsocksr | 145 |
| socks | 81 |
| hysteria | 14 |
| anytls | 11 |
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
| 82.71 | hysteria2 | 280.1 | 729.1 | 21.29 | 0.0 | 10.0 | 13.5 | 19.02 | Au1rxx-base64 | 159.223.157.129 |
| 80.37 | shadowsocks | 267.5 | 724.0 | 21.58 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 37.19.198.244 |
| 80.37 | shadowsocks | 267.7 | 713.4 | 21.58 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 37.19.198.160 |
| 78.57 | vless | 267.8 | 708.3 | 21.58 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 79.141.172.154 |
| 78.24 | vless | 282.0 | 661.2 | 21.25 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 138.124.60.146 |
| 76.83 | shadowsocks | 377.6 | 1032.4 | 19.04 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 198.98.53.130 |
| 76.22 | vless | 369.1 | 997.6 | 19.23 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 185.95.231.156 |
| 76.04 | vless | 368.7 | 924.9 | 19.24 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.35 |
| 75.96 | vless | 287.1 | 689.6 | 21.13 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 195.211.98.43 |
| 75.93 | vless | 381.7 | 972.8 | 18.94 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.15 |
| 75.7 | shadowsocks | 315.5 | 720.4 | 20.47 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 108.181.57.93 |
| 75.48 | vless | 365.3 | 957.2 | 19.32 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.168 |
| 75.4 | shadowsocks | 266.7 | 718.9 | 21.61 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 37.19.198.236 |
| 75.38 | vless | 405.8 | 971.3 | 18.39 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.182 |
| 75.33 | shadowsocks | 392.9 | 931.8 | 18.68 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 23.150.248.20 |
| 75.07 | shadowsocks | 422.5 | 1048.1 | 18.0 | 0.0 | 10.0 | 13.77 | 19.02 | Au1rxx-base64 | 38.180.135.156 |
| 74.99 | vless | 374.8 | 867.3 | 19.1 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.74 |
| 74.87 | vless | 385.1 | 897.4 | 18.86 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.235 |
| 74.77 | vless | 393.3 | 933.2 | 18.67 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 169.40.42.52 |
| 74.64 | vless | 351.3 | 915.6 | 19.65 | 0.0 | 10.0 | 7.97 | 19.02 | Au1rxx-base64 | 185.95.231.233 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.87 | 0.804 | 301 | 1703 | prefer |
| DeltaKronecker-all | 0.747 | 0.68 | 25 | 6324 | prefer |
| ermaozi | 0.727 | 0.731 | 26 | 325 | prefer |
| mheidari-all | 0.677 | 0.6 | 65 | 16289 | observe |
| Surfboard-tg-mixed | 0.531 | 0.451 | 142 | 7076 | observe |
| mahdibland-V2RayAggregator | 0.519 | 1.0 | 5 | 4252 | observe |
| xiaoji235-airport-v2ray-all | 0.418 | 0.5 | 10 | 4242 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4915 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 117 | observe |
| Epodonios-all | 0.255 | None | 0 | 7534 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8848 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5712 | observe |
| barry-far-vless | 0.255 | None | 0 | 6010 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 55 |
| geo | ClientOSError | - | 34 |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 19 |
| cn-block | ClientOSError | - | 14 |
| geo | TimeoutError | - | 9 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
