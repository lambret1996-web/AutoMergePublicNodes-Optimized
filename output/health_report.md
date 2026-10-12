# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-12 21:16:03 |
| 运行耗时 | 883.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 100399 |
| 去重后节点 | 27904 |
| TCP 可达 | 3000 |
| 真实可用 | 497 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27904 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.7 |
| tcp | 48.6 |
| probe | 373.4 |
| real_test | 365.1 |
| generate | 87.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59006 |
| vmess | 15855 |
| shadowsocks | 12033 |
| trojan | 11087 |
| hysteria2 | 1469 |
| http | 655 |
| shadowsocksr | 176 |
| socks | 69 |
| anytls | 26 |
| hysteria | 17 |
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
| 83.67 | hysteria2 | 281.2 | 710.0 | 21.27 | 0.0 | 10.0 | 14.48 | 19.42 | Au1rxx-base64 | 129.213.91.185 |
| 81.74 | shadowsocks | 240.1 | 596.7 | 22.22 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 156.146.38.169 |
| 81.48 | shadowsocks | 251.2 | 639.1 | 21.96 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 156.146.38.167 |
| 81.28 | shadowsocks | 260.0 | 647.1 | 21.76 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 156.146.38.168 |
| 80.86 | shadowsocks | 249.7 | 603.5 | 22.0 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 156.146.38.170 |
| 78.95 | shadowsocks | 309.0 | 742.9 | 20.62 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 37.19.198.244 |
| 78.87 | shadowsocks | 312.3 | 761.6 | 20.55 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 37.19.198.243 |
| 78.72 | shadowsocks | 306.0 | 743.2 | 20.69 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 37.19.198.160 |
| 77.71 | hysteria2 | 416.1 | 530.4 | 18.15 | 0.0 | 10.0 | 14.48 | 19.42 | Au1rxx-base64 | 66.94.121.46 |
| 77.37 | shadowsocks | 309.2 | 693.6 | 20.62 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 140.82.63.79 |
| 75.34 | shadowsocks | 311.2 | 605.0 | 20.57 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 173.244.56.6 |
| 74.61 | shadowsocks | 416.5 | 1067.6 | 18.14 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 66.23.205.83 |
| 73.77 | shadowsocks | 418.4 | 1074.2 | 18.09 | 0.0 | 9.34 | 14.1 | 19.42 | Au1rxx-base64 | ca225.vpnbook.com |
| 73.06 | trojan | 340.3 | 643.8 | 19.9 | 0.0 | 10.0 | 13.68 | 19.42 | Au1rxx-base64 | 34.220.15.24 |
| 72.91 | vless | 265.1 | 622.0 | 21.64 | 0.0 | 10.0 | 5.46 | 19.42 | Au1rxx-base64 | 172.245.253.16 |
| 72.86 | hysteria2 | 285.4 | 270.7 | 21.17 | 4.85 | 2.61 | 14.48 | 19.42 | Au1rxx-base64 | open.2ml.cc.cd |
| 72.73 | shadowsocks | 319.3 | 645.2 | 20.39 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 149.22.95.183 |
| 72.7 | shadowsocks | 485.2 | 1026.1 | 16.55 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 15.204.233.41 |
| 72.37 | trojan | 460.7 | 1180.6 | 17.11 | 0.0 | 10.0 | 13.68 | 19.42 | Au1rxx-base64 | 69.164.240.85 |
| 72.14 | shadowsocks | 345.9 | 809.6 | 19.77 | 0.0 | 10.0 | 14.1 | 19.42 | Au1rxx-base64 | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.91 | 356 | 1842 | prefer |
| mheidari-all | 0.92 | 0.854 | 48 | 23860 | prefer |
| Surfboard-tg-mixed | 0.759 | 0.686 | 51 | 7235 | prefer |
| DeltaKronecker-all | 0.637 | 0.558 | 120 | 5701 | observe |
| ermaozi | 0.578 | 0.553 | 47 | 675 | observe |
| ermaozi-get_subscribe | 0.333 | 1.0 | 2 | 532 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5028 | observe |
| Epodonios-all | 0.255 | None | 0 | 7736 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9955 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5776 | observe |
| barry-far-vless | 0.255 | None | 0 | 6023 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 34 |
| 204 | ProxyError | - | 26 |
| 204 | TimeoutError | - | 25 |
| geo | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 7 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 6 |
| speed | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
