O programa começa por pedir ao jogador para selecionar um modo de jogo:
- Se escrever 1, o jogador vai adivinhar o número que o computador escolheu.
- Se escrever 2, o computador tentará adivinhar o número que o jogador está a pensar.

Na primeira opção, a função random.randrange(0, 100) faz com que o computador escolha um número aleatório entre 0 e 99, armazenando-o na variável n.
- O computador pede ao jogador para tentar adivinhar o número e armazena esse palpite na variável "palpite".
- Enquanto o palpite não for igual ao número pensado pelo computador, o programa entra no "while" e vai dando dicas ao jogador:
  - Se o palpite for menor que o número pensado, o computador diz que o número é mais alto e pede outro palpite.
  - Se o palpite for maior que o número pensado, o computador diz que o número é mais baixo e pede outro palpite.
- A cada tentativa, a variável "tentativas" é incrementada para contar quantas tentativas o jogador fez.
- O jogo acaba quando o jogador acerta no número. O loop termina e o computador exibe uma mensagem de parabéns, dizendo o número de tentativas. 

Na segunda opção, o computador pede ao jogador para pensar num número entre 0 e 100, mas não pede para ele dizer qual é o número.
- Primeiro palpite do computador:
  - O computador diz um palpite aleatório usando random.randint(mínimo, máximo) (neste caso, entre 0 e 100). Esse palpite é mostrado ao jogador.
  - O número de tentativas começa em 1.
- O computador pergunta ao jogador se o número que ele está a pensar é:
  - Muito elevado (1),
  - Muito baixo (2)
  - Correto (3)
- Com base na resposta do jogador:
  - Se o número for muito baixo, o valor mínimo é ajustado para "número + 1".
  - Se o número for muito alto, o valor máximo é ajustado para "número - 1".
  - O computador, então, gera um novo palpite dentro dos limites ajustados (mínimo e máximo), e o processo continua até que o jogador indique que o palpite está correto (opção 3).
- O jogo acaba quando o computador acerta e o loop para. O computador informa sobre o número de tentativas. 

