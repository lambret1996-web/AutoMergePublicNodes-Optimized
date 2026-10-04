# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 16:46:44 |
| 运行耗时 | 665.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99556 |
| 去重后节点 | 27321 |
| TCP 可达 | 3000 |
| 真实可用 | 433 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27321 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.2 |
| tcp | 47.5 |
| probe | 331.1 |
| real_test | 200.3 |
| generate | 80.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59645 |
| vmess | 15935 |
| shadowsocks | 11483 |
| trojan | 10192 |
| hysteria2 | 1484 |
| http | 522 |
| shadowsocksr | 171 |
| socks | 74 |
| anytls | 27 |
| hysteria | 16 |
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
| 81.2 | shadowsocks | 242.1 | 634.2 | 22.17 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 156.146.38.169 |
| 81.01 | hysteria2 | 278.2 | 269.1 | 21.34 | 4.91 | 9.32 | 13.64 | 19.6 | Au1rxx-base64 | open.w2m.ink |
| 80.93 | shadowsocks | 253.8 | 637.5 | 21.9 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 156.146.38.167 |
| 79.57 | hysteria2 | 302.5 | 618.7 | 20.77 | 0.0 | 10.0 | 13.64 | 19.6 | Au1rxx-base64 | 66.94.121.46 |
| 78.38 | shadowsocks | 312.0 | 754.8 | 20.56 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 37.19.198.160 |
| 78.24 | hysteria2 | 287.7 | 726.6 | 21.12 | 0.0 | 10.0 | 13.64 | 16.98 | Surfboard-tg-mixed | 129.213.91.185 |
| 77.75 | shadowsocks | 253.6 | 634.7 | 21.91 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 156.146.38.170 |
| 76.75 | shadowsocks | 304.7 | 739.5 | 20.72 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 37.19.198.236 |
| 76.74 | shadowsocks | 273.4 | 582.6 | 21.45 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 5.78.51.123 |
| 75.94 | shadowsocks | 299.5 | 639.2 | 20.84 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 149.22.95.183 |
| 75.46 | shadowsocks | 291.9 | 609.3 | 21.02 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 173.244.56.9 |
| 74.03 | shadowsocks | 354.5 | 714.9 | 19.57 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 108.181.0.177 |
| 73.68 | shadowsocks | 393.6 | 929.2 | 18.67 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 108.181.57.93 |
| 73.27 | vless | 328.5 | 756.5 | 20.17 | 0.0 | 10.0 | 6.71 | 19.6 | Au1rxx-base64 | 66.70.179.198 |
| 72.83 | http | 448.7 | 1063.7 | 17.39 | 0.0 | 10.0 | 13.85 | 18.98 | ermaozi | 138.199.35.216 |
| 72.68 | http | 450.0 | 1067.6 | 17.36 | 0.0 | 10.0 | 13.85 | 18.98 | ermaozi | 138.199.35.198 |
| 72.55 | vless | 380.4 | 903.0 | 18.97 | 0.0 | 10.0 | 6.71 | 19.6 | Au1rxx-base64 | 159.89.87.21 |
| 72.49 | vless | 314.9 | 626.8 | 20.49 | 0.0 | 10.0 | 6.71 | 19.6 | Au1rxx-base64 | 195.123.240.65 |
| 72.35 | shadowsocks | 287.8 | 688.1 | 21.12 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 140.82.63.79 |
| 72.08 | shadowsocks | 286.2 | 577.5 | 21.15 | 0.0 | 10.0 | 13.43 | 19.6 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.972 | 0.901 | 303 | 1831 | prefer |
| ermaozi | 0.915 | 0.92 | 25 | 653 | prefer |
| mheidari-all | 0.85 | 0.78 | 59 | 23366 | prefer |
| Surfboard-tg-mixed | 0.723 | 0.646 | 127 | 7225 | prefer |
| ermaozi-get_subscribe | 0.379 | 1.0 | 3 | 518 | observe |
| DeltaKronecker-all | 0.318 | 0.235 | 17 | 5267 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7759 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9833 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5815 | observe |
| barry-far-vless | 0.255 | None | 0 | 6063 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 41 |
| cn-block | TimeoutError | - | 27 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 7 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 4 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
