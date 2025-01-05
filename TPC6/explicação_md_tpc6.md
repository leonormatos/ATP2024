- turmaA e turmaB: São listas de tuplos que representam alunos
- escola: É uma lista de tuplos, onde cada tuplo contém o nome da turma e a lista de alunos.

def MostrarMenu()
- Mostra o menu de opções disponíveis para o utilizador.
- Cada opção está numerada e corresponde a uma funcionalidade.

def turma_existente(nome_turma, escola)
- Verifica-se se uma turma já existe na lista escola.
- Converte o nome da turma para letras minúsculas.
- Utilizamos any() para retornar True se alguma turma na escola tiver o mesmo nome.

def CriarTurma(nome_turma, escola)
- Converte-se o nome da turma para minúsculas.
- Se a turma ainda não existir, cria-se uma nova lista para armazenar alunos e adiciona-se à escola.
- Vai aparecer uma mensagem de sucesso ou erro dependendo da situação.

def inserir_aluno(nome_turma, aluno)
- Percorre as turmas para encontrar a correspondente.
- Verifica se o ID do aluno já existe na turma antes de o adicionar.
- Adiciona o aluno e exibe uma mensagem de sucesso ou erro.

def listar(nome_turma)
- Dá uma lista de todos os alunos de uma turma específica.
- Percorre a lista de turmas em "escola" para encontrar a turma correspondente.

def consultar_aluno(id_aluno, nome_turma)
- Procura o aluno numa turma específica pelo ID.
- Exibe as informações do aluno ou uma mensagem de erro.

def guardar_turma(nome_turma, fnome)
- Salva os dados de uma turma num ficheiro.
- Cada aluno é armazenado numa linha do ficheiro com as suas informações.

def recuperar_turma(fnome)
- Lê um ficheiro e reconstrói a lista de alunos.
- Depois mostra os alunos recuperados ou uma mensagem se o ficheiro estiver vazio. 


 
