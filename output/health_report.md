# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 05:16:29 |
| 运行耗时 | 937.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99184 |
| 去重后节点 | 27677 |
| TCP 可达 | 3000 |
| 真实可用 | 463 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27677 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.5 |
| tcp | 47.1 |
| probe | 356.3 |
| real_test | 430.9 |
| generate | 93.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58079 |
| vmess | 15806 |
| shadowsocks | 11977 |
| trojan | 10754 |
| hysteria2 | 1583 |
| http | 676 |
| shadowsocksr | 167 |
| socks | 88 |
| anytls | 29 |
| hysteria | 16 |
| tuic | 9 |

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
| 82.99 | vless | 208.4 | 569.1 | 22.95 | 0.0 | 10.0 | 10.88 | 19.16 | Au1rxx-base64 | 137.175.82.40 |
| 82.67 | vless | 222.5 | 604.5 | 22.63 | 0.0 | 10.0 | 10.88 | 19.16 | Au1rxx-base64 | 47.251.108.158 |
| 82.54 | vless | 227.9 | 557.4 | 22.5 | 0.0 | 10.0 | 10.88 | 19.16 | Au1rxx-base64 | 15.204.97.216 |
| 81.87 | hysteria2 | 229.0 | 229.3 | 22.48 | 6.4 | 9.26 | 13.57 | 19.16 | Au1rxx-base64 | vp3.yysyy.online |
| 81.34 | hysteria2 | 226.9 | 241.9 | 22.53 | 5.93 | 9.92 | 13.57 | 19.16 | Au1rxx-base64 | 45.32.10.7 |
| 81.28 | vless | 282.4 | 718.6 | 21.24 | 0.0 | 10.0 | 10.88 | 19.16 | Au1rxx-base64 | 15.204.97.197 |
| 80.48 | shadowsocks | 224.4 | 564.2 | 22.58 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 108.181.118.10 |
| 80.43 | hysteria2 | 238.7 | 255.9 | 22.25 | 5.4 | 9.94 | 13.57 | 19.16 | Au1rxx-base64 | 158.101.148.79 |
| 80.38 | shadowsocks | 250.4 | 606.5 | 21.98 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 149.22.95.183 |
| 79.43 | shadowsocks | 269.7 | 690.7 | 21.53 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 108.181.0.177 |
| 79.11 | shadowsocks | 281.3 | 664.4 | 21.27 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 173.244.56.9 |
| 78.5 | vless | 290.8 | 657.1 | 21.05 | 0.0 | 10.0 | 10.88 | 18.96 | mheidari-all | 216.227.161.95 |
| 77.33 | shadowsocks | 270.7 | 273.5 | 21.51 | 4.74 | 9.94 | 13.24 | 19.16 | Au1rxx-base64 | 149.22.87.241 |
| 77.01 | hysteria2 | 391.7 | 604.4 | 18.71 | 0.0 | 10.0 | 13.57 | 19.16 | Au1rxx-base64 | 66.94.121.46 |
| 76.99 | shadowsocks | 286.7 | 646.2 | 21.14 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 156.146.38.168 |
| 76.7 | shadowsocks | 289.6 | 640.7 | 21.07 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 156.146.38.167 |
| 76.7 | vless | 394.1 | 993.0 | 18.66 | 0.0 | 10.0 | 10.88 | 19.16 | Au1rxx-base64 | 154.12.38.202 |
| 76.56 | hysteria2 | 390.3 | 892.3 | 18.74 | 0.0 | 10.0 | 13.57 | 19.16 | Au1rxx-base64 | 129.213.91.185 |
| 76.1 | vless | 247.0 | 624.8 | 22.06 | 0.0 | 10.0 | 10.88 | 19.16 | Au1rxx-base64 | 104.17.98.5 |
| 76.07 | shadowsocks | 292.5 | 654.3 | 21.01 | 0.0 | 10.0 | 13.24 | 19.16 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | 0.914 | 327 | 1781 | prefer |
| Surfboard-tg-mixed | 0.866 | 0.8 | 40 | 7193 | prefer |
| ermaozi-get_subscribe | 0.399 | 0.367 | 30 | 592 | observe |
| mheidari-all | 0.348 | 0.267 | 404 | 23407 | observe |
| ermaozi | 0.344 | 0.306 | 36 | 715 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7663 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9553 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5725 | observe |
| barry-far-vless | 0.255 | None | 0 | 5963 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1781 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 162 |
| speed | TimeoutError | - | 56 |
| 204 | ProxyError | - | 47 |
| geo | ClientOSError | - | 41 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyConnectionError | - | 20 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
