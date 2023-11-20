# Combinação Linear
Combinação linear é uma expressão construída a partir de um conjunto de termos multiplicados por uma constante. Por exemplo uma combinação linear de $x$ e $y$ seria qualquer expressão da forma $ax + by$. No caso de [[Vetores]], $x$ e $y$ seriam vetores, ou seja, multiplicamos vetores por constantes e somamos para termos outro vetor como resultado.

## Exemplo
Considere os vetores $\vec{v}, \vec{w}$ e $\vec{x}$ com uma origem em comum $0$ e cujos extremos são os pontos $A, B$ e $C$ respectivamente; se encontram sobre uma mesma linha reta. Dividindo o segmento $\overline{AB}$ na razão de $a : b$ e tomando $a+b=1$ por simplicidade, **mostre que $\vec{x} = a\vec{w} + b\vec{v}$**
![[CombinacaoLinear.png]]
Utilizando o gráfico acima, é possivel escrever o vetor $\vec{x}$ como $\vec{x} = \vec{v} + \vec{AC}$. Também é possivel realizarmos a relação de $\vec{AC} = a\vec{AB}$, como $\vec{AC}$ pode ser denotada como parte de $\vec{AB}$, temos que a constante $a$ seria um valor menor que $0$ para provar isso, que é de acordo com $a + b = 1$.
Como $\vec{AB} = \vec{w} - \vec{v}$  então
$$\vec{x} = \vec{v} + \vec{AC} = \vec{v} + a(\vec{w} - \vec{v}) = \vec{v} + a\vec{w} - a\vec{v} = a\vec{w} + \vec{v}(1 - a) = a\vec{w} + b\vec{v}$$
## Teorema
Quaisquer conjuntos $n + 1$ de vetores $\vec{v_1}, \vec{v_2}, ... , \vec{v_n}, \vec{v_{n + 1}}$ de um espaço $n$-dimensional $V_n$ são linearmente dependentes. Em outras palavras, os vetores de um determinado espaço poderão ser representados através da soma do produto entre os vetores e uma constante, como mostrado no exemplo acima

## Dependência Linear
Dizemos que um conjunto de vetores é linearmente dependente se é possivel formar um vetor de modo que $\vec{w} = a+1 \cdot \vec{v_1} + a_2 \cdot \vec{v_2} + ... + a_n \cdot \vec{v_n}$ . Se não, dizemos que são **Linearmente independentes**