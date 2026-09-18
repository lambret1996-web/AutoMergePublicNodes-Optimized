# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 12:30:52 |
| 运行耗时 | 612.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83287 |
| 去重后节点 | 22995 |
| TCP 可达 | 3000 |
| 真实可用 | 393 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22995 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.6 |
| geo | 1.3 |
| tcp | 38.8 |
| probe | 241.0 |
| real_test | 243.3 |
| generate | 84.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49579 |
| vmess | 13250 |
| shadowsocks | 10010 |
| trojan | 8211 |
| hysteria2 | 1378 |
| http | 649 |
| shadowsocksr | 127 |
| socks | 69 |
| hysteria | 8 |
| anytls | 4 |
| tuic | 2 |

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
| 82.97 | hysteria2 | 200.9 | 549.5 | 23.13 | 0.0 | 10.0 | 12.86 | 17.98 | Au1rxx-base64 | 66.94.121.46 |
| 76.71 | shadowsocks | 248.0 | 514.7 | 22.04 | 0.0 | 10.0 | 14.11 | 17.98 | Au1rxx-base64 | 108.181.118.10 |
| 75.23 | vless | 258.0 | 573.7 | 21.81 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 31.58.50.200 |
| 74.52 | vless | 317.8 | 716.5 | 20.42 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 172.235.43.210 |
| 73.7 | shadowsocks | 313.9 | 333.6 | 20.51 | 2.49 | 10.0 | 14.11 | 17.98 | Au1rxx-base64 | 84.247.155.196 |
| 73.32 | shadowsocks | 213.7 | 575.2 | 22.83 | 0.0 | 10.0 | 14.11 | 10.38 | mheidari-all | 149.22.95.183 |
| 73.05 | shadowsocks | 345.8 | 618.5 | 19.77 | 0.0 | 10.0 | 14.11 | 17.98 | Au1rxx-base64 | 23.150.248.20 |
| 72.29 | shadowsocks | 375.3 | 864.9 | 19.09 | 0.0 | 10.0 | 14.11 | 17.98 | Au1rxx-base64 | 156.146.38.169 |
| 71.34 | vless | 297.5 | 419.4 | 20.89 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 162.159.0.169 |
| 71.3 | vless | 230.1 | 445.6 | 22.45 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 104.18.46.46 |
| 70.68 | vless | 323.4 | 651.5 | 20.29 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 45.149.172.80 |
| 70.47 | vless | 275.8 | 621.0 | 21.39 | 0.0 | 10.0 | 8.11 | 13.82 | Surfboard-tg-mixed | 88.216.57.128 |
| 70.44 | vless | 378.4 | 787.5 | 19.02 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 79.141.172.154 |
| 70.08 | vless | 202.6 | 478.2 | 23.09 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 104.16.10.2 |
| 68.74 | vless | 510.0 | 1317.6 | 15.97 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 51.81.203.63 |
| 68.6 | vless | 356.0 | 390.1 | 19.54 | 0.37 | 9.86 | 8.11 | 17.98 | Au1rxx-base64 | 46.250.250.149 |
| 68.46 | hysteria2 | 494.9 | 840.5 | 16.32 | 0.0 | 9.37 | 12.86 | 17.98 | Au1rxx-base64 | 45.192.12.93 |
| 68.31 | vless | 310.5 | 426.7 | 20.59 | 0.0 | 10.0 | 8.11 | 17.98 | Au1rxx-base64 | 139.64.235.77 |
| 67.96 | shadowsocks | 403.7 | 365.8 | 18.43 | 1.28 | 8.88 | 14.11 | 17.98 | Au1rxx-base64 | 194.233.74.160 |
| 67.88 | vless | 288.1 | 451.8 | 21.11 | 0.0 | 10.0 | 8.11 | 11.72 | DeltaKronecker-all | 139.64.235.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.969 | 0.912 | 34 | 15778 | prefer |
| Au1rxx-base64 | 0.914 | 0.852 | 230 | 1624 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.678 | 143 | 7294 | prefer |
| ermaozi | 0.754 | 0.75 | 44 | 378 | prefer |
| DeltaKronecker-all | 0.436 | 0.354 | 99 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5076 | observe |
| Epodonios-all | 0.255 | None | 0 | 7751 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8732 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5763 | observe |
| barry-far-vless | 0.255 | None | 0 | 5979 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1624 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 47 |
| geo | ClientOSError | - | 36 |
| 204 | TimeoutError | - | 20 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 11 |
| speed | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
