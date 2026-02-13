# Requisitos do Sistema – Jogo da Forca Online

## 1. Introdução

Este documento descreve o levantamento de requisitos para o desenvolvimento de um sistema de Jogo da Forca Online, permitindo partidas individuais e multiplayer via navegador.

---

## 2. Requisitos Funcionais

RF01 – O sistema deve permitir que o usuário crie uma conta com e-mail e senha.

RF02 – O sistema deve permitir autenticação (login e logout) de usuários cadastrados.

RF03 – O sistema deve permitir partidas no modo singleplayer.

RF04 – O sistema deve permitir partidas multiplayer online.

RF05 – O sistema deve selecionar palavras aleatórias a partir de um banco de dados.

RF06 – O sistema deve exibir o número de tentativas restantes.

RF07 – O sistema deve exibir as letras já utilizadas pelo jogador.

RF08 – O sistema deve atualizar automaticamente o estado do jogo a cada tentativa.

RF09 – O sistema deve exibir mensagem de vitória quando o jogador acertar a palavra.


RF10 – O sistema deve registrar o histórico de partidas do usuário.

RF11 – O sistema deve exibir ranking de jogadores no modo multiplayer.

---

## 3. Requisitos Não Funcionais

RNF01 – O sistema deve carregar em até 2 segundos em conexões padrão de internet.

RNF02 – O sistema deve suportar no mínimo 100 usuários simultâneos.

RNF03 – O sistema deve garantir criptografia de senhas.

RNF04 – O sistema deve ser responsivo e funcionar em dispositivos móveis e desktop.

RNF05 – O sistema deve manter disponibilidade mínima de 99% mensal.

RNF06 – O sistema deve seguir boas práticas de usabilidade e acessibilidade.

RNF07 – O sistema deve garantir integridade e consistência dos dados das partidas.

---

## 4. Restrições

R01 – O sistema será desenvolvido como aplicação web.

R02 – O backend deverá utilizar API REST.

R03 – O banco de dados deverá armazenar usuários, palavras e histórico de partidas.

---

## 5. Considerações Finais

Evolução do documento conforme as necessidades encontradas durante o desenvolvimento do jogo.