O processador recebe dados da memória RAM e processa as informações para entender o que elas significam.

A CPU é dividida em 3 partes:
* 1ª Parte: **UC**, ou Unidade de Controle, que é responsável por pegar uma instrução, analisar bit a bit e entender o que o byte significa.
![Parte UC do Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/02/03-UC_do_Processador.png)

* 2ª Parte: **ULA**, ou Unidade Lógico Aritmética, é responsável por executar a maioria dos dados, realizando operações aritméticas, como soma, subtração, divisão, multiplicação, comparações e operações lógicas, como se é falso ou verdadeiro.
![Conceito da Parte ULA do Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/02/03-ULA_do_Processador-Conceito.png)
![Exemplo de FUncionamento da ULA do Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/02/03-ULA_do_Processador-Exemplo.png)

    * Para poupar tempo de processamento buscando os dados que estão sendo trabalhados, a partir da unidade de armazenamento, o processador armazena pequenos espaços próximos à ele para buscar os dados recentemente criados, acelerando o processamento, esses espaços são chamados de **registradores**.

* 3ª Parte: **Registradores**: Guardam dados de um processador, como uma instrução atual, posição da instrução atual, valores intermediários entre as operações do processador. Geralmente o processador possui centenas de resgistradores, resultando em centenas de bytes.
![Registradores do Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/02/03-Registradores.png)
![Função dos Registradores do Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/02/03-Registradores-Função.png)
![Funcionamento do Registrador do Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/02/03-Funcionamento_do_Processador.png)