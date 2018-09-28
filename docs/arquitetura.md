# Arquitetura
## Inicialização do tabuleiro (v1.0)
* As funções relacionadas ao gerenciamento das casas do jogo da velha
ficarão
no módulo **jogovelha.py**.
* O estado de cada casa do jogo será representada por uma string: "."
para casa
vazia; "X" para casa ocupada pelo 1o jogador; "O" para casa ocupada
pelo 2º Jogador.
* A função inicializar() retornará uma lista 3x3, onde cada posição
conterá uma string para indicar o estado de uma casa do jogo. A função
retornará todas as casas inicialmente vazias.
* A função jogar(jogador, linha, coluna) irá posicionar o **jogador**

## Verificação da validade das jogadas (v1.1)
* Foram realizadas mudanças no módulo **jogovelha.py** 
* A mudança consiste no acréscimo da string “X” e “O” na função jogar (jogador, linha, coluna).
* Foram acrescentadas três strings “X” e duas “O”.
* E de acordo com a regra do jogo da velha a string “X” ganha o jogo  

