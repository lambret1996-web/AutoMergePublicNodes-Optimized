# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-16 12:33:40 |
| 运行耗时 | 691.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 87305 |
| 去重后节点 | 24333 |
| TCP 可达 | 3000 |
| 真实可用 | 474 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24333 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.6 |
| tcp | 41.3 |
| probe | 276.8 |
| real_test | 229.7 |
| generate | 135.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52492 |
| vmess | 13630 |
| shadowsocks | 9962 |
| trojan | 8816 |
| hysteria2 | 1546 |
| http | 653 |
| shadowsocksr | 129 |
| socks | 62 |
| hysteria | 8 |
| tuic | 5 |
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
| 79.87 | shadowsocks | 257.7 | 642.1 | 21.81 | 0.0 | 10.0 | 13.8 | 18.26 | Au1rxx-base64 | 156.146.38.170 |
| 78.76 | hysteria2 | 269.2 | 669.9 | 21.55 | 0.0 | 10.0 | 12.95 | 15.36 | mheidari-all | 159.223.157.129 |
| 78.49 | shadowsocks | 260.0 | 661.7 | 21.76 | 0.0 | 8.67 | 13.8 | 18.26 | Au1rxx-base64 | 37.19.198.244 |
| 77.16 | vless | 257.4 | 660.2 | 21.82 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 216.152.147.28 |
| 77.13 | shadowsocks | 279.4 | 642.2 | 21.31 | 0.0 | 10.0 | 13.8 | 18.26 | Au1rxx-base64 | 38.180.135.156 |
| 76.86 | shadowsocks | 262.4 | 667.2 | 21.7 | 0.0 | 10.0 | 13.8 | 15.36 | mheidari-all | 37.19.198.243 |
| 75.78 | shadowsocks | 281.1 | 593.6 | 21.27 | 0.0 | 8.6 | 13.8 | 18.26 | Au1rxx-base64 | 23.150.248.20 |
| 75.75 | shadowsocks | 310.5 | 773.0 | 20.59 | 0.0 | 10.0 | 13.8 | 15.36 | mheidari-all | 37.19.198.160 |
| 75.46 | shadowsocks | 252.1 | 616.1 | 21.94 | 0.0 | 10.0 | 13.8 | 13.72 | Surfboard-tg-mixed | 156.146.38.167 |
| 75.32 | vless | 318.1 | 763.8 | 20.41 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 169.40.42.179 |
| 75.22 | vless | 320.8 | 685.2 | 20.35 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 169.40.42.89 |
| 74.53 | vless | 270.2 | 635.1 | 21.52 | 0.0 | 8.71 | 7.08 | 18.26 | Au1rxx-base64 | 195.123.235.177 |
| 74.03 | vless | 300.2 | 682.5 | 20.83 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 169.40.42.184 |
| 73.94 | vless | 332.1 | 802.3 | 20.09 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 66.70.179.198 |
| 73.77 | vless | 321.0 | 663.9 | 20.35 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 169.40.42.133 |
| 73.75 | shadowsocks | 248.9 | 615.5 | 22.02 | 0.0 | 8.6 | 13.8 | 18.26 | Au1rxx-base64 | 156.146.38.169 |
| 73.73 | vless | 299.2 | 713.7 | 20.85 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 169.40.42.75 |
| 73.7 | vless | 323.4 | 780.2 | 20.29 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 167.17.69.171 |
| 73.68 | vless | 294.0 | 710.0 | 20.97 | 0.0 | 10.0 | 7.08 | 18.26 | Au1rxx-base64 | 169.40.42.35 |
| 73.54 | hysteria2 | 360.1 | 840.8 | 19.44 | 0.0 | 8.26 | 12.95 | 18.26 | Au1rxx-base64 | 107.175.219.48 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | 0.871 | 287 | 1684 | prefer |
| DeltaKronecker-all | 0.842 | 0.775 | 40 | 6081 | prefer |
| Surfboard-tg-mixed | 0.808 | 0.731 | 134 | 7446 | prefer |
| mheidari-all | 0.761 | 0.687 | 67 | 16003 | prefer |
| ermaozi | 0.713 | 0.704 | 54 | 407 | prefer |
| ermaozi-get_subscribe | 0.438 | 0.444 | 18 | 438 | observe |
| roosterkid-openproxylist-v2ray | 0.275 | 0.667 | 3 | 150 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5115 | observe |
| Epodonios-all | 0.255 | None | 0 | 7906 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8759 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6044 | observe |
| barry-far-vless | 0.255 | None | 0 | 6260 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4206 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 29 |
| geo | ClientOSError | - | 26 |
| cn-block | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 14 |
| speed | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 9 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | exit-country | CN | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32123: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
