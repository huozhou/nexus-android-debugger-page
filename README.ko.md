# Nexus: Android 디버거

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Android **C/C++ 네이티브 코드**를 VS Code 안에서 바로 디버깅하세요 — 가볍고, 빠르고, 안정적입니다.

> CMake 기반 네이티브 프로젝트를 지원합니다.

**언어:** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · 한국어 · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Русский](README.ru.md) · [Português](README.pt.md)

[**마켓플레이스에서 설치**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**문제 신고**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**웹사이트**](https://huozhou.github.io/nexus-android-debugger-page/)

![Nexus VS Code 확장 데모](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## 왜 Nexus인가

Android Studio에서 네이티브 코드를 디버깅해 봤다면 아마 익숙한 상황일 것입니다:

- 프로젝트가 커지면 IDE가 **느려지고 버벅이며**, 켜 두는 것만으로도 무겁습니다.
- **중단점 적중이 느리고**, 한 단계씩 실행하는 것도 답답합니다.
- 디버그 세션이 **끊겨서** 처음부터 다시 시작해야 합니다.

Nexus는 네이티브 디버깅을 VS Code로 가져옵니다. VS Code는 **가볍고 반응이 빠르며**, **뛰어난 C/C++ 지원**을 갖추고 있어 IDE 전체 재빌드를 기다릴 필요 없이 기존 CMake/증분 빌드 워크플로를 그대로 이어갈 수 있습니다. Android 네이티브 코드에서 VS Code의 디버깅 경험(중단점, 변수, 호출 스택, 조사식, 디버그 콘솔)을 누릴 수 있습니다.

## 주요 기능

- **몇 번의 클릭으로 연결** — 한 번만 간단히 설정하고 프로세스를 선택하면 기기에서 바로 디버깅합니다.
- **방해하지 않음** — 기기와 가볍고 반응이 빠르며 안정적인 연결을 유지합니다.
- **현지화된 UI** — 자신의 언어로 확장을 사용하세요([언어](#언어) 참고).

## 요구 사항

- USB 디버깅이 활성화되고 디버그 가능한 빌드를 실행 중인 Android 기기 또는 에뮬레이터
- 설치된 Android NDK
- CMake 기반 네이티브 프로젝트

## 사용 방법

작업 표시줄에서 **Nexus** 뷰를 열고, 기기와 원하는 프로세스를 선택한 뒤 연결하면 끝입니다.

Nexus 뷰에는 세 가지 작업이 있습니다:

- **Attach(연결)** — 선택한 프로세스의 디버깅을 시작합니다.
- **Refresh(새로 고침)** — 연결된 기기와 프로세스를 다시 검색합니다.
- **Settings(설정, 톱니바퀴 아이콘)** — 아래 구성 패널을 엽니다.

## 설정

Nexus 뷰의 톱니바퀴 아이콘에서 설정 패널을 엽니다. 다음만 입력하면 됩니다:

- **NDK 경로** — Android NDK가 설치된 폴더입니다.
- **디버그 옵션** — 세션의 대상 앱/프로세스와 디버그 유형입니다.

![Nexus 설정 패널](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## 언어

확장 UI는 다음 언어로 제공됩니다:

- English(영어)
- 简体中文(중국어 간체)
- 繁體中文(중국어 번체)
- 日本語(일본어)
- 한국어
- Deutsch(독일어)
- Français(프랑스어)
- Español(스페인어)
- Русский(러시아어)
- Português(포르투갈어)

UI는 VS Code 표시 언어를 자동으로 따르며, 번역되지 않은 문자열은 영어로 대체됩니다.

## 피드백 및 지원

- **버그 신고 또는 기능 요청:** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## 라이선스

[LICENSE.txt](LICENSE.txt)를 참고하세요.
