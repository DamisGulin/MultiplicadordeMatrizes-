# Multiplicação de Matrizes

A multiplicação de matrizes é uma operação matemática que combina duas matrizes para produzir uma nova matriz. Essa operação é fundamental em várias áreas, como álgebra linear, computação gráfica e modelagem matemática.

## Como Funciona

Para multiplicar duas matrizes \( A \) e \( B \), a matriz \( A \) deve ter dimensões \( m \times n \) e a matriz \( B \) deve ter dimensões \( n \times p \). O resultado da multiplicação será uma nova matriz \( C \) com dimensões \( m \times p \).

Seja:

$$
A = \begin{pmatrix}
a_{11} & a_{12} & \ldots & a_{1n} \\
a_{21} & a_{22} & \ldots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \ldots & a_{mn}
\end{pmatrix}
$$

$$
B = \begin{pmatrix}
b_{11} & b_{12} & \ldots & b_{1p} \\
b_{21} & b_{22} & \ldots & b_{2p} \\
\vdots & \vdots & \ddots & \vdots \\
b_{n1} & b_{n2} & \ldots & b_{np}
\end{pmatrix}
$$

A multiplicação \( C = A \cdot B \) é dada por:

$$
C = \begin{pmatrix}
c_{11} & c_{12} & \ldots & c_{1p} \\
c_{21} & c_{22} & \ldots & c_{2p} \\
\vdots & \vdots & \ddots & \vdots \\
c_{m1} & c_{m2} & \ldots & c_{mp}
\end{pmatrix}
$$

onde cada elemento \( c_{ij} \) é calculado como:

$$
c_{ij} = \sum_{k=1}^{n} a_{ik} \cdot b_{kj}
$$

ou seja, \( c_{ij} \) é a soma do produto dos elementos da \( i \)-ésima linha de \( A \) com os elementos da \( j \)-ésima coluna de \( B \).

## Exemplo

Se temos as matrizes:

$$
A = \begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}, \quad
B = \begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
$$

A multiplicação \( C = A \cdot B \) é:

$$
C = \begin{pmatrix}
(1 \cdot 5 + 2 \cdot 7) & (1 \cdot 6 + 2 \cdot 8) \\
(3 \cdot 5 + 4 \cdot 7) & (3 \cdot 6 + 4 \cdot 8)
\end{pmatrix} = \begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

## Propriedades

1. **Não Comutativa**: Em geral, \( A \cdot B \neq B \cdot A \).
2. **Associativa**: \( (A \cdot B) \cdot C = A \cdot (B \cdot C) \).
3. **Distributiva**: \( A \cdot (B + C) = A \cdot B + A \cdot C \).

A multiplicação de matrizes é uma operação essencial, permitindo resolver sistemas de equações lineares, realizar transformações em espaços vetoriais e muito mais.
