# 🐍 Noções básicas de Python

## 🤔 Tipos de dados básicos

- Em Python, os tipos de dados básicos são as categorias nas quais podemos classificar os valores que utilizamos em nossos programas. 
- Compreender os diferentes tipos de dados é fundamental para trabalhar com variáveis e realizar operações em Python. 
- Os tipos de dados básicos incluem:

### 🔟 Inteiros (***int***)

- Os números inteiros são aqueles que não têm parte decimal. 
- Em Python, são representados simplesmente escrevendo o número sem aspas nem pontos decimais. 
- Por exemplo:

````sh
idade = 25
quantidade = 100
````
 

### 🔢 Flutuantes (***float***)

- Os números flutuantes, também conhecidos como números de ponto flutuante, são aqueles que têm uma parte decimal. 
- Em Python, são representados utilizando um ponto para separar a parte inteira da parte decimal. 
- Por exemplo:

````sh
preço = 9.99
altura = 1.75
````
 

### 📝 Cadeias de texto (***Strings***)

- As cadeias de texto, ou simplesmente cadeias, são sequências de caracteres encerradas entre aspas simples ('...') ou duplas ("..."). 
- São utilizadas para representar texto em Python. 
- Por exemplo:

````sh
nome = "Juan"
mensagem = '¡Hola, mundo!'
````

- Você pode incluir caracteres especiais nas cadeias utilizando o caractere de escape ``\``. 
- Por exemplo, para incluir aspas dentro de uma cadeia, você pode usar ``\'`` ou ``\"``. 
- Também pode utilizar a notação de tripla aspa (``'''...'''`` ou ``"""..."""``) para criar cadeias de várias linhas.


### 🕵️‍♂️ Booleanos

- Os valores booleanos representam os valores de verdade: **True** (verdadeiro) e **False** (falso). 
- São comumente utilizados em expressões condicionais e operações lógicas. Por exemplo:

````sh
é_maior_de_idade = True
tem_desconto = False
````

- **Tenha em mente! 🧠**
   - Os valores booleanos em Python começam com uma letra maiúscula: **True** e **False**.


## 🗃️ Variáveis

- As variáveis são contêineres que nos permitem armazenar e manipular dados em nossos programas. 
- Você pode pensar em uma variável como uma etiqueta à qual você atribui um valor específico. 
- Em Python, não é necessário declarar o tipo de dados de uma variável com antecedência, pois o Python infere o tipo de dados automaticamente com base no valor atribuído.


### ✍️ Declaração e atribuição de variáveis

- Para declarar e atribuir um valor a uma variável em Python, utilizamos o operador de atribuição `=`. 
- O nome da variável vai à esquerda do operador, e o valor que você deseja atribuir vai à direita. Por exemplo:

````sh
nome = "Juan"
idade = 25
altura = 1.75
eh_estudante = True
````

- No exemplo, declaramos e atribuímos valores às variáveis **nome**, **idade**, **altura** e **eh_estudante**. 
- O Python infere automaticamente o tipo de dados de cada variável com base no valor atribuído.
- Você também pode atribuir o mesmo valor a várias variáveis em uma única linha usando o operador de atribuição múltipla:

````sh
a = b = c = 10
````

- Neste caso, as variáveis **a**, **b** e **c** terão o valor **10**.


### 📜 Regras para nomear variáveis

- Ao nomear variáveis em Python, é importante seguir algumas regras para manter um código legível e evitar erros:
   - Os nomes das variáveis só podem conter letras (``a-z, A-Z``), números (``0-9``) e sublinhados (``_``). Não podem começar com um número.
   - O Python diferencia maiúsculas de minúsculas, então **nome** e **Nome** são variáveis diferentes.
   - Não se pode usar palavras-chave reservadas do Python como nomes de variáveis (por exemplo, **if**, **else**, **for**, **while**, etc.).
   - Recomenda-se usar nomes descritivos para as variáveis, que indiquem claramente seu propósito: **nome**, **idade**, **total_vendas**, etc.
