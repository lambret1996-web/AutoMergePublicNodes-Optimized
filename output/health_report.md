# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 22:15:09 |
| 运行耗时 | 418.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97982 |
| 去重后节点 | 27241 |
| TCP 可达 | 3000 |
| 真实可用 | 350 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27241 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.6 |
| tcp | 45.5 |
| probe | 172.1 |
| real_test | 116.8 |
| generate | 74.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60177 |
| vmess | 15251 |
| shadowsocks | 11355 |
| trojan | 9117 |
| hysteria2 | 1348 |
| http | 440 |
| shadowsocksr | 171 |
| socks | 68 |
| anytls | 32 |
| hysteria | 15 |
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
| 81.42 | hysteria2 | 273.8 | 683.1 | 21.44 | 0.0 | 10.0 | 13.64 | 17.44 | mheidari-all | 159.223.157.129 |
| 78.55 | shadowsocks | 247.1 | 619.3 | 22.06 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 198.98.53.130 |
| 78.27 | shadowsocks | 259.1 | 637.8 | 21.78 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 156.146.38.170 |
| 78.05 | shadowsocks | 283.5 | 731.3 | 21.22 | 0.0 | 10.0 | 13.39 | 17.44 | mheidari-all | 37.19.198.244 |
| 77.98 | shadowsocks | 253.1 | 614.3 | 21.92 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 156.146.38.167 |
| 77.69 | shadowsocks | 284.0 | 726.8 | 21.2 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 37.19.198.160 |
| 77.69 | shadowsocks | 284.0 | 725.1 | 21.2 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 37.19.198.243 |
| 77.51 | shadowsocks | 291.9 | 739.5 | 21.02 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 156.146.38.169 |
| 77.48 | hysteria2 | 269.8 | 563.7 | 21.53 | 0.0 | 10.0 | 13.64 | 17.1 | Au1rxx-base64 | 192.255.128.123 |
| 77.44 | vless | 266.3 | 666.5 | 21.61 | 0.0 | 10.0 | 8.73 | 17.1 | Au1rxx-base64 | 198.251.78.29 |
| 77.21 | shadowsocks | 196.8 | 557.4 | 23.22 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 66.23.204.219 |
| 75.89 | vless | 333.6 | 700.3 | 20.06 | 0.0 | 10.0 | 8.73 | 17.1 | Au1rxx-base64 | 169.40.42.90 |
| 75.75 | shadowsocks | 281.8 | 677.9 | 21.25 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 140.82.63.79 |
| 75.61 | shadowsocks | 367.2 | 881.9 | 19.28 | 0.0 | 10.0 | 13.39 | 17.44 | mheidari-all | 15.204.247.206 |
| 75.36 | vless | 273.0 | 646.3 | 21.46 | 0.0 | 10.0 | 8.73 | 17.1 | Au1rxx-base64 | 195.123.235.177 |
| 75.29 | vless | 271.8 | 639.3 | 21.49 | 0.0 | 10.0 | 8.73 | 17.44 | mheidari-all | 216.227.161.95 |
| 75.23 | vless | 342.6 | 859.0 | 19.85 | 0.0 | 10.0 | 8.73 | 17.1 | Au1rxx-base64 | 169.40.42.16 |
| 75.11 | shadowsocks | 338.2 | 886.9 | 19.95 | 0.0 | 10.0 | 13.39 | 17.1 | Au1rxx-base64 | 15.204.246.132 |
| 75.06 | vless | 308.7 | 736.8 | 20.63 | 0.0 | 10.0 | 8.73 | 17.1 | Au1rxx-base64 | 66.70.179.198 |
| 74.82 | vless | 379.8 | 843.4 | 18.99 | 0.0 | 10.0 | 8.73 | 17.1 | Au1rxx-base64 | 169.40.42.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.876 | 0.802 | 96 | 22901 | prefer |
| Au1rxx-base64 | 0.87 | 0.799 | 304 | 1803 | prefer |
| zhangkai | 0.646 | 0.8 | 15 | 144 | observe |
| Surfboard-tg-mixed | 0.606 | 0.889 | 9 | 7200 | observe |
| DeltaKronecker-all | 0.446 | 0.625 | 8 | 5434 | observe |
| ermaozi-get_subscribe | 0.307 | 0.444 | 9 | 362 | observe |
| tg-oneclickvpnkeys | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7696 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9724 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5833 | observe |
| barry-far-vless | 0.255 | None | 0 | 6072 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 45 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| geo | ClientOSError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 3 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
