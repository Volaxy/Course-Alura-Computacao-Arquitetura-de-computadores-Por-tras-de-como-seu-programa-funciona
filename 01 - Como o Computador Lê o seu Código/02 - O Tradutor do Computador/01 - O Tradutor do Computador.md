Supondo a seguinte linha de código: `let c = a + b`.

O computador irá interpretar da seguinte forma:
* Ele vai ler um caractere por vez, vai ler l, e, os caracteres com espaço, as letras, os símbolos especiais e até caracteres especiais invisíveis de quebra de linha.
* Feito isso, depois que ele leu um caractere por vez, interpretou a coisa como texto, ele vai identificar as palavras, identificar conjuntos de caracteres – por exemplo let, e tentar identificar quais são os significados desses caracteres.
* Então ele vai identificar os nomes de variáveis - que `c`, `a` e `b` são nomes de variáveis, ele vai identificar *let*, a sequência `l` e `t` significa está fazendo declaração de uma nova variável.
* Tem os símbolos igual e mais, então ele sabe agora que vai ter que fazer uma atribuição para uma variável e vai somar dois valores, dessa forma ele pega o significado de todos os conjuntos de símbolos e nesse meio tempo identifica erros.
* Vê se as variáveis que você está usando já foram declaradas antes, identifica quais são os tipos das variáveis que você está usando, vê se A é um texto ou número e coisas do tipo - ele faz todo esse processo de verificação, de tentar entender o que que esse conjunto de caracteres significa.
* A partir disso ele começa a produzir o código de máquina - tem uma coisa que ele vai fazer, ele vai usar a variável A, precisa do código de máquina para pegar o valor de A.
* Na hora de executar depois pega o valor de A, que nosso exemplo vai ter o valor de 7, em seguida ele também vai usar o B e vai somar o valor de A com o valor de B, ele usa o comando de código de máquina de soma.
* Em seguida ele soma o valor de A com o valor de B, que vai dar 9.
* Em seguida, depois de somados os valores de A e B, ele vai ter que criar essa nova variável C e guardar o resultado da soma, ele usa esse terceiro comando de código de máquina, que é guarda C.

Tanto instruções, quanto para quem eles estão realizando a instrução, vão ser transformadas em conjunto de zeros e uns, vão ser agrupados numa coisa só e vai virar o código de máquina final que pode dar para o computador executar.