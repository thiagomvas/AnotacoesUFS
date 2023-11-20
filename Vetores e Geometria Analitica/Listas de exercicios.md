# Lista 2
## 1) Considere os pontos $A(1, 2, 3), B(0, 1, 2), C(0,0,3), D(1,2,0)$. Quais desses pontos estão :
### i) No plano $xy$?
Basta olharmos os pontos cujo coordenadas no eixo $z$ é igual à $0$ e nos outros eixos é diferente de 0, ou seja, somente o ponto $D$.
### ii) No eixo $z$?
Basta olharmos os pontos cujo coordenadas nos eixos $x$ e $y$ são iguais à 0, cujo indica  que está no eixo $z$, ou seja, somente o ponto $C$
### iii) No plano $yz$?
Basta olharmos os pontos cujo coordenada no eixo $x$ é igual à $0$ e nos outros eixos é diferente de 0. Ou seja, somente o ponto $B$.

## 2) Tente descrever as figuras geométricas descritas pelas equações:
### a) $z \leq 2$ em $3D$.
Representa a região no espaço tridimensional que se estende infinitamente em todas as direções nos eixos $x$ e $y$, mas está limitada a estender apenas abaixo ou até $z \leq 2$.
### b) $x = 4$ em $2D$.
Num plano $xy$, será uma reta vertical paralela ao eixo $y$ que passa por $x = 4$ que se estende infinitamente acima e abaixo do eixo $x$
### c) $y \geq 0, z \geq 0$ em $2D$.
Representa o primeiro quadrante do plano $yz$, onde todos os pontos devem fazer parte da região em que as coordenadas em ambos os eixos são positivas ou iguais a $0$
### d) $z \geq 0, y \geq 0, x \geq 0$ em $3D.$
Representa o primeiro octante do espaço $xyz$, em que os valores das coordenadas em todos os eixos devem ser positivas ou iguais a $0$

