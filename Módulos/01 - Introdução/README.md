# 🐍 Introdução ao Python

- Python foi criado por Guido van Rossum, um programador holandês, no final dos anos 80 e início dos anos 90. 
- A primeira versão do Python, a 0.9.0, foi lançada em 1991. Guido van Rossum nomeou a linguagem em homenagem ao grupo de comédia britânico Monty Python, do qual era um grande fã. 
- O Python foi projetado com o objetivo de ser uma linguagem fácil de ler e escrever, com uma sintaxe clara e concisa. 
- Ao longo dos anos, evoluiu e ganhou popularidade até se tornar uma das linguagens de programação mais utilizadas no mundo. 


## 🧐 Características

- Python tem várias características que o tornam atraente tanto para iniciantes quanto para programadores experientes: 
	1. **Legibilidade:**
		- Python utiliza uma sintaxe clara e simples, o que facilita a leitura e compreensão do código. 
		- Utiliza indentação (espaços ou tabulações) para delimitar blocos de código, o que promove um estilo de programação estruturado e legível.
	2. **Tipagem Dinâmica:**
		- Em Python, não é necessário declarar explicitamente o tipo de dados das variáveis. 
		- Python infere automaticamente o tipo de dados com base no valor atribuído a uma variável, o que simplifica a escrita de código.
	3. **Interpretado:**
		- Python é uma linguagem interpretada, o que significa que o código é executado linha por linha em tempo real. 
		- Isso permite um ciclo de desenvolvimento rápido e facilita a depuração do código. 
	4. **Multiplataforma:**
		- Python pode ser executado em diferentes sistemas operacionais, como Windows, macOS e Linux, sem necessidade de modificar o código. 
		- Isso o torna uma linguagem versátil e portátil.
	5. **Ampla biblioteca padrão:**
		- Python vem com uma extensa biblioteca padrão que fornece uma grande quantidade de módulos e funções para realizar diversas tarefas, como manipulação de arquivos, conexão a bancos de dados, processamento de texto, entre outros. 
	6. **Comunidade ativa:**
		- Python conta com uma comunidade de desenvolvedores grande e ativa que contribui com bibliotecas, frameworks e ferramentas adicionais. 
		- Isso significa que você encontrará uma grande quantidade de recursos e suporte disponíveis.
	
	
## 💻 Aplicações

- O Python é utilizado em uma ampla gama de aplicações e domínios, alguns exemplos são:  
	1. **Desenvolvimento web:**
		- Python é amplamente utilizado no desenvolvimento web backend, com ***frameworks*** populares como **Django** e **Flask**.
	2. **Ciência de dados:**
		- Python é a linguagem preferida para análise de dados e ciência de dados devido a bibliotecas como **NumPy**, **Pandas** e **Matplotlib**. 
	3. **Inteligência artificial e machine learning:**
		- Python é a escolha principal para projetos de ***IA ***e ***machine learning***, graças a bibliotecas como **TensorFlow** e **Scikit-learn**. 
	3. **Automatização de tarefas:**
		- Python pode ser utilizado para automatizar tarefas repetitivas, como processamento de arquivos, web scraping e testes de software.
	4. **Desenvolvimento de jogos:**
		- Python é utilizado no desenvolvimento de jogos simples, especialmente com bibliotecas como **Pygame**. 


## 🔧 Configuração do ambiente de desenvolvimento

- Um ambiente de desenvolvimento integrado (IDE) é uma ferramenta que facilita a escrita, execução e depuração de código. 
- Embora você possa usar um editor de texto simples para escrever código Python, um IDE oferece recursos adicionais que melhoram a produtividade do desenvolvimento. 
- Alguns IDEs populares para Python são: 
	- **PyCharm:** é um IDE poderoso e completo desenvolvido pela JetBrains. Oferece funções avançadas, como autocompletar código, depuração, integração com sistemas de controle de versão e mais. 
	- **Visual Studio Code:** é um editor de código desenvolvido pela Microsoft. Com a extensão de Python, se torna um IDE leve e versátil para o desenvolvimento de Python. 
	- **Sublime Text:** é um editor de texto rápido e personalizável que suporta programação em Python através do uso de plugins. 

