# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 11:47:55 |
| 运行耗时 | 538.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96970 |
| 去重后节点 | 26329 |
| TCP 可达 | 3000 |
| 真实可用 | 375 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26329 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.5 |
| tcp | 43.3 |
| probe | 228.4 |
| real_test | 162.3 |
| generate | 97.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58826 |
| vmess | 15169 |
| shadowsocks | 11415 |
| trojan | 8991 |
| hysteria2 | 1643 |
| http | 635 |
| shadowsocksr | 172 |
| socks | 73 |
| anytls | 24 |
| hysteria | 15 |
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
| 82.56 | hysteria2 | 286.9 | 686.9 | 21.14 | 0.0 | 8.79 | 14.35 | 19.28 | Au1rxx-base64 | 66.94.121.46 |
| 79.58 | shadowsocks | 261.5 | 640.2 | 21.72 | 0.0 | 8.76 | 13.82 | 19.28 | Au1rxx-base64 | 156.146.38.168 |
| 76.79 | hysteria2 | 362.1 | 751.7 | 19.4 | 0.0 | 8.77 | 14.35 | 19.28 | Au1rxx-base64 | 159.223.157.129 |
| 75.99 | shadowsocks | 241.1 | 559.2 | 22.2 | 0.0 | 10.0 | 13.82 | 14.98 | Surfboard-tg-mixed | 5.78.51.123 |
| 75.92 | shadowsocks | 287.7 | 674.8 | 21.12 | 0.0 | 10.0 | 13.82 | 14.98 | Surfboard-tg-mixed | 173.244.56.9 |
| 74.71 | vless | 197.4 | 518.8 | 23.21 | 0.0 | 8.85 | 5.37 | 19.28 | Au1rxx-base64 | 192.3.247.109 |
| 73.56 | vless | 197.4 | 520.3 | 23.21 | 0.0 | 10.0 | 5.37 | 14.98 | Surfboard-tg-mixed | 172.235.38.85 |
| 73.09 | hysteria2 | 338.3 | 559.8 | 19.95 | 0.0 | 7.62 | 14.35 | 19.28 | Au1rxx-base64 | open.w2m.ink |
| 72.89 | shadowsocks | 194.6 | 486.2 | 23.27 | 0.0 | 10.0 | 13.82 | 14.98 | Surfboard-tg-mixed | 108.181.0.177 |
| 72.84 | shadowsocks | 305.1 | 357.4 | 20.71 | 1.6 | 8.71 | 13.82 | 19.28 | Au1rxx-base64 | 149.22.87.204 |
| 71.96 | shadowsocks | 381.6 | 829.5 | 18.95 | 0.0 | 8.72 | 13.82 | 19.28 | Au1rxx-base64 | 198.98.53.130 |
| 71.78 | shadowsocks | 362.8 | 769.7 | 19.38 | 0.0 | 8.76 | 13.82 | 19.28 | Au1rxx-base64 | 185.156.47.97 |
| 71.59 | http | 254.2 | 676.0 | 21.89 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.198 |
| 71.55 | http | 255.9 | 676.2 | 21.85 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.200 |
| 71.55 | http | 256.2 | 670.3 | 21.85 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.216 |
| 71.54 | http | 256.7 | 673.3 | 21.84 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.206 |
| 71.54 | http | 256.7 | 682.4 | 21.84 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.201 |
| 71.51 | http | 257.6 | 674.7 | 21.81 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.203 |
| 71.5 | http | 258.1 | 677.5 | 21.8 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.210 |
| 71.5 | http | 258.2 | 671.2 | 21.8 | 0.0 | 10.0 | 9.84 | 12.86 | ermaozi | 138.199.35.217 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | 0.899 | 238 | 1624 | prefer |
| mheidari-all | 0.817 | 0.743 | 74 | 22444 | prefer |
| Surfboard-tg-mixed | 0.753 | 0.676 | 102 | 7280 | prefer |
| ermaozi | 0.701 | 0.696 | 46 | 338 | prefer |
| DeltaKronecker-all | 0.361 | 0.4 | 10 | 5452 | observe |
| ermaozi-get_subscribe | 0.269 | 1.0 | 1 | 359 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| Epodonios-all | 0.255 | None | 0 | 7869 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9069 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5801 | observe |
| barry-far-vless | 0.255 | None | 0 | 6140 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4324 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 24 |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 11 |
| speed | TimeoutError | - | 5 |
| geo | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
