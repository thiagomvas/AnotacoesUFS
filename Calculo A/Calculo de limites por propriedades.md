# Propriedades de Limites
Suponha $f$ e $g$ funções, $c$ um numero real e que os [[Limite|limites]] $\underset{x \to a}{\lim} f(x) = L_1$ e $\underset{x \to a}{\lim} g(x) = L_2$ . Então, são validas as seguintes propriedades:

## Propriedades básicas: 
- ### **Limite da soma de funções:** $\underset{x \to a}{\lim} ( f(x) + g(x)) = \underset{x \to a}{\lim}f(x) + \underset{x \to a}{\lim}g(x)$
- ### **Limite da subtração de funções:** $\underset{x \to a}{\lim} (f(x) - g(x)) = \underset{x \to a}{\lim} f(x) - \underset{x \to a}{\lim}g(x)$
- ### **Limite do produto de função com numero real:**  $\underset{x \to a}{\lim} c \cdot f(x) = c \cdot \underset{x \to a}{\lim} f(x)$  
- ### **Limite do produto de duas funções:** $\underset{x \to a}{\lim} f(x) \cdot g(x) = (\underset{x \to a}{\lim} f(x)) \cdot (\underset{x \to a}{\lim} g(x))$
- ### **Limite da divisão de funções:** $\underset{x \to a}{\lim} \dfrac{f(x)}{g(x)} = \dfrac{\underset{x \to a}{\lim} f(x)}{\underset{x \to a}{\lim} g(x)}, L_2 \neq 0$
- ### **Limite da função com expoente:** $\underset{x \to a}{\lim} [f(x)]^n = [\underset{x \to a}{\lim} f(x)]^n$
## Utilização das propriedades acima:
Sabendo que $\underset{x \to a}{\lim} f(x) = 1, \underset{x \to a}{\lim} g(x) = 5, \underset{x \to a}{\lim} h(x) = 3$, calcule o limite $\underset{x \to a}{\lim} (4f(x) - \frac{2 \cdot h(x)}{3 \cdot g(x)})$
$$\begin{align*}
\lim_{x \to a} \left (4 \cdot f(x) - \dfrac{2 \cdot h(x)}{3 \cdot g(x)} \right ) =&  \lim_{x \to a} 4 \cdot f(x) - \dfrac{\underset{x \to a}{\lim} 2 \cdot h(x)}{\underset{x \to a}{\lim} 3 \cdot g(x)} \\
=& \ 4 \cdot \underset{x \to a}{\lim} f(x) - \dfrac{2 \cdot \underset{x \to a}{\lim} h(x)}{3 \cdot \underset{x \to a}{\lim} g(x)} \\
=& \ 4 \cdot 1 - \dfrac{2 \cdot 3}{3 \cdot 5} \\
=& \ 4 - \dfrac{2}{5} \\
=& \ 3.6
\end{align*}$$
## Regra da substituição direta
Se $f(x)$ é um polinômio ou uma função racional e $f(a)$ existe, então $\underset{x \to a}{\lim}f(x) = f(a)$
### Propriedades que seguem essa regra:
- $\underset{x \to a}{\lim} c = c$
- $\underset{x \to a}{\lim} x = a$
- $\underset{x \to a}{\lim} x^n = a^n$
- $\underset{x \to a}{\lim} \sqrt[n]{x} = \sqrt[n]{a}$, se $n$ for par,  então $a > 0$
- $\underset{x \to a}{\lim} \sqrt[n]{f(x)} = \sqrt[n]{\underset{x \to a}{\lim} f(x)}$

## Teorema:
Se $f(x) = g(x)$ quando $x \neq a$, $\underset{x \to a}{\lim} f(x) = \underset{x \to a}{\lim} g(x)$ quando um dos limites existem.
### Exemplo:
Calcule $\underset{x \to 1}{\lim} \frac{x-1}{x^2 - 1}$.
Note que $f(1)$ não existe, mas considere agora $g(x) = \frac{1}{x + 1}$. Calculando $g(1)$ temos $0.5$. Então, note que:
$$f(x) = \dfrac{x-1}{x^2 - 1} = \dfrac{x - 1}{(x - 1) \cdot (x + 1)} = \dfrac{1}{x + 1} = g(x)$$
Então,

$$\underset{x \to 1}{\lim} f(x) = \underset{x \to 1}{\lim} g(x) = \dfrac{1}{1 + 1} = 0.5$$
## Teorema da desigualdade
Se $f(x) \leq g(x)$ para $x$ próximo de $a$, então $\underset{x \to a}{\lim} f(x) \leq \underset{x \to a}{\lim} g(x)$

## Teorema do confronto
Se $f(x) \leq g(x) \leq h(x)$, para $x$ próximo de $a$, então:
$$\begin{align*}
& \underset{x \to a}{\lim} f(x) = L = \underset{x \to a}{\lim} h(x)\\
& \Rightarrow \underset{x \to a}{\lim} g(x) = L
\end{align*}$$
### Exemplo:
$\underset{x \to 0}{\lim} (x^2 \cdot \sin{x}) = \ ?$

Note que $-1 \leq \sin{x} \leq 1$ e $x^2 \geq 0$. Então:
$$\begin{align*}
&x^2 \cdot (-1) \leq x^2 \sin{x} \\
&\Rightarrow -x^2 \leq x^2 \cdot \sin{x} \leq x^2
\end{align*}$$
Agora:
$$\underset{x \to 0}{\lim} -x^2 = 0 = \lim_{x \to 0} x^2 \Rightarrow \lim_{x \to 0} x^2 \sin{x} = 0$$