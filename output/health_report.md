# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 06:35:50 |
| 运行耗时 | 679.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84629 |
| 去重后节点 | 22797 |
| TCP 可达 | 3000 |
| 真实可用 | 502 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22797 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 37.3 |
| probe | 231.6 |
| real_test | 328.1 |
| generate | 74.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51866 |
| vmess | 12762 |
| shadowsocks | 9758 |
| trojan | 7860 |
| hysteria2 | 1531 |
| http | 639 |
| shadowsocksr | 131 |
| socks | 53 |
| tuic | 15 |
| hysteria | 11 |
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
| 80.42 | shadowsocks | 215.8 | 579.0 | 22.78 | 0.0 | 10.0 | 14.4 | 19.24 | Au1rxx-base64 | 198.98.53.130 |
| 79.92 | vless | 231.5 | 662.6 | 22.42 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 79.141.172.154 |
| 79.87 | vless | 233.7 | 621.3 | 22.37 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 195.123.235.177 |
| 79.64 | shadowsocks | 314.4 | 828.7 | 20.5 | 0.0 | 10.0 | 14.4 | 19.24 | Au1rxx-base64 | 51.222.200.165 |
| 79.55 | vless | 247.3 | 653.8 | 22.05 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.225 |
| 79.18 | vless | 263.2 | 740.8 | 21.68 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 47.253.226.114 |
| 79.16 | vless | 264.3 | 648.4 | 21.66 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.90 |
| 79.03 | vless | 270.0 | 718.1 | 21.53 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 167.17.69.171 |
| 78.91 | vless | 275.0 | 720.9 | 21.41 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.212 |
| 78.81 | shadowsocks | 350.1 | 1009.2 | 19.67 | 0.0 | 10.0 | 14.4 | 19.24 | Au1rxx-base64 | 15.204.247.206 |
| 78.73 | vless | 283.1 | 696.0 | 21.23 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.235 |
| 78.64 | vless | 286.9 | 648.0 | 21.14 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.184 |
| 78.51 | vless | 292.2 | 672.2 | 21.01 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.104 |
| 78.27 | vless | 302.8 | 811.2 | 20.77 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.173 |
| 78.12 | vless | 309.1 | 791.7 | 20.62 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 66.70.179.198 |
| 78.02 | vless | 258.5 | 630.2 | 21.79 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.89 |
| 77.6 | vless | 263.1 | 690.3 | 21.69 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.223 |
| 77.58 | vless | 265.0 | 694.0 | 21.64 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.133 |
| 77.34 | vless | 342.7 | 806.0 | 19.84 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.179 |
| 76.99 | vless | 275.3 | 673.9 | 21.4 | 0.0 | 10.0 | 8.26 | 19.24 | Au1rxx-base64 | 169.40.42.231 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | 0.87 | 299 | 1681 | prefer |
| Surfboard-tg-mixed | 0.768 | 0.69 | 168 | 7444 | prefer |
| ermaozi | 0.696 | 0.686 | 51 | 417 | observe |
| mheidari-all | 0.633 | 0.554 | 101 | 15963 | observe |
| ermaozi-get_subscribe | 0.51 | 0.6 | 15 | 444 | observe |
| DeltaKronecker-all | 0.378 | 0.293 | 82 | 5892 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Epodonios-all | 0.255 | None | 0 | 7945 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8951 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6094 | observe |
| barry-far-vless | 0.255 | None | 0 | 6325 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1681 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 61 |
| geo | ClientOSError | - | 31 |
| 204 | ProxyError | - | 28 |
| speed | TimeoutError | - | 24 |
| speed | ClientOSError | - | 23 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
