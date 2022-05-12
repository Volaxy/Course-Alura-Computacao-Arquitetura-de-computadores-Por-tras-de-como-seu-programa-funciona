Uma **DRAM** é mais barata, porém lentao, e a **SRAM** é mais rápida, porém cara.

![DRAM e SRAM](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/04/01-DRAMeSRAM.png)

Esse tipo de memória rápida vai ser responsável por guardar os dados que serão trabalhados no momento, esse tipo de memória é chamada de **Memória Cache**. Ela guarda um bloco de instruções trazidos da memória RAM, e armazena no cache para maior rapidez.

![SRAM no Processador](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/04/01-SRAMnoProcessador.png)

![SRAM no Processador - 1º Passo](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/04/01-SRAMnoProcessador-Passo1.png)

Usando a **memória cache**, é bem provável que os comandos que são próximos tenham alguma relação, logo, o processador armazena esses comandos nessa memória, para uma maior rapidez em responde-los.

A memória cache é dividida em várias partes, onde a cada nível abaixo (1, 2, 3, etc), a velocidade fica um pouco mais lenta, mas o espaço para o cache aumenta.

![SRAM no Processador - 1º Passo](https://raw.githubusercontent.com/Volaxy/Course-Alura-Computacao-Arquitetura-de-computadores-Por-tras-de-como-seu-programa-funciona/master/Images/04/01-CachesNoProcessador.png)