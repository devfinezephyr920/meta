# GitHub 上的 Clash Pro 仓库

一句话：两个在搜索结果里靠前的 Clash Pro 仓库，一个是复刻仓且没有发布文件，一个发布的安装包文件名与 Clash Meta for Android 的命名方式一致但带 alpha、debug 字样。都无法与原作者核对。

## Sjj1024/ClashPro（2026-09-15）

| 项目 | 数据 |
| --- | --- |
| 是否复刻 | 是 |
| 创建 / 最近提交 | 2025-02-27 / 2025-02-28 |
| 许可证 | GPL-3.0 |
| 发布文件 | 无 |
| 仓库描述 | 「A modern GUI client based on Tauri, designed to run in Windows, macOS and Linux for tailored proxy experience」 |
| 主页字段 | www.clashverge.dev（文本，不链接） |

描述和主页字段与 clash-verge-rev/clash-verge-rev 完全相同，说明是从那边复刻过来的；创建后第二天起没有再提交，也没有发布任何安装包。

需要这个软件的，直接去原仓库：https://github.com/clash-verge-rev/clash-verge-rev/releases

## xuefei666/Clash-Pro（2026-09-15）

| 项目 | 数据 |
| --- | --- |
| 是否复刻 | 否 |
| 创建 / 最近提交 | 2026-01-11 / 2026-08-14 |
| 许可证 | 未声明 |
| 最近发布 | v2.11.22（2026-01-12）、v2.11.21（2026-01-11） |
| 发布文件 | `cmfa-2.11.22-alpha-arm64-v8a-debug.apk` 等 5 个；v2.11.21 为 `-alpha-…-release.apk` |
| 仓库描述 | 自称「内置多源公共订阅获取能力」「自动拉取订阅」 |

几点可以直接从文件名看出的事实：

- 文件名前缀 `cmfa-` 与 MetaCubeX/ClashMetaForAndroid 的发布文件命名方式一致，但这个仓库不属于 MetaCubeX。
- v2.11.22 的文件带 `debug` 字样，是调试构建，不是正式发布构建。
- 仓库没有声明许可证。

MetaCubeX 官方的 Clash Meta for Android 同期版本号是 v2.11.33（2026-08-16），发布页：https://github.com/MetaCubeX/ClashMetaForAndroid/releases

内置公共订阅的问题见 [内置公共订阅的风险](public-subscription.md)。

---

数据来源：GitHub API，2026-09-15。返回 [目录](../README.md)
