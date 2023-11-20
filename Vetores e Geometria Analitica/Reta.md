---
tags: []
---
# Reta
Criado em: 2023-07-19 : 09:28

## Definição

## Teoremas
- ### 1.1 ( Equação Vetorial da Reta)
	Dado um ponto $P_{0} (x_{0}, y_{0}, z_{0})$ na reta L e $\vec{v}$ um [[Vetores|vetor]] não nulo em $\mathbb{R}^{3}$, então a equação da reta que passa por P e é paralela ao [[Vetores|vetor]] $\vec{v}$ será dada por
	$$\vec{r} = \vec{p} + t\vec{v}$$
	em que $\vec{p} = (x_{0}, y_{0}, z_{0}), \vec{r}=(x,y,z) \mbox{ e } \vec{v} = (v_{x}, v_{y},v_{z})$ seria o [[Vetores|vetor]] diretor da reta
 - ### 2.1 ( Equação paramétrica da Reta )
	 Dado um ponto $P_{0}(x_{0}, y_{0}, z_{0})$ de uma reta e $\vec{v}$ um [[Vetores|vetor]] não nulo em $\mathbb{R}^{3}$ então todos os pontos $(x, y, z)$  da reta que passa por P e é paralela a $\vec{v}$ sera dada por
	 $$\begin{align*}
x &= x_{0}+ v_{x}t\\
y &= y_{0}+ v_{y}t\\
z &= z_{0}+ v_{z}t
\end{align*}$$
	com $t \in \mathbb{R}$ 
- ### 3.1 ( Representação simétrica da Reta ) 
	A equação simétrica da reta e dada por  
	$$\dfrac{x - x_{0}}{v_{x}}= \dfrac{y - y_0}{v_{y}}= \dfrac{z - z_0}{v_z} $$
	com $v_{x}, v_{y}, v_{z}$ todos não nulos.

## Casos Particulares
1. $v_{x}= 0 \Rightarrow x = x_{0}, \dfrac{y - y_{0}}{v_{y}}= \dfrac{z - z_0}{v_z}$
2. $v_{y}= 0 \Rightarrow y = y_{0}, \dfrac{x - x_{0}}{v_{x}}= \dfrac{z - z_{0}}{v_z}$ 
3. $v_{z} = 0 \Rightarrow z = z_{0}, \dfrac{x - x_{0}}{v_{x}} = \dfrac{y - y_{0}}{v_{y}}$
## Distancia do ponto a reta
Sejam $P$ e $Q$ dois pontos distintos e $r$ uma reta. A distancia de Q e a reta $r$ sera dada por
$$d = \dfrac{|\vec{u} \times \vec{PQ}}{|\vec{u}|}$$
em que $P(x_{0}, y_{0})$ pertence a reta $r$ e $\vec{u}$ um vetor paralelo a reta.
## Proposições 
1. Seja $P_{1}(x_{1}, y_{1}, z_{1}), P_{2}(x_{2}, y_{2}, z_{2})$ pontos distintos em $\mathbb{R}^{2}$ e $\vec{P_{1}P_{2}} = (x_{2}-x_{1}, y_{2}-y_{1}, z_{2}-z_{1})$. Então a reta $L$ que passa por $P_{1}$ e $P_{2}$ sera descrita por
	$$\begin{align*}
\vec{r} &= (x_{1}, y_{1}, z_{1}) + (x_{2}-x_{1}, y_{2} - y_{1}, z_{2} - z_{1})t\\
\\
x &= x_{1} + (x_{2} - x_{1})t\\
y &= y_{1} + (y_{2}- y_{1})t \\
z &= z_{1}+ (z_{2}- z_{1})t\\
\\
&\dfrac{x - x_{1}}{x_{2}-  x_{1}} = \dfrac{y - y_{1}}{y_{2}- y_{1}} = \dfrac{z - z_{1}}{z_{2}- z_{1}}\\
\end{align*}$$

## Exemplos e Exercícios
- Determine os pontos de interseções (caso existam) das retas dadas por: 
$$\left \{ \begin{align*}L_{1}&: x = 7 + 3s, y = -4 - 3s, z = -7 - 5s\\
L_{2}&: x = 1 + 6t, y = 2 + t, z = 3 - 2t
\end{align*} \right .$$
$$
(x_{1}, y_{1}, z_{1})= (x_{2}, y_{2}, z_{2})
$$$$\begin{matrix}\begin{matrix}
7 + 3s = 1 + 6t && -4 - 3s = 2 + t &&-7 - 5s=3 - 2t\\
6 + 3s = 6t && -6 - 3s = t && - 10 - 5s = 2t\\
2 + s = 2t && &&\end{matrix}
\end{matrix}$$
$$\left \{\begin{align*}
t &= -6 - 3s\\
2t &= 2 + s
\end{align*} \right.$$
$$\left \{\begin{align*}
t &= -6-3s\\
6t &= 6 + 3s
\end{align*} \right.$$
$$t = 0$$
$$-6-3s = t \Rightarrow -6-3s = 0 \Rightarrow -3s = 6 \Rightarrow s = -2$$
- Um coelho parte de $P_{0}(3, -1, -5)$ com velocidade $v = 21$ em movimento retilíneo e uniforme e segue na direção do vetor $\vec{s} = - 2\vec{i} + 6\vec{j} + 2\vec{k}$. Determine as equações paramétricas da localização do coelho.
$$\begin{align*}
\vec{r} = \vec{p} + \vec{v}t &= (3, -1, -5) + v \dfrac{\vec{s}}{s}t\\
s &= \sqrt{44} = 2\sqrt{11}\\
\vec{r} &= (3, -1, -5) + 21 \dfrac{(-2, 6, 2)}{2\sqrt{11}}t\\
\end{align*}$$
Temos então que
$$\left \{ \begin{align*}
x &= 3 - \frac{21}{\sqrt{11}}t\\
y &= -1 - \frac{63}{\sqrt{11}}t\\
z &= -5 + \frac{21}{\sqrt{11}}t\\
\end{align*} \right .$$
- Determine a distancia do ponto $(3, -1, 2)$ a reta $$(x, y, z) = (2, 0, 1) + (-1, -1, 2)t$$
$$\begin{align*}
d = \dfrac{|\vec{u} \times \vec{PQ}|}{u} &= \dfrac{|(-1, -1, 2) \times (1, -1, 2)|}{\sqrt{6}}\\

\end{align*}$$

## Angulo entre retas
$$cos{\theta} = \dfrac{\vec{v_{1}} \cdot \vec{v_{2}}}{v_{1}v_{2}}$$

## Referencias
1. 