- Seguindo essas regras, alguns exemplos de nomes de variáveis válidos são:

````sh
idade
nome_completo
total_vendas
_contador
````

- E alguns exemplos de nomes de variáveis inválidos são:

````sh
1idade   # Começa com um número
nome-completo   # Usa um hífen em vez de um sublinhado
if   # Palavra-chave reservada do Python
````

- **Tenha em mente! 🧠**
  - Escolher nomes descritivos para suas variáveis facilita a leitura e compreensão do código, tanto para você quanto para outros desenvolvedores que possam trabalhar no mesmo projeto.


## ➕ Operadores

- Os operadores são símbolos especiais que nos permitem realizar operações em variáveis e valores.
- O Python fornece diferentes tipos de operadores para realizar operações aritméticas, comparações e operações lógicas.

### 🧮 Aritméticos

- Os operadores aritméticos são utilizados para realizar operações matemáticas básicas. 
- Os principais operadores aritméticos em Python são:
   - **Soma (`+`):** soma dois valores.
   - **Subtração (`-`):** subtrai o segundo valor do primeiro.
   - **Multiplicação (`*`):** multiplica dois valores.
   - **Divisão (`/`):** divide o primeiro valor pelo segundo e devolve um resultado de tipo flutuante.
   - **Divisão inteira (`//`):** divide o primeiro valor pelo segundo e devolve um resultado de tipo inteiro (a parte decimal é descartada).
   - **Módulo (%):** devolve o resto da divisão entre o primeiro valor e o segundo.
   - **Exponenciação (`**`):** eleva o primeiro valor à potência do segundo.

````sh
a = 10
b = 3


soma = a + b   # 13
subtracao = a - b    # 7
multiplicacao = a * b    # 30
divisao = a / b   # 3.333333333
divisao_inteira = a // b   # 3
modulo = a % b   # 1
exponenciacao = a ** b   # 1000
````

### ⚖️ De comparação

- Os operadores de comparação são utilizados para comparar dois valores e devolvem um valor booleano (**True** ou **False**) segundo o resultado da comparação. 
- Os operadores de comparação em Python são:

  - **Igual a (`==`):** devolve **True** se ambos os valores são iguais.
  - **Diferente de (`!=`):** devolve **True** se os valores são diferentes.
  - **Maior que (`>`):** devolve **True** se o primeiro valor é maior que o segundo.
  - **Menor que (`<`):** devolve **True** se o primeiro valor é menor que o segundo.
  - **Maior ou igual que (`>=`):** devolve **True** se o primeiro valor é maior ou igual que o segundo.
  - **Menor ou igual que (`<=`):** devolve **True** se o primeiro valor é menor ou igual que o segundo.

````sh
a = 10
b = 3


igual = a == b   # False
diferente = a != b   # True
maior que = a > b   # True
menor que = a < b   # False
maior ou igual = a >= b   # True
menor ou igual = a <= b   # False
````


### 🤔 Lógicos

- Os operadores lógicos são utilizados para combinar expressões condicionais e avaliar múltiplas condições. 
- Os operadores lógicos em Python são:

  - **AND (and):** devolve **True** se ambas as condições são verdadeiras.
  - **OR (or):** devolve **True** se ao menos uma das condições é verdadeira.
  - **NOT (not):** inverte o valor de uma condição, devolve **True** se a condição é falsa e **False** se a condição é verdadeira.

````sh
a = 10
b = 3


resultado_and = (a > 5) and (b < 5)   # True
resultado_or = (a > 15) or (b < 5)   # True
resultado_not = not (a > 5)   # False
````

- **⚠ Importante!**
   - Python segue as regras de precedência de operadores, onde certos operadores têm prioridade sobre outros. 
   - Em geral, a precedência segue a ordem: 
     1. **Parênteses;**
     2. **Exponenciação;**
     3. **Multiplicação/Divisão;**
     4. **Soma/Subtração;**
     5. **Operadores de Comparação;**
     6. **Operadores lógicos.**