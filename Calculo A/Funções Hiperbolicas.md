# Funções Hiperbólicas
Criado em: 2023-09-25 : 20:54

## Definições
- $sinh (x) = \dfrac{e^{x}-e^{-x}}{2}$  
- $cosh(x) = \dfrac{e^{x} + e^{-x}}{2}$
- $tgh(x) = \dfrac{senh(x)}{cosh(x)} = \dfrac{\dfrac{e^{x}-e^{-x}}{2}}{\dfrac{e^{x}+e^{-x}}{2}}= \dfrac{e^{x}-e^{-x}}{e^{x}+e^{-x}}$ 
- $sech(x) = \dfrac{1}{cosh(x)}$
- $cossech(x) = \dfrac{1}{senh(x)}$
- $cotgh(x) = \dfrac{e^{x}+e^{-x}}{e^{x}-e^{-x}}$

## Identidades
- $senh(-x) = -senh(x)$
- $cosh(-x) = cosh(x)$
- $cosh^{2}(x) - senh^{2}(x) = 1$
- $1 - tgh^{2}(x) = sech^{2}(x)$
- $senh(x + y) = senh(x)cosh(y) + cosh(x)senh(y)$
- $cosh(x + y) = cosh(x)cosh(y) + senh(x)senh(y)$  

## [[Derivadas]]
- $\dfrac{d}{dx}senh(x) = cosh(x)$
- $\dfrac{d}{dx}cosh(x) = senh(x)$
- $\dfrac{d}{dx} tgh(x) = sech^{2}(x)$
As inversas das funções trigonométricas se aplicam nas hiperbólicas

## Exemplos e Exercícios
- Derive $cosh(\sqrt{x})$
$$\begin{align*}
\dfrac{d}{dx} cosh(\sqrt{x}) &= cosh'(\sqrt{x}) \cdot (\sqrt{x})'\\
&= senh(\sqrt{x}) \cdot \frac{1}{2\sqrt{x}}\\
&= \frac{senh(\sqrt{x});..}{2\sqrt{x}}
\end{align*}$$
- Derive $e^{x}\cdot senh(x^{2})$
$$\begin{align*}
\dfrac{d}{dx}f(x) &= e^{x}\cdot cosh(x^{2})\cdot 2x + e^{x}senh(x^{2})\\
&= e^{x}(2xcosh(x^{2})+ senh(x^{2}))
\end{align*}$$

## Referencias
1. 

