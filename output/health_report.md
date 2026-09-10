# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 12:34:45 |
| 运行耗时 | 747.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91588 |
| 去重后节点 | 24229 |
| TCP 可达 | 3000 |
| 真实可用 | 473 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24229 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 41.7 |
| probe | 269.4 |
| real_test | 352.4 |
| generate | 76.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55745 |
| vmess | 13146 |
| shadowsocks | 11036 |
| trojan | 8860 |
| hysteria2 | 1904 |
| http | 685 |
| shadowsocksr | 124 |
| socks | 56 |
| hysteria | 15 |
| tuic | 10 |
| anytls | 7 |

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
| 81.22 | shadowsocks | 213.4 | 536.0 | 22.84 | 0.0 | 10.0 | 13.82 | 19.06 | Au1rxx-base64 | 108.181.118.10 |
| 81.14 | vless | 269.2 | 683.7 | 21.55 | 0.0 | 10.0 | 10.53 | 19.06 | Au1rxx-base64 | 172.235.43.210 |
| 80.67 | shadowsocks | 232.1 | 556.8 | 22.41 | 0.0 | 9.38 | 13.82 | 19.06 | Au1rxx-base64 | 173.244.56.9 |
| 80.45 | vless | 272.8 | 699.0 | 21.46 | 0.0 | 9.4 | 10.53 | 19.06 | Au1rxx-base64 | 172.235.38.85 |
| 80.31 | trojan | 209.0 | 534.1 | 22.94 | 0.0 | 7.54 | 13.77 | 19.06 | Au1rxx-base64 | us01.duotg.top |
| 79.81 | shadowsocks | 247.0 | 629.6 | 22.06 | 0.0 | 9.37 | 13.82 | 19.06 | Au1rxx-base64 | 108.181.0.177 |
| 79.51 | vless | 312.8 | 824.1 | 20.54 | 0.0 | 9.38 | 10.53 | 19.06 | Au1rxx-base64 | 15.204.97.216 |
| 79.02 | vless | 247.4 | 592.2 | 22.05 | 0.0 | 9.38 | 10.53 | 19.06 | Au1rxx-base64 | 31.58.50.200 |
| 78.57 | shadowsocks | 322.7 | 820.8 | 20.31 | 0.0 | 9.38 | 13.82 | 19.06 | Au1rxx-base64 | 173.244.56.6 |
| 77.26 | shadowsocks | 294.0 | 663.3 | 20.97 | 0.0 | 10.0 | 13.82 | 19.06 | Au1rxx-base64 | 156.146.38.169 |
| 76.36 | shadowsocks | 296.3 | 662.2 | 20.92 | 0.0 | 9.25 | 13.82 | 19.06 | Au1rxx-base64 | 156.146.38.170 |
| 76.33 | shadowsocks | 288.3 | 651.9 | 21.1 | 0.0 | 10.0 | 13.82 | 19.06 | Au1rxx-base64 | 156.146.38.168 |
| 75.85 | http | 230.6 | 603.6 | 22.44 | 0.0 | 10.0 | 11.05 | 15.36 | ermaozi | 138.199.35.216 |
| 75.57 | http | 242.8 | 631.5 | 22.16 | 0.0 | 10.0 | 11.05 | 15.36 | ermaozi | 138.199.35.210 |
| 75.56 | http | 243.3 | 635.5 | 22.15 | 0.0 | 10.0 | 11.05 | 15.36 | ermaozi | 138.199.35.198 |
| 75.48 | trojan | 348.6 | 964.6 | 19.71 | 0.0 | 10.0 | 13.77 | 14.5 | mheidari-all | 34.94.125.227 |
| 74.58 | http | 242.1 | 634.7 | 22.17 | 0.0 | 10.0 | 11.05 | 15.36 | ermaozi | 138.199.35.219 |
| 74.52 | http | 244.9 | 639.0 | 22.11 | 0.0 | 10.0 | 11.05 | 15.36 | ermaozi | 138.199.35.218 |
| 74.34 | shadowsocks | 371.5 | 290.3 | 19.18 | 4.11 | 9.38 | 13.82 | 19.06 | Au1rxx-base64 | 84.247.155.196 |
| 74.31 | vless | 564.2 | 1565.0 | 14.72 | 0.0 | 10.0 | 10.53 | 19.06 | Au1rxx-base64 | 51.81.203.63 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.948 | 0.886 | 271 | 1629 | prefer |
| mheidari-all | 0.904 | 0.833 | 72 | 19290 | prefer |
| Surfboard-tg-mixed | 0.821 | 0.744 | 168 | 7439 | prefer |
| ermaozi | 0.763 | 0.755 | 53 | 449 | prefer |
| DeltaKronecker-all | 0.425 | 0.4 | 15 | 5853 | observe |
| ermaozi-get_subscribe | 0.274 | 1.0 | 1 | 469 | observe |
| tg-oneclickvpnkeys | 0.264 | 1.0 | 1 | 214 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7808 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9102 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6025 | observe |
| barry-far-vless | 0.255 | None | 0 | 6215 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4358 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3508 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 23 |
| 204 | ProxyError | - | 19 |
| cn-block | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 13 |
| speed | ClientOSError | - | 9 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 6 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
