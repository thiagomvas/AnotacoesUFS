# Integrais definidos
Criado em: 2023-11-18 : 09:15

## Definição
Integrais definidas é o calculo da area sob a curva de uma função, que podem representar o valor acumulado de uma função mudando em relação ao tempo, que tem aplicações na física.

Seja $f : [a, b] \to \mathbb{R}, f(x) > 0$. Tome $x_{0} = a, x_{n} = b, \frac{b-a}{h}=\Delta x$, onde $\Delta x$ é o intervalo entre cada retângulo. Temos então
$$\begin{align*}
x_{0} &= a\\
x_{1}&= x_{0} + \Delta x\\
x_{2}&= x_{1} + \Delta x\\
\vdots\\
x_{n-1}&= x_{n-2}+ \Delta x\\
x_{n}&= x_{n-1}+ \Delta x =b\\
\end{align*}$$
![[Curva para integrar.jpg]]
Assim, temos que a area será
$$\begin{align*}
A = R_{n}&=  f(x_{1})\Delta x+f(x_{2})\Delta x+\cdots+f(x_{n})\Delta x\\
&= \sum_{i = 1}^{n} f(x_{i})\Delta x\\
&= \underset{n \to \infty} \lim R_{n}\\
&= \int_{a}^{b}f(x) dx\\
\end{align*}$$


## Notação
$$\int_{a}^{b}f(x) dx$$
## Calculando integrais definidos
Utilizaremos $f(x) = e^{-x}, x \in [0, 2]$ como exemplo. Isto é, queremos $\int_{0}^{2}e^{-x}dx$  
1. Encontre a [[Primitivas|primitiva]] de $f(x)$.
$$F(x) = \int f(x)dx = \int e^{-x}dx=-e^{-x} + C$$
2. Calcule $F(a)$ e $F(b)$, isto é, $F(0), F(2)$.
$$\begin{align*}
F(0) &= -e^{-0}=-1 + C\\
F(2)&= -e^{-2} + C
\end{align*}$$
3. Subtraia $F(b) - F(a)$, isto é, $F(2) - f(0)$
$$\begin{align*}
F(2) - F(0) &= -e^{-2}+C - (-1 + C)\\
&= -e^{-2}+ 1\\
&= 1 - e^{-2}
\end{align*}$$
## Referencias
1. 

