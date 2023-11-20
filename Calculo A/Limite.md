# Limite
#Calculo
Vamos iniciar a introdução de limite de através de um exemplo. Considere a $f(x) = x^2 - x + 2$. A medida que calculamos valores para $x$ cada vez mais próximos de $2$, o resultado dessa função se aproximará de 4. Sabendo disso, pode-se dizer que o limite de $f(x)$ quando $x \to 2$ é igual a $4$

## Notação: 
- $\underset{x \to 2}{\lim} (x^2 - x + 2)$

## Definição:
Suponha $f(x)$ uma função definida que possa ser calculada em valores próximos à um valor $a$, não sendo necessário que $f(a)$ seja um valor possível de calcular. Escrevemos $\underset{x\to a}{\lim} f(x) = L$ que significa **"O limite de $f(x)$, quando $x$ tende à $a$ é igual a $L$"**. Simbolicamente:
$$\begin{matrix}\underbrace{a \to x \Longleftrightarrow f(x) \to L}\\ \underset{x \to a}{\lim} f(x) = L\end{matrix}$$
## Exemplo:
- #### Calcule $\underset{x\to a}{\lim} \frac{x - 1}{x^2 - 1}$
Nessa função, se $x = 1$, teremos $\frac{0}{0}$, que é indefinido, então vamos calcular para valores cada fez mais próximos de $1$.
$$\begin{bmatrix} f(0.9) & \cdots & 0.52631 \\ f(0.99) & \cdots & 0.50251 \\ f(0.999) & \cdots & 0.50025 \\ f(1.001) & \cdots & 0.49975 \\ \end{bmatrix}$$
Logo, o limite será 0.5. De outra forma, note:
$$\dfrac{x - 1}{x^2 - 1} = \dfrac{(x - 1) \cdot 1}{(x - 1) \cdot (x + 1)}, |x| \neq 1. = \dfrac{1}{x + 1}$$