# Limites no Infinito
Dada a função $f(x) = \frac{x^{2} - 1}{x^{2} + 1}$. Note que na medida em que $x \to \infty$, $f(x)$ se aproxima cada vez mais de $1$. Logo, dizemos que seu [[Limite]] será $\underset{x \to \infty} \lim f(x) = 1$.

## Definição
Seja $f$ uma função definida em $(a, \infty)$. Escrevemos então $\underset{x \to \infty} \lim f(x) = L$ para dizer que os valores de $f(x)$ ficam arbitrariamente próxima de $L$ na medida que $x$ fica arbitrariamente gigante.

## Teorema
Considere $f(x) = \frac{1}{x^{r}}, r > 0$ e racional:
- Vale sempre $\underset{x \to \infty} \lim \frac{1}{x^{r}}= 0$
- Se $f(x)$ esta bem definido nos valores negativos, então $\underset{x \to -\infty} \lim f(x) = 0$

## Exemplo
Calcule $\underset{x \to \infty} \lim \dfrac{3x^{2}- x - 2}{5x^{2}+ 4x + 1}$
$$\begin{align*}
\lim_{x \to \infty} \dfrac{3x^{2}- x - 2}{5x^{2}+ 4x + 1} &= \dfrac{\frac{3x^{2}- x - 2}{x^{2}}}{\frac{5x^{2}+ 4x + 1}{x^{2}}}\\
&= \underset{x \to \infty} \lim\dfrac{3 - \frac{1}{x} - \frac{2}{x^{2}}}{5 + \frac{4}{x} + \frac{1}{x^{2}}}\\
&= \dfrac{\underset{x \to \infty}\lim (3 - \frac{1}{x} - \frac{2}{x^{2}})}{\underset{x \to \infty} \lim (5 + \frac{4}{x} + \frac{1}{x^{2}})}\\
&= \dfrac{3}{5} = 0.6 
\end{align*}$$

