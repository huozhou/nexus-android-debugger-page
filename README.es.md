# Nexus: depurador de Android

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Depura **código nativo C/C++** de Android directamente en VS Code: ligero, rápido y estable.

> Compatible con proyectos nativos basados en CMake.

**Idiomas:** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · Español · [Русский](README.ru.md) · [Português](README.pt.md)

[**Instalar desde el Marketplace**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**Informar de un problema**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**Sitio web**](https://huozhou.github.io/nexus-android-debugger-page/)

![Demostración de la extensión Nexus para VS Code](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## Por qué Nexus

Si depuras código nativo de Android en Android Studio, esto probablemente te suene familiar:

- El IDE se vuelve **lento y con tirones** en proyectos grandes, y solo mantenerlo abierto resulta pesado.
- Los **puntos de interrupción tardan** en activarse y la ejecución paso a paso se arrastra.
- Las sesiones de depuración **se cortan y se desconectan**, así que tienes que empezar de nuevo.

Nexus lleva la depuración nativa a VS Code, que se mantiene **ligero y ágil**, ofrece **excelente compatibilidad con C/C++** y te permite seguir con tu flujo de trabajo existente de CMake / compilación incremental en lugar de esperar a reconstrucciones completas del IDE. Obtienes la experiencia de depuración de VS Code (puntos de interrupción, variables, pila de llamadas, inspección, consola de depuración) en tu código nativo de Android.

## Qué hace

- **Adjunta con un par de clics**: configura un poco una vez, elige el proceso y ya estás depurando en el dispositivo.
- **No te estorba**: una conexión ligera, ágil y estable con tu dispositivo.
- **Interfaz localizada**: usa la extensión en tu propio idioma (consulta [Idiomas](#idiomas)).

## Requisitos

- Un dispositivo Android o emulador conectado con la depuración USB habilitada, ejecutando una compilación depurable
- Android NDK instalado
- Un proyecto nativo basado en CMake

## Uso

Abre la vista **Nexus** desde la barra de actividades, elige tu dispositivo y el proceso que quieras, y adjúntate. Eso es todo.

La vista Nexus tiene tres acciones:

- **Attach (Adjuntar)**: iniciar la depuración del proceso seleccionado.
- **Refresh (Actualizar)**: volver a buscar dispositivos y procesos conectados.
- **Settings (Configuración, icono de engranaje)**: abrir el panel de configuración de abajo.

## Configuración

Abre el panel de configuración con el icono de engranaje en la vista Nexus. Solo necesitas indicar:

- **Ruta del NDK**: la carpeta donde está instalado tu Android NDK.
- **Opciones de depuración**: la app/el proceso de destino y el tipo de depuración de la sesión.

![Panel de configuración de Nexus](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## Idiomas

La interfaz de la extensión está disponible en:

- English (inglés)
- 简体中文 (chino simplificado)
- 繁體中文 (chino tradicional)
- 日本語 (japonés)
- 한국어 (coreano)
- Deutsch (alemán)
- Français (francés)
- Español
- Русский (ruso)
- Português (portugués)

La interfaz sigue automáticamente el idioma de visualización de VS Code y recurre al inglés cuando una cadena no está traducida.

## Comentarios y soporte

- **Informar de un error o solicitar una función:** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## Licencia

Consulta [LICENSE.txt](LICENSE.txt).
