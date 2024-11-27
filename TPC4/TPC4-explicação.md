
Primeiro, apresentamos ao utilizador o menu com as opções disponíveis.
A lista "lista" é inicialmente vazia. O utilizador tem que escolher uma opção do menu.
O ciclo while opcao !=0 controla o menu, que se vai repetir até que o utilizador escolha a opção 0 (Sair).

Opção1: 
Gera uma lista de números aleatórios entre 1 e 100 e volta a colocar a variável "lista" vazia para evitar conflitos com listas anteriores.

Opção 2:
Permite ao utilizador criar uma lista escolhida por ele. O utilizador escolhe os números e estes são adicionados á lista. 

Opção 3:
Calcula a soma dos números presentes na lista atual. A soma começa a 0 e à medida que percorremos a lista, vamos adiconando os elementos da lista. 

Opção 4:
Calcula a media da lista atual. Primeiro calculamos a soma como na opção anterior e depois calculamos a média: soma/comprimento da lista.

Opção 5:
Determina o maior número da lista comparando todos os elementos. Dizemos que o maior elemento é o 1º da lista e à medida que vamos percorrendo 
a lista, o "maior" vai mudando até obtermos o número que é o verdadeiro "maior da lista".

Opção 6:
Determina o menor número da lista comparando todos os elementos. Tal como na opção anterior, define-se o menor elemento como o 1º da lista. 
Depois percorremos a lista toda e no final vamos obter o "menor da lista".

Opção 7:
Verifica se a lista está ordenada por ordem crescente. Consideramos incialmente o resultado como "Sim". À medida que percorremos a lista, 
assumimos que esta está ordenada por ordem crescente. Se verificarmos a dada altura que um elemento maior que outro está antes dele na lista, 
mudamos o resultado para "Não", indicando que não está ordenada por ordem crescente.

Opção 8:
Verifica se a lista está ordenada por ordem decrescente. Consideramos incialmente o resultado como "Sim". À medida que percorremos a lista, 
assumimos que esta está ordenada por ordem decrescente. Se verificarmos a dada altura que um elemento menor que outro está antes dele na lista, 
mudamos o resultado para "Não", indicando que não está ordenada por ordem decrescente.

Opção 9:
Procura um número escolhido pelo utilizador na lista e exibe sua posição ou -1 caso não esteja presente na lista. 

Opção 0:
No início definimos que o menu seria sempre demonstrado depois de realizar uma das opções apenas se esta fosse difreente de "0". Se for "0", 
imprimimos a lista atual. 

