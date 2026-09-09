# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 12:33:19 |
| 运行耗时 | 650.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 85006 |
| 去重后节点 | 22116 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22116 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 37.0 |
| probe | 247.8 |
| real_test | 263.1 |
| generate | 94.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52615 |
| vmess | 12073 |
| shadowsocks | 9858 |
| trojan | 7992 |
| hysteria2 | 1630 |
| http | 639 |
| shadowsocksr | 124 |
| socks | 56 |
| hysteria | 9 |
| tuic | 8 |
| anytls | 2 |

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
| 80.2 | shadowsocks | 225.0 | 584.9 | 22.57 | 0.0 | 10.0 | 14.13 | 17.5 | Surfboard-tg-mixed | 198.98.53.130 |
| 79.97 | vless | 238.4 | 639.5 | 22.26 | 0.0 | 9.16 | 10.47 | 18.08 | Au1rxx-base64 | 137.184.218.169 |
| 79.42 | vless | 262.6 | 665.6 | 21.7 | 0.0 | 9.17 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.224 |
| 79.32 | vless | 264.5 | 695.9 | 21.65 | 0.0 | 9.12 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.232 |
| 79.05 | vless | 280.1 | 625.5 | 21.29 | 0.0 | 9.21 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.229 |
| 79.01 | vless | 250.8 | 703.7 | 21.97 | 0.0 | 9.49 | 10.47 | 18.08 | Au1rxx-base64 | 47.253.226.114 |
| 78.97 | shadowsocks | 234.0 | 645.3 | 22.36 | 0.0 | 10.0 | 14.13 | 16.48 | mheidari-all | 37.19.198.160 |
| 78.93 | shadowsocks | 236.0 | 644.8 | 22.32 | 0.0 | 10.0 | 14.13 | 16.48 | mheidari-all | 37.19.198.236 |
| 78.87 | hysteria2 | 235.1 | 647.5 | 22.34 | 0.0 | 10.0 | 14.0 | 17.5 | Surfboard-tg-mixed | 159.223.157.129 |
| 78.79 | vless | 294.0 | 739.4 | 20.97 | 0.0 | 9.27 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.231 |
| 78.7 | shadowsocks | 245.9 | 676.1 | 22.09 | 0.0 | 10.0 | 14.13 | 16.48 | mheidari-all | 37.19.198.244 |
| 78.65 | shadowsocks | 248.1 | 686.2 | 22.04 | 0.0 | 10.0 | 14.13 | 16.48 | mheidari-all | 37.19.198.243 |
| 78.64 | vless | 295.8 | 653.0 | 20.93 | 0.0 | 9.16 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.52 |
| 78.3 | vless | 312.6 | 836.5 | 20.54 | 0.0 | 9.21 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.35 |
| 78.25 | vless | 313.1 | 848.3 | 20.53 | 0.0 | 9.17 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.163 |
| 78.2 | vless | 313.1 | 723.2 | 20.53 | 0.0 | 9.12 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.212 |
| 78.1 | vless | 314.9 | 727.7 | 20.49 | 0.0 | 9.16 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.89 |
| 78.0 | vless | 323.7 | 884.0 | 20.28 | 0.0 | 9.17 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.182 |
| 77.76 | shadowsocks | 308.8 | 766.3 | 20.63 | 0.0 | 10.0 | 14.13 | 17.5 | Surfboard-tg-mixed | 51.222.200.165 |
| 77.73 | vless | 337.2 | 850.2 | 19.97 | 0.0 | 9.21 | 10.47 | 18.08 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.954 | 0.887 | 248 | 1749 | prefer |
| mheidari-all | 0.883 | 0.812 | 64 | 16452 | prefer |
| Surfboard-tg-mixed | 0.82 | 0.743 | 175 | 7479 | prefer |
| ermaozi-get_subscribe | 0.618 | 0.632 | 19 | 473 | observe |
| ermaozi | 0.613 | 0.6 | 40 | 442 | observe |
| DeltaKronecker-all | 0.372 | 0.444 | 9 | 5187 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 180 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7926 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9096 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6181 | observe |
| barry-far-vless | 0.255 | None | 0 | 6404 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 23 |
| geo | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 4 |
| geo | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
