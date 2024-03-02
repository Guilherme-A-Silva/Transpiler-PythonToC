

![Transpilador](https://devopedia.org/images/article/19/7689.1528048234.png)

--
Tem que Suportar PELO MENOS
Declaraçao/ atribuiçao de Valores e Variaveis ✅
Expressoes aritmeticas com os 4 operadores ✅
Um comando condificonal (if/else ou switch/case) ✅
um comando de repetiçao(for, while ou do while/repeat until); 🚫
Expressoes lógicas com E e OU;✅
Declaraçao e chamada de funçao com parametros posicionais 🚫
obs: Reconhece float se usar virgula

# Documento Transpilador

Abordagem ascendente com analisador lexico. <br>
Lin para o repositorio fonte e intruçoes para executalo <br>
Linguagem de Origem: Python <br>
Linguagem de destino: C <br>
Justificativa: O Transpilador de Python para C é uma ferramenta valiosa para ajudar alunos do
curso a entenderem e visualizarem seus códigos em C, especialmente quando
professores utilizam essa linguagem em sala de aula. Essa abordagem suaviza a
transição dos conceitos aprendidos em Python para C, promovendo um ambiente de
aprendizado inclusivo. Percebemos isso após uma conversa presencial com o
professor.
 <br>

#Tokens Suportados <br>

```c++

tokens = (
    'NUMBER',
    'PLUS',
    'MINUS',
    'TIMES',
    'DIVIDE',
    'LPAREN',
    'RPAREN',
    'GREATER',
    'LESS',
    'EQUALS',
    'IF',
    'ELSE',
    'PRINT',
    'COLON',
    'COMMA',
    'STRING',
    'NAME',
    'AND',
    'OR',
)

```
