# Assíntota Vertical
A reta $x = a$ é chamada de assíntota vertical da curva $f(x)$ quando acatar algum dos casos de limites infinitos.

## Exemplos:
$f(x) = \frac{1}{x - 1}$ tem assíntota vertical $x = 1$. De fato:
$x \to 1^- \Rightarrow x \to 1, x < 1 \Rightarrow x - 1 < 0 \Rightarrow \frac{1}{x - 1} < 0 \Rightarrow \underset{x \to 1}{\lim} \frac{x}{x - 1} = -\infty$

$f(x) = \tan{x} = \frac{\sin{x}}{\cos{x}}$
Sabemos que $\cos{x} \Longleftrightarrow x = \frac{\pi}{2}$. No caso entre $-\frac{\pi}{2}$ e $\frac{\pi}{2}$, temos:
- $\underset{x \to \frac{\pi}{2}}{\lim} \tan{x} = \infty$
- $\underset{x \to -\frac{\pi}{2}}{\lim} \tan{x} = -\infty$
Por ser uma função periódica, todo múltiplo de $\frac{\pi}{2}$ será uma assíntota.
![[GraficoTan.png]]

Tendo $g(x) = \dfrac{1}{x}$, seu limite sendo infinito e sua assíntota $x = 0$.

# Assíntota Horizontal
A reta $y = L$ é chamada de assíntota horizontal quando $\underset{x \to \infty} \lim f(x) = L$ ou $\underset{x \to -\infty} \lim f(x) = L$

## Exemplo:
Para $f(x) = \frac{1}{x}$, a assíntota horizontal será $y = 0$ para $\underset{x \to \infty} \lim f(x)$

# Assíntota Obliqua
Uma função $f(x)$ tem assíntota $y = mx + b$ quando
$$\underset{x \to \infty} \lim [f(x) - (mx + b)] = 0$$