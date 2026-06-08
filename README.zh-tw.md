# Nexus：Android 偵錯工具

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

直接在 VS Code 中偵錯 Android **C/C++ 原生程式碼** —— 輕量、快速、穩定。

> 支援以 CMake 為基礎的原生專案。

**語言：** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · 繁體中文 · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Русский](README.ru.md) · [Português](README.pt.md)

[**從市集安裝**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**回報問題**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**官方網站**](https://huozhou.github.io/nexus-android-debugger-page/)

![Nexus VS Code 擴充功能示範](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## 為什麼選擇 Nexus

如果你在 Android Studio 中偵錯原生程式碼，下列情況你應該不陌生：

- 專案一大，IDE 就**卡頓遲緩**，光是開著就很耗資源。
- **中斷點命中慢**，單步執行也拖泥帶水。
- 偵錯工作階段**頻繁中斷**，只能重頭再來。

Nexus 將原生偵錯帶進了 VS Code —— 它**輕量且反應迅速**，擁有**出色的 C/C++ 支援**，讓你沿用既有的 CMake／增量建置流程，而不必等待 IDE 整體重建。你將在 Android 原生程式碼上獲得 VS Code 的完整偵錯體驗（中斷點、變數、呼叫堆疊、監看、偵錯主控台）。

## 功能

- **點幾下即可附加** —— 只需設定一次，選擇程序，就能在裝置上開始偵錯。
- **不干擾你的工作** —— 與裝置之間維持輕量、靈敏、穩定的連線。
- **在地化介面** —— 以你自己的語言使用擴充功能（見 [語言](#語言)）。

## 系統需求

- 一台已啟用 USB 偵錯、執行可偵錯建置的 Android 裝置或模擬器
- 已安裝 Android NDK
- 一個以 CMake 為基礎的原生專案

## 使用方式

從活動列開啟 **Nexus** 檢視，選擇裝置與目標程序，然後附加。就這麼簡單。

Nexus 檢視提供三個動作：

- **Attach（附加）** —— 開始偵錯所選程序。
- **Refresh（重新整理）** —— 重新掃描已連線的裝置與程序。
- **Settings（設定，齒輪圖示）** —— 開啟下方的設定面板。

## 設定

點擊 Nexus 檢視中的齒輪圖示開啟設定面板。你只需要提供：

- **NDK 路徑** —— Android NDK 的安裝目錄。
- **偵錯選項** —— 本次工作階段的目標應用程式／程序以及偵錯類型。

![Nexus 設定面板](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## 語言

擴充功能介面支援以下語言：

- English（英語）
- 简体中文（簡體中文）
- 繁體中文
- 日本語（日語）
- 한국어（韓語）
- Deutsch（德語）
- Français（法語）
- Español（西班牙語）
- Русский（俄語）
- Português（葡萄牙語）

介面會自動跟隨你的 VS Code 顯示語言，未翻譯的文字會回退為英文。

## 意見回饋與支援

- **回報 bug 或提出功能建議：** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## 授權

見 [LICENSE.txt](LICENSE.txt)。
