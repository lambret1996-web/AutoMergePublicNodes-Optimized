# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 12:28:25 |
| 运行耗时 | 323.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 90936 |
| 去重后节点 | 25288 |
| TCP 可达 | 3000 |
| 真实可用 | 545 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25288 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 42.3 |
| probe | 93.2 |
| real_test | 131.7 |
| generate | 47.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56742 |
| vmess | 12428 |
| shadowsocks | 10253 |
| trojan | 8970 |
| hysteria2 | 1821 |
| http | 502 |
| shadowsocksr | 128 |
| socks | 54 |
| hysteria | 16 |
| tuic | 11 |
| anytls | 11 |

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
| 84.84 | http | 204.9 | 517.5 | 23.04 | 0.0 | 10.0 | 14.8 | 20.0 | ermaozi | 138.199.35.216 |
| 83.39 | http | 267.4 | 712.9 | 21.59 | 0.0 | 10.0 | 14.8 | 20.0 | ermaozi | 138.199.35.198 |
| 82.68 | hysteria2 | 217.0 | 505.7 | 22.76 | 0.0 | 9.24 | 13.04 | 18.64 | Au1rxx-base64 | 66.94.121.46 |
| 81.9 | http | 202.2 | 514.5 | 23.1 | 0.0 | 10.0 | 14.8 | 20.0 | ermaozi | 138.199.35.219 |
| 81.89 | http | 202.4 | 503.0 | 23.09 | 0.0 | 10.0 | 14.8 | 20.0 | ermaozi | 138.199.35.196 |
| 80.67 | http | 203.5 | 519.9 | 23.07 | 0.0 | 10.0 | 14.8 | 18.8 | ermaozi-get_subscribe | 138.199.35.202 |
| 80.63 | http | 256.8 | 679.7 | 21.83 | 0.0 | 10.0 | 14.8 | 20.0 | ermaozi | 138.199.35.210 |
| 80.61 | http | 205.9 | 519.5 | 23.01 | 0.0 | 10.0 | 14.8 | 18.8 | ermaozi-get_subscribe | 138.199.35.201 |
| 79.92 | vless | 201.9 | 487.7 | 23.1 | 0.0 | 10.0 | 8.18 | 18.64 | Au1rxx-base64 | 172.235.38.85 |
| 79.48 | http | 254.7 | 674.7 | 21.88 | 0.0 | 10.0 | 14.8 | 18.8 | ermaozi-get_subscribe | 138.199.35.218 |
| 79.06 | vless | 205.8 | 518.7 | 23.01 | 0.0 | 9.23 | 8.18 | 18.64 | Au1rxx-base64 | 23.94.227.94 |
| 79.0 | vless | 241.6 | 631.4 | 22.18 | 0.0 | 10.0 | 8.18 | 18.64 | Au1rxx-base64 | 38.244.20.160 |
| 78.9 | vless | 246.3 | 609.4 | 22.08 | 0.0 | 10.0 | 8.18 | 18.64 | Au1rxx-base64 | 172.233.139.46 |
| 78.32 | shadowsocks | 210.5 | 548.9 | 22.9 | 0.0 | 9.21 | 13.83 | 18.64 | Au1rxx-base64 | 108.181.0.177 |
| 78.16 | shadowsocks | 250.8 | 533.5 | 21.97 | 0.0 | 10.0 | 13.83 | 16.36 | Surfboard-tg-mixed | 173.244.56.6 |
| 78.03 | shadowsocks | 256.5 | 541.2 | 21.84 | 0.0 | 10.0 | 13.83 | 16.36 | Surfboard-tg-mixed | 173.244.56.9 |
| 77.43 | http | 343.0 | 627.9 | 19.84 | 0.0 | 10.0 | 14.8 | 20.0 | ermaozi | 38.28.193.188 |
| 77.16 | vless | 321.4 | 844.4 | 20.34 | 0.0 | 10.0 | 8.18 | 18.64 | Au1rxx-base64 | 15.204.97.216 |
| 76.69 | trojan | 203.2 | 534.3 | 23.07 | 0.0 | 10.0 | 7.98 | 18.64 | Au1rxx-base64 | us01.duotg.top |
| 76.39 | vless | 268.1 | 579.6 | 21.57 | 0.0 | 10.0 | 8.18 | 18.64 | Au1rxx-base64 | 38.246.229.58 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | 0.912 | 330 | 1727 | prefer |
| ermaozi | 0.863 | 0.857 | 56 | 450 | prefer |
| Surfboard-tg-mixed | 0.783 | 0.706 | 170 | 7431 | prefer |
| ermaozi-get_subscribe | 0.767 | 0.833 | 18 | 470 | prefer |
| mheidari-all | 0.452 | 0.37 | 154 | 22334 | observe |
| DeltaKronecker-all | 0.4 | 0.75 | 4 | 6097 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 212 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4657 | observe |
| Epodonios-all | 0.255 | None | 0 | 7885 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8435 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6201 | observe |
| barry-far-vless | 0.255 | None | 0 | 6423 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4209 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 44 |
| geo | ClientOSError | - | 43 |
| 204 | TimeoutError | - | 33 |
| cn-block | TimeoutError | - | 27 |
| 204 | ProxyConnectionError | - | 9 |
| speed | ClientOSError | - | 9 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
