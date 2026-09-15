# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 18:27:56 |
| 运行耗时 | 575.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84957 |
| 去重后节点 | 23035 |
| TCP 可达 | 3000 |
| 真实可用 | 456 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23035 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.8 |
| tcp | 38.1 |
| probe | 214.4 |
| real_test | 220.4 |
| generate | 95.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51852 |
| vmess | 12987 |
| shadowsocks | 9458 |
| trojan | 8332 |
| hysteria2 | 1505 |
| http | 624 |
| shadowsocksr | 126 |
| socks | 55 |
| hysteria | 11 |
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
| 80.26 | vless | 255.4 | 669.8 | 21.87 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 45.149.172.74 |
| 80.18 | hysteria2 | 279.5 | 688.9 | 21.31 | 0.0 | 10.0 | 11.88 | 18.18 | Au1rxx-base64 | 107.175.219.48 |
| 79.75 | shadowsocks | 241.3 | 637.0 | 22.19 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 173.244.56.9 |
| 79.74 | shadowsocks | 241.9 | 642.0 | 22.18 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 173.244.56.6 |
| 79.62 | hysteria2 | 238.3 | 548.6 | 22.26 | 0.0 | 9.76 | 11.88 | 18.18 | Au1rxx-base64 | 66.94.121.46 |
| 79.39 | shadowsocks | 235.2 | 587.4 | 22.33 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 108.181.0.177 |
| 79.2 | vless | 300.9 | 800.8 | 20.81 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 192.3.247.109 |
| 79.06 | vless | 263.6 | 536.7 | 21.68 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 144.172.104.26 |
| 77.22 | shadowsocks | 264.5 | 639.0 | 21.66 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 156.146.38.169 |
| 76.86 | shadowsocks | 260.6 | 627.8 | 21.74 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 156.146.38.170 |
| 76.68 | vless | 193.9 | 487.3 | 23.29 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 172.235.43.210 |
| 76.67 | hysteria2 | 195.7 | 492.5 | 23.25 | 0.0 | 10.0 | 11.88 | 14.54 | Surfboard-tg-mixed | 45.149.172.80 |
| 76.41 | vless | 217.3 | 508.6 | 22.75 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 172.64.158.146 |
| 76.24 | vless | 234.7 | 523.7 | 22.35 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 172.64.32.108 |
| 75.89 | vless | 240.9 | 482.3 | 22.2 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 162.159.48.32 |
| 75.78 | vless | 231.4 | 483.6 | 22.42 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 162.159.38.127 |
| 75.74 | shadowsocks | 268.7 | 655.2 | 21.56 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 156.146.38.168 |
| 74.88 | shadowsocks | 289.1 | 612.6 | 21.09 | 0.0 | 10.0 | 13.38 | 18.18 | Au1rxx-base64 | 149.22.95.183 |
| 74.54 | shadowsocks | 244.0 | 562.7 | 22.13 | 0.0 | 10.0 | 13.38 | 14.54 | Surfboard-tg-mixed | 5.78.51.123 |
| 74.14 | vless | 242.2 | 540.2 | 22.17 | 0.0 | 10.0 | 10.21 | 18.18 | Au1rxx-base64 | 31.58.50.200 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | 0.887 | 311 | 1587 | prefer |
| DeltaKronecker-all | 0.933 | 0.875 | 32 | 5932 | prefer |
| ermaozi | 0.802 | 0.8 | 40 | 406 | prefer |
| mheidari-all | 0.797 | 0.727 | 44 | 15952 | prefer |
| Surfboard-tg-mixed | 0.696 | 0.618 | 136 | 7516 | observe |
| ermaozi-get_subscribe | 0.328 | 1.0 | 2 | 422 | observe |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 163 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 7980 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9067 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6065 | observe |
| barry-far-vless | 0.255 | None | 0 | 6287 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 21 |
| cn-block | ClientOSError | - | 16 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 8 |
| geo | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
