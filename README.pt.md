# Nexus: depurador de Android

[![Version](https://img.shields.io/visual-studio-marketplace/v/northwind.nexus-android-debugger?label=VS%20Marketplace&color=007ACC)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger)
[![Rating](https://img.shields.io/visual-studio-marketplace/r/northwind.nexus-android-debugger)](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger&ssr=false#review-details)

Depure **código nativo C/C++** do Android diretamente no VS Code — leve, rápido e estável.

> Compatível com projetos nativos baseados em CMake.

**Idiomas:** [English](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [简体中文](README.zh-cn.md) · [繁體中文](README.zh-tw.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Русский](README.ru.md) · Português

[**Instalar pelo Marketplace**](https://marketplace.visualstudio.com/items?itemName=northwind.nexus-android-debugger) · [**Relatar um problema**](https://github.com/huozhou/nexus-android-debugger-page/issues) · [**Site**](https://huozhou.github.io/nexus-android-debugger-page/)

![Demonstração da extensão Nexus para VS Code](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/vscode-extension-demo.gif)

## Por que o Nexus

Se você depura código nativo de Android no Android Studio, isto provavelmente soa familiar:

- A IDE fica **lenta e travada** em projetos maiores, e só mantê-la aberta já é pesado.
- Os **pontos de interrupção demoram** a serem atingidos, e a execução passo a passo se arrasta.
- As sessões de depuração **caem e se desconectam**, então você precisa começar de novo.

O Nexus traz a depuração nativa para o VS Code — que permanece **leve e responsivo**, tem **excelente suporte a C/C++** e permite continuar no seu fluxo de trabalho existente de CMake / compilação incremental em vez de esperar por reconstruções completas da IDE. Você obtém a experiência de depuração do VS Code (pontos de interrupção, variáveis, pilha de chamadas, inspeção, console de depuração) no seu código nativo de Android.

## O que faz

- **Anexe com alguns cliques** — configure um pouco uma vez, escolha o processo e você já está depurando no dispositivo.
- **Não atrapalha** — uma conexão leve, responsiva e estável com o seu dispositivo.
- **Interface localizada** — use a extensão no seu próprio idioma (consulte [Idiomas](#idiomas)).

## Requisitos

- Um dispositivo Android ou emulador conectado com a depuração USB ativada, executando uma compilação depurável
- Android NDK instalado
- Um projeto nativo baseado em CMake

## Como usar

Abra a visualização **Nexus** na Barra de Atividades, escolha o seu dispositivo e o processo desejado e anexe. É só isso.

A visualização Nexus tem três ações:

- **Attach (Anexar)** — iniciar a depuração do processo selecionado.
- **Refresh (Atualizar)** — verificar novamente dispositivos e processos conectados.
- **Settings (Configurações, ícone de engrenagem)** — abrir o painel de configuração abaixo.

## Configurações

Abra o painel de configurações pelo ícone de engrenagem na visualização Nexus. Você só precisa fornecer:

- **Caminho do NDK** — a pasta onde o seu Android NDK está instalado.
- **Opções de depuração** — o app/processo de destino e o tipo de depuração da sessão.

![Painel de configurações do Nexus](https://raw.githubusercontent.com/huozhou/nexus-android-debugger-page/main/assets/settings-panel.png)

## Idiomas

A interface da extensão está disponível em:

- English (inglês)
- 简体中文 (chinês simplificado)
- 繁體中文 (chinês tradicional)
- 日本語 (japonês)
- 한국어 (coreano)
- Deutsch (alemão)
- Français (francês)
- Español (espanhol)
- Русский (russo)
- Português

A interface segue automaticamente o idioma de exibição do VS Code e recorre ao inglês quando uma cadeia de texto não está traduzida.

## Feedback e suporte

- **Relatar um bug ou solicitar um recurso:** [GitHub Issues](https://github.com/huozhou/nexus-android-debugger-page/issues)
## Licença

Consulte [LICENSE.txt](LICENSE.txt).
