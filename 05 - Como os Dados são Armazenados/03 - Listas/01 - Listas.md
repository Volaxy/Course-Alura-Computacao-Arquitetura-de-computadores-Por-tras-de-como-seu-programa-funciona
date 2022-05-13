Para se representar uma lista, é alocada na memória RAM espaços contíguos para cada um dos valores, um do lado do outro, as vantagens são a eficiencia com cache, e facilidade de encontrar os valores.

![Listas em RAM](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/05/03-ListasEmRAM.png)

![Posições da Lista Em RAM](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/05/03-PosicoesListaEmRAM.png)

![Posicoes 2x em Lista Em RAM](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/05/03-Posicoes2xListaEmRAM.png)

Caso se tenha várias listas em uma memória RAM, e de tamanhos variados, a solução é guardar o valor do endereço de cada uma das listas.

![Comeco da Lista Em RAM](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/05/03-ComecoListaEmRAM.png)

Um **Ponteiro** é uma referência que aponta para um endereço na memória.