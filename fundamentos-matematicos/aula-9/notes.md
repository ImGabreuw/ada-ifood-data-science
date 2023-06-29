# Fundamentos matemáticos | Matrizes, determinantes e sistemas | Aula 09

## Matrizes

Uma matriz é uma tabela retangular de números ou expressões dispostos em linhas e colunas. Ela é denotada por letras maiúsculas. Por exemplo, uma matriz $A$ com $m$ linhas e $n$ colunas é representada da seguinte forma:

$$
A = \begin{bmatrix}
a_{11} & a_{12} & \ldots & a_{1n} \\
a_{21} & a_{22} & \ldots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \ldots & a_{mn} \\
\end{bmatrix}
$$

## Determinantes

O determinante é uma propriedade associada a matrizes quadradas (com o mesmo número de linhas e colunas). Ele é calculado usando a regra de Sarrus para matrizes 3x3 ou a regra de Laplace para matrizes de ordem maior.

O determinante de uma matriz $A$ é denotado por $|A|$ ou $\text{det}(A)$. Ele fornece informações sobre as propriedades e comportamento do sistema linear associado à matriz.

## Sistemas de Equações

Um sistema de equações lineares é um conjunto de equações lineares com as mesmas variáveis. Pode ser representado por meio de matrizes. Por exemplo, um sistema de $m$ equações lineares com $n$ variáveis pode ser representado como:

$$
\begin{align*}
a_{11}x_1 + a_{12}x_2 + \ldots + a_{1n}x_n &= b_1 \\
a_{21}x_1 + a_{22}x_2 + \ldots + a_{2n}x_n &= b_2 \\
\vdots \\
a_{m1}x_1 + a_{m2}x_2 + \ldots + a_{mn}x_n &= b_m \\
\end{align*}
$$

Onde $x_1, x_2, \ldots, x_n$ são as variáveis desconhecidas, $a_{ij}$ são os coeficientes das variáveis e $b_1, b_2, \ldots, b_m$ são os termos constantes.

## Solução de Sistemas Lineares

A solução de um sistema de equações lineares pode ser encontrada por meio de diferentes métodos, como eliminação de Gauss, substituição, matriz inversa, entre outros. Esses métodos envolvem manipulações algébricas das equações e operações nas matrizes associadas.

A solução de um sistema pode ser um conjunto vazio (sistema inconsistente), um único ponto (sistema consistente e determinado) ou um conjunto infinito de pontos (sistema consistente e indeterminado).
