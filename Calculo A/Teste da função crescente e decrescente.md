# Teste da função Crescente/Decrescente

Seja $f$ função [[Derivadas|derivável]], se:
- $f'(x) > 0$ em um intervalo, então $f$ é crescente nesse intervalo
- $f'(x) < 0$ em um intervalo, então $f$ é decrescente nesse intervalo

## Exemplos
1. Determine onde a função $f(x) = 3x^{4}-4x^{3}-12x^{2}+5$ é crescente e onde é decrescente
$$\begin{align*}
f'(x) &= 12x^{3}-12x^{2}-24x\\
&= 12x(x^{2}- x - 2)\\
&= 12x(x-2)(x-1)\\
&= (x + 1) \cdot (12x) \cdot (x - 2)
\end{align*}$$
Raízes: $x = -1, x = 0, x = 2$

|              | $x + 1$ | $12x$ | $x - 2$ | $f'(x)$ |
| ------------ | ------- | ----- | ------- | ------- |
| $x < -1$     | -       | -     | -       | D       |
| $-1 < x < 0$ | +       | -     | -       | C       |
| $0 < x < 2$  | +       | +     | -       | D       |
| $x > 2$      | +       | +     | +       | C        |
