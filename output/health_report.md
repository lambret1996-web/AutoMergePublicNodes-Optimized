# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 15:21:53 |
| 运行耗时 | 775.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99135 |
| 去重后节点 | 27579 |
| TCP 可达 | 3000 |
| 真实可用 | 404 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27579 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 47.7 |
| probe | 338.4 |
| real_test | 292.6 |
| generate | 87.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58179 |
| vmess | 16619 |
| shadowsocks | 12004 |
| trojan | 10145 |
| hysteria2 | 1342 |
| http | 571 |
| shadowsocksr | 169 |
| socks | 57 |
| anytls | 26 |
| hysteria | 17 |
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
| 83.09 | hysteria2 | 244.8 | 679.1 | 22.11 | 0.0 | 10.0 | 13.5 | 18.98 | Au1rxx-base64 | 129.213.91.185 |
| 80.89 | vless | 243.2 | 654.0 | 22.15 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 147.45.60.160 |
| 80.66 | shadowsocks | 254.8 | 710.6 | 21.88 | 0.0 | 10.0 | 13.8 | 18.98 | Au1rxx-base64 | 37.19.198.244 |
| 80.53 | shadowsocks | 260.3 | 709.1 | 21.75 | 0.0 | 10.0 | 13.8 | 18.98 | Au1rxx-base64 | 37.19.198.243 |
| 80.5 | vless | 259.8 | 631.5 | 21.76 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 195.211.98.43 |
| 80.46 | shadowsocks | 263.5 | 705.1 | 21.68 | 0.0 | 10.0 | 13.8 | 18.98 | Au1rxx-base64 | 37.19.198.160 |
| 80.1 | vless | 277.3 | 698.0 | 21.36 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 66.70.179.198 |
| 78.35 | vless | 280.6 | 736.5 | 21.28 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 169.40.42.90 |
| 78.28 | vless | 314.9 | 846.1 | 20.49 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 167.17.69.171 |
| 78.22 | vless | 358.4 | 996.4 | 19.48 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 185.95.231.156 |
| 77.97 | vless | 343.2 | 949.2 | 19.83 | 0.0 | 9.4 | 9.76 | 18.98 | Au1rxx-base64 | 195.123.235.183 |
| 77.29 | vless | 251.6 | 709.7 | 21.95 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 47.253.226.114 |
| 77.23 | shadowsocks | 288.8 | 655.9 | 21.09 | 0.0 | 10.0 | 13.8 | 18.98 | Au1rxx-base64 | 156.146.38.167 |
| 76.52 | shadowsocks | 281.5 | 647.9 | 21.26 | 0.0 | 10.0 | 13.8 | 18.98 | Au1rxx-base64 | 156.146.38.168 |
| 75.48 | vless | 304.7 | 700.1 | 20.73 | 0.0 | 9.16 | 9.76 | 18.98 | Au1rxx-base64 | 198.23.169.170 |
| 75.26 | vless | 399.8 | 1016.9 | 18.52 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 169.40.42.182 |
| 74.82 | vless | 349.6 | 728.9 | 19.68 | 0.0 | 9.07 | 9.76 | 18.98 | Au1rxx-base64 | 5.34.178.120 |
| 74.72 | shadowsocks | 277.9 | 642.2 | 21.34 | 0.0 | 10.0 | 13.8 | 18.98 | Au1rxx-base64 | 156.146.38.169 |
| 74.37 | shadowsocks | 285.9 | 655.1 | 21.16 | 0.0 | 9.37 | 13.8 | 18.98 | Au1rxx-base64 | 156.146.38.170 |
| 73.79 | vless | 384.1 | 821.2 | 18.89 | 0.0 | 10.0 | 9.76 | 18.98 | Au1rxx-base64 | 169.40.42.173 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.864 | 0.786 | 471 | 1993 | prefer |
| ermaozi | 0.57 | 0.55 | 20 | 623 | observe |
| Surfboard-tg-mixed | 0.398 | 0.31 | 42 | 7171 | observe |
| mheidari-all | 0.37 | 0.312 | 16 | 23770 | observe |
| ermaozi-get_subscribe | 0.275 | 1.0 | 1 | 510 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| Epodonios-all | 0.255 | None | 0 | 7678 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9904 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5617 | observe |
| barry-far-vless | 0.255 | None | 0 | 5865 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 69 |
| 204 | ProxyError | - | 18 |
| speed | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyConnectionError | - | 11 |
| 204 | ClientOSError | - | 10 |
| speed | TimeoutError | - | 8 |
| geo | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
