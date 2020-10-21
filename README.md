# Desafio - Contando peças de Xadrez

O xadrez é um jogo de tabuleiro estratégico, em que dois jogadores disputam a vitoria, o jogo consiste em um tabuleiro com um arranjo de 8 linhas e colunas, formando 64 posições diferentes como uma matriz [8 x 8].

Existem 6 diferentes tipos de peças no xadrez e cada tipo possui uma quantidade (destacada por parênteses):

- Peão (8)
- Bispo (2)
- Cavalo (2)
- Torre (2)
- Rainha (1)
- Rei (1)

---

Um tabuleiro completo possui trinta e duas peças. Cada tipo de peça, segundo a ordem que aparecem, receberão um código (ex.: peão = 1, bispo = 2, …, rei = 6 e o vazio = 0).

- Neste desafio, você deverá contabilizar e exibir a quantidade de cada peça em um tabuleiro de xadrez sem usar estruturas condicionais ou de múltipla escolha (sem *if*s, else e switch case).

## Resultado esperado

### Entrada

    0 0 0 0 0 0 0 0
    0 0 0 0 0 0 0 0
    0 0 0 0 0 0 0 0
    0 0 0 1 1 0 0 0
    0 0 0 1 1 0 0 0
    0 0 0 0 0 0 0 0
    0 0 0 0 0 0 0 0
    0 0 0 0 0 0 0 0

### Saida

    - Peão: 4 peça(s)
    - Bispo: 0 peça(s)
    - Cavalo: 0 peça(s)
    - Torre: 0 peça(s)
    - Rainha: 0 peça(s)
    - Rei: 0 peça(s)

## Condições

Para o desafio, assuma:

Apenas inteiros positivos ou nulo podem ser usados como limites.

- O preenchimento do tabuleiro pode envolver uma leitura parcial dos valores (número por número), total (uma linha completa) ou definido no próprio código.

- O intervalo compreende -1 < x < 7, onde x representa o número da peça (ou ausência dela, no caso de 0).
