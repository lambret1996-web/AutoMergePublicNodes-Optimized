# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 06:11:18 |
| 运行耗时 | 1063.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 100384 |
| 去重后节点 | 27896 |
| TCP 可达 | 3000 |
| 真实可用 | 441 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27896 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 47.4 |
| probe | 354.1 |
| real_test | 575.2 |
| generate | 77.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58524 |
| vmess | 16142 |
| shadowsocks | 12190 |
| trojan | 11069 |
| hysteria2 | 1411 |
| http | 759 |
| shadowsocksr | 176 |
| socks | 60 |
| anytls | 29 |
| hysteria | 18 |
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
| 83.56 | hysteria2 | 249.7 | 681.9 | 22.0 | 0.0 | 10.0 | 13.42 | 19.64 | Au1rxx-base64 | 129.213.91.185 |
| 81.28 | shadowsocks | 253.6 | 707.1 | 21.91 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.243 |
| 81.26 | shadowsocks | 254.5 | 709.4 | 21.89 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.244 |
| 81.25 | shadowsocks | 254.7 | 712.8 | 21.88 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.236 |
| 81.15 | shadowsocks | 258.9 | 725.9 | 21.78 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 37.19.198.160 |
| 81.15 | vless | 283.2 | 679.3 | 21.22 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.212 |
| 81.15 | vless | 283.3 | 711.4 | 21.22 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 66.70.179.198 |
| 81.06 | shadowsocks | 241.3 | 602.9 | 22.19 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 66.23.205.83 |
| 80.93 | vless | 292.8 | 728.1 | 21.0 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.89 |
| 80.89 | vless | 294.4 | 670.2 | 20.96 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.173 |
| 80.8 | vless | 298.6 | 751.4 | 20.87 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.15 |
| 80.42 | vless | 261.2 | 681.6 | 21.73 | 0.0 | 10.0 | 10.29 | 18.4 | mheidari-all | 167.17.69.171 |
| 80.42 | vless | 261.4 | 642.6 | 21.73 | 0.0 | 10.0 | 10.29 | 18.4 | mheidari-all | 195.211.98.43 |
| 80.27 | vless | 321.4 | 875.6 | 20.34 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 159.89.87.21 |
| 80.18 | vless | 325.2 | 907.3 | 20.25 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 185.95.231.156 |
| 79.56 | vless | 351.9 | 844.5 | 19.63 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.133 |
| 79.4 | shadowsocks | 313.1 | 863.4 | 20.53 | 0.0 | 10.0 | 13.73 | 19.64 | Au1rxx-base64 | 15.204.246.132 |
| 79.23 | vless | 269.4 | 655.0 | 21.54 | 0.0 | 10.0 | 10.29 | 18.4 | mheidari-all | 169.40.42.202 |
| 79.2 | vless | 266.8 | 705.1 | 21.6 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.90 |
| 79.11 | vless | 371.6 | 908.8 | 19.18 | 0.0 | 10.0 | 10.29 | 19.64 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.974 | 0.906 | 329 | 1761 | prefer |
| ermaozi | 0.541 | 0.512 | 41 | 723 | observe |
| Surfboard-tg-mixed | 0.418 | 0.5 | 10 | 7206 | observe |
| mheidari-all | 0.375 | 0.294 | 385 | 24063 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5028 | observe |
| Epodonios-all | 0.255 | None | 0 | 7717 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9931 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5725 | observe |
| barry-far-vless | 0.255 | None | 0 | 5926 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1761 | observe |
| DeltaKronecker-all | 0.223 | 0.115 | 26 | 5701 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 155 |
| speed | TimeoutError | - | 60 |
| geo | ClientOSError | - | 27 |
| 204 | ProxyError | - | 26 |
| cn-block | TimeoutError | - | 24 |
| speed | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyConnectionError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
