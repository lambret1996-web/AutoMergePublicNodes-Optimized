# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 12:32:23 |
| 运行耗时 | 603.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96830 |
| 去重后节点 | 26517 |
| TCP 可达 | 3000 |
| 真实可用 | 443 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26517 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.7 |
| tcp | 42.5 |
| probe | 279.4 |
| real_test | 161.6 |
| generate | 111.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59335 |
| vmess | 14947 |
| shadowsocks | 11131 |
| trojan | 8829 |
| hysteria2 | 1636 |
| http | 651 |
| shadowsocksr | 174 |
| socks | 77 |
| anytls | 24 |
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
| 80.01 | hysteria2 | 282.3 | 724.7 | 21.24 | 0.0 | 8.91 | 13.64 | 17.32 | Au1rxx-base64 | 159.223.157.129 |
| 75.72 | shadowsocks | 274.6 | 634.3 | 21.42 | 0.0 | 8.98 | 14.33 | 17.32 | Au1rxx-base64 | 156.146.38.168 |
| 74.28 | shadowsocks | 431.5 | 1179.2 | 17.79 | 0.0 | 8.84 | 14.33 | 17.32 | Au1rxx-base64 | 142.4.216.225 |
| 74.2 | hysteria2 | 275.4 | 641.7 | 21.4 | 0.0 | 7.84 | 13.64 | 17.32 | Au1rxx-base64 | newstate.vihodest.net |
| 74.04 | vless | 258.0 | 721.1 | 21.81 | 0.0 | 8.88 | 6.03 | 17.32 | Au1rxx-base64 | 79.141.172.154 |
| 73.93 | shadowsocks | 223.0 | 584.7 | 22.62 | 0.0 | 10.0 | 14.33 | 10.98 | Surfboard-tg-mixed | 198.98.53.130 |
| 73.76 | hysteria2 | 371.6 | 804.8 | 19.18 | 0.0 | 8.85 | 13.64 | 17.32 | Au1rxx-base64 | 66.94.121.46 |
| 73.68 | vless | 276.9 | 661.8 | 21.37 | 0.0 | 8.96 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.224 |
| 73.57 | vless | 281.7 | 739.5 | 21.26 | 0.0 | 8.96 | 6.03 | 17.32 | Au1rxx-base64 | 185.95.231.156 |
| 73.39 | vless | 287.0 | 663.0 | 21.13 | 0.0 | 8.91 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.184 |
| 72.9 | shadowsocks | 267.1 | 721.8 | 21.59 | 0.0 | 10.0 | 14.33 | 10.98 | Surfboard-tg-mixed | 37.19.198.243 |
| 72.65 | vless | 318.9 | 860.0 | 20.4 | 0.0 | 8.9 | 6.03 | 17.32 | Au1rxx-base64 | 137.184.218.169 |
| 72.56 | vless | 335.5 | 820.0 | 20.01 | 0.0 | 10.0 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.212 |
| 72.37 | vless | 331.0 | 872.8 | 20.12 | 0.0 | 8.9 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.168 |
| 72.03 | shadowsocks | 426.3 | 959.0 | 17.91 | 0.0 | 9.03 | 14.33 | 17.32 | Au1rxx-base64 | 15.204.233.41 |
| 71.59 | vless | 363.9 | 917.9 | 19.36 | 0.0 | 8.89 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.225 |
| 71.56 | vless | 373.0 | 958.2 | 19.14 | 0.0 | 9.07 | 6.03 | 17.32 | Au1rxx-base64 | 66.70.179.198 |
| 71.51 | vless | 379.0 | 994.4 | 19.0 | 0.0 | 9.16 | 6.03 | 17.32 | Au1rxx-base64 | 185.95.231.233 |
| 71.22 | vless | 359.5 | 948.4 | 19.46 | 0.0 | 9.01 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.235 |
| 71.17 | vless | 369.5 | 993.8 | 19.23 | 0.0 | 8.91 | 6.03 | 17.32 | Au1rxx-base64 | 169.40.42.173 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | 0.932 | 237 | 1599 | prefer |
| Surfboard-tg-mixed | 0.801 | 0.725 | 138 | 7036 | prefer |
| ermaozi | 0.76 | 0.754 | 57 | 346 | prefer |
| mheidari-all | 0.576 | 0.496 | 139 | 22242 | observe |
| ermaozi-get_subscribe | 0.324 | 0.385 | 13 | 372 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 6471 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 117 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7633 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9052 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5755 | observe |
| barry-far-vless | 0.255 | None | 0 | 5975 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4187 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 35 |
| 204 | ProxyError | - | 29 |
| cn-block | ClientOSError | - | 28 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 16 |
| geo | TimeoutError | - | 10 |
| speed | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
