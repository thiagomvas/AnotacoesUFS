# Formas Indeterminadas

## Definição
São casos em que não podemos calcular o [[Limite|limite]] devido à nos dar uma forma que não existe um valor, que chamamos de forma indeterminada. Dentre elas, temos
- $\frac{0}{0}$
- $\dfrac{\pm \infty}{\pm \infty}$
- $0 \cdot \infty$
- $\infty \pm \infty$
- $0^{0}$
- $\infty^{0}$
- $1^\infty$

A seguir existem exemplos de como solucionar estes casos
### Caso $\frac{0}{0}$
$$
\underset{x \to 1} \lim \dfrac{\ln(x)}{x - 1} = ?
$$
Note que:
$$\begin{align*}
f(x) &= \ln(x)\\
g(x) &= x - 1\\
f(1) &= 0\\
g(1) &= 0 
\end{align*}$$
Então, aplicando a [[Lei de L'hopital]]
$$\begin{align*}
\underset{x \to 1} \lim \dfrac{\ln(x)}{x - 1} &= \dfrac{\frac{d}{dx}\ln x}{\frac{d}{dx}(x - 1)}\\
&= \underset{x \to 1} \lim \dfrac{\frac{1}{x}}{1}\\
&= \underset{x \to 1} \lim \frac{1}{x}\\
&= 1
\end{align*}$$

### Caso $\frac{\infty}{\infty}$
$$\underset{x \to \infty} \lim \dfrac{x^{2}-1}{2x^2+1}$$
Note que
$$\begin{align*}
\underset{x \to \infty} \lim x^{2}-1 &= \infty\\
\underset{x \to \infty} \lim 2x^{2}+1 &= \infty
\end{align*}$$
Então, aplicando a [[Lei de L'hopital]]
$$\begin{align*}
\underset{x \to \infty} \lim \dfrac{x^{2}-1}{2x^{2}+1}&=\underset{x \to \infty} \lim \dfrac{(x^{2}-1)'}{(2x^{2}+1)'} \\
&= \underset{x \to \infty} \lim \frac{2x}{4x}\\
&= \frac{1}{2}
\end{align*}$$

### Caso $0 \cdot \infty$
No geral, se 
$$\underset{x \to a} \lim g(x) = \infty$$devemos observar que
$$f(x)\cdot g(x) = \dfrac{f(x)}{\frac{1}{g(x)}}$$
podendo assim aplicar L'Hopital.
$$\begin{align*}
\underset{x \to 0} \lim x \ln x &= \underset{x \to 0} \lim \dfrac{\ln x}{\frac{1}{x}}\\
&= \underset{x \to 0} \lim \frac{(\ln x)'}{(\frac{1}{x})'}\\
&= \underset{x \to 0} \lim \frac{\frac{1}{x}}{\frac{-1}{x^{2}}}\\
&= \underset{x \to 0} \lim \frac{-x^{2}}{x}\\
&= \underset{x \to 0} \lim -x\\
&= 0
\end{align*}$$

### Caso $\infty \pm \infty$
$$\underset{x \to \frac{\pi}{2}^{-}} \lim (\sec x - \tan x)$$
Note que,
$$\underset{x \to \frac{\pi}{2}^{-}} \lim (\sec x - \tan x) = \underset{x \to \frac{\pi}{2}^{-}} \lim \frac{1}{\cos x}- \frac{\sin x}{\cos x} = \underset{x \to \frac{\pi}{2}^{-}} \lim \frac{1- \sin x}{\cos x}= \frac{0}{0}$$
Aplicando a [[Lei de L'hopital]]
$$\begin{align*}
\underset{x \to \frac{\pi}{2}^{-}} \lim \frac{1- \sin x}{\cos x} &= \underset{x \to \frac{\pi}{2}^{-}} \lim \frac{(1- \sin x)'}{(\cos x)'}\\
&= \underset{x \to \frac{\pi}{2}^{-}} \lim \frac{-\cos x}{- \sin x}=0
\end{align*}$$

### Casos de potencia
Nos 3 casos de potência, devemos considerar
$$\begin{align*}
y &= [f(x)]^{g(x)}\\
\ln y &= ln[f(x)]^{g(x)}\\
&= g(x) \cdot \ln (f(x))\\
\Rightarrow e^{\ln y}&= e^{g(x)\cdot \ln(f(x))}\\
y &= e^{g(x)\cdot \ln(f(x))}\\
[f(x)]^{g(x)}&= e^{g(x)\cdot \ln(f(x))}\\
\underset{x \to a} \lim [f(x)]^{g(x)} &= \underset{x \to a} \lim e^{g(x)\cdot \ln(f(x))}
\end{align*}$$