# Fundamentos matemáticos | Análise combinatória | Aula 06

## Permutação

A permutação é uma forma de arranjar um conjunto de elementos em uma ordem específica. Ela representa todas as possíveis maneiras de organizar esses elementos.

A fórmula para calcular o número de permutações de um conjunto de \(n\) elementos é dada por:

$$
P(n) = n!
$$

Onde \(n!\) (lê-se "n fatorial") é o produto de todos os números inteiros positivos de 1 a \(n\).

Por exemplo, se tivermos um conjunto de 4 elementos, o número de permutações possíveis será:

$$
P(4) = 4! = 4 \times 3 \times 2 \times 1 = 24
$$

## Permutação com Repetição

A permutação com repetição é uma variação da permutação em que há elementos repetidos no conjunto. Isso significa que algumas das permutações serão idênticas.

A fórmula para calcular o número de permutações com repetição de um conjunto com \(n\) elementos, onde há \(n_1\) elementos do tipo 1, \(n_2\) elementos do tipo 2, e assim por diante, é dada por:

$$
P(n_1, n_2, \ldots, n_k) = \frac{{(n_1 + n_2 + \ldots + n_k)!}}{{n_1! \cdot n_2! \cdot \ldots \cdot n_k!}}
$$

Por exemplo, se tivermos um conjunto com 6 elementos, sendo 2 elementos do tipo A, 2 elementos do tipo B e 2 elementos do tipo C, o número de permutações com repetição será:

$$
P(2, 2, 2) = \frac{{(2 + 2 + 2)!}}{{2! \cdot 2! \cdot 2!}} = \frac{{6!}}{{2! \cdot 2! \cdot 2!}} = \frac{{720}}{{8}} = 90
$$

Isso significa que há 90 maneiras diferentes de organizar os 6 elementos, levando em consideração as repetições.

Certamente! Aqui está uma explicação dos conceitos de arranjo simples e princípio multiplicativo usando Markdown com LaTeX:

## Arranjo Simples

O arranjo simples é uma forma de selecionar um subconjunto ordenado de elementos de um conjunto maior. Ele leva em consideração tanto a seleção dos elementos quanto a ordem em que eles são dispostos.

A fórmula para calcular o número de arranjos simples de \(n\) elementos tomados \(k\) a \(k\) (onde \(n\) é o tamanho do conjunto e \(k\) é o número de elementos selecionados) é dada por:

$$
A(n, k) = \frac{{n!}}{{(n-k)!}}
$$

Por exemplo, se tivermos um conjunto com 5 elementos e quisermos selecionar 3 elementos em uma ordem específica, o número de arranjos simples será:

$$
A(5, 3) = \frac{{5!}}{{(5-3)!}} = \frac{{5!}}{{2!}} = \frac{{5 \times 4 \times 3!}}{{2 \times 1!}} = 60
$$

Isso significa que há 60 maneiras diferentes de selecionar 3 elementos distintos e organizá-los em uma ordem específica.

## Princípio Multiplicativo

O princípio multiplicativo é uma regra que descreve a contagem de maneiras de realizar múltiplas escolhas independentes. Ele afirma que, se uma tarefa pode ser dividida em várias etapas independentes, o número total de maneiras de realizar a tarefa é o produto dos números de escolhas em cada etapa.

Por exemplo, se você tem \(n\) opções para a primeira etapa, \(m\) opções para a segunda etapa e \(p\) opções para a terceira etapa, o número total de maneiras de realizar as três etapas será \(n \times m \times p\).

Por exemplo, suponha que você tem 3 camisas diferentes, 2 calças diferentes e 4 sapatos diferentes. Usando o princípio multiplicativo, o número total de combinações possíveis que você pode criar com uma camisa, uma calça e um par de sapatos é:

$$
3 \times 2 \times 4 = 24
$$

Isso significa que existem 24 combinações diferentes possíveis ao escolher uma camisa, uma calça e um par de sapatos.
