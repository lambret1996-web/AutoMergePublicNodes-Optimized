# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 15:42:29 |
| 运行耗时 | 662.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98080 |
| 去重后节点 | 27710 |
| TCP 可达 | 3000 |
| 真实可用 | 388 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27710 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 47.9 |
| probe | 278.5 |
| real_test | 243.1 |
| generate | 83.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57779 |
| vmess | 16736 |
| shadowsocks | 11753 |
| trojan | 9609 |
| hysteria2 | 1308 |
| http | 613 |
| shadowsocksr | 167 |
| socks | 69 |
| anytls | 22 |
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
| 83.01 | hysteria2 | 240.3 | 696.0 | 22.22 | 0.0 | 10.0 | 13.57 | 18.72 | Au1rxx-base64 | 129.213.91.185 |
| 80.93 | shadowsocks | 253.5 | 704.5 | 21.91 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 37.19.198.243 |
| 80.89 | shadowsocks | 255.1 | 706.3 | 21.87 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 37.19.198.160 |
| 80.87 | shadowsocks | 256.1 | 711.0 | 21.85 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 37.19.198.244 |
| 79.4 | vless | 248.4 | 669.6 | 22.03 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 147.45.60.160 |
| 79.2 | vless | 256.8 | 679.6 | 21.83 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 195.123.235.183 |
| 78.39 | vless | 292.1 | 659.4 | 21.02 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.90 |
| 78.32 | shadowsocks | 289.7 | 651.3 | 21.07 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 156.146.38.167 |
| 78.17 | trojan | 412.1 | 1170.7 | 18.24 | 0.0 | 10.0 | 14.21 | 18.72 | Au1rxx-base64 | 69.164.240.85 |
| 77.64 | vless | 324.4 | 814.5 | 20.27 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.74 |
| 77.59 | shadowsocks | 286.2 | 641.2 | 21.15 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 156.146.38.168 |
| 77.4 | hysteria2 | 331.0 | 618.9 | 20.11 | 0.0 | 10.0 | 13.57 | 18.72 | Au1rxx-base64 | 66.94.121.46 |
| 77.4 | vless | 334.7 | 863.3 | 20.03 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.133 |
| 77.3 | shadowsocks | 283.1 | 650.6 | 21.22 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 156.146.38.170 |
| 77.13 | shadowsocks | 282.4 | 638.5 | 21.24 | 0.0 | 10.0 | 14.3 | 18.72 | Au1rxx-base64 | 156.146.38.169 |
| 76.95 | vless | 354.3 | 851.2 | 19.58 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.89 |
| 76.88 | vless | 357.1 | 925.6 | 19.51 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.231 |
| 76.64 | vless | 367.7 | 1028.1 | 19.27 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 185.95.231.156 |
| 76.56 | vless | 284.7 | 700.4 | 21.19 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.229 |
| 76.49 | vless | 373.9 | 900.0 | 19.12 | 0.0 | 10.0 | 8.65 | 18.72 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.908 | 0.841 | 339 | 1729 | prefer |
| mheidari-all | 0.898 | 0.839 | 31 | 23775 | prefer |
| ermaozi | 0.682 | 0.667 | 30 | 639 | observe |
| Surfboard-tg-mixed | 0.622 | 0.543 | 94 | 7095 | observe |
| DeltaKronecker-all | 0.356 | 0.263 | 19 | 4750 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7485 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10058 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5602 | observe |
| barry-far-vless | 0.255 | None | 0 | 5815 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 43 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 17 |
| geo | ClientOSError | - | 16 |
| speed | ClientOSError | - | 12 |
| geo | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
