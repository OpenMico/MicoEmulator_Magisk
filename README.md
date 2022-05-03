# MicoLauncher - Magisk 版
> 一个用于在 Android 设备上模拟 MicoLauncher 以及依赖的 Magisk 模块  
> 高度实验性警告！不要尝试在带有重要数据的设备上运行，可能导致数据丢失

# 当前工作的
- 锁屏样式 (ScreenSaver)
- 米家控制 (MiSmartHome)
- 语音/视频通话 (MicoVoip)
- 整点报时 (MicoLauncher)

# 需要修复的 (TO-DO)
- 账号登录 (MicoProvision)
- 在线资源下发 (MicoLauncher)
- 语音引擎 (MicoLauncher)

# 下载
- [OpenMico/MicoEmulator_Magisk/releases](https://github.com/OpenMico/MicoEmulator_Magisk/releases)

# 使用方式
- 下载
- 修改 `system.prop` 内的 `mi.did` (可选，如果需要接入米家则修改为真实 deviceId)
- 修改设备 DPI
- 在 Magisk Manager 内安装模块
- 重新启动

# 推荐运行环境
- 至少需要 `Magisk v19.0 +`
- 基于 [MIUI](https://www.miui.com/download.html) 或 [MIUI by Xiaomi.eu](Xiaomi.eu) 的 `Android 8.0 ~ 10.0` 之间的 MIUI 系统

# 报告兼容问题
- 如果无法在你的设备上运行 (如发生闪退、崩溃)，请按照如下格式发送 Issus 给我
```
Android 版本: 8.0
运行设备: 小米 5
系统类型: MIUI EU
系统版本: MIUI 11
崩溃位置: #粗略描述即可#
崩溃时日志: #最好附上闪退、崩溃时输出的日志#
```
