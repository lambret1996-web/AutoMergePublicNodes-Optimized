# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 17:10:43 |
| 运行耗时 | 547.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97420 |
| 去重后节点 | 26478 |
| TCP 可达 | 3000 |
| 真实可用 | 330 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26478 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 15.3 |
| geo | 1.5 |
| tcp | 42.9 |
| probe | 245.7 |
| real_test | 164.1 |
| generate | 78.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59592 |
| vmess | 15138 |
| shadowsocks | 11281 |
| trojan | 8915 |
| hysteria2 | 1600 |
| http | 599 |
| shadowsocksr | 170 |
| socks | 76 |
| anytls | 27 |
| hysteria | 15 |
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
| 81.23 | vless | 257.4 | 709.5 | 21.82 | 0.0 | 8.94 | 11.25 | 19.22 | Au1rxx-base64 | 79.141.172.154 |
| 81.04 | vless | 265.1 | 649.4 | 21.64 | 0.0 | 8.93 | 11.25 | 19.22 | Au1rxx-base64 | 195.211.98.43 |
| 79.91 | vless | 360.1 | 982.8 | 19.44 | 0.0 | 10.0 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.202 |
| 79.46 | vless | 338.9 | 855.5 | 19.93 | 0.0 | 9.06 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.179 |
| 79.34 | vless | 339.4 | 930.7 | 19.92 | 0.0 | 8.95 | 11.25 | 19.22 | Au1rxx-base64 | 185.95.231.156 |
| 78.62 | vless | 415.9 | 1132.6 | 18.15 | 0.0 | 10.0 | 11.25 | 19.22 | Au1rxx-base64 | 185.95.231.233 |
| 78.46 | vless | 379.1 | 861.4 | 19.0 | 0.0 | 8.99 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.90 |
| 78.31 | vless | 383.6 | 985.1 | 18.9 | 0.0 | 8.94 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.35 |
| 78.13 | vless | 386.6 | 933.3 | 18.83 | 0.0 | 8.95 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.104 |
| 77.56 | vless | 418.0 | 1097.0 | 18.1 | 0.0 | 8.99 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.229 |
| 77.47 | shadowsocks | 256.7 | 711.9 | 21.84 | 0.0 | 10.0 | 13.29 | 16.34 | mheidari-all | 37.19.198.236 |
| 77.42 | shadowsocks | 258.6 | 713.2 | 21.79 | 0.0 | 10.0 | 13.29 | 16.34 | mheidari-all | 37.19.198.160 |
| 77.39 | vless | 328.0 | 762.2 | 20.18 | 0.0 | 8.91 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.163 |
| 77.39 | vless | 397.3 | 1086.8 | 18.58 | 0.0 | 9.0 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.173 |
| 77.35 | vless | 417.8 | 1155.5 | 18.11 | 0.0 | 8.91 | 11.25 | 19.22 | Au1rxx-base64 | 169.40.42.75 |
| 77.17 | shadowsocks | 247.8 | 680.6 | 22.04 | 0.0 | 10.0 | 13.29 | 16.34 | mheidari-all | 140.82.63.79 |
| 77.14 | vless | 285.5 | 788.4 | 21.17 | 0.0 | 10.0 | 11.25 | 19.22 | Au1rxx-base64 | 162.35.96.39 |
| 76.78 | shadowsocks | 389.3 | 1041.0 | 18.77 | 0.0 | 10.0 | 13.29 | 19.22 | Au1rxx-base64 | 38.180.135.156 |
| 76.51 | vless | 290.9 | 751.2 | 21.04 | 0.0 | 10.0 | 11.25 | 19.22 | Au1rxx-base64 | 38.77.133.202 |
| 76.49 | shadowsocks | 285.7 | 658.1 | 21.16 | 0.0 | 8.97 | 13.29 | 19.22 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.917 | 0.852 | 250 | 1699 | prefer |
| Surfboard-tg-mixed | 0.772 | 0.703 | 37 | 7258 | prefer |
| mheidari-all | 0.723 | 0.646 | 127 | 22782 | prefer |
| ermaozi | 0.399 | 0.438 | 16 | 304 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7757 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9237 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5857 | observe |
| barry-far-vless | 0.255 | None | 0 | 6083 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4324 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1699 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 30 |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 14 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
