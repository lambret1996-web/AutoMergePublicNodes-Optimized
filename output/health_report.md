# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 18:28:38 |
| 运行耗时 | 636.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83355 |
| 去重后节点 | 22917 |
| TCP 可达 | 3000 |
| 真实可用 | 472 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22917 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 38.3 |
| probe | 283.8 |
| real_test | 220.1 |
| generate | 86.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50587 |
| vmess | 12643 |
| shadowsocks | 9663 |
| trojan | 8052 |
| hysteria2 | 1595 |
| http | 614 |
| shadowsocksr | 128 |
| socks | 54 |
| hysteria | 8 |
| tuic | 8 |
| anytls | 3 |

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
| 80.91 | vless | 235.1 | 513.2 | 22.34 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 172.233.139.46 |
| 80.78 | vless | 240.6 | 608.0 | 22.21 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 172.235.43.210 |
| 80.64 | shadowsocks | 201.9 | 484.4 | 23.1 | 0.0 | 10.0 | 13.7 | 18.34 | Au1rxx-base64 | 108.181.0.177 |
| 76.82 | vless | 211.4 | 468.9 | 22.88 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 104.21.70.21 |
| 76.42 | vless | 299.3 | 782.2 | 20.85 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 15.204.97.214 |
| 76.34 | vless | 238.1 | 559.5 | 22.27 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 172.64.229.2 |
| 75.94 | shadowsocks | 235.9 | 555.2 | 22.32 | 0.0 | 10.0 | 13.7 | 13.92 | mheidari-all | 149.22.95.183 |
| 75.67 | shadowsocks | 226.1 | 574.3 | 22.55 | 0.0 | 10.0 | 13.7 | 13.92 | mheidari-all | 108.181.118.10 |
| 75.44 | vless | 201.4 | 458.3 | 23.12 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 104.18.34.14 |
| 75.34 | hysteria2 | 341.5 | 709.1 | 19.87 | 0.0 | 10.0 | 13.12 | 18.34 | Au1rxx-base64 | 159.223.157.129 |
| 75.14 | vless | 290.0 | 399.8 | 21.06 | 0.01 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 172.64.158.146 |
| 74.62 | vless | 268.8 | 480.9 | 21.55 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 172.64.42.85 |
| 74.59 | vless | 227.0 | 496.4 | 22.52 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 172.64.32.108 |
| 74.41 | vless | 299.9 | 783.7 | 20.84 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 15.204.97.195 |
| 73.83 | shadowsocks | 240.5 | 570.4 | 22.21 | 0.0 | 10.0 | 13.7 | 13.92 | mheidari-all | 173.244.56.9 |
| 73.19 | vless | 568.5 | 1540.9 | 14.62 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 51.81.203.63 |
| 72.84 | shadowsocks | 332.8 | 778.7 | 20.07 | 0.0 | 10.0 | 13.7 | 15.84 | Surfboard-tg-mixed | 156.146.38.167 |
| 72.26 | shadowsocks | 279.4 | 610.1 | 21.31 | 0.0 | 10.0 | 13.7 | 13.92 | mheidari-all | 156.146.38.170 |
| 72.26 | trojan | 360.4 | 823.3 | 19.44 | 0.0 | 10.0 | 12.69 | 18.34 | Au1rxx-base64 | 64.94.95.114 |
| 72.11 | vless | 381.8 | 756.1 | 18.94 | 0.0 | 10.0 | 10.23 | 18.34 | Au1rxx-base64 | 216.152.147.28 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | 0.872 | 47 | 15867 | prefer |
| Au1rxx-base64 | 0.922 | 0.86 | 315 | 1604 | prefer |
| DeltaKronecker-all | 0.682 | 0.604 | 169 | 5970 | observe |
| Surfboard-tg-mixed | 0.636 | 0.557 | 88 | 7345 | observe |
| ermaozi | 0.338 | 0.316 | 19 | 393 | observe |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7800 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8543 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5912 | observe |
| barry-far-vless | 0.255 | None | 0 | 6127 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1604 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 52 |
| 204 | TimeoutError | - | 37 |
| speed | ClientOSError | - | 21 |
| 204 | ProxyError | - | 18 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 11 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 4 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47628: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
