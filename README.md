# DBD Overlay Studio — Beta

Aplicativo para Windows com overlays de Dead by Daylight: Timer 1v1, WinStreak, Confronto e Crosshair.

Esta versão beta está disponível para testes. Baixe **DBD-Overlay-Studio-Beta-2.1.20-Windows-x64-Setup.exe** na seção **Releases**, feche qualquer versão anterior e execute o instalador. Após a instalação, abra **DBD Overlay Studio** pelo menu Iniciar.

[Baixar a Beta 2.1.20](https://github.com/jumperjjj/DBD-Overlay-Studio-Beta/releases/tag/v2.1.20-beta.1)

[Site e demonstrações](https://dbd-overlay-studio.pages.dev/)

Instalações novas começam com destaque amarelo em todos os módulos, PLAYER 1 / PLAYER 2 no Timer e TIME A / TIME B no Confronto. A beta 2.1.20 aproxima a foto do Killer no WinStreak Minimal e mantém as escolhas já salvas.

## Requisitos

- Windows x64.
- Microsoft Edge WebView2 Runtime. O instalador verifica se ele está disponível e baixa o componente se necessário (precisa de internet nesse caso).
- Não é necessário instalar Node.js, Rust ou Electron.

## Como testar

- Configure a aba desejada e clique em **Mostrar overlay**.
- Desbloqueie Timer, WinStreak ou Confronto para arrastar a overlay; bloqueie para os cliques passarem ao jogo.
- Crosshair fica centralizado no monitor principal e não pode ser arrastado.
- **Somente OBS** retira Timer, WinStreak e Confronto da tela, mantendo a saída para captura. Crosshair continua visível quando ativado.
- Fechar a janela principal mantém o aplicativo na bandeja. Use **Fechar aplicativo** ou **Sair** na bandeja para encerrar.

## OBS

Com o aplicativo aberto, use uma fonte de navegador com um destes endereços:

- Timer: `http://127.0.0.1:17385/obs-timer`
- WinStreak: `http://127.0.0.1:17384/obs-streak`
- Confronto: `http://127.0.0.1:17384/obs-match`
- Crosshair: `http://127.0.0.1:17384/obs-crosshair`

## Feedback

Abra uma **Issue** descrevendo o problema, a versão do aplicativo e os passos para reproduzir. Se possível, inclua uma imagem e informe o modo de tela do jogo e o tipo de fonte utilizado no OBS.

A versão está em desenvolvimento. A interação sobre o jogo e os métodos de captura do OBS podem variar conforme o ambiente; teste também em janela sem bordas.

Este repositório disponibiliza os executáveis beta e informações de uso. O código-fonte não é publicado aqui.
