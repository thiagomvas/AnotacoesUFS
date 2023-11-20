# Sentenças abertas
Criado em: 2023-07-21 : 10:51

## Definição
É uma que envolve uma ou mais variáveis e que torna-se uma [[Calculo Proposicional#Proposição|proposição]] ao atribuirmos valores a essas variáveis. Por exemplo:
$$p(x): x \in \mathbb{R}, x \geq 0$$
$$\left \{\begin{align*}
p(1) &= V\\
p(2) &= V\\
p(-1) &= F
\end{align*} \right.$$
## Quantificador universal ( $\forall$ )
Escrevemos $(\forall x \in \mathbb{R}, p(x))$ quando $p(x)$ for verdadeiro para todo $x \in \mathcal{U}$ 
$$r(x) : x^{2} + 1 = 0, \forall x \in \mathbb{R}, x^{2}+1>0$$

## Quantificador existencial ( $\exists$ )
Escrevemos $(\exists x \in \mathcal{U}, p(x))$ quando pelo menos um $a \in \mathcal{U}$ tal que $p(a)$ é verdadeiro
$$r(x): x^{2}+ 1 = 0; \exists x \in \mathbb{R}, x^{2}- 1 = 0$$

## Propriedades
- $\lnot(\forall x \in \mathcal{U}, p(x)) \equiv \exists x \in \mathcal{U}, \lnot p(x)$
- $\lnot (\exists x \in \mathcal{U}, p(x)) \equiv \forall x \in \mathcal{U}, \lnot p(x)$

## Regras de validade de argumentos com quantificação
1. Se $(\forall x \in \mathcal{U}; p(x))$ for verdadeira, então $p(a)$ é verdadeira para todo $a \in \mathcal{U}$
2. Se $(\exists x \in \mathcal{U}; p(x))$ for verdadeiro, então existe $a \in \mathcal{U}$ tal que $p(a)$ é verdadeira
## Exemplos e Exercícios
- Todos os atletas são fortes. André é um atleta. Portanto, André é forte
	$a(x):$ x é atleta
	$f(x)$ : x é forte	$$\forall x, a(x) \Rightarrow f(x); \ a(A) \mapsto f(A)$$
	$$\begin{align*}
1)& \forall x, a(x) \Rightarrow f(x)\\
2)& a(A)\\
3)& a(a) \Rightarrow f(A) (R1)\\
4)& f(a) (2, 3 MP)
\end{align*}$$

## Referencias
1. 