``Para começar, recomendamos usar o Visual Studio Code, pois é leve, fácil de usar e tem uma grande quantidade de extensões disponíveis.``

- Outra alternativa é o uso de Jupyter Notebooks, uma aplicação web interativa que permite criar e compartilhar documentos que contêm código ao vivo, equações, visualizações e texto explicativo. É comumente usado em ciência de dados, análise e aprendizado de Python. 
- Para usar Jupyter Notebook: 
	- Abra a linha de comando (Terminal no macOS/Linux ou Prompt de Comando no Windows). 
	- Execute o seguinte comando para instalar Jupyter Notebooks: ``pip install jupyter notebooks``.
	- Uma vez instalado, execute o seguinte comando para iniciar Jupyter Notebook: ``jupyter notebooks``.
	- Uma janela do navegador será aberta com a interface do **Jupyter Notebook**.
	- Clique em **"New"** e selecione **"Python 3"** para criar um novo caderno (notebook).
	
- **Importante!**
	- **Jupyter Notebook** é uma excelente ferramenta para explorar, experimentar e compartilhar código Python de maneira interativa.


## 👨‍💻 Seu primeiro programa Python

### "Olá Mundo"

- É uma tradição no mundo da programação começar com um programa simples chamado "Olá Mundo". 
- Este programa simplesmente mostra a mensagem "Olá Mundo" na tela. 

- Abra seu IDE ou editor de texto preferido e crie um novo arquivo.
- Nomeie o arquivo como **"ola_mundo.py"**. 
- A extensão **".py"** indica que é um arquivo de Python. 
- No arquivo, escreva o seguinte código: ``print ("Olá, Mundo!")``.
- Salve o arquivo e execute o programa. 
- Se estiver utilizando um **IDE**, procure a opção **"Run"** ou **"Execute"**. 
- Você verá que a mensagem **"Olá, Mundo!"** é impressa na tela.


## 👨‍🏫 Conceitos básicos da sintaxe em Python

- Antes de mergulharmos em conceitos mais avançados, é importante familiarizar-se com alguns aspectos básicos da sintaxe do Python.

### Indentação

- No Python, a indentação (espaços ou tabulações no início de uma linha) é utilizada para delimitar blocos de código. 
- Diferente de outras linguagens que utilizam chaves ou palavras-chave, o Python utiliza a indentação para determinar o escopo das declarações. 
- Por exemplo: 

````sh
if condition:
    # Bloco de código se a condição for verdadeira
    instrucao1
    instrucao2

else:
    # Bloco de código se a condição for falsa
    instrucao3
    instrucao4
````

- **Importante:** É fundamental manter uma indentação consistente em todo o código para evitar erros de sintaxe.
 

### Comentários

- Os comentários são linhas de texto no código que são ignoradas pelo interpretador do Python. 
- Eles são utilizados para explicar ou documentar o código. 
- No Python, os comentários de uma única linha começam com o símbolo **#**, enquanto os comentários de várias linhas são delimitados por três aspas **"""** . 
- Por exemplo:

````sh
# Este é um comentário de uma única linha

"""
Este é um comentário
de várias linhas
"""
````
 

### Sensibilidade a maiúsculas e minúsculas

- Python distingue entre maiúsculas e minúsculas. 
- Portanto, **variável**, **Variável** e **VARIÁVEL** são consideradas variáveis diferentes.

 

### Ponto e vírgula

- Diferente de outras linguagens, o Python não requer o uso de ponto e vírgula **(;)** ao final de cada instrução. 
- No entanto, se você desejar escrever várias instruções em uma única linha, pode separá-las com um ponto e vírgula. Por exemplo:

````sh
instrucao1; instrucao2; instrucao3
````
 

### Uso de parênteses

- Os parênteses são utilizados para agrupar expressões, definir funções e realizar chamadas a funções. 
- Por exemplo:

````sh
resultado = (a + b) * c
````
