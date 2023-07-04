# Cálculo Básico | Introdução | Aula 01

> ## **Função**

### **Produto cartesiano**

O produto cartesiano serve para enunciar todas as relações possível entre 2 conjuntos, ou seja, são todos os pares ordenados de um dado conjunto A e B:

$$
Conjuntos \; A, B \\
\text{Produto cartesiano:} A \times B = \{(a, b) | a \in A; b \in B\}
$$

Veja o exemplo abaixo:

$$
A = \{1, 2, 3\} \\
B = \{4, 6\} \\
A \times B = \{(1, 4); (1, 6); (2, 4); (2, 6); (3, 4); (3, 6)\}
$$

### **Relação**

Uma relação $R$ entre os conjuntos $A$ e $B$ será uma função se ela satisfazer a seguinte propriedade:

$$
\forall a \in A \exists b \in B : (a, b) \in R
$$

Após a definição formal de uma função, precisamos conhecer a sua representação:

$$
f: A \to B \\
a \mapsto b \\
\\
\therefore \\
f(a) = b
$$

Sendo $A$ o domínio de $f$ e $B$ o contradomínio de $f$. Já a imagem da função $f$ é um subconjunto de $B$ ($Im \subseteq B$) e pode ser definido da seguinte forma:

$$
Im(f) = \{b \in B : \exists a \in A \;com\; f(a) = b\}
$$

**OBS**: todos os elementos de $A$ (domínio) devem ser mapeados (ter correspondentes em $B$), mas nem todos os elementos de $B$ precisam ser mapeados.

### **Funções injetoras, sobrejetora e bijetora**

Uma função $f: A \to B$ é denominada **injetora** se cada elemento em $A$ é mapeado para um elemento diferente em $B$. Matematicamente, isso significa que para todo $x_1, x_2 \in A$, se $x_1 \neq x_2$, então $f(x_1) \neq f(x_2)$.Podemos representar uma função injetora usando a seguinte notação:

$f: A \rightarrow B$ é injetora se $\forall x_1, x_2 \in A, (x_1 \neq x_2) \Rightarrow (f(x_1) \neq f(x_2))$

Uma função $f: A \to B$ é chamada **sobrejetora** se cada elemento em $B$ possui pelo menos um elemento correspondente em $A$. Matematicamente, isso significa que para todo $y \in B$, existe um $x \in A$ tal que $f(x) = y$. Podemos expressar uma função sobrejetora da seguinte forma:

$f: A \rightarrow B$ é sobrejetora se $\forall y \in B, \exists x \in A$ tal que $f(x) = y$

Uma função $f: A \to B$ é dita **bijetora** se ela é tanto injetora quanto sobrejetora, ou seja, cada elemento em $A$ é mapeado para um elemento diferente em $B$ e cada elemento em $B$ possui pelo menos um elemento correspondente em $A$.Podemos escrever a definição de uma função bijetora da seguinte maneira:

$f: A \rightarrow B$ é bijetora se ela é injetora e sobrejetora, ou seja:

- Para todo $x_1, x_2 \in A$, se $x_1 \neq x_2$, então $f(x_1) \neq f(x_2)$
- Para todo $y \in B$, existe um $x \in A$ tal que $f(x) = y$
