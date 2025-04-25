# ♟️ Sistema de Xadrez em Java

Este é um projeto de jogo de xadrez simples, executado no terminal, desenvolvido em Java.  
O objetivo é permitir que dois jogadores disputem uma partida de xadrez diretamente no console, com suporte às regras clássicas do jogo.

## 🚀 Funcionalidades

- Visualização do tabuleiro em ASCII
- Movimentação de peças com validação de jogadas
- Captura de peças adversárias
- Promoção de peões
- Exibição das peças capturadas por cada jogador
- Suporte a regras especiais como roque e xeque

## 🛠️ Tecnologias e Conceitos Utilizados

- Java SE (sem dependências externas)
- Programação orientada a objetos
- Herança, polimorfismo e encapsulamento
- Tratamento de exceções
- Estruturas de dados como listas e matrizes
- Organização em camadas e boas práticas de codificação

## 📦 Estrutura do Projeto

O código-fonte está localizado na pasta `src`, organizado em pacotes que representam diferentes camadas do sistema:

- `application`: Contém a classe principal que inicia o jogo
- `boardgame`: Inclui classes genéricas relacionadas ao tabuleiro e peças
- `chess`: Contém as classes específicas do jogo de xadrez, como peças e lógica de jogo
