# Nexus: Android デバッガー

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Android の **C/C++ ネイティブコード**を VS Code 内で直接デバッグ — 軽量・高速・安定。

> CMake ベースのネイティブプロジェクトに対応しています。

**言語:** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · 日本語 · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Русский](README.ru.md) · [Português](README.pt.md)

[**マーケットプレイスからインストール**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**問題を報告**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**ウェブサイト**](https://huozhou.github.io/nexus-android-debugger-page/)

![Nexus VS Code 拡張機能のデモ](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## なぜ Nexus なのか

Android Studio で Android のネイティブコードをデバッグしていると、こんな経験はありませんか？

- プロジェクトが大きくなると IDE が**重く、もたつく**ようになり、開いているだけでも負担が大きい。
- **ブレークポイントの反応が遅く**、ステップ実行ももたつく。
- デバッグセッションが**切断**され、最初からやり直しになる。

Nexus はネイティブデバッグを VS Code に持ち込みます。VS Code は**軽量で応答性が高く**、**優れた C/C++ サポート**を備えており、IDE 全体の再ビルドを待つことなく、既存の CMake／インクリメンタルビルドのワークフローをそのまま活かせます。Android のネイティブコードに対して、VS Code のデバッグ体験（ブレークポイント、変数、コールスタック、ウォッチ、デバッグコンソール）を得られます。

## できること

- **数クリックでアタッチ** — 一度だけ少し設定し、プロセスを選べば、デバイス上でデバッグを開始できます。
- **作業の邪魔をしない** — デバイスとの軽量で応答性が高く安定した接続。
- **ローカライズされた UI** — 自分の言語で拡張機能を利用できます（[言語](#言語)を参照）。

## 必要条件

- USB デバッグが有効で、デバッグ可能なビルドを実行している Android デバイスまたはエミュレーター
- Android NDK がインストールされていること
- CMake ベースのネイティブプロジェクト

## 使い方

アクティビティバーから **Nexus** ビューを開き、デバイスと対象のプロセスを選んでアタッチするだけです。

Nexus ビューには 3 つの操作があります。

- **Attach（アタッチ）** — 選択したプロセスのデバッグを開始します。
- **Refresh（更新）** — 接続中のデバイスとプロセスを再スキャンします。
- **Settings（設定、歯車アイコン）** — 下記の設定パネルを開きます。

## 設定

Nexus ビューの歯車アイコンから設定パネルを開きます。指定が必要なのは次の項目だけです。

- **NDK パス** — Android NDK がインストールされているフォルダー。
- **デバッグオプション** — セッションの対象アプリ／プロセスとデバッグタイプ。

![Nexus 設定パネル](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## 言語

拡張機能の UI は以下の言語で利用できます。

- English（英語）
- 简体中文（簡体字中国語）
- 繁體中文（繁体字中国語）
- 日本語
- 한국어（韓国語）
- Deutsch（ドイツ語）
- Français（フランス語）
- Español（スペイン語）
- Русский（ロシア語）
- Português（ポルトガル語）

UI は VS Code の表示言語に自動的に従い、翻訳されていない文字列は英語にフォールバックします。

## フィードバックとサポート

- **バグの報告・機能のリクエスト:** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## ライセンス

[LICENSE.txt](LICENSE.txt) を参照してください。
