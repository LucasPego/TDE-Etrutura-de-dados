# TDE-Etrutura-de-dados

# Trabalho prático 1 - Labirinto utilizando Pilhas

Este trabalho consiste em um labirinto feito em java utilizando a biblioteca Stack, onde um algoritmo foi criado com pilha em que o próprio java deve encontrar a saída.
Os labirintos foram criados em um arquivo .txt. Na imagem abaixo é possível ver como ele funciona no .txt:

![alt text](https://github.com/RafaelKampa/TDE-Etrutura-de-dados/blob/04f7c6631162e640fbd91cd7b69c58eeadba1568/LabirintoTXT.png)

O programa percorre todas as possibilidades até encontrar a saída e devolve no console da IDE os caminhos seguidos, como demonstrado na figura abaixo:

![alt text](https://github.com/RafaelKampa/TDE-Etrutura-de-dados/blob/0b0632c803af067a022888280e5c85ad71beb491/CaminhoPercorrido.png)

# Trabalho prático 2 - Labirinto controlável utilizando Fila

Este trabalho é uma alteração do trabalho 1, onde agora é utilizada a classe LinkedQueue para percorrer o labirinto, porém agora cabe ao usuário digitar o caminho a ser percorrido.
Na imagem abaixo é possível ver os comandos que o usuário deve fornecer:

![alt text](https://github.com/RafaelKampa/TDE-Etrutura-de-dados/blob/0b0632c803af067a022888280e5c85ad71beb491/ComandosLabirinto2.png)

O console imprime o labirinto com a posição selecionada pelo jogador e com o caminho percorrido.
Foram utilizados os valores 0 para parede, 1 para caminho válido, 2 para a saída e 3 como a posição do usuário e também como caminho percorrido.
A imagem abaixo demonstra o labirinto impresso no console após algumas jogadas e saída encontrada:

![alt text](https://github.com/RafaelKampa/TDE-Etrutura-de-dados/blob/0b0632c803af067a022888280e5c85ad71beb491/CaminhoPercorridoLabirinto2.png)

# Trabalho prático 3 - Implementação de classe de Lista

Este trabalho é a implementação de uma classe de uma lista duplamente encadeada, contando com todos os comandos que esta lista deve possuir.
Na imagen abaixo é possível verificar como o processo de adicionar um item a lista seja adicionando ao final dela ou no meio.

![alt text](https://github.com/RafaelKampa/TDE-Etrutura-de-dados/blob/0b0632c803af067a022888280e5c85ad71beb491/LinkedListADD.png)

O método getNode procura o node procurado para incluir um item dentro da Lista, para isso ele divide o tamanho da lista em 2 e verifica se a posição indicada pelo usuário fica mais próximo do começo ou do final da lista, sendo assim ele não precisa procurar pela lista inteira toda vez que seja adicionado um novo item a lista.

![alt text](https://github.com/RafaelKampa/TDE-Etrutura-de-dados/blob/0b0632c803af067a022888280e5c85ad71beb491/LinkedListGETNODE.png)
