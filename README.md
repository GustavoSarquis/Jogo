# Jogo
O jogo principal conta com 3 minijogos desenvolvidos e o código do jogo se divide em 4 partes.
No desenvolvimento do jogo foi utilizado 5 bibliotecas:
- <stdio.h> 
- <stdlib.h>
- <time.h>
- <string.h>
- <locale.h>
A primeira parte do jogo é o menu principal, o qual foi utilizado switch case com quatro opções de case, o primeiro direciona o usuário para o primeiro jogo(Perguntas e Respostas), o segundo case direciona o usuário para o segundo jogo(Cobra na Caixa!), o terceiro case direciona o usuário para o terceiro jogo(Gousmar War), e o último case fecha o jogo, fechando o programa.

O primeiro minijogo é o "Perguntas e Respostas", nesse jogo, o usuário deve responder 5 perguntas acerca de temas gerais, as perguntas possuem 4 afirmativas com uma certa, ao final do jogo é mostrado a quantidade de acertos do jogador.
Acerca do desenvolvimento do jogo: Foi ultilizado um laço de repetição (while), com a finalidade de o usuário poder jogar o jogo novamente ou finalizar o minijogo e voltar ao menu principal. Além do laço de repetição, o jogo também apresenta switch case para cada pergunta, cada switch possuí 4 cases, o codigo possuí também um contador, que ao usuário marcar a alternativa certa, aumenta de 1 em 1, e, ao final do jogo, é mostrado o numero de acertos/5.

O segundo minijogo é o "Cobra na Caixa!", nesse jogo, são dois jogadores, que, primeiramente, devem escolher seus personagens dentre os 7 predefinidos, após isso, ocorre um sorteio para ver qual usuário vai começar, após o sorteio, o primeiro jogador deve escolher uma caixa dentre as 5 possiveis, 1 possuí uma cobra, que elimina o jogador, 1 possuí um botão, que abre a porta e o usuário ganha, e 3 que não possuem nada, fazendo com que o jogador passe a vez para o outro jogador.
Acerca do desenvolvimento do jogo:  
