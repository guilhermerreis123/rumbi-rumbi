# rumbi-rumbi

Jogo de plataforma vertical feito em HTML5 Canvas e JavaScript puro, em um único arquivo (`index.html`). Pule de plataforma em plataforma, colete frutas e fuja do monstro que sobe por baixo.

## Como jogar

Não precisa instalar nada: abra o `index.html` em qualquer navegador.

1. Na tela inicial, escolha um personagem com as teclas **1** a **5**:

   | Tecla | Personagem |
   | ----- | ---------- |
   | 1 | 🦊 Sheidi |
   | 2 | 🐸 Welix |
   | 3 | 🐱 Bile |
   | 4 | 🐵 Jerry |
   | 5 | 🐧 Thaat |

2. O personagem pula sozinho ao tocar uma plataforma.

## Controles

| Tecla | Ação |
| ----- | ---- |
| **←** / **→** | Move para a esquerda / direita |
| **←←** / **→→** (toque duplo no ar) | Dash lateral (uma vez por pulo) |

## Regras

- **Vidas:** você começa com 3. Cair para fora da tela ou ser alcançado pelo monstro custa uma vida. Ao perder todas, o jogo recomeça do zero.
- **Proteção inicial:** nos primeiros 10 segundos de cada tentativa você não perde vidas.
- **Plataformas azuis** dão um pulo mais alto.
- **Frutas** (🍌 🍒 🍓) sobre as plataformas valem 1 ponto cada.
- **Tempo:** cada etapa dura 30 segundos. A cada 2 etapas você sobe um andar.
