def listar(cinema)
- cinema[0][2] serve para aceder ao nome do filme da sala 1 do cinema.
- cinema[1][2] serve para aceder ao nome do filme da sala 2 do cinema.
- Fazemos print dos filmes em exibição.

def disponivel(cinema, filme, lugar)
- A variável res é usada para armazenar o resultado.
- O for percorre cada sala do cinema.
- A condição if sala[2] == filme verifica se o filme está em exibição na sala.
- O segundo if verifica se o lugar pretendido não está ocupado.
- Retorna o resultado (True ou False).

def vendebilhete(cinema, filme, lugar)
- Uma nova lista cinema2 é usada para atualizar o cinema.
- Se o filme estiver na sala e o lugar estiver disponível, uma nova sala é criada, adicionando o lugar à lista de lugares ocupados.
- Caso contrário, a sala permanece inalterada.
- No final, a lista atualizada é devolvida.

def listardisponibilidades(cinema)
- Para cada sala, calcula-se a diferença entre a capacidade total (sala[0]) e o número de lugares ocupados (len(sala[1])).
- Fazemos print para vermos o nome do filme e o número de lugares disponíveis.

def inserirSala(cinema, nova_sala)
- A função verifica se a sala já existe comparando a capacidade (sala[0]) e o nome do filme (sala[2]).
- Caso a sala não exista, ela é adicionada ao cinema.
- No fim, devolve a lista atualizada de salas.



