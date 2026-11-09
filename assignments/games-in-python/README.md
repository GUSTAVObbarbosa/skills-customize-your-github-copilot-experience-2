# 📘 Assignment: Games in Python

## 🎯 Objective

Crie jogos interativos em Python para praticar entrada de dados, variáveis, condicionais, loops e o uso do módulo `random`. Ao final, você terá implementado dois jogos de terminal com regras claras e mensagens para o jogador.

## 📝 Tasks

### 🛠️ Criar um Jogo de Adivinhação

#### Descrição
Implemente um jogo em que o computador escolhe um número secreto e o jogador tenta adivinhá-lo. Dê dicas para orientar cada tentativa e informe se o jogador venceu ou perdeu.

#### Requisitos
O programa concluído deve:

- Escolher aleatoriamente um número inteiro entre 1 e 100 usando `random`.
- Permitir até 7 tentativas válidas e informar se o número secreto é maior ou menor que cada palpite incorreto.
- Rejeitar entradas que não sejam números inteiros entre 1 e 100 sem consumir uma tentativa.
- Encerrar quando o jogador acertar ou esgotar as tentativas, revelando o número secreto se perder.
- Exibir quantas tentativas foram usadas quando o jogador vencer.

### 🛠️ Criar um Jogo de Pedra, Papel e Tesoura

#### Descrição
Implemente uma partida de três rodadas entre o jogador e o computador. Em cada rodada, o computador escolhe sua jogada aleatoriamente; compare as escolhas e mantenha o placar.

#### Requisitos
O programa concluído deve:

- Aceitar `pedra`, `papel` ou `tesoura` como jogada do jogador, sem diferenciar letras maiúsculas de minúsculas.
- Solicitar novamente uma jogada inválida sem avançar a rodada.
- Escolher a jogada do computador aleatoriamente entre as três opções.
- Aplicar as regras: pedra vence tesoura, tesoura vence papel e papel vence pedra; escolhas iguais resultam em empate.
- Jogar exatamente 3 rodadas válidas e exibir o resultado de cada rodada e o placar final.
- Informar quem venceu a partida ou se houve empate.
