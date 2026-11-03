# 第三方组件与许可证

本项目自身代码以 **GPL-3.0** 发布（见 `LICENSE`）。以下组件由第三方提供，分别适用其自身许可证；本项目不改变、也不能改变这些条款。

## 源码级依赖

| 组件 | 许可证 | 说明 |
|---|---|---|
| ShadowHook（ByteDance） | MIT | `sensor-native/linkLibs/`、`sensorprobe/linkLibs/` 中的 `libshadowhook.so` 与 `shadowhook.h`，用于 PLT/指令级 Hook |
| AndroidX / Jetpack Compose | Apache-2.0 | Android UI 与生命周期基础库 |
| miuix (compose-miuix-ui) | Apache-2.0 | Compose 组件库 |
| Kotlin / Kotlin Coroutines | Apache-2.0 | 语言与协程运行时 |
| Koin | Apache-2.0 | 依赖注入 |
| OkHttp / Room 等 | Apache-2.0 | 网络与本地数据库 |

## 专有 SDK（不属于 GPL）

| 组件 | 许可证 | 说明 |
|---|---|---|
| 高德地图 SDK（AMap） | AMap Software License 1.0 | 地图、定位、搜索、离线地图；受高德开放平台条款约束（Key 绑定、配额、禁止逆向等） |
| 百度地图 SDK | 百度 LBS 开放平台协议 | 可选地图引擎；受百度条款约束 |

使用这些 SDK 时需遵守其各自的申请、Key 绑定、配额与数据使用规则；本项目不附带任何地图 Key。

## 再分发注意

- 分发本项目源码或 APK 时，请一并保留本文件与 `LICENSE`。
- ShadowHook 的 MIT 声明、AndroidX/miuix 的 Apache-2.0 NOTICE 不得删除。
- 高德/百度 SDK 的再分发受其商业条款限制，不能仅凭 GPL 授权转授。