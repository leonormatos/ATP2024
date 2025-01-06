- Primeiro pede-se ao jogador para escolher o modo (1 ou 2) e guarda a escolha em "modo".
- Definimos o número inicial de fósforos como 21.
- Se o modo for 1, o jogador começa (jogador_first = True).
- Se o modo for 2, o computador começa (jogador_first = False).
- O jogo continua enquanto houver fósforos restantes (fosforos > 0).
- O número de fósforos restantes é exebido no início de cada turno.
- Se for a vez do jogador:
     . Pergunta-se quantos fósforos o jogador quer tirar (entre 1 e 4).
     . Se a jogada for menor que 1, maior que 4 ou maior que o número de fósforos restantes, uma mensagem de erro é exebida. 
- Subtrai-se o número de fósforos tirados pelo jogador.
- Se o jogador tirar o último fósforo (fosforos == 0), uma mensagem de derrota é exebida e termina o jogo.
- Se for a vez do computador:
     . O computador decide a jogada:
     . Se houver 4 ou menos fósforos, tira 1 fósforo para evitar perder.
     . Caso contrário, tira 2 fósforos (uma escolha simples e fixa neste caso).
     . Mostra-se quantos fósforos o computador tirou.
- Subtrai-se o número de fósforos tirados pelo computador.
- Se o computador tirar o último fósforo (fosforos == 0), uma mensagem de vitória é devolvida para o jogador e termina o jogo. 