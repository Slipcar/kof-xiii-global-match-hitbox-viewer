# KOF XIII Global Match – Hitbox Viewer & Training Tool by Slipcar
![Game](https://img.shields.io/badge/Game-KOFXIII%20(Steam%20x32)-red)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Overlay em tempo real para **The King of Fighters XIII: Global Match** (PC, versão 32-bit) que desenha hitboxes/hurtboxes/pushboxes e traz um conjunto de ferramentas de treino (pausa, frame-advance, controle de super/drive) e um frame meter (medidor de vantagem de frames) ao vivo.

> ⚠️ **Uso educacional / prática pessoal.** Esta ferramenta só lê e escreve memória do processo local do jogo (nenhuma modificação de arquivos, nenhuma interação online). Não use em partidas online/ranqueadas. Use por sua conta e risco.

---

## 📸 Preview
![Preview](img/active.png)
![Preview](img/active2.png)
![Preview](img/active3.png)
![Preview](img/frame_advantage.png)

## O que o programa faz
- **Categorização por tipo de caixa**, com cor e nome:
  

  Cada categoria pode ser **ligada/desligada individualmente** (veja hotkeys).
- **Frame meter (medidor de frame data) ao vivo**, para os dois jogadores, mostrando:
  - Fases Startup / Active / Recovery / Hitstun / Blockstun, coloridas por bloco, quadro a quadro.
  - Frame de vantagem/desvantagem calculado automaticamente após o impacto.
  - A barra segue o **desenho real das hitboxes** (não apenas a animação), então é sensível a golpes com hitbox ativa por tempos variáveis.
- **Ferramentas de treino**:
  - Pausar/despausar o jogo instantaneamente.
  - Avançar exatamente 1 frame com o jogo pausado (frame-by-frame).
  - Ajustar manualmente a barra de Super (estoque, 0–5) e a barra de Drive (0–100) de qualquer um dos dois jogadores.
  - Auto-refill: mantém super e drive sempre cheios automaticamente enquanto ativado.
- **Menu de ajuda in-game** (estilo tela de pause do próprio jogo) com a lista completa de hotkeys, para consulta rápida sem sair da partida.
- **Mensagens de status na tela** confirmando quando uma categoria de hitbox é ligada/desligada.

---

## Hotkeys

| Tecla | Ação |
|---|---|
| `F1` | Pausa / despausa o jogo |
| `Shift+F1` |	Abre/fecha o menu de ajuda com a lista de comandos |
| `F2` | Avança 1 quadro (só funciona com o jogo pausado) |
| `Shift+F2` | Mostrar/ocultar referência dos tipos de box |
| `F3` | Muda o estilo do preenchimento das hitboxes |
| `F4 / Shift+F4` | Ligar/desligar exibição das hitboxes números/nomes segurando Shift |
| `F5 / Shift+F5` |  Enviar player 1 para Narnia / Player 2 segurando Shift |
| `F6` | Ligar/desligar o frame meter |
| `F7 / Shift+F7` | 	Jogador 1: aumenta / diminui a barra de Super |
| `F8 / Shift+F8` | 	Jogador 1: aumenta / diminui a barra de Drive(50%) |
| `F9 / Shift+F9` | 	Jogador 2: aumenta / diminui a barra de Super |
| `F10 / Shift+F10` | 	Jogador 2: aumenta / diminui a barra de Drive(50%) |
| `F11` | Barras e drives recarregam ao chegar em 0 |
| `Shift + Esc` | Fechar o programa |

### Ligar/desligar categorias de hitbox individualmente

| Tecla | Categoria |
|---|---|
| `Ctrl + 0` | Ataque |
| `Ctrl + 1` | Pushbox |
| `Ctrl + 2` | Proximidade |
| `Ctrl + 3` | Vulnerável (hurtbox) |
| `Ctrl + 4` | Defesa |
| `Ctrl + 5` | Counter |
| `Ctrl + 6` | Magia (Colisão) |
| `Ctrl + 7` | Agarrão |
| `Ctrl + 8` | Magia (Refletor) |
| `Ctrl + 9` | Magia (Ataque) |

---

## Requisitos

- Um computador com Windows
- O jogo KOF XIII Global Match instalado e aberto
- O programa baixado no seu computador

---

## Como usar

1. Abra o KOF XIII Global Match e entre em uma partida (modo treino, versus, ou até um replay salvo).
2. Rode o executável
3. Aperte `F1` a qualquer momento para ver a lista de hotkeys sem sair do jogo.
4. Aperte `Shift + Esc` para fechar o overlay.

---

## Personalizando/expandindo o catálogo de hitboxes

Novos IDs e tipos de caixa encontrados durante o uso podem ser informados para serem atualizados.

---

## Aviso legal

Este projeto é resultado de engenharia reversa feita para fins de estudo pessoal e prática em modo treino/replay offline. Não é afiliado, endossado ou distribuído pela SNK ou por qualquer publisher do jogo. Use por sua conta e risco, e apenas em partidas offline/locais.
