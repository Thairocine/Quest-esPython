# Questões Python  

_Repositório para os alunos de Ciência da Computação da UFCG resolverem questões sobre Python._ 

## Principais Assuntos 

- Entrada e Saida 
- Programas e Sequências 
- Condicionais 
- Laços For 
- Laços While
- Funções 
- Tuplas
- Listas
- Dicionários 

![Primeiros Passos](https://github.com/Thairocine/Quest-esPython/blob/main/download.gif)   

## Entrada e Saída

_Para entender melhor sobre entrada e saída de dados é necessário saber como o computador pode receber sua entrada, que pode ser atráves de linha de comando, teclado, entre outros. Em Python, a principal forma de um programa receber seus dados é por meio da funcionalidade "input", que permite o usuário a informar alguns dados que deseja._ 

A função *input* do Python recebe um parâmetro que é uma string. A string é geralmente chamada de prompt porque contém um texto informativo que informa o usuário a digitar algum dado. Para entender melhor, verifique o exemplo abaixo: 


![](https://github.com/Thairocine/Quest-esPython/blob/main/giphy%20(1).gif)

Podemos perceber através desse gif que através do input, o usuário pode digitar um dado. 



Entretanto, você deve está se perguntando o que seria o "nome = input()" ? Bom, o "nome" corresponde a como iremos chamar nossa variável, o "=" o que iremos atribuir a ela. 

Veja mais exemplos de variáveis com input, abaixo: 

nome = input() 
cidade = input() 
idade = input() 

Acredito que nessa altura do campeonato, você esteja se perguntando como o Python através das variáveis e do input ler dados de entrada como números reais, números inteiros, booleanos ( True ou False) e textos? 

Para ler dados com números inteiros precisamos do int, como exemplo, podemos escrever o seguinte programinha:  

idade = int(input()) 

_Mas o que seriam os inteiros?_ 

_São os números que são positivos, ou negativos, ou zero, sem parte decimal. Por exemplo, os números 5 , -5 , 0 , 1 , 4._ 



Para ler dados com números reais precisamos do float, como exemplo, podemos escrever o seguinte programinha: 

preco_pizza = float(input())  

Mas o que seriam números reais? 

- Números Naturais (N): N = {0, 1, ..}
- Números Inteiros (Z): Z= {-2, -1, 0, 1, 2...}
- Números Racionais (Q): Q = {...,1/2, 3/4, –5/4...}
- Números Irracionais (I): I = {...,√2, √3,√7, 3,141592....}

