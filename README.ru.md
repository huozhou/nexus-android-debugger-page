# Nexus: отладчик Android

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Отлаживайте **нативный код C/C++** для Android прямо в VS Code — легко, быстро и стабильно.

> Поддерживает нативные проекты на основе CMake.

**Языки:** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · Русский · [Português](README.pt.md)

[**Установить из Marketplace**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**Сообщить о проблеме**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**Веб-сайт**](https://huozhou.github.io/nexus-android-debugger-page/)

![Демонстрация расширения Nexus для VS Code](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## Почему Nexus

Если вы отлаживаете нативный код Android в Android Studio, вам это, скорее всего, знакомо:

- На крупных проектах IDE становится **медленной и тормозит**, а держать её открытой уже тяжело.
- **Точки останова срабатывают медленно**, а пошаговое выполнение тянется.
- Сеансы отладки **обрываются и теряют соединение**, и приходится начинать заново.

Nexus переносит нативную отладку в VS Code — он остаётся **лёгким и отзывчивым**, имеет **отличную поддержку C/C++** и позволяет работать в вашем привычном процессе CMake / инкрементальной сборки, не дожидаясь полной пересборки в IDE. Вы получаете отладку в стиле VS Code (точки останова, переменные, стек вызовов, наблюдение, консоль отладки) для вашего нативного кода Android.

## Возможности

- **Подключение в пару кликов** — один раз немного настройте, выберите процесс — и вы отлаживаете на устройстве.
- **Не мешает работе** — лёгкое, отзывчивое и стабильное соединение с устройством.
- **Локализованный интерфейс** — используйте расширение на своём языке (см. [Языки](#языки)).

## Требования

- Подключённое устройство Android или эмулятор с включённой отладкой по USB, на котором запущена отлаживаемая сборка
- Установленный Android NDK
- Нативный проект на основе CMake

## Использование

Откройте представление **Nexus** на панели действий, выберите устройство и нужный процесс, затем подключитесь. Вот и всё.

В представлении Nexus три действия:

- **Attach (Подключить)** — начать отладку выбранного процесса.
- **Refresh (Обновить)** — повторно просканировать подключённые устройства и процессы.
- **Settings (Настройки, значок шестерёнки)** — открыть панель конфигурации ниже.

## Настройки

Откройте панель настроек по значку шестерёнки в представлении Nexus. Нужно указать всего лишь:

- **Путь к NDK** — папку, где установлен ваш Android NDK.
- **Параметры отладки** — целевое приложение/процесс и тип отладки для сеанса.

![Панель настроек Nexus](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## Языки

Интерфейс расширения доступен на следующих языках:

- English (английский)
- 简体中文 (китайский упрощённый)
- 繁體中文 (китайский традиционный)
- 日本語 (японский)
- 한국어 (корейский)
- Deutsch (немецкий)
- Français (французский)
- Español (испанский)
- Русский
- Português (португальский)

Интерфейс автоматически следует языку отображения VS Code и переключается на английский, если строка не переведена.

## Обратная связь и поддержка

- **Сообщить об ошибке или предложить функцию:** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## Лицензия

См. [LICENSE.txt](LICENSE.txt).
