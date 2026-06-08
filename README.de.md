# Nexus: Android Debugger

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Debuggen Sie nativen Android-**C/C++-Code** direkt in VS Code — leicht, schnell und stabil.

> Unterstützt CMake-basierte native Projekte.

**Sprachen:** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · Deutsch · [Français](README.fr.md) · [Español](README.es.md) · [Русский](README.ru.md) · [Português](README.pt.md)

[**Im Marketplace installieren**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**Problem melden**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**Website**](https://huozhou.github.io/nexus-android-debugger-page/)

![Nexus VS Code-Erweiterung – Demo](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## Warum Nexus

Wenn Sie nativen Android-Code in Android Studio debuggen, kommt Ihnen das wahrscheinlich bekannt vor:

- Die IDE wird bei größeren Projekten **langsam und träge**, und schon das Offenhalten ist ressourcenintensiv.
- **Haltepunkte greifen langsam**, und das schrittweise Durchgehen des Codes zieht sich.
- Debug-Sitzungen **brechen ab und trennen die Verbindung**, sodass Sie von vorne beginnen müssen.

Nexus bringt das native Debugging stattdessen in VS Code — das **leicht und reaktionsschnell** bleibt, **hervorragende C/C++-Unterstützung** bietet und es Ihnen ermöglicht, in Ihrem bestehenden CMake-/inkrementellen Build-Workflow weiterzuarbeiten, statt auf vollständige IDE-Neukompilierungen zu warten. Sie erhalten das Debugging-Erlebnis von VS Code (Haltepunkte, Variablen, Aufrufliste, Überwachung, Debugkonsole) für Ihren nativen Android-Code.

## Funktionen

- **Mit wenigen Klicks anhängen** — einmalig etwas konfigurieren, den Prozess auswählen, und Sie debuggen auf dem Gerät.
- **Hält sich zurück** — eine leichte, reaktionsschnelle und stabile Verbindung zu Ihrem Gerät.
- **Lokalisierte Benutzeroberfläche** — nutzen Sie die Erweiterung in Ihrer eigenen Sprache (siehe [Sprachen](#sprachen)).

## Voraussetzungen

- Ein verbundenes Android-Gerät oder einen Emulator mit aktiviertem USB-Debugging, auf dem ein debugfähiger Build läuft
- Installiertes Android NDK
- Ein CMake-basiertes natives Projekt

## Verwendung

Öffnen Sie die **Nexus**-Ansicht über die Aktivitätsleiste, wählen Sie Ihr Gerät und den gewünschten Prozess aus und hängen Sie sich an. Das war's.

Die Nexus-Ansicht bietet drei Aktionen:

- **Attach (Anhängen)** — Debugging des ausgewählten Prozesses starten.
- **Refresh (Aktualisieren)** — verbundene Geräte und Prozesse erneut suchen.
- **Settings (Einstellungen, Zahnradsymbol)** — das Konfigurationspanel unten öffnen.

## Einstellungen

Öffnen Sie das Einstellungspanel über das Zahnradsymbol in der Nexus-Ansicht. Sie müssen nur Folgendes angeben:

- **NDK-Pfad** — der Ordner, in dem Ihr Android NDK installiert ist.
- **Debug-Optionen** — die Ziel-App/der Zielprozess und der Debug-Typ für die Sitzung.

![Nexus-Einstellungspanel](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## Sprachen

Die Benutzeroberfläche der Erweiterung ist verfügbar in:

- English (Englisch)
- 简体中文 (vereinfachtes Chinesisch)
- 繁體中文 (traditionelles Chinesisch)
- 日本語 (Japanisch)
- 한국어 (Koreanisch)
- Deutsch
- Français (Französisch)
- Español (Spanisch)
- Русский (Russisch)
- Português (Portugiesisch)

Die Oberfläche folgt automatisch Ihrer VS Code-Anzeigesprache und fällt auf Englisch zurück, wenn eine Zeichenfolge nicht übersetzt ist.

## Feedback & Support

- **Fehler melden oder Funktion vorschlagen:** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## Lizenz

Siehe [LICENSE.txt](LICENSE.txt).
