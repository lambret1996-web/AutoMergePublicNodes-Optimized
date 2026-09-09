# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 18:30:36 |
| 运行耗时 | 577.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83949 |
| 去重后节点 | 21979 |
| TCP 可达 | 3000 |
| 真实可用 | 478 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21979 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 37.0 |
| probe | 212.7 |
| real_test | 239.5 |
| generate | 81.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51379 |
| vmess | 12155 |
| shadowsocks | 10092 |
| trojan | 7924 |
| hysteria2 | 1640 |
| http | 555 |
| shadowsocksr | 133 |
| socks | 53 |
| hysteria | 8 |
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
| 82.19 | hysteria2 | 272.9 | 684.0 | 21.46 | 0.0 | 10.0 | 14.17 | 17.66 | mheidari-all | 159.223.157.129 |
| 81.38 | vless | 290.8 | 736.2 | 21.05 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 47.253.226.114 |
| 80.88 | shadowsocks | 253.8 | 626.2 | 21.9 | 0.0 | 10.0 | 13.9 | 19.08 | Au1rxx-base64 | 156.146.38.169 |
| 80.74 | vless | 318.1 | 847.6 | 20.41 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 216.152.147.28 |
| 79.77 | vless | 276.9 | 646.3 | 21.37 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 195.123.235.177 |
| 79.61 | vless | 355.8 | 886.3 | 19.54 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 137.184.218.169 |
| 79.57 | vless | 320.4 | 665.3 | 20.36 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.95 |
| 79.32 | shadowsocks | 259.8 | 638.3 | 21.76 | 0.0 | 10.0 | 13.9 | 17.66 | mheidari-all | 156.146.38.168 |
| 79.28 | vless | 353.3 | 741.5 | 19.6 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.235 |
| 79.2 | shadowsocks | 304.8 | 794.3 | 20.72 | 0.0 | 10.0 | 13.9 | 19.08 | Au1rxx-base64 | 15.204.246.189 |
| 79.03 | shadowsocks | 255.9 | 626.1 | 21.85 | 0.0 | 10.0 | 13.9 | 17.66 | mheidari-all | 156.146.38.170 |
| 78.93 | vless | 290.7 | 692.3 | 21.05 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.224 |
| 78.84 | vless | 312.3 | 732.5 | 20.55 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 66.70.179.198 |
| 78.83 | shadowsocks | 281.2 | 714.7 | 21.27 | 0.0 | 10.0 | 13.9 | 17.66 | mheidari-all | 37.19.198.243 |
| 78.42 | vless | 305.7 | 686.9 | 20.7 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.184 |
| 78.42 | vless | 345.2 | 836.6 | 19.79 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.225 |
| 78.34 | vless | 375.4 | 833.0 | 19.09 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.212 |
| 78.03 | shadowsocks | 261.3 | 650.7 | 21.73 | 0.0 | 10.0 | 13.9 | 16.4 | Surfboard-tg-mixed | 37.19.198.160 |
| 78.0 | vless | 326.1 | 793.7 | 20.23 | 0.0 | 10.0 | 11.25 | 19.08 | Au1rxx-base64 | 169.40.42.89 |
| 77.96 | shadowsocks | 264.3 | 660.4 | 21.66 | 0.0 | 10.0 | 13.9 | 16.4 | Surfboard-tg-mixed | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | 0.914 | 290 | 1557 | prefer |
| ermaozi | 0.775 | 0.778 | 27 | 410 | prefer |
| Surfboard-tg-mixed | 0.767 | 0.69 | 145 | 7400 | prefer |
| DeltaKronecker-all | 0.705 | 0.633 | 30 | 5187 | prefer |
| mheidari-all | 0.699 | 0.622 | 111 | 16196 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 190 | observe |
| Au1rxx-clash | 0.317 | 1.0 | 1 | 1558 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 418 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7880 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9272 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5999 | observe |
| barry-far-vless | 0.255 | None | 0 | 6218 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4247 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 40 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 6 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
