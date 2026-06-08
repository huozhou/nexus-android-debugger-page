# Nexus：Android 调试器

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

在 VS Code 中直接调试 Android **C/C++ 原生代码** —— 轻量、快速、稳定。

> 支持基于 CMake 的原生项目。

**语言：** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · 简体中文 · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Русский](README.ru.md) · [Português](README.pt.md)

[**从市场安装**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**上报问题**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**官网**](https://huozhou.github.io/nexus-android-debugger-page/)

![Nexus VS Code 扩展演示](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## 为什么选择 Nexus

如果你在 Android Studio 中调试原生代码，下面这些场景你大概不陌生：

- 项目一大，IDE 就**卡顿迟缓**，光是开着都很吃资源。
- **断点命中慢**，单步执行也拖沓。
- 调试会话**频繁掉线**，只能重新来过。

Nexus 把原生调试搬进了 VS Code —— 它**轻量且响应迅速**，拥有**出色的 C/C++ 支持**，让你沿用现有的 CMake / 增量构建工作流，而不必等待 IDE 整体重建。你将在 Android 原生代码上获得 VS Code 的完整调试体验（断点、变量、调用栈、监视、调试控制台）。

## 它能做什么

- **几次点击即可附加** —— 只需配置一次，选择进程，就能在设备上开始调试。
- **不打扰你的工作** —— 与设备之间保持轻量、灵敏、稳定的连接。
- **本地化界面** —— 用你自己的语言使用扩展（见 [语言](#语言)）。

## 环境要求

- 一台已启用 USB 调试、运行可调试构建的 Android 设备或模拟器
- 已安装 Android NDK
- 一个基于 CMake 的原生项目

## 如何使用

从活动栏打开 **Nexus** 视图，选择设备和目标进程，然后附加。就这么简单。

Nexus 视图提供三个操作：

- **Attach（附加）** —— 开始调试所选进程。
- **Refresh（刷新）** —— 重新扫描已连接的设备和进程。
- **Settings（设置，齿轮图标）** —— 打开下方的配置面板。

## 设置

点击 Nexus 视图中的齿轮图标打开设置面板。你只需提供：

- **NDK 路径** —— Android NDK 的安装目录。
- **调试选项** —— 本次会话的目标应用/进程以及调试类型。

![Nexus 设置面板](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## 语言

扩展界面支持以下语言：

- English（英语）
- 简体中文
- 繁體中文
- 日本語（日语）
- 한국어（韩语）
- Deutsch（德语）
- Français（法语）
- Español（西班牙语）
- Русский（俄语）
- Português（葡萄牙语）

界面会自动跟随你的 VS Code 显示语言，未翻译的文本会回退为英文。

## 反馈与支持

- **报告 bug 或提出功能建议：** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## 许可证

见 [LICENSE.txt](LICENSE.txt)。
