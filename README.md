# HomePod 音频桥（Windows）

中文界面的 Windows 音频桥，可通过局域网把电脑声音播放到 HomePod 等 AirPlay 2 设备。

## 下载与安装

**[下载最终版 Windows x64 压缩包](https://github.com/zhr110726-cpu/HomePod-Audio-Bridge-Windows/releases/download/v1.0.0/HomePod-Audio-Bridge-Windows-x64-v1.0.0.zip)**（约 72 MB）

1. 完整解压 ZIP。
2. 双击其中的“HomePod 音频桥.exe”；请保留旁边的 `core` 文件夹和其他文件。
3. 在同一局域网中选择设备并点击连接播放。首次配对时按音箱提示操作。

无需另行安装 .NET、Rust 或 Visual Studio。关闭主窗口会收起到托盘；右键托盘图标可完全退出。快捷控制面板可以从主窗口或托盘打开。音量和额外增强请从低档逐步调整，避免突然过响。

**请下载上面的 Release 附件**。GitHub 自动生成的“Source code (zip/tar.gz)”不是可运行软件；本仓库的程序与音频核心源码也包含在 Release 附件内。

## 功能

- 自动发现局域网 AirPlay 2 设备，中文界面与系统明暗主题。
- 托盘快捷控制、设备切换、音量、静音、响应速度和额外音频增强。
- 连接后可自动静音电脑，停止或退出时恢复原状态。

## 开源与声明

音频核心基于 [OpenAir](https://github.com/Antoinenz/OpenAir)，遵循 GPL-3.0-only。发布包包含许可证、修改后的音频核心源码及中文界面源码。本项目不是 Apple 官方软件。

原始发布包不含个人设置、配对信息或运行日志。

SHA-256：`71c9cf7c7fe581d1e2781c72ab443e135b7f51377b9e27c9f85ee4815fd83f93`

作者抖音 ID：难评。
