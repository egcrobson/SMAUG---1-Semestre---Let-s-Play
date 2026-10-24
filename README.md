<div align="center">

<img src="Animations/MenuInicialFundo/Default/000.png" alt="Let's Play — Demo" width="320" style="image-rendering: pixelated;">

# Let's Play

**Um jogo de terror e quebra-cabeças em pixel art, feito em Construct 2.**

Projeto do grupo **Smaug** · Jogos Digitais · 1º semestre de 2021 — Fatec Carapicuíba

![Construct 2](https://img.shields.io/badge/Construct%202-r244-1f6feb?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-WebGL-E34F26?style=flat-square&logo=html5&logoColor=white)
![Gênero](https://img.shields.io/badge/g%C3%AAnero-terror%20%2F%20puzzle-8b0000?style=flat-square)
![Classificação](https://img.shields.io/badge/classifica%C3%A7%C3%A3o-16%20anos-red?style=flat-square)
![Status](https://img.shields.io/badge/status-demo-lightgrey?style=flat-square)

<br>

<a href="https://devrobson.itch.io/lets-play"><img src="https://img.shields.io/badge/Baixar%20no-itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white" alt="Baixar no itch.io"></a>

</div>

---

## 📖 Sobre o jogo

> *"Nos conhecemos do passado, meu velho amigo... lembre-se: conheço seus pecados."*

**Fred** acorda vendado em uma masmorra escura, sem saber como chegou ali. Uma voz misteriosa avisa que ele só sairá com vida se resolver todos os desafios do lugar — e que, ao longo do caminho, vai descobrir **o real motivo de estar preso** e **pagar pelos seus pecados**.

Entre armadilhas, salas trancadas, pergaminhos enigmáticos e bilhetes deixados pelo sequestrador, Fred precisa desvendar quem está por trás de tudo isso e qual segredo do passado o trouxe até aqui.

<div align="center">

<img src="Animations/Fred/parado/000.png" alt="Fred" width="96" style="image-rendering: pixelated;">
&nbsp;&nbsp;&nbsp;&nbsp;
<img src="Animations/William/Parado/000.png" alt="???" width="96" style="image-rendering: pixelated;">

<sub><b>Fred</b>, o protagonista &nbsp;·&nbsp; <b>???</b>, o anfitrião misterioso</sub>

</div>

## ⬇️ Baixar e jogar

O jogo está disponível no **itch.io**:

👉 **[devrobson.itch.io/lets-play](https://devrobson.itch.io/lets-play)**

Baixe o arquivo `Let's Play 1JDM.rar`, extraia o conteúdo e abra o executável do jogo.

## 🎮 Como jogar

| Tecla | Ação |
| :---: | --- |
| <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> | Movimentar o Fred |
| <kbd>Espaço</kbd> | Interagir com objetos (alavancas, notas, pergaminhos, portas) |
| <kbd>Espaço</kbd> | Fechar cartas e notas abertas |
| Mouse / toque | Navegar pelos menus |

Sempre que o símbolo **LET'S** aparecer sobre o Fred, significa que ele pode interagir com o item à sua frente — seja para avançar no jogo, seja para descobrir mais da história.

<div align="center">
<img src="Animations/Explica%C3%A7%C3%A3oLets/Default/000.png" alt="Indicador de interação LET'S" width="320" style="image-rendering: pixelated;">
</div>

## 🗝️ Estrutura do jogo

```mermaid
flowchart LR
    A[Owl Studio Games] --> B[Menu inicial]
    B --> I[Instruções]
    B --> O[Opções]
    B --> C1[Cutscene de abertura]
    C1 --> D1[Desafio 1<br/>o pergaminho]
    D1 --> D2[Desafio 2<br/>a nota e a parede]
    D2 --> H[O Salão]
    H --> L[O Labirinto]
    L --> CF[Cutscene final]
```

- **Cutscene de abertura** — Fred acorda vendado e ouve a voz que vai guiá-lo (e atormentá-lo).
- **Desafio 1** — um pergaminho traz pistas sobre dragões e estrelas; um único erro pode ser fatal.
- **Desafio 2** — bilhetes do sequestrador e uma passagem escondida na parede.
- **O Salão** — a pedra que abre caminho para a última etapa.
- **O Labirinto** — o desafio final antes do confronto.
- **Cutscene final** — a verdade sobre o passado de Fred é revelada.

### ⚠️ Perigos

Espinhos que saem do chão, armadilhas de fogo, armadilhas que empurram e buracos no piso. Cair em uma delas leva direto à tela de **Game Over**.

<div align="center">
<img src="Animations/GameOver/Default/000.png" alt="Você perdeu" width="320" style="image-rendering: pixelated;">
</div>

## ▶️ Como abrir e rodar o projeto

O projeto foi salvo com o **Construct 2 (release 244)**, que roda no Windows.

1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/egcrobson/SMAUG---1-Semestre---Let-s-Play.git
   ```
2. Abra o arquivo **`Let's Play.caproj`** no Construct 2.
3. Pressione <kbd>F5</kbd> (*Run layout*) para jogar no navegador.
4. Para gerar uma versão jogável, use **File → Export project → HTML5 website**.

## 📁 Estrutura do repositório

```
├── Let's Play.caproj   # Arquivo principal do projeto (abra no Construct 2)
├── Layouts/            # Telas e fases (menu, desafios, cutscenes)
├── Event sheets/       # Lógica de cada tela (eventos do Construct 2)
├── Animations/         # Sprites e animações em pixel art
├── Textures/           # Fontes em sprite
└── Files/              # Sons, músicas e ícones
```

## 🛠️ Tecnologias

- **[Construct 2](https://www.construct.net/en/construct-2/manuals/construct-2)** — engine e editor do jogo
- **HTML5 + WebGL** — plataforma de exportação
- Comportamentos usados: *8 Direction*, *Solid*, *Scroll To*, *Turret*
- Plugins usados: *Keyboard*, *Mouse*, *Touch*, *Audio*, *Array*, *Function*, *Sprite Font*

## 👥 Equipe

Desenvolvido pela **Owl Studio Games** — grupo **Smaug**, turma da manhã do curso de **Jogos Digitais** da **Fatec Carapicuíba**.

| Nome | Links |
| --- | --- |
| **Robson dos Santos Silva** | [GitHub](https://github.com/egcrobson) · [itch.io](https://devrobson.itch.io) · [Linktree](https://linktr.ee/devrobson) |
| **Leonardo Souza de Oliveira** | — |

<div align="center">
<img src="Animations/LogoOwl/Default/000.png" alt="Owl Studio Games" width="200">
</div>

## 🎵 Créditos

- **Músicas:** faixas de **Alexander Ehlers** — *Great Mission*, *Spacetime*, *Twists* e *Waking the Devil*.
- **Efeitos sonoros:** passos, tochas, alavancas, espinhos, coruja e outros, na pasta [`Files/`](Files).

## 🏫 Contexto acadêmico

Proposta de um *escape room* desenvolvida no **1º semestre de 2021** do curso de **Jogos Digitais** da **Fatec Carapicuíba**, pelo grupo **Smaug**.

---

<div align="center">
<sub>Feito com ☕ e muitos sustos por Owl Studio Games</sub>
</div>
