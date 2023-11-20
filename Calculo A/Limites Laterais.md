# Limites Laterais
Para inicializar [[Limite]]s Laterais, vamos considerar o exemplo da função
$$H(t) = \left \{ \begin{matrix} 0, & \mbox{se }t < 0 \\ 1, & \mbox{se }t \geq 0 \end{matrix} \right. \qquad \lim_{t \to 0} H(t) = ?$$

Calculando o [[Limite]] pelo "lado esquerdo", temos que $\underset{t < 0}{t \to 0} \Rightarrow H(t) = 0$ e pelo "lado direito" temos que $\underset{t > 0}{t \to 0} \Rightarrow H(t) = 1$

## Notação:
- $t \to 0^-$ quando $t < 0$
- $t \to 0^+$ quando $t > 0$

## Definição:
Escrevemos $\underset{x \to a^-}{\lim} f(x) = L$ quando $x$ tende à $a$ da esquerda e $\underset{x \to a^+}{\lim}f(x) = L$ quando $x$ tende à $a$ da direita

## Teorema:
$$\lim_{x \to a} f(x) = L \Longleftrightarrow \lim_{x \to a^-}f(x) = L \mbox{ e} \lim_{x \to a^+}f(x) = L$$
Dessa forma, $\underset{t \to 0}{\lim} H(t)$ não existe, pois viola o teorema