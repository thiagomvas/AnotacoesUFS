Vamos iniciar considerando como exemplo: $f(x) = x^{2}$ e $g(x) = x$. Ja conhecemos 
$$\dfrac{d}{dx}(6 \cdot f(x)) = 6 \cdot \dfrac{d}{dx} f(x)$$
$$\dfrac{d}{dx}(f(x) + g(x)) = \dfrac{d}{dx}f(x) + \dfrac{d}{dx}g(x)$$
Mas como sera $\dfrac{d}{dx}(f(x) \cdot g(x))$? Note que
$$f(x) \cdot g(x) = x^{3}$$
Além disso,
$$\begin{align*}
\dfrac{d}{dx}f(x) &= 2x\\
\dfrac{d}{dx}g(x) &= 1\\
\dfrac{d}{dx} x^{3} &= 3x^{2}\\
\end{align*}$$
Teremos então
$$\dfrac{d}{dx}(f(x) \cdot g(x)) = 3x^{2} \neq 2x \cdot 1 = \dfrac{d}{dx}f(x) \cdot \dfrac{d}{dx}g(x)$$
e isto mostra que a derivada de um produto **não e o produto das derivadas.**
Para descobrir uma regra, vamos olhar novamente para a definição
$$\dfrac{d}{dx} \Big ( f(x) \cdot g(x)\Big) = \underset{h \to 0} \lim \dfrac{f(a + h) \cdot g(a + h) - f(a)\cdot f(g)}{h}$$
Reescrevendo os objetos, temos que
$$\begin{align*}
\Delta x &= h\\
\Delta u &= f(x + \Delta x) - f(x)\\
\Delta v &= g(x + \Delta x) - g(x)\\
u &= f(x)\\
v &= g(x)
\end{align*}$$
Imaginando um retângulo de comprimento  $(u + \Delta u)$ e altura $(v + \Delta v)$, e outro de lados $u$ e $v$, a area do retângulo menor seria $u \cdot v$, enquanto a do maior seria $(u + \Delta u) \cdot (v + \Delta v)$. A variação desse retângulo sera $\Delta(u \cdot v)$ 
$$\begin{align*}
\Delta(u \cdot v) &=  (u + \Delta u ) (v + \Delta v) - uv\\
&= uv + u \cdot \Delta v + v \cdot \Delta v + \Delta u \cdot \Delta v - uv\\
&=  u \cdot \Delta v + v \cdot \Delta u + \Delta u \cdot \Delta v\\
\end{align*}$$
Dessa forma, 
$$\dfrac{\Delta (u \cdot v)}{\Delta x} = u \cdot \dfrac{\Delta v}{h} + v\cdot \dfrac{\Delta u}{h} + \dfrac{\Delta u \cdot \Delta v}{h}$$
$$\begin{align*}
\dfrac{\Delta u}{\Delta x} &= \dfrac{d}{dx}f(x)\\
\dfrac{\Delta v}{\Delta h} &= \dfrac{d}{dx}g(x)\\
\dfrac{\Delta u \Delta v}{h} &= \underset{\Delta x \to 0} \lim \dfrac{\Delta u}{h} \underset{\Delta x \to 0} \lim \Delta v = 0 
\end{align*}$$

$$\dfrac{\Delta (u \cdot v)}{h} = u \cdot \dfrac{d}{dx}f(x) + v \cdot \dfrac{d}{dx}g(x) $$
