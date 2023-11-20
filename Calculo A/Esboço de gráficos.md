# Esboço de gráficos
No geral, o processo de esboçar gráficos seguirá o seguinte roteiro:

1. Domínio.
2. Interseções de $f(x)$ com os eixos $x$ e $y$
3. Simetrias
	- $f(x) = f(-x) \Rightarrow$ Função Par
	- $f(-x) = -f(x) \Rightarrow$ Função Impar
	- $f(x + p) = f(x) \Rightarrow$ Função Periódica
4. [[Assíntotas]]
5. [[Teste da função crescente e decrescente|Intervalos de crescimento e decrescimento]]
6. [[Máximos e Mínimos]]
7. [[Concavidade]] e [[Concavidade#Ponto de Inflexão|pontos de inflexão]] 
8. Esboço do gráfico

## Ex: Esboce $f(x) = \frac{x^{3}}{x^{2}+1}$
1. $D = {x \in \mathbb{R}}$
2. $$f(x) = 0 \Rightarrow \frac{x^{3}}{x^{2}+1}= 0 \Rightarrow x^{2}+ 1 > 0 \Rightarrow x^{3}= 0 \Rightarrow x= 0$$
3. $f(-x) = \dfrac{(-x)^{3}}{(-x)^{2}+1} = -\dfrac{x^{3}}{x^{2}+1} = -f(x)$ Impar
4. Não existe divisão por 0, logo não tem assíntota vertical
	$\underset{x \to \infty} \lim \frac{x^{3}}{x^{2}+1}= \frac{x}{\frac{1+1}{x^{2}}}= \infty$. Logo, não tem assintota horizontal
	$$\begin{align*}
\underset{x \to \infty} \lim \left[\frac{x^{3}}{x^{2}+1}-x\right]&= \underset{x \to \infty} \lim \left[\dfrac{x^3-x^3-x}{x^2+1} \right]\\
&= \underset{x \to \infty} \lim \frac{-x}{x^{2}+1}\\
	&= \underset{x \to \infty} \lim \frac{\frac{-1}{x}}{\frac{1+1}{x^{2}}}\\
&= \frac{-0}{1+0} =0\\
\end{align*}$$
$y = x$ é assintota????
5. $$\begin{align*}
f'(x) &= \dfrac{(x^2+1)(3x^{2})-x^{3}2x}{(x^{2}+1)^{2}}\\
&= \dfrac{3x^{4}+3x^{2}-2x^{4}}{(x^{2}+1)^{2}}\\
&= \dfrac{x^{4}+3x^{2}}{(x^{2}+1)^{2}}
\end{align*}$$
|       | $x^{4}+3x^{2}$ | $(x^2 +1)^{2}$ | $f'(x)$ |
| ----- | -------------- | -------------- | ------- |
| $x<0$ | +              | +              | C       |
| $x>0$ | +              | +              | C        |

$\forall x \in \mathbb{R}, f'(x) > 0$

6. $f''(x) = \dfrac{2x(x^{2}-3)}{(x^{2}+1)^{3}}$. Não tem max e min

7.

|                     | $x^{2}-3$ | $2x$ | $2x(x^{2}-3)$ | $f''(x)$ |
| ------------------- | --------- | ---- | ------------- | -------- |
| $x < -\sqrt{3}$     | +         | -    | -             | +        |
| $-\sqrt{3} < x < 0$ | -         | -    | +             | -        |
| $0<x<\sqrt{3}$      | -         | +    | -             | +        |
| $x > \sqrt{3}$      | +         | +    | +             | -         |

8.![[Pasted image 20230925232412.png]]

## Ex: Esboce $f(x) = \frac{2x^{2}}{x^{2}- 1}$
1. ${x \in \mathbb{R}, x \neq -1, x \neq 1}$
2. $f(x) = 0 \Leftrightarrow \dfrac{2x^{2}}{x^{2}-1} = 0 \Rightarrow 2x^{2}= 0 \Rightarrow x = 0$
3. $f(-x) = \dfrac{2 \cdot (-x)^{2}}{(-x)^{2}-1} = \frac{2x^{2}}{x^{2}-1}= f(x) \Longrightarrow$ Função Par
4. Calculando $\underset{x \to a} \lim (x^{2}-1)$ quando $x^{2}-1 =0$ temos que $x^{2}=1 \Rightarrow x = 1, x = -1$ 
	Ambos os valores de $x$ geram assíntotas verticais quando calculamos seus limites
	Calculando agora o limite para $x \to \infty$, temos
	$$\underset{x \to \infty} \lim \frac{2x^{2}}{x^{2}-1}= \underset{x \to \infty} \lim \frac{2}{1 - \frac{1}{x^{2}}}= 2$$
	$$\underset{x \to -\infty} \lim \frac{2x^{2}}{x^{2}-1}= \underset{x \to -\infty} \lim \frac{2}{1 - \frac{1}{x^{2}}}=2$$
	Gerando assíntota horizontal em $y = 2$
5. $$\begin{align*}
f'(x) &= \left ( \dfrac{2x^{2}}{x^{2}-1}\right)\\
&= \dfrac{(x^{2}- 1)(4x) - (2x^{2})(2x)}{(x^{2}-1)^{2}}\\
&= \dfrac{4x^{3}-4x-4x^{3}}{(x^{2}-1)^{2}}\\
&= \frac{-4x}{(x^{2}-1)^{2}}
\end{align*}$$
	- $x > 0 \Rightarrow -4x < 0 \Rightarrow f'(x) < 0$. Decrescente
	- $x < 0 \Rightarrow -4x > 0 \Rightarrow f'(x) > 0$. Crescente
	- $x = 0$ é numero critico
6. $x = 0 \Rightarrow$ Máximo Local
7. $$\begin{align*}
f''(x) &= \left( \dfrac{-4x}{(x^{2}-1)^{2}}\right)\\
&= \dfrac{-4(x^2-1)^{2}-(-4x)\cdot2\cdot(x^2-1)\cdot2x}{(x^2-1)^{4}}\\
&= \dfrac{12x^{2}+4}{(x^2-1)^{3}}
\end{align*}$$
	- $x < -1 \Rightarrow f''(x) > 0$
	- $-1 < x < 0 \Rightarrow f''(x) > 0$
	- $0 < x < 1 \Rightarrow f''(x) < 0$
	- $x > 1 \Rightarrow f''(x) < 0$
8. ![[Pasted image 20230925232217.png]]