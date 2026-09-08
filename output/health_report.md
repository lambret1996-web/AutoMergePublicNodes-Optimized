# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 00:33:24 |
| 运行耗时 | 331.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91664 |
| 去重后节点 | 25195 |
| TCP 可达 | 3000 |
| 真实可用 | 736 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25195 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 42.7 |
| probe | 86.3 |
| real_test | 158.7 |
| generate | 35.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57133 |
| vmess | 12354 |
| shadowsocks | 10698 |
| trojan | 8931 |
| hysteria2 | 1819 |
| http | 503 |
| shadowsocksr | 118 |
| socks | 62 |
| hysteria | 17 |
| anytls | 16 |
| tuic | 13 |

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
| 82.78 | hysteria2 | 270.9 | 678.1 | 21.51 | 0.0 | 10.0 | 12.39 | 19.98 | Au1rxx-base64 | 159.223.157.129 |
| 81.65 | vless | 303.7 | 723.6 | 20.75 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 66.70.179.198 |
| 81.37 | vless | 297.2 | 670.6 | 20.9 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.223 |
| 80.37 | vless | 312.0 | 641.6 | 20.56 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.224 |
| 80.11 | vless | 370.7 | 881.5 | 19.2 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.74 |
| 80.09 | shadowsocks | 306.6 | 805.8 | 20.68 | 0.0 | 10.0 | 13.93 | 19.98 | Au1rxx-base64 | 15.204.246.108 |
| 79.98 | vless | 285.0 | 678.4 | 21.18 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.90 |
| 79.82 | vless | 380.6 | 970.1 | 18.97 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 185.95.231.156 |
| 79.7 | hysteria2 | 268.4 | 569.6 | 21.56 | 0.0 | 10.0 | 12.39 | 19.98 | Au1rxx-base64 | 66.94.121.46 |
| 79.63 | vless | 298.0 | 684.3 | 20.88 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 195.123.235.177 |
| 79.55 | vless | 317.0 | 780.2 | 20.44 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.235 |
| 79.24 | vless | 381.3 | 915.6 | 18.95 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.104 |
| 79.05 | vless | 366.6 | 903.0 | 19.29 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 137.184.218.169 |
| 78.96 | vless | 326.8 | 738.9 | 20.21 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.163 |
| 78.9 | vless | 344.9 | 739.7 | 19.79 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.212 |
| 78.87 | vless | 257.9 | 614.7 | 21.81 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 130.94.115.231 |
| 78.77 | vless | 322.2 | 686.8 | 20.32 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.232 |
| 78.73 | vless | 422.7 | 977.8 | 17.99 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.89 |
| 78.56 | vless | 323.1 | 739.5 | 20.3 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 169.40.42.35 |
| 78.55 | vless | 293.1 | 720.4 | 20.99 | 0.0 | 10.0 | 11.18 | 19.98 | Au1rxx-base64 | 184.107.106.68 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.931 | 377 | 1805 | prefer |
| ermaozi | 0.993 | 1.0 | 38 | 450 | prefer |
| ermaozi-get_subscribe | 0.86 | 0.944 | 18 | 465 | prefer |
| Surfboard-tg-mixed | 0.833 | 0.755 | 245 | 7423 | prefer |
| mheidari-all | 0.626 | 0.547 | 181 | 16494 | observe |
| xiaoji235-airport-v2ray-all | 0.513 | 0.429 | 28 | 5750 | observe |
| DeltaKronecker-all | 0.483 | 0.4 | 65 | 6417 | observe |
| tg-oneclickvpnkeys | 0.457 | 0.857 | 7 | 196 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7917 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8733 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6226 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 59 |
| speed | TimeoutError | - | 43 |
| geo | ClientOSError | - | 39 |
| cn-block | ClientOSError | - | 24 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 11 |
| 204 | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44716: bind: address already in use | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
