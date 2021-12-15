# Estrutura de Dados, Arrays e Registro 

*Estrutura de dados é uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta.*

*Essas estruturas encontram muitas aplicações no desenvolvimento e sistemas, sendo que algumas são altamente especializadas e utilizadas em tarefas específicas. Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em bancos de dados ou serviços de busca.*

*Em uma estrutura de dados devemos saber como realizar um determinado conjunto de operações básicas, como por exemplo: Inserir dados, excluir dados, localizar um elemento, percorrer todos os itens constituintes da estrutura para visualização, classificar que se resume em colocar os itens de dados em uma determinada ordem (numérica, alfabética, etc.)*

####  Algoritmo

*Um algoritmo é um conjunto de instruções estruturadas e ordenadas, seu objetivo é realizar uma tarefa ou operação específica.
Os algoritmos são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados.*

#### Principais Estruturas de Dados

*Vetores e Matrizes, Registro, Lista, Pilha, Fila, Árvore, Tabela Hash, Grafos.*

#### Vetores e Matrizes

*Vetores e Matrizes ou Arrays são estruturas de dados simples que podem auxiliar quando já muitas variáveis do mesmo tipo em um algoritmo.*

*Vetor ou array uni-dimensional é uma variável que armazena várias variáveis do mesmo tipo.*

*O vetor é uma estrutura de dados indexada, que pode armazenar uma determinada quantidade de valores do mesmo tipo.*

*Matriz ou array multi-dimensional é um vetor de vetores.*

*Uma matriz é um vetor que possui duas ou mais dimensões.*

#### Registros

*Um registro é uma estrutura que fornece um formato especializado para armazenar informações em memória.*

*Enquanto arrays nos permitem armazenar vários dados de um único tipo de dados, o recurso de Registro nos permite armazenar mais de um tipo de dado.*

*Um registro é composto por campos que especificam cada uma das informações que o compõem.*

*Exemplos de alguns campos que constituem o registro de um cliente (cpf, nome, endereço, contato) (tipos de dados diferentes)*.

*Toda estrutura de registro tem um nome (ex: livro), e seus campos podem ser acessados por meio do uso do operador (.).*
*Por exemplo, para acessar o preço de um livro, poderíamos utilizar a seguinte declaração: (livro.preco)*



# Listas, Pilhas e Filas

#### O Que são Listas:

*Estrutura de dados do tipo lista, armazena dados de um determinado tipo em uma ordem específica.*
*A diferença entre listas e arrays é a de que as listas possuem tamanho ajustável, enquanto arrays possuem tamanho fixo.*
*Existem dois tipos de listas: <u>Ligadas e Duplamente Ligadas</u>*

#### Lista Ligada:

*Na estrutura do tipo lista existem os nós onde cada um dos nós conhece o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele: por isso ela é chamada de "lista ligada", pois os nós são amarrados com essa indicação de qual é o próximo nó.*

#### Lista Duplamente Ligada:

*A grande diferença das listas duplamente ligadas para as listas ligadas é que elas são bidirecionais. Vimos que, naturalmente, não conseguimos "andar para trás" em listas ligadas, pois os nós de uma lista ligada sabem somente quem é o próximo elemento. Nas listas duplamente ligadas, os nós sabem quem é o próximo elemento e também quem é o elemento anterior, o que permite a navegação reversa.*

#### O que são Pilhas:

*Uma pilha é uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado.
O acesso aos itens de uma pilha é restrito, somente um item pode ser lido ou removido por vez.
Existem dois tipos de Pilhas: <u>LIFO ou PEPS, FIFO ou UEPS.</u>*

#### Pilha LIFO ou UEPS

*A estrutura do tipo Pilha LIFO (Last in First Out) ou UEPS (Último que Entra Primeiro que Sai), apresenta o seguinte critério: O primeiro elemento a ser retirado é o último que tiver sido inserido.*

#### Pilha FIFO ou PEPS

*A estrutura do tipo PILHA FIFO (First in First Out) ou PEPS (Primeiro que Entra Primeiro que Sai), apresenta o seguinte critério: O primeiro elemento a ser retirado é o primeiro que tiver sido inserido.*

#### O que são Filas:

*A estrutura do tipo Fila admite remoção de elementos e inserção de novos sujeita à seguinte regra de operação:
O elemento removido é o que está na estrutura há mais tempo ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido seguindo o conceito FIFO.*



# Estruturas de Dados do Tipo Árvore, Tabela Hash e Grafos

#### O que são Árvores:

*É uma estrutura de dados que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas.*

#### O que são Tabelas Hash:

*Uma tabela hash, de dispersão ou espalhamento é uma estrutura de dados especial, que associa chaves de pesquisa a valores.*

*Uma tabela hash é uma generalização da idéia de array, porém utiliza uma função denominada Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do "array" que defina a tabela.*

#### Porque Espalhar?

*A tabela hash permite a associação de "valores a "chaves".*

*Valores: é a posição ou índice onde o elemento se encontra.*

*Chave: é a parte da informação que compõe o elemento a ser manipulado.*

*Espalhar facilita a busca na estrutura de dados, pois a partir de uma chave podemos acessar de forma rápida uma posição do "array".*

#### O que são grafos:

*Grafos são estruturas que permitem programar a relação entre objetos.
Os objetos são vértices ou "nós" do grafo. Os relacionamentos são arestas.*

