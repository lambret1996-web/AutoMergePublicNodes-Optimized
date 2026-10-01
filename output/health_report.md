# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-01 05:43:54 |
| 运行耗时 | 825.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97857 |
| 去重后节点 | 27309 |
| TCP 可达 | 3000 |
| 真实可用 | 451 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27309 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.6 |
| tcp | 45.8 |
| probe | 280.7 |
| real_test | 416.8 |
| generate | 72.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59764 |
| vmess | 15332 |
| shadowsocks | 11435 |
| trojan | 9074 |
| hysteria2 | 1407 |
| http | 551 |
| shadowsocksr | 164 |
| socks | 66 |
| anytls | 40 |
| hysteria | 16 |
| tuic | 8 |

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
| 81.78 | hysteria2 | 285.6 | 788.9 | 21.17 | 0.0 | 10.0 | 14.21 | 17.4 | Au1rxx-base64 | 192.255.128.123 |
| 81.19 | vless | 195.8 | 511.7 | 23.25 | 0.0 | 10.0 | 10.54 | 17.4 | Au1rxx-base64 | 172.235.43.210 |
| 81.16 | vless | 196.8 | 511.7 | 23.22 | 0.0 | 10.0 | 10.54 | 17.4 | Au1rxx-base64 | 172.233.139.46 |
| 80.66 | trojan | 206.0 | 531.4 | 23.01 | 0.0 | 10.0 | 12.75 | 17.4 | Au1rxx-base64 | 192.236.151.43 |
| 80.26 | shadowsocks | 224.2 | 514.5 | 22.59 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 173.244.56.6 |
| 79.74 | shadowsocks | 181.7 | 485.7 | 23.57 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 104.192.225.110 |
| 79.65 | shadowsocks | 255.6 | 621.3 | 21.86 | 0.0 | 10.0 | 14.27 | 17.52 | mheidari-all | 156.146.38.168 |
| 79.53 | shadowsocks | 255.7 | 622.0 | 21.86 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 156.146.38.167 |
| 79.44 | vless | 271.3 | 675.5 | 21.5 | 0.0 | 10.0 | 10.54 | 17.4 | Au1rxx-base64 | 137.175.82.40 |
| 79.42 | shadowsocks | 260.4 | 636.6 | 21.75 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 156.146.38.169 |
| 79.33 | vless | 236.8 | 596.7 | 22.3 | 0.0 | 10.0 | 10.54 | 17.4 | Au1rxx-base64 | 195.123.240.65 |
| 78.62 | vless | 265.9 | 626.8 | 21.62 | 0.0 | 10.0 | 10.54 | 17.4 | Au1rxx-base64 | 23.95.222.127 |
| 77.89 | hysteria2 | 330.7 | 744.2 | 20.12 | 0.0 | 10.0 | 14.21 | 17.4 | Au1rxx-base64 | 159.223.157.129 |
| 77.8 | hysteria2 | 228.9 | 232.2 | 22.48 | 6.29 | 9.33 | 14.21 | 17.4 | Au1rxx-base64 | vp3.yysyy.online |
| 77.78 | shadowsocks | 309.8 | 821.2 | 20.61 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 108.181.0.177 |
| 77.76 | shadowsocks | 180.8 | 482.3 | 23.59 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 173.234.25.90 |
| 77.63 | shadowsocks | 321.3 | 805.3 | 20.34 | 0.0 | 10.0 | 14.27 | 17.52 | mheidari-all | 108.181.118.10 |
| 77.39 | shadowsocks | 218.6 | 541.9 | 22.72 | 0.0 | 10.0 | 14.27 | 17.4 | Au1rxx-base64 | 173.244.56.9 |
| 77.35 | vless | 269.4 | 584.9 | 21.54 | 0.0 | 10.0 | 10.54 | 17.4 | Au1rxx-base64 | 15.204.97.216 |
| 76.49 | vless | 290.7 | 648.0 | 21.05 | 0.0 | 10.0 | 10.54 | 17.52 | mheidari-all | 216.227.161.95 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.937 | 0.952 | 21 | 588 | prefer |
| Au1rxx-base64 | 0.875 | 0.809 | 314 | 1694 | prefer |
| Surfboard-tg-mixed | 0.507 | 0.75 | 8 | 7136 | observe |
| mheidari-all | 0.443 | 0.362 | 450 | 22835 | observe |
| ermaozi-get_subscribe | 0.428 | 0.833 | 6 | 487 | observe |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 80 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7637 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9403 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5815 | observe |
| barry-far-vless | 0.255 | None | 0 | 6001 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 144 |
| speed | ClientOSError | - | 65 |
| speed | TimeoutError | - | 57 |
| geo | ClientOSError | - | 32 |
| 204 | ProxyError | - | 26 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
