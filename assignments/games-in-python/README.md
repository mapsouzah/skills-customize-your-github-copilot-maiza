# 🎮 Atividade: Jogo da Forca

## 🎯 Objetivo

Crie um jogo da Forca em que o jogador tenta descobrir uma palavra secreta antes de esgotar as tentativas. Ao concluir a atividade, você praticará manipulação de strings, listas, entrada de dados, condicionais e loops. Nível: iniciante.

Use o arquivo `starter-code.py` como ponto de partida.

## 📝 Tarefas

### 🛠️ Implementar o jogo

#### Descrição

Complete o código inicial para escolher uma palavra secreta e permitir que o jogador tente adivinhá-la letra por letra.

#### Requisitos

O programa concluído deve:

- Escolher aleatoriamente uma palavra de uma lista predefinida.
- Exibir as letras descobertas e representar as letras ainda não descobertas por `_`.
- Solicitar palpites de letras e revelar todas as ocorrências corretas na palavra.
- Contar e exibir as tentativas incorretas restantes, diminuindo essa contagem quando o palpite não estiver na palavra.
- Encerrar quando o jogador descobrir a palavra ou esgotar as tentativas.
- Informar se o jogador venceu ou perdeu; em caso de derrota, revelar a palavra secreta.

### 🛠️ Validar e testar os palpites

#### Descrição

Melhore a interação com o jogador e teste diferentes situações para garantir que a partida termine corretamente.

#### Requisitos

O programa concluído deve:

- Aceitar apenas um palpite de uma letra por vez e tratar letras maiúsculas e minúsculas da mesma forma.
- Informar quando o jogador repetir uma letra já tentada, sem descontar uma tentativa.
- Testar palpites corretos e incorretos, letras repetidas, vitória e derrota.
