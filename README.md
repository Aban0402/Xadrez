# Xadrez
# ♟️ Jogo de Xadrez em C (Console)

Este é um projeto simples de um jogo de xadrez implementado em linguagem C, executado diretamente no terminal.  
O objetivo é simular o tabuleiro e permitir movimentação básica das peças entre dois jogadores.

---

## 📌 Funcionalidades

- Inicialização automática do tabuleiro de xadrez
- Exibição do tabuleiro no terminal
- Sistema de jogadas por coordenadas (ex: `e2 e4`)
- Alternância entre jogadores (branco e preto)
- Validação básica de movimento (verifica se há peça na origem)

---

## 🧠 Como o programa funciona

O tabuleiro é representado por uma matriz 8x8:

int tabuleiro[8][8];

Cada peça possui um valor numérico:

0 → vazio
1 → peão
2 → torre
3 → cavalo
4 → bispo
5 → rainha
6 → rei
🎮 Como jogar

As jogadas são feitas no formato:

origem destino

Exemplo:

e2 e4

O programa:

Converte as coordenadas (ex: e2 → linha/coluna)
Verifica se existe peça na posição de origem
Move a peça para o destino
Alterna o jogador

🧾 Exemplo de execução
  a b c d e f g h
8 T C B Q K B C T
7 P P P P P P P P
...

Jogador 1, faça sua jogada (ex: e2 e4):
