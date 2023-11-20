# Aproximação Linear
## Definição
Dada uma função $f(x)$ [[Derivadas|derivável]] em $x = a$, podemos escrever a reta tangente à $f(a)$ no ponto $(a, f(a))$ por
$$L(x) = f'(a) \cdot (x-a) +f(a)$$
de modo que
$$f(x) \approx f'(a) \cdot (x-a) + f(a)$$
Assim, $L(x)$ é chamado de aproximação linear pela reta tangente de $f$ em $a$

## Exemplos e Exercícios
- Encontre a linearização de $f(x) = \sqrt{x + 3}$ em $a = 1$ e use-a para aproximar os valores de $\sqrt{3.98}$ e $\sqrt{4.05}$
	$$\begin{align*}
f(x) &=  (x + 3)^{\frac{1}{2}}\\
f'(x) &= \dfrac{1}{2\sqrt{x + 3}}\\
f(1) &= 2\\
f'(1) &= \frac{1}{4}\\
\Rightarrow L(x) &= \frac{1}{4}\cdot (x - 1) + 2 = \frac{x + 7}{4}\\
\sqrt{3.98} \approx L(0.98) &= \frac{7.98}{4}=  1.995  \\
\sqrt{4.95} \approx L(1.05) &= \frac{8.05}{4}=2.0125
\end{align*}$$

