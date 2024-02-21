### Projects in development for Programming Lab class.

## Class 1_project1
O paradigma imperativo é o estilo de programação característico pelos programas com uma sequência de comandos que 
modificam o estado presente programa. 

Aqui estão algumas características do paradigma imperativo no seu programa:
* Sequência de Comandos: O programa é estruturado como uma sequência de comandos que são executados em ordem. 
* Estado Mutável: A variável t é modificada dentro do loop while para contar o tempo regressivamente.
* Controle de Fluxo: O programa utiliza estruturas de controle de fluxo, nesse caso específico, o programa utiliza 
um loop while para contar o tempo regressivamente e realizar outras ações em uma ordem específica.
* Procedural: O código é estruturado em uma série de procedimentos (funções). A função timer é um procedimento que realiza a contagem
 quando chamada.

Vale destacar que o programa também incorpora alguns elementos do paradigma de programação funcional, especialmente na 
formatação da string e na utilização da função divmod (retorna uma tupla de: quociente, dividendo). 

## Class 1_project2
O código destaca-se por abordar o paradigma de programação orientada a objetos (OOP). 

Algumas características que indicam isso:
* Classe e Método Estático: O código contém uma classe chamada Main e um método main, que é o ponto de entrada da aplicação Java.
A presença da classe e do método estático é uma característica típica da programação orientada a objetos em Java.
* Uso de Objetos String: A manipulação de strings é realizada usando objetos da classe String. As operações como toUpperCase(), toLowerCase(),
length(), indexOf(), e concatenação (+) são métodos da classe String.
* Variáveis e Tipos de Dados: O código declara variáveis usando tipos de dados, mas a manipulação primária é realizada por meio de objetos. Por exemplo, 
String phrase = "I hope I can master Java some day in the future."; declara uma variável phrase do tipo String.
* Encapsulamento e Composição: O código encapsula funcionalidades relacionadas dentro de métodos e usa composição ao chamar esses métodos. Cada método 
executa uma operação específica, promovendo uma abordagem modular.

## Class 2_project1
Uma versão recursiva do programa ainda se encaixa principalmente no paradigma imperativo.

* Instruções Específicas: O código ainda usa instruções específicas para controlar o fluxo do programa, como condições (if-else) 
e operações de lista (map, join). OBS.: # Uma forma de conversão de lista para string é usando a função map junto com join. A função map usa a função e aplica para iterável que pode ser lista, tupla, etc.
* Mudança de Estado: A função sequence realiza mudanças de estado por meio de variáveis, como pos. As chamadas 
recursivas e as manipulações de lista são usadas para acumular resultados.
* Detalhes de Implementação: O código ainda descreve como realizar a tarefa (encontrar índices) em termos de iteração e condicionais,
detalhando a implementação específica e de como obter o resultado desejado.

## Class 2_project2
Como você pode ser notado, a estrutura de código neste exemplo é mais concisa, legível e flexível. 
* Por usar este tipo de função lambda (sintaxe: lambda argumentos: expressão) em apenas uma linha de código.

Ao contrário do exemplo de programação imperativa, não é necessário descrever os passos. Em vez de usar um loop para iterar toda a nossa lista, utiliza o sorted na lista indicada e faz a leitura com base no len.
Em outras palavras, você pode ler o **código declarativo do Python** como encontrando a comprimento de todas as palvras da lista. Você só se importa com o resultado, não com o processo.

## Class 2_project3
A função reduce() é outra função nativa do python, ela vai aplicar uma função em todos os valores passados em forma de lista, e retornar apenas um valor.

Curiosidade: reduce faz parte da lib functools, ou seja, precisa ser importada esta biblioteca antes de utilizá-la. 

* Utiliza List comprehension para simplificar a criação da lista letras.
* Modifiquei a função lambda para ter dois parâmetros (acc para acumulador e letra para a letra atual).
Ele solicitará que você digite cinco letras, e então, combinará essas letras em uma palavra.

No código há predominância de paradigma imperativo, uma vez que tem um loop for que itera sobre um intervalo, solicita entrada do usuário, 
converte a entrada para minúsculas e a adiciona a uma lista. Em seguida, você utiliza a função reduce para 
combinar as letras da lista em uma única palavra.

## Class 3_project1
O código em C define uma função Potencia que calcula a exponenciação de uma base (bas) elevada a um dado expoente (expo). 

* A função principal chama-se Potencia(3, 3) e imprime o resultado com duas casas decimais.
* A função Potencia recebe dois argumentos inteiros: bas (a base) e expo (o expoente).
* Se o expoente é 0, a função retorna 1 (regra matemática).
* Caso contrário, ele inicializa uma variável p para 1 e itera através de um loop while, multiplicando p pela base bas para cada iteração até que o expoente se torne 0.
