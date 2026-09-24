# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 21:33:27 |
| 运行耗时 | 491.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98134 |
| 去重后节点 | 26547 |
| TCP 可达 | 3000 |
| 真实可用 | 353 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26547 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 20.3 |
| geo | 1.5 |
| tcp | 43.7 |
| probe | 186.8 |
| real_test | 165.4 |
| generate | 74.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60229 |
| vmess | 14904 |
| shadowsocks | 11269 |
| trojan | 9245 |
| hysteria2 | 1598 |
| http | 592 |
| shadowsocksr | 174 |
| socks | 76 |
| anytls | 22 |
| hysteria | 18 |
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
| 82.78 | vless | 220.5 | 572.2 | 22.67 | 0.0 | 8.5 | 11.87 | 19.74 | Au1rxx-base64 | 172.235.43.210 |
| 80.77 | vless | 194.9 | 518.1 | 23.27 | 0.0 | 8.89 | 11.87 | 19.74 | Au1rxx-base64 | 192.3.247.109 |
| 80.48 | vless | 290.3 | 693.8 | 21.06 | 0.0 | 8.48 | 11.87 | 19.74 | Au1rxx-base64 | 136.117.218.86 |
| 78.76 | shadowsocks | 193.9 | 511.3 | 23.29 | 0.0 | 10.0 | 13.45 | 16.52 | mheidari-all | 192.3.247.109 |
| 77.7 | shadowsocks | 239.5 | 603.9 | 22.23 | 0.0 | 10.0 | 13.45 | 16.52 | mheidari-all | 108.181.118.10 |
| 77.41 | shadowsocks | 242.7 | 613.7 | 22.16 | 0.0 | 10.0 | 13.45 | 16.3 | Surfboard-tg-mixed | 108.181.0.177 |
| 77.34 | vless | 223.4 | 534.7 | 22.61 | 0.0 | 8.62 | 11.87 | 19.74 | Au1rxx-base64 | 172.64.154.8 |
| 77.27 | vless | 281.1 | 382.3 | 21.27 | 0.67 | 8.62 | 11.87 | 19.74 | Au1rxx-base64 | 188.114.97.6 |
| 77.08 | vless | 245.6 | 433.1 | 22.09 | 0.0 | 8.63 | 11.87 | 19.74 | Au1rxx-base64 | 172.64.158.146 |
| 76.81 | vless | 248.6 | 431.3 | 22.02 | 0.0 | 8.68 | 11.87 | 19.74 | Au1rxx-base64 | 162.159.0.53 |
| 76.11 | vless | 439.2 | 1131.4 | 17.61 | 0.0 | 8.5 | 11.87 | 19.74 | Au1rxx-base64 | 51.81.203.63 |
| 75.62 | shadowsocks | 340.5 | 869.7 | 19.9 | 0.0 | 10.0 | 13.45 | 16.3 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.62 | vless | 353.9 | 767.6 | 19.59 | 0.0 | 8.49 | 11.87 | 19.74 | Au1rxx-base64 | 79.141.172.154 |
| 75.58 | hysteria2 | 289.4 | 206.3 | 21.08 | 7.27 | 6.93 | 14.17 | 19.74 | Au1rxx-base64 | hk01.kfc-520.com |
| 75.5 | vless | 177.2 | 479.8 | 23.68 | 0.0 | 8.68 | 11.87 | 19.74 | Au1rxx-base64 | 137.175.82.40 |
| 75.19 | shadowsocks | 301.7 | 675.5 | 20.79 | 0.0 | 8.66 | 13.45 | 19.74 | Au1rxx-base64 | 156.146.38.168 |
| 75.03 | vless | 221.6 | 541.8 | 22.65 | 0.0 | 8.68 | 11.87 | 19.74 | Au1rxx-base64 | 104.18.34.14 |
| 74.85 | vless | 351.0 | 717.2 | 19.65 | 0.0 | 8.57 | 11.87 | 19.74 | Au1rxx-base64 | 195.211.98.43 |
| 74.33 | shadowsocks | 361.9 | 933.7 | 19.4 | 0.0 | 10.0 | 13.45 | 16.3 | Surfboard-tg-mixed | 173.244.56.9 |
| 73.53 | shadowsocks | 301.9 | 662.1 | 20.79 | 0.0 | 10.0 | 13.45 | 16.3 | Surfboard-tg-mixed | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | 0.911 | 257 | 1626 | prefer |
| Surfboard-tg-mixed | 0.858 | 0.788 | 52 | 7419 | prefer |
| mheidari-all | 0.827 | 0.753 | 85 | 22744 | prefer |
| ermaozi | 0.475 | 0.615 | 13 | 298 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5845 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4405 | observe |
| ermaozi-get_subscribe | 0.267 | 1.0 | 1 | 304 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 65 | observe |
| Epodonios-all | 0.255 | None | 0 | 7888 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9086 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5963 | observe |
| barry-far-vless | 0.255 | None | 0 | 6215 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 6 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| speed | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