## 3) Sabendo o extremo de um segmento retilíneo desde $A(2, 3, -1)$ e seu ponto médio $C(-1, -3, 1)$, encontre o outro extremo $B(x,y,z)$.
Sabendo que $C$ é o ponto medio do segmento $AB$, para encontrarmos as coordenadas de $B$, basta calcularmos a distancia entre as coordenadas nos eixos $x, y$ e $z$ do ponto $A$ ao ponto $C$, e somarmos ao ponto $C$, encontrando as coordenadas de $B$. Isto é:
$$B = \left \{ \begin{matrix} 
B_x = C_x + (C_x - A_x) = -1 + (-1 - 2) = -4\\
B_y = C_y + (C_y - A_y) = -3 + (-3 - 3) = -9\\
B_z = C_z + (C_z - A_z) = 1 + (1 - (-1)) = 3\\
\end{matrix} \right.$$
Logo, o ponto $B$ será $B(-4, -9, 3)$

## 4) Considere a figura da esfera ao lado e um ponto P se movendo sobre ela de tal modo que sua distância ao centro $P_0(x_0, y_0, z_0)$ da esfera é sempre constante e igual a a. Mostre que:
### a) a equação desta esfera é $(x − x_0 )^2 + (y − y_0 )^2 + (z − z_0 )^2 = a^2$ . 
Sabendo que a distância entre dois pontos em um plano $3D$ é dada por $d^2 = \Delta x^2 + \Delta y ^2 + \Delta z^2$ onde $\Delta$ representa a diferença entre as duas coordenadas no dado eixo. Sabendo também que essa distância será constante, irá então formar uma esfera quando considerarmos todos os pontos em que a distância será $d$, consequentemente essa mesma distância $d$ será seu raio, logo temos que a equação dessa esfera, tomando $a$ como raio será $a^2 = (x − x_0 )^2 + (y − y_0 )^2 + (z − z_0 )^2$
### b) Se o centro é o ponto $(0, 0, 0)$ qual a equação da esfera? 
Utilizando a mesma formula que foi mostrada, e sabendo que a diferença entre um valor e 0 é o próprio valor, temos então que a equação da esfera será $a^2 = (x − 0 )^2 + (y − 0 )^2 + (z − 0 )^2 = x^2 + y^2 + z^2$
### c) Suponha que o movimento é realizado apenas sobre o plano $xy$ com as mesmas condições. Encontre a equação da circunferência neste plano
Definindo os pontos $O(x_0, y_0), P(x, y)$, $O$ sendo o centro da circunferência e $P$ sendo um ponto que define a distancia $a$ entre todos os pontos no perímetro da circunferência, temos que a equação será $a^2 = \Delta x^2 + \Delta y^2 = (x - x_0)^2 + (y - y_0)^2$
![[ListaDouglasQ4L2.png]]

## 5) Obtenha retas perpendiculares às retas dadas:
### a) $x - 2y + 3 = 0$
$$2y = x + 3 \Rightarrow y = \dfrac{x}{2} + \dfrac{3}{2} \Rightarrow coef_{normal} = \dfrac{1}{2}$$
$$coef_{perpen.} = - (\dfrac{1}{2})^{-1} = -2$$
Logo a equação geral da reta será $y = ax + b = -2x + b$
### b) $x + y - 1 = 0$
$$-y = x - 1 \Rightarrow y = 1 - x \Rightarrow m = -1$$
O coeficiente angular de  reta perpendicular será então $n = - (m)^{-1} = - (-1)^{-1} = 1$. Então a equação da reta perpendicular será $y = nx + b = x + b$ onde $b$ varia em $\mathbb{R}$ 
### c) $2x - y + 10 = 0$
$$y = 2x + 10 \Rightarrow m = 2$$
$$n = -(m)^{-1} = -(2)^{-1} = -\dfrac{1}{2}$$
Logo a equação de uma reta perpendicular será $y = -\dfrac{x}{2} + b$
### d) $3x + y - 1 = 0$
$$-y = 3x - 1 \Rightarrow y = 1 - 3x \Rightarrow m = -3$$
$$n = -(-3)^{-1} = \dfrac{1}{3}$$
Logo, a equação de uma reta perpendicular será $y = \dfrac{x}{3} + b$

## 6) Obtenha a reta perpendicular à reta
### a) $x - 4y + 3 = 0$ cruzando o ponto $(0, 0)$
$$4y = x + 3 \Rightarrow m = \dfrac{1}{4}$$
$$n = -(\dfrac{1}{4})^{-1} = 4$$
A equação de uma reta perpendicular então será $y = 4x + b$. Sabendo disso, para encontrar a reta que passa em $(0, 0)$, temos que $0 = 4 \times 0 + b \Rightarrow b = 0$. Logo, a reta perpendicular que passa em $(0,0)$ será $y = 4x$
### b) $x + 2y - 1 = 0$ cruzando o ponto $(1, 0)$
$$- 2y = x - 1 \Rightarrow y = \dfrac{1}{2} - \dfrac{x}{2} \Rightarrow m = -\dfrac{1}{2} \Rightarrow n = 2$$
A equação de uma reta perpendicular será $y = 2x + b$, para que ela cruze em $(1, 0)$ temos então $0 = 2 \times 1 + b \Rightarrow b = -2$, então, a reta perpendicular que cruza nesse ponto será $y = 2x - 2$.
### c) $2x - 2y + 1 = 0$ cruzando o ponto $(-1, 2)$
$$-2y = 2x + 1 \Rightarrow y = x - \dfrac{1}{2} \Rightarrow m = 1 \rightarrow n = -1$$
A equação de uma reta perpendicular será $y = -x + b$, para encontrar a reta que cruza em $(-1, 2)$ teremos então que $2 =1 + b \Rightarrow b = 2$, então, a reta será $y = -x + 2$
### d) $3x + 2y - 1 = 0$ cruzando o ponto $(0, 0)$
$$-2y = 3x - 1 \Rightarrow  y= 1 - \dfrac{3x}{2} \Rightarrow m = \dfrac{3}{2} \Rightarrow n = -\dfrac{2}{3}$$
A equação de uma reta perpendicular será $y = -\dfrac{2x}{3} + b$. Para encontrar a reta que cruza a origem, temos então que $0 = -\dfrac{0}{3} + b \Rightarrow b = 0$, logo, a equação da reta será $y = -\dfrac{2x}{3}$
## 7) Determine as equações das retas que passam pelos pontos:
### a) $A(0, 0), B(2, 1)$
$$\begin{matrix}
m = \dfrac{1 - 0}{2 - 0} = 0.5\\
0 = 0.5\times 0 + b \Rightarrow b=  0\\
y = 0.5x
\end{matrix}$$

### b) $A(-1, 0), B(-2, 1)$
$$\begin{matrix} 
m = \dfrac{1 - 0}{-2 - (-1)} = \dfrac{1}{-1} = -1 \\ 
0 = -1\times(-1) + b \Rightarrow b = -1 \\ 
y = -x - 1
\end{matrix}$$
### c) $A(3, -2), B(2, 1)$
$$\begin{matrix}
m = \dfrac{1 - (-2)}{2 - 3} = \dfrac{3}{-1} = -3 \\ 
-2 = -3 \times 3 + b \Rightarrow b  = 7 \\ 
y = -3x +7
\end{matrix}$$
### d) $A(0,0), B(0, -1)$
Como ambos os pontos estão no eixo $y$ a equação da reta será $x = 0$
### e) $A(0, a), B(-a, a)$
$$\begin{matrix}
m = \dfrac{a - a}{-a - 0} = \dfrac{0}{-a} = 0 \\ 
a = 0 +b \Rightarrow b = a \\ 
y = 0x + a = a
\end{matrix}$$
### f) $A(a, -a), B(-b, b)$
Dado que $f(a) = a$ e $f(-b) = b$, é perceptível que a função simplesmente calcula o oposto do valor, ou seja, $y = -x$





## 8)  Determine:
### a) A equação da reta que passa pelo ponto (0, 2) e tem declividade $m = -1$
$$\begin{matrix}
m = -1 \\ 
2 = 1 \times 0 + b \Rightarrow b = 2 \\ 
y = -x + 2
\end{matrix}$$
### b) A equação da reta formando ângulo de $30°$ com o eixo $x$ e passando por $(0, 1)$
$$\begin{matrix}
m = \tan{30°} = \frac{\sqrt{3}}{3} \\ 
1 = \frac{\sqrt{3}}{3}0 + b \Rightarrow b = 1 \\ 
y = \frac{\sqrt{3} \times x}{3}+ 1
\end{matrix}$$
### c) A equação da reta formando ângulo de $45°$ com o eixo $y$ e passando por $(1, -1)$
$$\begin{matrix}
m = \tan{45°} = 1 \\
-1 = 1 \times 1 + b \Rightarrow b = -2 \\ 
y = x - 2
\end{matrix}$$
### d) A equação da reta formando ângulo de $20°$ com o eixo $x$ e passando por $(1, 2)$
$$\begin{matrix}
m = \tan{20°} \approx 0.364 \\ 
2 = 0.364 \times 1 + b \Rightarrow b \approx 1.636 \\ 
y = 0.364x + 1.636
\end{matrix}$$
