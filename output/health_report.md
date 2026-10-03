# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-03 04:31:01 |
| 运行耗时 | 874.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98934 |
| 去重后节点 | 27172 |
| TCP 可达 | 3000 |
| 真实可用 | 471 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27172 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.2 |
| tcp | 47.5 |
| probe | 293.5 |
| real_test | 446.8 |
| generate | 77.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60527 |
| vmess | 15583 |
| shadowsocks | 11422 |
| trojan | 8973 |
| hysteria2 | 1616 |
| http | 522 |
| shadowsocksr | 164 |
| socks | 68 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 12 |

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
| 81.72 | vless | 260.0 | 652.4 | 21.76 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 198.251.78.29 |
| 80.76 | vless | 301.2 | 690.9 | 20.8 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 169.40.42.182 |
| 80.73 | vless | 293.5 | 699.3 | 20.98 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 159.89.87.21 |
| 80.69 | vless | 288.8 | 699.2 | 21.09 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 79.83 | hysteria2 | 263.8 | 572.7 | 21.67 | 0.0 | 10.0 | 12.95 | 18.36 | Au1rxx-base64 | 192.255.128.123 |
| 79.36 | hysteria2 | 293.3 | 736.9 | 20.99 | 0.0 | 10.0 | 12.95 | 16.52 | mheidari-all | 159.223.157.129 |
| 79.08 | vless | 295.5 | 678.4 | 20.94 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 169.40.42.16 |
| 79.01 | vless | 273.9 | 644.5 | 21.44 | 0.0 | 10.0 | 11.6 | 16.52 | mheidari-all | 216.227.161.95 |
| 78.62 | shadowsocks | 251.4 | 623.8 | 21.96 | 0.0 | 10.0 | 12.3 | 18.36 | Au1rxx-base64 | 156.146.38.170 |
| 78.57 | shadowsocks | 253.4 | 623.3 | 21.91 | 0.0 | 10.0 | 12.3 | 18.36 | Au1rxx-base64 | 156.146.38.169 |
| 78.31 | vless | 386.5 | 1005.6 | 18.83 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 169.40.42.179 |
| 78.3 | vless | 361.2 | 919.1 | 19.42 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 137.184.218.169 |
| 78.18 | vless | 384.4 | 1004.4 | 18.88 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 185.95.231.156 |
| 77.95 | vless | 319.9 | 732.5 | 20.37 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 169.40.42.235 |
| 77.78 | shadowsocks | 287.5 | 740.2 | 21.12 | 0.0 | 10.0 | 12.3 | 18.36 | Au1rxx-base64 | 37.19.198.243 |
| 77.12 | vless | 338.6 | 782.8 | 19.94 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 167.17.69.171 |
| 76.96 | vless | 315.1 | 662.9 | 20.48 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 169.40.42.184 |
| 76.83 | vless | 302.9 | 748.3 | 20.77 | 0.0 | 10.0 | 11.6 | 18.36 | Au1rxx-base64 | 169.40.42.90 |
| 76.64 | shadowsocks | 315.1 | 861.3 | 20.48 | 0.0 | 10.0 | 12.3 | 18.36 | Au1rxx-base64 | 185.156.47.97 |
| 76.56 | vless | 268.5 | 621.8 | 21.56 | 0.0 | 9.92 | 11.6 | 18.36 | Au1rxx-base64 | us51.mech-pro.online |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | 0.923 | 273 | 1751 | prefer |
| ermaozi | 0.706 | 0.696 | 23 | 645 | prefer |
| Surfboard-tg-mixed | 0.646 | 0.568 | 81 | 7256 | observe |
| mheidari-all | 0.431 | 0.351 | 439 | 23323 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.289 | 0.667 | 3 | 516 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7743 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9351 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5980 | observe |
| barry-far-vless | 0.255 | None | 0 | 6214 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4357 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 154 |
| speed | TimeoutError | - | 87 |
| geo | ClientOSError | - | 37 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 8 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
