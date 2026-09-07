# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 12:36:38 |
| 运行耗时 | 155.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 94680 |
| 去重后节点 | 24961 |
| TCP 可达 | 300 |
| 真实可用 | 185 |
| Verified 输出 | 30 |
| Global 输出 | 30 |
| All 输出 | 24961 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.4 |
| tcp | 41.9 |
| probe | 16.3 |
| real_test | 42.8 |
| generate | 45.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59130 |
| vmess | 12777 |
| shadowsocks | 11098 |
| trojan | 9202 |
| hysteria2 | 2087 |
| http | 138 |
| shadowsocksr | 130 |
| socks | 61 |
| anytls | 22 |
| hysteria | 21 |
| tuic | 14 |

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
| 85.8 | hysteria2 | 183.7 | 504.8 | 23.53 | 0.0 | 10.0 | 13.75 | 19.52 | Au1rxx-base64 | 66.94.121.46 |
| 79.65 | vless | 270.0 | 547.3 | 21.53 | 0.0 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 172.233.139.46 |
| 77.87 | vless | 325.1 | 715.5 | 20.25 | 0.0 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 172.235.43.210 |
| 77.78 | vless | 276.1 | 544.4 | 21.39 | 0.0 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 172.235.38.85 |
| 76.39 | http | 292.1 | 643.7 | 21.02 | 0.0 | 10.0 | 13.12 | 18.38 | zhangkai | 138.199.35.216 |
| 76.14 | vless | 318.6 | 325.5 | 20.4 | 2.79 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 3.114.220.22 |
| 76.11 | vless | 513.9 | 1454.5 | 15.88 | 0.0 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 51.81.203.63 |
| 76.04 | vless | 342.6 | 334.5 | 19.85 | 2.46 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 172.64.32.108 |
| 76.0 | vless | 346.1 | 299.6 | 19.77 | 3.77 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 18.177.61.231 |
| 75.92 | vless | 319.6 | 329.9 | 20.38 | 2.63 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 18.183.215.124 |
| 75.9 | vless | 321.1 | 327.7 | 20.34 | 2.71 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 3.112.131.211 |
| 75.87 | vless | 319.5 | 329.9 | 20.38 | 2.63 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 54.238.241.88 |
| 75.83 | vless | 318.6 | 330.9 | 20.4 | 2.59 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 13.231.19.51 |
| 75.82 | vless | 319.9 | 327.5 | 20.37 | 2.72 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 3.112.47.207 |
| 75.7 | vless | 318.0 | 325.1 | 20.42 | 2.81 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 52.194.245.53 |
| 75.7 | vless | 321.7 | 332.2 | 20.33 | 2.54 | 9.99 | 10.71 | 19.52 | Au1rxx-base64 | 54.249.200.131 |
| 75.67 | vless | 290.9 | 645.1 | 21.04 | 0.0 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 38.244.20.160 |
| 75.64 | vless | 318.7 | 333.1 | 20.4 | 2.51 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 13.230.222.139 |
| 75.51 | vless | 319.9 | 336.1 | 20.37 | 2.4 | 9.99 | 10.71 | 19.52 | Au1rxx-base64 | 43.207.162.145 |
| 75.5 | vless | 296.1 | 634.2 | 20.92 | 0.0 | 10.0 | 10.71 | 19.52 | Au1rxx-base64 | 38.246.229.58 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.939 | 0.872 | 179 | 1788 | prefer |
| mheidari-all | 0.349 | 0.667 | 3 | 21631 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 7247 | observe |
| tg-oneclickvpnkeys | 0.275 | 0.667 | 3 | 151 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 6417 | observe |
| Epodonios-all | 0.255 | None | 0 | 7707 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8437 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6245 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5750 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1788 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 13 |
| speed | TimeoutError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 30 | - |
| global | False | 300 | 30 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
