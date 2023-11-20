# Circunferência

## Definição
Dada uma [[Cônicas|cônica]] de centro $(h, k)$, ela terá todos os seus pontos à uma distancia $R$ desse mesmo centro, formando um circulo.

## Equação Geral
$$(x - h)^{2}+ (y - k)^{2}= R^2$$
Expandindo essa formula temos:
$$x^{2}- 2hx + h^{2}+y^{2}- 2ky + k^{2}=R^{2}$$
## Teoremas
- ### 1.1 Circunferência formada por 3 pontos.
	A equação da circunferência que passa pelos pontos $(x_1,y_1),(x_2,y_2),(x_3,y_3)$ não colineares é obtido pela solução da determinante
	$$\begin{bmatrix}x^{2}+y^{2} & x & y & 1 \\ x^2_{1}+y^2_{1} & x_{1} & y_1 & 1 \\ x^2_2+y^2_2 & x_2 & y_2 & 1 \\ x^2_3+y^2_3 & x_3 & y_3 & 1\end{bmatrix}$$
	ou, substituindo todos os pontos na equação geral e resolvendo um sistema de equações.

## Parametrização da Circunferência
Dado um ponto $P(x,y)$ que está à um ângulo $\phi$ do centro $(h,k)$, temos que:
$$\left\{ \begin{align*}
x &= h + R\cos{\phi}\\
y&= k + R\sin{\phi}
\end{align*} \right.$$
## Exemplos e Exercícios
- ### Obtenha a equação da circunferência que passa por $A(1, 2), B(0, -1), C(-3, 0)$
$$\left\{ \begin{align*}
(1-h)^{2}+(2-k)^{2}&= R^{2}\\
1 - 2h + h^{2}+ 4 - 4k + k^{2}&= R^{2}\\
h^{2}- 2h + k^{2}- 4k + 5 &= R^{2}
\end{align*} \right.\ \  \ (A)$$
$$\left\{ \begin{align*}
(0 - h)^{2}+(-1 -k)^{2}&= R^2\\
h^{2}+ k^{2}+ 2k + 2 &= R^{2}\\
\end{align*} \right.\ \ \ (B)$$
$$\left\{ \begin{align*}
(-3 -h)^{2}+ (0 - k)^{2} &= R^{2}\\
9 + 6h + h^{2}+ k^{2}&= R^{2}\\
h^{2}+ 6h + k^{2}+9 &= R^{2}\\
\end{align*} \right. \ \ \ (C)$$
Resolvendo o sistema de equações de $(A)$ e $(B)$, chegamos à $h + 3k = 2$. Fazendo o mesmo para $(A)$ e $(C)$ temos $-2h -k = 1$. Resolvendo esse mesmo sistema de equação temos que $k = 1, h = -1, R^{2}= 5$. Logo, a equação da circunferência será $(x - 1)^{2} + (y + 1)^{2}= 5$


## Referencias
1. 

