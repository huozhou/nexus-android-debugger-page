# Nexus : débogueur Android

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Déboguez le **code natif C/C++** Android directement dans VS Code — léger, rapide et stable.

> Prend en charge les projets natifs basés sur CMake.

**Langues :** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · Français · [Español](README.es.md) · [Русский](README.ru.md) · [Português](README.pt.md)

[**Installer depuis le Marketplace**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**Signaler un problème**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**Site web**](https://huozhou.github.io/nexus-android-debugger-page/)

![Démo de l'extension Nexus pour VS Code](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## Pourquoi Nexus

Si vous déboguez du code natif Android dans Android Studio, cela vous semblera sans doute familier :

- L'IDE devient **lent et saccadé** sur les projets volumineux, et le simple fait de le garder ouvert est lourd.
- Les **points d'arrêt sont lents** à se déclencher, et l'exécution pas à pas traîne.
- Les sessions de débogage **se coupent et se déconnectent**, vous obligeant à tout recommencer.

Nexus apporte le débogage natif dans VS Code — qui reste **léger et réactif**, offre une **excellente prise en charge du C/C++** et vous permet de conserver votre flux de travail CMake / de compilation incrémentale existant plutôt que d'attendre des reconstructions complètes de l'IDE. Vous bénéficiez de l'expérience de débogage de VS Code (points d'arrêt, variables, pile d'appels, espion, console de débogage) sur votre code natif Android.

## Fonctionnalités

- **Attachement en quelques clics** — configurez une fois, choisissez le processus, et vous déboguez sur l'appareil.
- **Discret** — une connexion légère, réactive et stable avec votre appareil.
- **Interface localisée** — utilisez l'extension dans votre propre langue (voir [Langues](#langues)).

## Prérequis

- Un appareil Android ou un émulateur connecté avec le débogage USB activé, exécutant une version débogable
- Android NDK installé
- Un projet natif basé sur CMake

## Utilisation

Ouvrez la vue **Nexus** depuis la barre d'activité, choisissez votre appareil et le processus souhaité, puis attachez-vous. C'est tout.

La vue Nexus propose trois actions :

- **Attach (Attacher)** — démarrer le débogage du processus sélectionné.
- **Refresh (Actualiser)** — rechercher à nouveau les appareils et processus connectés.
- **Settings (Paramètres, icône d'engrenage)** — ouvrir le panneau de configuration ci-dessous.

## Paramètres

Ouvrez le panneau des paramètres via l'icône d'engrenage dans la vue Nexus. Vous n'avez qu'à fournir :

- **Chemin du NDK** — le dossier où votre Android NDK est installé.
- **Options de débogage** — l'application/le processus cible et le type de débogage de la session.

![Panneau des paramètres de Nexus](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## Langues

L'interface de l'extension est disponible en :

- English (anglais)
- 简体中文 (chinois simplifié)
- 繁體中文 (chinois traditionnel)
- 日本語 (japonais)
- 한국어 (coréen)
- Deutsch (allemand)
- Français
- Español (espagnol)
- Русский (russe)
- Português (portugais)

L'interface suit automatiquement la langue d'affichage de VS Code et revient à l'anglais lorsqu'une chaîne n'est pas traduite.

## Retours et assistance

- **Signaler un bogue ou demander une fonctionnalité :** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## Licence

Voir [LICENSE.txt](LICENSE.txt).
