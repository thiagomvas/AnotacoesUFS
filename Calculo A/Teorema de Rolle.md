# Teorema de Rolle

## Definição
Seja $f$ função que satisfaz:
- $f$ [[Continuidade|continua]] no intervalo $[a, b]$
- $f$ [[Derivadas|derivável]] no intervalo $[a, b]$
- $f(a) = f(b)$
Então, existe $c \in (a, b)$ tal que $f'(c) = 0$

## Exemplos e Exercícios
- Verifique que a seguinte equação tem uma **única** raiz: $x^{3}+ x - 1$
Note que $f(x)$ é continua para $x \in \mathbb{R}$ e que $f(0) = -1, f(1) = 1 \Rightarrow f(0) < 0, f(1) > 0$. Logo, pelo Teorema do Valor Intermediário, $\exists x_{0} \in [0, 1], f(x) = 0$. 

Para garantir unicidade, imagine outra raiz $x_{1}$. Então
$$f(x_{0}) = 0 = f(x_{1}), x_{1}\neq x_{0}$$
Assim temos um intervalo $[x_{0}, x_{1}]$, então:
	- $f(x)$ é continua em $[x_{0}, x_{1}]$
	- $f(x)$ é derivável em $(x_{0}, x_{1})$
	- $f(x_{0}) = f(x_{1}) \star$ 
Então, pelo Teorema de Rolle, existe $c \in (x_{0}, x_{1})$ tal que $f'(c) = 0$.
$$f'(x) = 3x^{2} + 1 = 0$$
Como $3x^{2} > 0$, não existe $c \in \mathbb{R}$ tal que $3c^{2}=-1$. Logo, não pode existir outra raiz


