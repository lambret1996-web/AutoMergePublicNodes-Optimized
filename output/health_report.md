# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 16:01:15 |
| 运行耗时 | 504.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99542 |
| 去重后节点 | 27331 |
| TCP 可达 | 3000 |
| 真实可用 | 334 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27331 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.5 |
| tcp | 47.7 |
| probe | 189.4 |
| real_test | 173.4 |
| generate | 83.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60961 |
| vmess | 15419 |
| shadowsocks | 11441 |
| trojan | 9373 |
| hysteria2 | 1543 |
| http | 521 |
| shadowsocksr | 170 |
| socks | 65 |
| anytls | 24 |
| hysteria | 17 |
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
| 81.23 | shadowsocks | 254.2 | 710.2 | 21.89 | 0.0 | 10.0 | 13.54 | 19.8 | Au1rxx-base64 | 37.19.198.244 |
| 81.14 | shadowsocks | 258.3 | 719.8 | 21.8 | 0.0 | 10.0 | 13.54 | 19.8 | Au1rxx-base64 | 37.19.198.243 |
| 80.74 | shadowsocks | 254.1 | 664.5 | 21.9 | 0.0 | 10.0 | 13.54 | 19.8 | Au1rxx-base64 | 140.82.63.79 |
| 79.59 | hysteria2 | 291.0 | 588.0 | 21.04 | 0.0 | 10.0 | 13.5 | 19.8 | Au1rxx-base64 | 192.255.128.123 |
| 78.05 | shadowsocks | 283.5 | 649.0 | 21.22 | 0.0 | 10.0 | 13.54 | 19.8 | Au1rxx-base64 | 156.146.38.170 |
| 77.92 | vless | 281.0 | 714.0 | 21.27 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 66.70.179.198 |
| 76.27 | shadowsocks | 252.4 | 706.1 | 21.93 | 0.0 | 10.0 | 13.54 | 19.8 | Au1rxx-base64 | 37.19.198.236 |
| 76.07 | vless | 293.1 | 657.7 | 20.99 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 169.40.42.231 |
| 74.94 | hysteria2 | 313.4 | 651.9 | 20.52 | 0.0 | 9.47 | 13.5 | 19.8 | Au1rxx-base64 | 66.94.121.46 |
| 74.11 | vless | 251.3 | 662.8 | 21.96 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 162.159.0.169 |
| 74.1 | vless | 378.3 | 996.8 | 19.02 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 169.40.42.90 |
| 74.02 | vless | 322.8 | 885.8 | 20.31 | 0.0 | 7.06 | 6.85 | 19.8 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 73.18 | hysteria2 | 412.3 | 760.7 | 18.23 | 0.0 | 10.0 | 13.5 | 19.8 | Au1rxx-base64 | 217.60.33.215 |
| 73.07 | hysteria2 | 476.5 | 950.7 | 16.75 | 0.0 | 10.0 | 13.5 | 19.8 | Au1rxx-base64 | 64.188.98.171 |
| 72.86 | hysteria2 | 256.5 | 682.7 | 21.84 | 0.0 | 10.0 | 13.5 | 8.62 | mheidari-all | 159.223.157.129 |
| 71.82 | vless | 249.8 | 671.5 | 21.99 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 137.184.218.169 |
| 71.6 | vless | 345.1 | 857.6 | 19.79 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 169.40.42.89 |
| 71.35 | vless | 312.3 | 863.0 | 20.55 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 159.89.87.21 |
| 71.32 | hysteria2 | 449.2 | 666.2 | 17.38 | 0.0 | 8.86 | 13.5 | 19.8 | Au1rxx-base64 | open.w2m.ink |
| 71.03 | vless | 337.5 | 627.4 | 19.97 | 0.0 | 10.0 | 6.85 | 19.8 | Au1rxx-base64 | 172.235.38.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.919 | 0.851 | 261 | 1778 | prefer |
| ermaozi | 0.906 | 0.913 | 23 | 656 | prefer |
| Surfboard-tg-mixed | 0.796 | 0.72 | 107 | 7404 | prefer |
| mheidari-all | 0.705 | 0.636 | 22 | 23342 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5192 | observe |
| Epodonios-all | 0.255 | None | 0 | 7883 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9374 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6035 | observe |
| barry-far-vless | 0.255 | None | 0 | 6273 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4335 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1778 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 8 |
| 204 | ProxyConnectionError | - | 6 |
| geo | TimeoutError | - | 5 |
| geo | ClientOSError | - | 3 |
| speed | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
