# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 00:46:47 |
| 运行耗时 | 1323.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90248 |
| 去重后节点 | 25751 |
| TCP 可达 | 3000 |
| 真实可用 | 638 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25751 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 41.8 |
| probe | 464.2 |
| real_test | 722.8 |
| generate | 86.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55857 |
| vmess | 13132 |
| shadowsocks | 10245 |
| trojan | 8351 |
| hysteria2 | 1835 |
| http | 603 |
| shadowsocksr | 124 |
| socks | 55 |
| anytls | 22 |
| hysteria | 14 |
| tuic | 10 |

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
| 84.02 | hysteria2 | 269.3 | 665.5 | 21.54 | 0.0 | 10.0 | 13.64 | 19.94 | Au1rxx-base64 | 159.223.157.129 |
| 82.49 | vless | 257.6 | 641.5 | 21.82 | 0.0 | 8.96 | 11.77 | 19.94 | Au1rxx-base64 | 198.251.78.29 |
| 82.06 | vless | 273.0 | 706.3 | 21.46 | 0.0 | 8.89 | 11.77 | 19.94 | Au1rxx-base64 | 79.141.172.154 |
| 80.94 | vless | 326.6 | 870.4 | 20.22 | 0.0 | 9.01 | 11.77 | 19.94 | Au1rxx-base64 | 216.152.147.28 |
| 80.86 | vless | 289.1 | 687.3 | 21.09 | 0.0 | 9.0 | 11.77 | 19.94 | Au1rxx-base64 | 167.17.69.171 |
| 80.48 | vless | 293.7 | 701.6 | 20.98 | 0.0 | 8.93 | 11.77 | 19.94 | Au1rxx-base64 | 137.184.218.169 |
| 79.92 | vless | 321.3 | 744.8 | 20.34 | 0.0 | 8.87 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.89 |
| 79.89 | vless | 315.5 | 647.8 | 20.48 | 0.0 | 8.93 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.184 |
| 79.86 | shadowsocks | 290.5 | 731.1 | 21.05 | 0.0 | 9.05 | 13.82 | 19.94 | Au1rxx-base64 | 156.146.38.167 |
| 79.48 | vless | 378.1 | 950.5 | 19.03 | 0.0 | 8.93 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.168 |
| 79.48 | vless | 389.2 | 987.3 | 18.77 | 0.0 | 9.0 | 11.77 | 19.94 | Au1rxx-base64 | 185.95.231.156 |
| 79.46 | vless | 363.6 | 867.6 | 19.36 | 0.0 | 9.19 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.224 |
| 79.32 | vless | 343.2 | 823.0 | 19.83 | 0.0 | 9.13 | 11.77 | 19.94 | Au1rxx-base64 | 66.70.179.198 |
| 79.25 | vless | 372.6 | 896.9 | 19.15 | 0.0 | 9.05 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.225 |
| 79.13 | hysteria2 | 255.7 | 513.4 | 21.86 | 0.0 | 8.84 | 13.64 | 19.94 | Au1rxx-base64 | 107.175.219.48 |
| 78.96 | vless | 282.6 | 706.1 | 21.24 | 0.0 | 8.51 | 11.77 | 19.94 | Au1rxx-base64 | lizca2.footballfantasyforum.com |
| 78.58 | shadowsocks | 291.7 | 727.6 | 21.02 | 0.0 | 8.98 | 13.82 | 19.94 | Au1rxx-base64 | 156.146.38.170 |
| 78.52 | vless | 319.5 | 772.0 | 20.38 | 0.0 | 9.0 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.182 |
| 78.41 | vless | 283.8 | 713.9 | 21.21 | 0.0 | 8.99 | 11.77 | 19.94 | Au1rxx-base64 | 47.253.226.114 |
| 78.09 | vless | 443.6 | 1031.3 | 17.51 | 0.0 | 9.03 | 11.77 | 19.94 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.921 | 0.856 | 354 | 1668 | prefer |
| Surfboard-tg-mixed | 0.753 | 0.676 | 102 | 7572 | prefer |
| ermaozi | 0.61 | 0.6 | 35 | 393 | observe |
| DeltaKronecker-all | 0.542 | 0.461 | 154 | 5972 | observe |
| mheidari-all | 0.324 | 0.243 | 704 | 21472 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 135 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 8068 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8761 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6105 | observe |
| barry-far-vless | 0.255 | None | 0 | 6322 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4099 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 273 |
| geo | ClientOSError | - | 106 |
| speed | TimeoutError | - | 105 |
| speed | ClientOSError | - | 79 |
| cn-block | ClientOSError | - | 75 |
| 204 | ProxyError | - | 30 |
| cn-block | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 14 |
| 204 | ProxyConnectionError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
