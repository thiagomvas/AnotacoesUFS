## Equação do Plano
$$ax + by + cz + d = 0$$
$$\begin{align*}
a^{2}+b^{2}+c^{2} \neq 0\\
a, b, c, d \in \mathbb{R}
\end{align*}$$

## Vetor normal
Toda equação linear sob a forma
$$ax + by + cz + d = 0$$
com $a^{2}+b^{2}+c^{2}\neq 0$ representa um plano com um vetor normal $\vec{N} = (a, b, c)$

## Casos particulares
- $a = 0$, o plano é paralelo ao eixo $x$
- $b = 0$, o plano é paralelo ao eixo $y$
- $c = 0$, o plano é paralelo ao eixo $z$
- $d = 0$, o plano passa pelo ponto $(0, 0 ,0)$

- $a = 0, b = 0$, o plano é paralelo ao plano $xy$ e perpendicular ao eixo $z$
- $b = 0, c = 0$, o plano é paralelo ao plano $yz$ e perpendicular ao eixo $x$
- $a = 0, c = 0$, o plano é paralelo ao plano $xz$ e perpendicular ao eixo $y$

- $a = 0, d = 0$, o plano passa pelo eixo $x$
- $b = 0, d = 0$, o plano passa pelo eixo $y$
- $c = 0, d = 0$, o plano passa pelo eixo $z$

- $a = 0, b = 0, d = 0$, representa o plano $xy$
- $b = 0, c = 0, d = 0$, representa o plano $yz$
- $a = 0, c = 0, d = 0$, representa o plano $xz$

## Classificação de 2 planos
Dado dois planos 
$$\begin{align*}
a_{1}x + b_{1}y + c_{1}z + d_{1} &=  0\\
a_{2}x + b_{2}y + c_{2}z + d_{2} &=  0
\end{align*}$$
Eles podem ser classificados em: 
- paralelos se $\vec{N_{1}}= k\vec{N_{2}}$, $k \in \mathbb{R}, k \neq 0$ 
- coincidentes se $\vec{N_{1}} = \vec{N_{2}}$ e $d_{1}=d_{2}$
- tem uma reta de interseção se não forem paralelos ou coincidentes

## Planos definidos por três pontos
Dados três pontos $P_{1}, P_{2}, P_{3}$ definidos por $\vec{r_{1}},\vec{r_{2}},\vec{r_{3}}$ e $\vec{r} = x \vec{i} + y \vec{j} + z \vec{k}$, temos que

$$(\vec{r} - \vec{r_{1}}) \cdot \Big( (\vec{r_{2}}- \vec{r_{1}}) \times (\vec{r_{3}} - \vec{r_{1}}) \Big) = 0$$
Por exemplo, tomando os seguintes pontos, podemos encontrar o seu plano:
$$\begin{align*}
P_{1}&= (4, 9, 3)\\
P_{2}&= (5, 2, 5)\\
P_{3}&= (5, 4, 3)\\\\
\vec{r_{2}} - \vec{r_{1}} &= (1, -7, 2)\\
\vec{r_{3}} - \vec{r_{1}} &= (1, -5, 0)\\
(\vec{r_{2}}- \vec{r_{1}}) \times (\vec{r_{3}} - \vec{r_{1}}) &= (10, 2, 12)\\
\\
\vec{r} - \vec{r_{1}} &= (x - 4, y-9,z-3)\\
\end{align*}$$
Logo, a equação do plano será
$$10x + 2y + 12z - 85 = 0$$

## Interseção entre planos
Uma reta pode ser definida a partir das interseções de dois planos não paralelos e não coincidentes. Dados dois planos
$$\begin{align*}
\pi_{1}: a_{1}x + b_{1}y + c_{1}z + d_{1} &=  0\\
\pi_{2}: a_{2}x + b_{2}y + c_{2}z + d_{2} &=  0
\end{align*}$$
Podemos descrever uma reta em termos de um dos eixos, isto é:
$$\left \{ \begin{align*}
&\big(x, y(x), z(x)\big)\\
&\big(x(y), y, z(y)\big)\\
&\big(x(z), y(z), z\big)
\end{align*} \right.$$
### Exemplo
- Dado os seguintes planos, encontre a equação da reta que identifica a interseção dos mesmos
$$\begin{align*}
\pi_{1}: 5x - 2y + z + 7 &= 0\\
\pi_{2}: 3x - 3y + z + 4 &= 0
\end{align*}$$
Nesse caso, iremos escrever a reta em termos de $x$. Formando sistemas de equações, temos:
$$\left\{ \begin{align*}
5x - 2y + z + 7 &= 0 &(-1)\\
3x - 3y + z + 4 &= 0 
\end{align*} \right.$$
$$\left\{ \begin{align*}
-5x + 2y - z - 7 &= 0\\
3x - 3y + z + 4 &= 0\\
\end{align*}\right.\ \Longrightarrow -2x - y - 3 \Rightarrow y = -2x - 3$$

$$\left\{ \begin{align*}
5x - 2y + z + 7 &= 0 &(-3)\\
3x - 3y + z + 4 &= 0 &(2)
\end{align*} \right.$$
$$\left\{ \begin{align*}
-15x + 6y - 3z - 21 &= 0\\
6x - 6y + 2z + 8 &= 0
\end{align*} \right. \Longrightarrow -9x - z - 13 \Rightarrow z = -9x - 13$$
Temos então que a reta formada pela interseção dos planos será descrita por$(x, -2x - 3, -9x - 13)$

## Ângulo entre planos
Utilizando a mesma formula de [[Reta#Angulo entre retas|ângulo entre retas]], porém utilizando os [[Planos#Vetor normal|vetores normais]] como parâmetros, temos que o ângulo entre os planos será o ângulo entre os vetores normais $\vec{n_{1}}$ e $\vec{n_{2}}$, i.e.
$$\cos \theta = \dfrac{\vec{n_{1}} \cdot \vec{n_{2}}}{n_{1}n_{2}},0 \leq \theta \leq \frac{\pi}{2}$$

## Distância de ponto a plano
Dado um ponto $Q(x_{0},y_{0}, z_{0})$ e um plano, temos que sua distância será dado pelas seguintes equações:
$$|proj_{\vec{n}}\vec{PQ}| = \dfrac{\vec{PQ}\cdot\vec{n}}{n}$$
ou
$$\dfrac{|ax_{0}+by_{0}+cz_{0}+d|}{n} = \dfrac{|ax_{0}+by_{0}+cz_{0}+d|}{\sqrt{a^{2}+b^{2}+c^{2}}}$$
### Exemplo
- Calcule a distância entre o ponto $Q(1, 0, -2)$ ao plano $$x - y + 2z - 2 = 0$$
$$\vec{n} = (1, -1, 2) \Rightarrow \dfrac{|1 - 4 - 2|}{\sqrt{1^{2}+ (-1)^{2}+ 2^{2}}} = \dfrac{5}{\sqrt{6}}$$

## Ângulo entre plano e reta
Utilizando a mesma formula de [[Reta#Angulo entre retas|ângulo entre retas]], porem usando o vetor normal do plano e o vetor diretor da reta, temos que o ângulo entre eles será dado por
$$\cos{(\frac{\pi}{2}-\phi)} = \sin{\phi} = \dfrac{|\vec{N} \cdot \vec{v}|}{Nv}$$
