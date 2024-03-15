Jogo da Velha em Pascal

Este é um simples jogo da velha implementado em Pascal. O código utiliza procedimentos e funções para facilitar a organização e compreensão do jogo. Abaixo estão detalhes sobre cada parte do código.

 Variáveis

- `v`: Matriz 3x3 de caracteres para armazenar o estado atual do tabuleiro.
- `L`, `C`: Índices para linhas e colunas do tabuleiro.
- `Cont`: Contador utilizado para preencher inicialmente o tabuleiro.
- `Po`: Posição escolhida pelo jogador.
- `Simb`: Representa o símbolo do jogador atual ("X" ou "O").
- `R`: Indica se a jogada foi bem-sucedida ou não.

 Procedimentos e Funções

 `mostraVelha()`

Procedimento para exibir o estado atual do tabuleiro.

 `mudaJogador()`

Procedimento para alternar entre os jogadores ("X" e "O").

 `Jogar(S: Caractere; P: Inteiro): Logico`

Função para realizar uma jogada no tabuleiro. Retorna verdadeiro se a jogada for válida e falso caso contrário.

 `TerminouVelha(): Logico`

Função que verifica se o jogo terminou, seja por vitória de algum jogador ou empate ("VELHA").

Fluxo Principal

O programa inicia preenchendo o tabuleiro com números de 1 a 9. Em seguida, entra em um loop principal, onde os jogadores alternam suas jogadas até que o jogo seja concluído. O programa verifica se houve um vencedor ou se o jogo resultou em empate.

Como Jogar

O jogador deve escolher uma posição no tabuleiro (de 1 a 9) para realizar sua jogada. O jogo exibirá mensagens de jogada inválida caso a posição escolhida já esteja ocupada ou seja inválida. O jogo termina quando um jogador vence ou ocorre um empate.

Divirta-se jogando o Jogo da Velha em Pascal!
