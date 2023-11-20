# Derivação Implícita

## Definição
Dado uma função cujo não seja possivel escrever-la no formato $y = f(x)$, temos que sua [[Derivadas|derivada]] será calculada substituindo $y$ por uma função $f(x)$ e deriva-se os dois "lados" e manipula-se a equação para encontrar $f'(x)$.

### Ex: Derive $x^{3}+y^{3}= 6xy$
$$\begin{align*}
x^{3}+y^{3}&= 6xy\\
x^{3}+ [y(x)]^{3}&= 6x\cdot f(x)\\
\dfrac{d}{dx}\Big(x^{3}+ [y(x)]^{3}\Big) &= \dfrac{d}{dx}\Big(6 \cdot x \cdot [y(x)]\Big)\\
\dfrac{d}{dx}x^{3}+ \dfrac{d}{dx}[y(x)]^{3}&= y(x) \cdot \dfrac{d}{dx}6x + 6x \dfrac{d}{dx}y(x)\\
3x^{2}+ 3[y(x)]^{2}\cdot \dfrac{d}{dx}y(x) &= 6 \cdot [y(x)] + 6x[y'(x)]\\
3[y(x)]^{2}\dfrac{d}{dx}[y(x)] - 6x \dfrac{d}{dx}[y(x)] &= 6\cdot[y(x)] - 3x^{2}\\
\dfrac{d}{dx}y(x) \cdot (3[y(x)]^{2}- 6x) &= 6[y(x)] - 3x^{2}\\
\dfrac{d}{dx}y(x) &= \dfrac{6[y(x)] - 3x^{2}}{3[y(x)]^{2}- 6x}
\end{align*}$$

