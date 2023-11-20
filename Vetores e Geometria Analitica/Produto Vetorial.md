# Produto Vetorial
Seja $\vec{u}$ e $\vec{v}$ [[Vetores]] no espaço. O **produto vetorial** deles é denotado por
$$\vec{u} \times \vec{v}$$ Esse produto fornece um novo vetor, varacterizando-se por ser ortogonal aos dois vetores dados.

## Teorema
Se $\theta$ é o ângulo entre os vetores $\vec{u}$ e $\vec{v}$, o produto vetorial entre eles é dado por
$$\vec{u} \times \vec{v} = uv\sin{\theta}\vec{e}$$
onde $\vec{e}$ é um vetor unitário perpendicular a ambos $\vec{u}$ e $\vec{v}$. Ou seja:
$$\begin{align*}
|\vec{e}| &= 1\\
\vec{e} \cdot \vec{u} &= 0\\
\vec{e} \cdot \vec{v} &= 0\\
\end{align*}$$
Além disso, temos que:
$$\begin{align*}
\vec{u} \cdot (\vec{u} \times \vec{v}) &= 0\\
\vec{v} \cdot (\vec{u} \times \vec{v}) &= 0
\end{align*}$$
## Teorema
Utilizando $\vec{i}, \vec{j}, \vec{k}$ como os vetores unitários que representam os eixos $X, Y, Z$ temos que na medida que é "movido" de um eixo pro outro, na ordem mencionada, temos que o produto vetorial entre eles será o restante, porem dependendo da ordem seu sinal mudará. Isto é:
$$\begin{align*}
\vec{i} \times \vec{j} &= \vec{k}\\
\vec{j} \times \vec{k} &= \vec{i}\\
\vec{k} \times \vec{i} &= \vec{j}\\
\vec{i} \times \vec{k} &= -\vec{j}\\
\vec{k} \times \vec{j} &= -\vec{i}\\
\vec{j} \times \vec{i} &= - \vec{k}\\
\end{align*}$$
## Propriedades
- $\vec{u} \times \vec{v} = -(\vec{v} \times \vec{u})$
- $\vec{u} \times (\vec{v} + \vec{w}) = (\vec{u} \times \vec{v}) + (\vec{u} + \vec{w})$ 
- $c (\vec{u} \times \vec{v}) = (c \vec{u}) \times \vec{v} = \vec{u} \times (c \vec{v})$ 
- $\vec{u} \times \vec{0} = (\vec{0} \times \vec{u}) = 0$
- $\vec{u} \times \vec{u} = \vec{0}$
- $\vec{u} \cdot (\vec{v} \times \vec{w}) = (\vec{u} \times \vec{v}) \cdot \vec{w}$
- $\vec{u} \times (\vec{v} \times \vec{w}) = (\vec{u} \cdot \vec{w}) \vec{v} - (\vec{u} \cdot \vec{v}) \vec{w}$ 

## Identidade de Jacobi (com vetores)
$$\vec{u} \times (\vec{v} \times \vec{w}) + \vec{v} \times (\vec{w} \times \vec{u}) + \vec{w} \times (\vec{u} \times \vec{v}) = \vec{0}$$
## Proposição
Dado $\vec{u} = u_{x}\vec{i} + u_{y}\vec{j} + u_{z}\vec{k}$ e  $\vec{v} = v_{x}\vec{i} + v_{y}\vec{j} + v_{z}\vec{k}$, temos que:
$$\begin{align*}
\vec{u} \times \vec{v} &= (u_{x}\vec{i} + u_{y}\vec{j} + u_{z}\vec{k}) \times (\vec{v} = v_{x}\vec{i} + v_{y}\vec{j} + v_{z}\vec{k})\\
&= (u_{y}v_{z}- u_{z}v_{y})\vec{i} + (u_{z}v_{x} - u_{x}v_{z})\vec{j} + (u_{x}v_{y} - u_{y}v_{x})\vec{k}
\end{align*}$$
Para explicar esse calculo, é possivel fazer o uso de matrizes
$$\begin{bmatrix}
\vec{i} & \vec{j} & \vec{k} \\ 
u_{x}  & u_{y} & u_{z} \\ 
v_{x} & v_{y} & v_{z}
\end{bmatrix}$$
Para chegarmos em $(u_{y}v_{z}- u_{z}v_{y})\vec{i}$, seguimos a seguinte logica: Ignoramos a coluna do vetor $\vec{i}$ devido à propriedade de que $\vec{i} \times \vec{i} = 0$. Saindo na ordem "crescente"(de $X$ à $Z$ / de $\vec{i}$ à $\vec{k}$), traçaremos a diagonal dando um passo para a direita e outro para baixo, ou seja, $\vec{i} \to u_{y}\to v_z$, nos dando $\vec{i}u_{y}v_{z}$, em seguida, faremos o mesmo porem para a esquerda. Como seguindo na "direção oposta" em um produto vetorial resulta no oposto, ou seja, negativo, teremos $-\vec{i}v_{z}u_{y}$, colocando em evidência temos $(u_{y}v_{z}- u_{z}v_{y})\vec{i}$. Repete-se o mesmo para os outros vetores unitários que nos deixa com o calculo acima da matriz.

## Exemplos e Exercícios
- #### Tendo $\vec{a} = (3\vec{i} + 2\vec{j} + 2\vec{k}), \vec{b} = (18\vec{i} - 22\vec{j} - 5\vec{k})$, calcule $|\vec{a} \times \vec{b}|$
$$\begin{bmatrix}\vec{i} & \vec{j} & \vec{k} \\ 
3 & 2 & 2 \\ 
18 & -22 & -5\end{bmatrix}$$
$$\begin{align*}
\vec{a} \times \vec{b} &=  (2 \cdot (-5) - 2 \cdot (-22))\vec{i} + (2 \cdot 18 - 3 \cdot(-5))\vec{j} + (3 \cdot (-22) - 2 \cdot 18)\\
\vec{a} \times \vec{b} &= 34\vec{i} + 51\vec{j}-102\vec{k}\\
|\vec{a} \times \vec{b}| &= \sqrt{34^{2}+51^{2}+(-102)^{2}}\\
|\vec{a} \times \vec{b}| &= 119
\end{align*}$$