# Derivadas
Criado em: 2023-07-12 : 21:22



## Definição
Uma função $f$ é derivável ou "diferenciavel" em $a$ quando $f'(a)$ existir. Dizemos ainda que $f$ é derivável em um intervalo $(a, b)$ ou $[(-\infty, a), (a, \infty) \mbox{ ou } (-\infty, \infty)]$ quando $f$ é derivável em cada numero do intervalo.

## Notação
Dado que a reta tangente à $y = f(x)$ no ponto $P$ é a reta que passa por $P$ com inclinação $\underset{x \to a} \lim \dfrac{f(x) - f(a)}{x - a} = \underset{h \to 0} \lim \dfrac{f(a + h) - f(a)}{h}$ quando o [[Limite|limite]] existir, escrevemos então que:
$$\left. \begin{matrix}f'(x) \\ \\  y' \\ \\  \dfrac{dy}{dx} \\ \\  \dfrac{df}{dx}\end{matrix} \right \} = \underset{h \to 0} \lim \dfrac{f(a + h) - f(a)}{h}$$

## Propriedades
- $\dfrac{d}{dx} (f(x) + g(x)) = \dfrac{d}{dx}f(x) + \dfrac{d}{dx}g(x)$
- $\dfrac{d}{dx}(f(x) - g(x)) = \dfrac{d}{dx}f(x) - \dfrac{d}{dx}g(x)$
- $\dfrac{d}{dx} (c \cdot f(x)) = c \cdot \left ( \dfrac{d}{dx} f(x) \right)$  
- $\dfrac{d}{dx}\Big ( f(x) \cdot g(x) \Big ) = f(x) \cdot \dfrac{d}{dx} g(x) + g(x) \cdot \dfrac{d}{dx}f(x)$ (Veja [[Regra de Derivacao do Produto]])

## Teoremas
- ### 1.1
- ### 2.1

## Exemplos e Exercícios
1. Dado $f(x) = x^{2} - 8x + 9$, calcule $f'(a)$
$$\begin{align*}
f'(a) &= \underset{h \to 0} \lim \dfrac{f(a + h) - f(a)}{h}\\
f(a + h) &= (a+h)^{2}- 8(a+h) + 9 \\
&= a^{2}+2ah+h^{2}-8a-8h+9\\
f(a) &= a^{2}- 8a + 9\\
f(a + h) - f(a) &= a^{2}+ 2ah+h^{2}-8a-8h+9-a^2+8a-9\\
&=2ah+h^2-8h\\
&= h(2a+h-8)\\
\underset{h \to 0} \lim f'(a) &= \underset{h \to 0} \lim \dfrac{h(2a+h-8)}{h}\\
&= \underset{h \to 0} \lim 2a + h - 8\\
&= 2a - 8
\end{align*}$$
2. $f(x) = |x|$, quais os intervalos que $f$ é derivável?
$$
\dfrac{dy}{dx} f(x)= \underset{h \to 0} \lim \dfrac{|x + h| - |x|}{h}$$
$$\begin{align*}
x < 0&: x + h < 0 \Rightarrow \dfrac{-(x + h) + x}{h} = \dfrac{-h}{h} = -1\\
x > 0 &: x + h > 0 \Rightarrow \dfrac{x + h - x}{h} =\dfrac{h}{h} = 1 \\
	x = 0&: \underset{h \to 0^{-}} \lim \dfrac{|0 + h| - |0|}{h} = -1, \underset{h \to 0^{+}} \lim \dfrac{|0+h| - |0|}{h} =1
\end{align*} $$
	Logo, $f$ é derivável para todo $x \neq 0$ 

3.  $\dfrac{d}{dx}\Big (f(x) \cdot g(x) \Big) = ?, f(x) = x^{2}, g(x) = x$
$$\begin{align*}
\dfrac{d}{dx}\Big (f(x) \cdot g(x) \Big) &= f(x) \cdot \dfrac{d}{dx}g(x) + g(x) \cdot \dfrac{d}{dx}f(x)\\
&= x^{2}\cdot 1 + x \cdot 2x\\
&= 3x^{2}
\end{align*}$$

4. Derive $f(x) = x e^{x}$
	Note que $f(x)$ e um produto, dito isso, podemos dividir a função $f$ em 2: $g(x) = x$ e $h(x) = e^{x}$ . Dito isso:
$$\begin{align*}
\dfrac{d}{dx}\Big ( g(x) \cdot h(x) \Big) &= x \cdot \dfrac{d}{dx}e^{x} + e^{x} \cdot x\\
&= x \cdot e^{x} + e^{x}\cdot 1\\
&= e^{x}(x + 1)
\end{align*}$$
## Referencias
