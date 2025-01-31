# Redes Jogo da Velha 
  Redes Jogo da Velha é uma implementação em Python do popular jogo de tabuleiro, feita como uma atividade da disciplina de Redes De Computadores da Universidade Federal Fluminense, ministrada pelo docente Flavio Luiz Seixas. Este programa permite dois jogadores competirem online em um tabuleiro virtual utilizando comunicação por socket.

## Descrição do Projeto
O jogo segue as regras clássicas do Jogo da Velha:
- Dois jogadores se alternam fazendo jogadas.
- Cada jogador escolhe uma coluna para colocar sua peça ("X" ou "O").
- O objetivo é alinhar três peças consecutivas horizontalmente, verticalmente ou diagonalmente.

O programa utiliza comunicação em rede para conectar os dois jogadores. Um jogador atua como "anfitrião" (host), enquanto o outro se conecta como cliente (guest).

## Funcionalidades
- Interface baseada em texto para exibição do tabuleiro e interação com os jogadores.
- Suporte à comunicação por sockets para conectar dois jogadores remotamente.
- Verificação automática de vitórias, empates e jogadas válidas.

## Requisitos
- Python 3.x
- Conexão à internet ou rede local (LAN) para os dois jogadores

## Exemplo de execução

- https://youtu.be/iBrvBndk2Cs
