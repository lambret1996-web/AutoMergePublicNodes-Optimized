# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 05:37:50 |
| 运行耗时 | 957.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98379 |
| 去重后节点 | 27433 |
| TCP 可达 | 3000 |
| 真实可用 | 548 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27433 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 47.0 |
| probe | 362.0 |
| real_test | 462.2 |
| generate | 76.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58266 |
| vmess | 15910 |
| shadowsocks | 11658 |
| trojan | 10222 |
| hysteria2 | 1379 |
| http | 615 |
| shadowsocksr | 165 |
| socks | 107 |
| anytls | 28 |
| hysteria | 17 |
| tuic | 12 |

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
| 83.94 | vless | 218.2 | 559.5 | 22.73 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 15.204.97.216 |
| 83.11 | hysteria2 | 306.1 | 680.8 | 20.69 | 0.0 | 10.0 | 14.06 | 19.36 | Au1rxx-base64 | 66.94.121.46 |
| 82.69 | vless | 230.7 | 506.3 | 22.44 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 137.175.82.40 |
| 82.37 | vless | 237.4 | 530.9 | 22.28 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 47.251.108.158 |
| 82.1 | vless | 297.6 | 778.5 | 20.89 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 51.81.203.63 |
| 81.82 | hysteria2 | 210.1 | 218.2 | 22.92 | 6.82 | 10.0 | 14.06 | 19.36 | Au1rxx-base64 | 45.32.10.7 |
| 81.66 | trojan | 226.4 | 555.0 | 22.54 | 0.0 | 10.0 | 13.26 | 19.36 | Au1rxx-base64 | guided-ferret.rooster465.autos |
| 81.65 | shadowsocks | 209.3 | 566.2 | 22.93 | 0.0 | 10.0 | 13.36 | 19.36 | Au1rxx-base64 | 149.22.95.183 |
| 79.75 | hysteria2 | 221.2 | 242.6 | 22.66 | 5.9 | 10.0 | 14.06 | 19.36 | Au1rxx-base64 | 158.101.148.79 |
| 79.54 | trojan | 231.3 | 571.5 | 22.42 | 0.0 | 10.0 | 13.26 | 19.36 | Au1rxx-base64 | 34.220.15.24 |
| 78.98 | trojan | 298.6 | 768.1 | 20.86 | 0.0 | 10.0 | 13.26 | 19.36 | Au1rxx-base64 | ultimate-jaguar.rooster465.autos |
| 78.88 | vless | 220.6 | 576.6 | 22.67 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 15.204.97.197 |
| 78.76 | shadowsocks | 255.4 | 260.5 | 21.87 | 5.23 | 10.0 | 13.36 | 19.36 | Au1rxx-base64 | 149.22.87.240 |
| 78.26 | shadowsocks | 259.0 | 271.1 | 21.78 | 4.83 | 10.0 | 13.36 | 19.36 | Au1rxx-base64 | 149.22.87.241 |
| 77.96 | vless | 320.8 | 302.1 | 20.35 | 3.67 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 46.250.250.149 |
| 77.86 | hysteria2 | 352.2 | 748.4 | 19.62 | 0.0 | 10.0 | 14.06 | 19.36 | Au1rxx-base64 | 159.223.157.129 |
| 77.33 | vless | 305.3 | 657.4 | 20.71 | 0.0 | 10.0 | 11.85 | 18.48 | mheidari-all | 216.227.161.95 |
| 77.29 | vless | 201.1 | 441.0 | 23.12 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 172.64.158.146 |
| 77.15 | shadowsocks | 246.7 | 505.3 | 22.07 | 0.0 | 10.0 | 13.36 | 18.48 | mheidari-all | 108.181.118.10 |
| 76.78 | vless | 214.2 | 427.9 | 22.82 | 0.0 | 10.0 | 11.85 | 19.36 | Au1rxx-base64 | 162.159.43.187 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.998 | 0.928 | 362 | 1801 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.75 | 48 | 7083 | prefer |
| ermaozi | 0.653 | 0.63 | 54 | 691 | observe |
| mheidari-all | 0.409 | 0.328 | 421 | 23039 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9601 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5600 | observe |
| barry-far-vless | 0.255 | None | 0 | 5876 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1801 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 180 |
| speed | TimeoutError | - | 71 |
| geo | ClientOSError | - | 33 |
| 204 | ProxyError | - | 25 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 10 |
| speed | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
