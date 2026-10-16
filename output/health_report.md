# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 16:28:59 |
| 运行耗时 | 839.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99087 |
| 去重后节点 | 27699 |
| TCP 可达 | 3000 |
| 真实可用 | 387 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27699 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.3 |
| tcp | 48.6 |
| probe | 401.1 |
| real_test | 302.1 |
| generate | 80.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58347 |
| vmess | 16351 |
| shadowsocks | 12096 |
| trojan | 10043 |
| hysteria2 | 1313 |
| http | 662 |
| shadowsocksr | 164 |
| socks | 59 |
| anytls | 29 |
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
| 80.82 | hysteria2 | 271.4 | 701.6 | 21.5 | 0.0 | 10.0 | 14.06 | 16.76 | Au1rxx-base64 | 129.213.91.185 |
| 78.21 | shadowsocks | 248.4 | 644.1 | 22.03 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 156.146.38.167 |
| 78.05 | hysteria2 | 293.7 | 613.3 | 20.98 | 0.0 | 10.0 | 14.06 | 16.76 | Au1rxx-base64 | 66.94.121.46 |
| 76.7 | shadowsocks | 308.4 | 747.6 | 20.64 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 37.19.198.160 |
| 76.6 | vless | 257.8 | 642.3 | 21.81 | 0.0 | 10.0 | 8.03 | 16.76 | Au1rxx-base64 | 195.211.98.43 |
| 76.3 | vless | 270.9 | 674.0 | 21.51 | 0.0 | 10.0 | 8.03 | 16.76 | Au1rxx-base64 | 147.45.60.160 |
| 74.98 | shadowsocks | 311.4 | 762.6 | 20.57 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 37.19.198.244 |
| 74.68 | shadowsocks | 306.7 | 732.8 | 20.68 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 37.19.198.243 |
| 73.23 | shadowsocks | 247.2 | 613.4 | 22.05 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 156.146.38.169 |
| 73.09 | shadowsocks | 253.4 | 660.6 | 21.91 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 156.146.38.170 |
| 72.14 | shadowsocks | 301.2 | 613.3 | 20.8 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 173.244.56.6 |
| 71.94 | shadowsocks | 291.9 | 605.1 | 21.02 | 0.0 | 10.0 | 13.42 | 16.76 | Au1rxx-base64 | 173.244.56.9 |
| 71.81 | vless | 321.5 | 745.3 | 20.34 | 0.0 | 10.0 | 8.03 | 16.76 | Au1rxx-base64 | 137.184.218.169 |
| 70.96 | shadowsocks | 334.7 | 322.7 | 20.03 | 2.9 | 9.62 | 13.42 | 16.76 | Au1rxx-base64 | 149.22.87.204 |
| 70.68 | trojan | 472.0 | 1174.1 | 16.85 | 0.0 | 10.0 | 12.72 | 16.76 | Au1rxx-base64 | 69.164.240.85 |
| 70.65 | shadowsocks | 335.9 | 330.2 | 20.0 | 2.62 | 9.63 | 13.42 | 16.76 | Au1rxx-base64 | 149.22.87.241 |
| 70.64 | vless | 410.7 | 1008.3 | 18.27 | 0.0 | 10.0 | 8.03 | 16.76 | Au1rxx-base64 | 185.95.231.156 |
| 70.26 | shadowsocks | 341.0 | 337.4 | 19.88 | 2.35 | 9.62 | 13.42 | 16.76 | Au1rxx-base64 | 149.22.87.240 |
| 70.06 | vless | 320.6 | 786.0 | 20.36 | 0.0 | 10.0 | 8.03 | 16.76 | Au1rxx-base64 | uspanel.unixzone.us |
| 69.93 | vless | 340.6 | 724.1 | 19.89 | 0.0 | 10.0 | 8.03 | 16.76 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.822 | 0.743 | 444 | 1991 | prefer |
| DeltaKronecker-all | 0.509 | 0.425 | 40 | 4946 | observe |
| ermaozi | 0.444 | 0.417 | 60 | 618 | observe |
| Surfboard-tg-mixed | 0.376 | 0.28 | 25 | 7090 | observe |
| mheidari-all | 0.372 | 0.444 | 9 | 23974 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 484 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 7602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9917 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 62 |
| 204 | ProxyError | - | 47 |
| cn-block | TimeoutError | - | 24 |
| speed | TimeoutError | - | 17 |
| speed | ClientOSError | - | 13 |
| geo | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
