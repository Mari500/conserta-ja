# Conserta Já 🛠️

Jogo mobile de **mini-jogos de reparo** (*repair minigames*): escolha a ferramenta certa, na ordem certa, antes que o estrago aumente.

▶ **Jogar:** https://mari500.github.io/conserta-ja (após ativar o GitHub Pages)

## Fases
| # | Fase | Etapas | Dificuldade | Medidor |
|---|------|--------|-------------|---------|
| 1 | Janela na tempestade | 5 | Fácil | Água no chão |
| 2 | Cano estourado | 5 | Fácil | Alagamento |
| 3 | Tomada em curto | 5 | Médio | Risco de incêndio |
| 4 | Goteira no telhado | 6 | Médio | Infiltração |
| 5 | Pneu furado na estrada | 8 | Difícil | Perigo na pista |
| 6 | Chuveiro queimado | 8 | Difícil | Fila do banho |

## Mecânicas
- **Escolha de ferramenta**: o objetivo é descrito, a ferramenta não. Ferramenta errada = +8 de dano.
- **Erros perigosos**: ferramentas fora de hora causam +25 (ex.: mexer na tomada sem desligar o disjuntor, ligar o chuveiro sem água).
- **Toques repetidos** e **segurar o dedo**: algumas etapas exigem trabalho na cena (apertar, desparafusar, levantar o carro, impermeabilizar).
- **Pressão de tempo**: o medidor de dano sobe continuamente; etapas concluídas desaceleram o estrago.
- **QTE**: botões de reflexo surgem de repente — toque antes do anel fechar ou leve +12 de dano.
- **Tempo para ler**: 4 s de pausa para observar a cena no início e 1,5 s de respiro após cada etapa.
- **Dica**: após 8 s parada numa etapa, a ferramenta certa começa a piscar.
- **Estrelas (1–3)** por dano, erros e reflexos perdidos; recordes salvos no navegador.

## Tecnologia
Um único `index.html` (HTML + CSS + JavaScript puro). Cenas e ícones em SVG feito à mão, som com Web Audio API e vibração no celular. Sem dependências.

## Publicar no GitHub Pages
*Settings → Pages → Deploy from a branch → `main` / `(root)` → Save*
