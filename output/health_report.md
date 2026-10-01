# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 07:10:08 |
| 运行耗时 | 669.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97940 |
| 去重后节点 | 27098 |
| TCP 可达 | 3000 |
| 真实可用 | 382 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27098 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.7 |
| tcp | 46.1 |
| probe | 264.3 |
| real_test | 270.5 |
| generate | 80.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59814 |
| vmess | 15346 |
| shadowsocks | 11408 |
| trojan | 9130 |
| hysteria2 | 1415 |
| http | 533 |
| shadowsocksr | 164 |
| socks | 66 |
| anytls | 40 |
| hysteria | 16 |
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
| 82.67 | hysteria2 | 254.8 | 578.1 | 21.88 | 0.0 | 10.0 | 14.29 | 17.5 | Au1rxx-base64 | 66.94.121.46 |
| 80.38 | hysteria2 | 290.1 | 613.4 | 21.06 | 0.0 | 10.0 | 14.29 | 17.5 | Au1rxx-base64 | 192.255.128.123 |
| 79.43 | shadowsocks | 241.1 | 617.8 | 22.2 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 156.146.38.167 |
| 79.34 | shadowsocks | 244.8 | 628.8 | 22.11 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 156.146.38.169 |
| 78.03 | hysteria2 | 325.8 | 750.0 | 20.24 | 0.0 | 10.0 | 14.29 | 17.5 | Au1rxx-base64 | 159.223.157.129 |
| 77.43 | http | 271.6 | 575.3 | 21.49 | 0.0 | 10.0 | 13.8 | 18.74 | ermaozi | 138.199.35.216 |
| 76.55 | http | 276.2 | 585.7 | 21.38 | 0.0 | 10.0 | 13.8 | 18.74 | ermaozi | 138.199.35.198 |
| 75.64 | shadowsocks | 279.6 | 635.0 | 21.3 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 104.192.225.110 |
| 74.83 | shadowsocks | 243.6 | 532.4 | 22.14 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 173.234.25.90 |
| 74.78 | shadowsocks | 297.6 | 659.2 | 20.89 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 198.98.53.130 |
| 74.71 | shadowsocks | 285.0 | 601.1 | 21.18 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 108.181.118.10 |
| 74.55 | shadowsocks | 287.8 | 580.4 | 21.12 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 173.244.56.6 |
| 74.1 | vless | 302.2 | 730.6 | 20.78 | 0.0 | 10.0 | 6.49 | 17.5 | Au1rxx-base64 | 79.141.172.154 |
| 74.06 | shadowsocks | 326.8 | 815.0 | 20.21 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 103.214.111.162 |
| 74.04 | shadowsocks | 271.0 | 515.5 | 21.51 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 108.181.0.177 |
| 73.68 | shadowsocks | 246.7 | 535.4 | 22.07 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 103.214.109.197 |
| 73.44 | shadowsocks | 343.3 | 788.0 | 19.83 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 37.19.198.160 |
| 73.36 | shadowsocks | 339.4 | 776.0 | 19.92 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 37.19.198.244 |
| 73.16 | shadowsocks | 319.5 | 660.1 | 20.38 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 149.22.95.183 |
| 73.05 | shadowsocks | 342.5 | 785.0 | 19.85 | 0.0 | 10.0 | 13.73 | 17.5 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.871 | 0.805 | 303 | 1699 | prefer |
| ermaozi | 0.831 | 0.833 | 24 | 588 | prefer |
| Surfboard-tg-mixed | 0.59 | 0.51 | 143 | 7136 | observe |
| mheidari-all | 0.362 | 0.279 | 140 | 22835 | observe |
| ermaozi-get_subscribe | 0.331 | 1.0 | 2 | 487 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 66 | observe |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 5434 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7625 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9403 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5815 | observe |
| barry-far-vless | 0.255 | None | 0 | 6050 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4241 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 69 |
| speed | ClientOSError | - | 55 |
| speed | TimeoutError | - | 35 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 17 |
| cn-block | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |
| 204 | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
