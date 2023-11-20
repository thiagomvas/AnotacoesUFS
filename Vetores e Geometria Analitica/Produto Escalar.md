# Produto Escalar
Produto escalar entre dois [[Vetores]] $\vec{v}$ e $\vec{w}$ é definido pela soma dos produtos de suas componentes, ou seja:
$$\vec{v} \cdot \vec{w} = v_xw_x +v_yw_y + v_zw_z$$
Se esses vetores são definidos em um plano 2D, então basta calcular com os componentes nos dois eixos. Além disso, quando calculado o produto escalar de dois vetores idênticos (ou o mesmo vetor) seja $\vec{v} \cdot \vec{v}$ ou $\vec{v} \cdot \vec{w}, \vec{v} = \vec{w}$, temos que o resultado será denotado por $|\vec{v}^2|$.

As propriedades básicas de aritmética também se aplicam a vetores, ou seja, a ordem dos fatores de um produto não afetam a soma, $k\cdot(\vec{v} \cdot \vec{u}) = (k\cdot\vec{v})\cdot\vec{u} = \vec{v}\cdot(k\cdot\vec{u})$, etc.

## Produto escalar em termos do ângulo entre vetores.

### Teorema
Denotando $\theta$ como o ângulo entre dois vetores $\vec{a}$ e $\vec{b}$, então temos que seu produto escalar será
$$\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos{\theta}$$
Dependendo do ângulo $\theta$ entre os vetores, o seu sinal também será diferente:

$$ \begin{matrix}
\mbox{Produto Escalar} & \mbox{Angulo }\theta \\
\vec{a} \cdot \vec{b} \geq 0 & 0 \leq \theta \leq \dfrac{\pi}{2}\mbox{(90°)} \\
\vec{a} \cdot \vec{b} < 0 & \dfrac{\pi}{2} < \theta \leq \pi\mbox(180°) 
\end{matrix}$$

## Cossenos diretores
Dado um vetor $\vec{v}$, com seus componentes $v_x, v_y, v_z$ , e dados os vetores $\vec{i}, \vec{j}, \vec{k}$ como os vetores que representam os eixos $X, Y, Z$ respectivamente, temos que os cossenos diretores serão dados por
- $\vec{v} \cdot  \vec{i} = |\vec{v}| |\vec{i}| \cos{\alpha}$
- $\vec{v} \cdot  \vec{j} = |\vec{v}| |\vec{j}| \cos{\beta}$
- $\vec{v} \cdot  \vec{k} = |\vec{v}| |\vec{k}| \cos{\gamma}$

Com trigonometria, também é possivel calcular seus componentes:
- $v_x = v \cos{\alpha}$
- $v_y = v \cos{\beta}$
- $v_z = v \cos{\gamma}$

![[CossenosDiretores.png]]

