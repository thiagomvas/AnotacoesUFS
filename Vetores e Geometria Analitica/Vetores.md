# Vetores
#VetoresEGeometriaAnalitica

## Definição:
É um segmento de reta que representa uma medida que contem:
- Tamanho (Módulo)
- Direção
- Sentido
![[GraficoVetores.png]]
Temos também que:
$$
\begin{align*}
\sin{\theta} =& \dfrac{v_y}{v} \Rightarrow v_y = v \cdot \sin{\theta} \\
\cos{\theta} =& \dfrac{v_x}{v} \Rightarrow v_x = v \cdot \cos{\theta}\\ \tan{\theta} =& \dfrac{v_y}{v_x} = \dfrac{y_2 - y_1}{x_2 - x_1} \\
\end{align*}
$$
## Operações com vetores
### Soma e Subtração com vetores paralelos
Basta somar/subtrais seus módulos.
#### Exemplo:
Considere os vetores abaixo, como eles são paralelos, basta somarmos seus módulos para obtermos o vetor soma. Logo: $\vec{v} + \vec{w} = 9u + (-6u) = 3u \Rightarrow \vec{s} = 3u$
![[SomaDeVetores.png]]
### Soma e Subtração de vetores perpendiculares
Com vetores perpendiculares entre si não ocorre subtração, o que ocorre na verdade é que o vetor terá um sinal negativo $(-\vec{v})$ significando que está em seu sentido oposto. Para calcular este vetor basta aplicar o **Teorema de Pitágoras**.
#### Exemplo
Considere os vetores $\vec{v}$ e $\vec{w}$, como eles são paralelos, basta utilizarmos o Teorema de Pitágoras para encontrar o vetor soma. Logo, $s^2 = v^2 + w^2 = 3^2 + 4^2 = 5^2.$ Logo, o vetor $\vec{s}$ terá módulo ${5u}$
![[SomaDeVetores2.png]]
### Soma e Subtração de vetores oblíquos
Com vetores oblíquos entre si, ou seja, formando um ângulo diferente de $0°, 90°, 180°$. Este calculo usará a regra do paralelogramo e, para descobrir seu módulo, a lei dos cossenos, cuja formula é:
$$hipotenusa^2 = cateto_1^2 + cateto_2^2 - 2 \cdot cateto_1 \cdot cateto_2 \cdot \cos{\theta}$$
#### Exemplo:
Considere os vetores $\vec{v}$ e $\vec{w}$. Ao usarmos a regra do paralelogramo temos o polígono resultante da regra. Considere $\theta = 60°$. Em seguida, basta calcularmos o seu módulo:
$$\begin{align*}
s^2 =& \ v^2 + w^2 - 2 \cdot v \cdot w \cdot \cos{\theta}\\
s^2 =& \ 3^2 + 4^2 - 2 \cdot 3 \cdot 4 \cdot \cos{60°}\\
s^2 =& \ 9 + 16 - 24 \cdot 0.5\\
s^2 =& \ 16 + 9 - 12\\
s^2 =& \ 13\\
s =& \sqrt{13} \approx 3.6u
\end{align*}$$
![[SomaDeVetores3.png]]
### Multiplicação de um vetor por um numero real
Neste caso, basta simplesmente multiplicarmos o modulo do vetor pelo numero e teremos o resultado.