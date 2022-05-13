# Arquitetura de computadores: Por trás de como seu programa funciona

Curso da Alura sobre Computadores e como eles funcionam.

## Objetivo Final &#x1F3AF;

Objetivo resumido

URL do curso -> [Arquitetura de computadores: Por trás de como seu programa funciona](https://www.alura.com.br/curso-online-arquitetura-computadores-funcionamento-programa)
![Arquitetura de computadores: Por trás de como seu programa funciona](https://www.alura.com.br/assets/api/share/curso-arquitetura-computadores-funcionamento-programa.png)

## Links Úteis &#x1F517;
* [Prefixos SI](https://pt.wikipedia.org/wiki/Prefixos_do_Sistema_Internacional_de_Unidades) - Site para todas as unidades de medida existentes.

## Siglas &#x1F5FA;
* **bit** - Binary Digit - Dígito Binário.
* **byte** - Grupos de 8 bits.
* **JIT Compilation** - **J**ust **I**n **T**ime **C**ompilation - Compilação na Hora Certa.
* **JVM** - **J**ava **V**irtual **M**achine - Máquina Virtual Java.
* **HD** - **H**ard **D**isk - Disco Rígido.
* **SSD** - **S**olid **S**tate **D**rive - Unidade de Estado Sólido.
* **RAM** - **R**andom **A**ccess **M**emory - Memória de Acesso Aleatório.
* **ROM** - **R**ead-**O**nly **M**emory - Memória de Apenas Leitura.
* **BIOS** - **B**asic **I**nput/**O**utput **S**ystem - Sistema Básico de Entrada/Saída.
* **CPU** - **C**entral **P**rocess **U**nit - Unidade Central de Processamento.
* **GPU** - **G**raphics **P**rocessing **U**nit - Placa de Vídeo.
* **TPU** - **T**ensor **P**rocessing **U**nit - Unidade de Processamento de Tensores.
* **DRAM** - **D**ynamic **RAM** - RAM Dinâmica.
* **SRAM** - **S**tatic **RAM** - RAM Estática.
* **ASCII** - **A**merican **S**tandard **C**ode for **I**nformation **I**nterchange - Código Padrão Americano para o Intercâmbio de Informação.

## Atalhos &#x2328;

## 01 - Como um computador lê o seu código &#x1F516;
* Como funciona a linguagem que o computador entende: a **linguagem de máquina**;
* O computador precisa de um programa tradutor para transformar um código em uma linguagem de programação de alto nível para linguagem de máquina;
* Existem, em geral, dois tipos de tradutores: **compiladores e interpretadores**;
* Quais as diferenças entre compiladores e interpretadores, e suas implementações modernas;

### 01 - O Código de Máquina
* Funcionamento das linguagens de programação.
* Diferença entre **Bits** e **Bytes**.

### 02 - O Tradutor do Computador
* Como o computador interpreta uma linha de comando.
* Como o código fonte se transforma em código binário.

### 03 - Executando Diferentes Linguagens
* Introdução à linguagens **compiladas** e **interpretadas**.

### 04 - Compiladores VS Interpretadores
* **Vantagens** e **desvantagens** das linguagens compiladas ou interpretadas.

### 05 - Implementações Modernas
* Exemplo da **JVM** do **Java**.

***

## 02 - Como um Computador Executa um Programa &#x1F516;
* Como o SSD e HD funcionam e quais as diferenças entre eles;
* Qual é o papel da memória RAM no computador e qual sua diferença para a memória secundária (SSD ou HD);
* Como funcionam os principais componentes de um processador;
* Como um programa em código de máquina é executado no computador;
* A importância do clock do processador para a velocidade de processamento;
* Que existem limitações de memória num computador e como criar programas eficientes para contornar esse problema.

### 01 - Armazenando Código
* Diferenças entre linguagens compiladas e interpretadas.

### 02 - Memória RAM
* Como a memória RAM funciona.
* Para que serve a memória RAM.

### 03 - Funcionamento do Processador
* A divisão de tarefas dentro de um **Processador**.
* Como um **Processador** processa as informações.

### 04 - Executando Código
* Passo a passo do funcionamento de um *Processador*.
* Função do **contador** no Processador.
* O que é **clock**.

***

## 03 - Como um Computador Executa Vários Programas &#x1F516;
* As diversas otimizações feitas no processadores modernos, como pipelining e multi-core;
* Como podemos nos comunicar com o computador por meio dos dispositivos de entrada e saída;
* Como monitores e teclados funcionam;
* Como o computador executa vários programas ao mesmo tempo por meio de multitasking.

### 01 - Lei de Moore
* O que é a **Lei de Moore**.
* Como aumentar o poder de processamento.

### 02 - Entrada e Saída
* O que é um **Pixel**.
* Como o teclado funciona.

### 03 - Placa de Vídeo
* História das placas de vídeo.

***

## 04 - Como a Memória Funciona &#x1F516;
* A função da memória cache para melhorar a performance do computador;
* Como as memórias de um computador são divididas de forma hierárquica;
* O que é o princípio da localidade;
* Qual a diferença entre processadores 32 e 64 bits, e qual é o impacto disso na hora de escolher o instalador de um programa.

### 01 - Cache - Trazer para Perto
* O que é **DRAM**.
* O que é **SRAM**.
* Como funciona o **cache** do processador.
* Como o cache funciona nos navegadores.

### 02 - Hierarquia de Memória
* Como funciona a hierarquia das memórias.
* Princípio da Localidade.

### 03 - Processador de 32 ou 64 Bits
* Diferença entre um processador de 32 Bits e 64 Bits.
* Vantagens do Processador de 64 Bits.

***

## 05 - Como os Dados são Armazenados &#x1F516;
* Como números inteiros, caracteres, listas e números decimais são armazenados na memória;
* O que são os formatos ASCII, Latin1, Unicode e qual sua relação com o UTF-8;
* A importância do contexto para o computador entender os dados que estão guardados na memória;
* Passagem de parâmetros por valor e por referência;
* Quais são os problemas inerentes aos números de ponto flutuante.

### 01 - Números Inteiros
* Como os números inteiros são representados através dos Bytes.

### 02 - Cracteres
* O que é a tabela **ASCII**.
* O que é o **UTF-8**.

### 03 - Listas
* Como funciona o endereço de memória para listas no computador.

### 04 - Números de Ponto Flutuante
* Erro do número com ponto flutuante.