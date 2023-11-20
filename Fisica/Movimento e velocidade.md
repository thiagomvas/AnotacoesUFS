#Fisica
# Movimento e velocidade

## Definições
- Velocidade escalar média: $V_{esc}=\frac{d}{\Delta t}$ 
- Velocidade média: $\vec{V}_{med} = \frac{\Delta r}{\Delta t}= \frac{\vec{r}_{f}- \vec{r}_{i}}{\Delta t}$
- Velocidade instantânea: $\vec{V} = \underset{\Delta t \to 0} \lim \Delta \vec{r} = \dfrac{d\vec{r}}{dt}$ 

## Propriedades
#### 1: Se $x(t)$ é a função da posição, podemos [[Derivadas|derivar]] ela para encontrar a sua velocidade e sua aceleração. 
Por exemplo, seja $x(t) = 2 + 3t + \frac{9t^{2}}{2}$, temos que:
	- Sua velocidade é:
	$$\begin{align*}
v(t) &= \dfrac{dx}{dt}\\
&= 3 + 9t
\end{align*}$$
	- Sua aceleração é:
	$$\begin{align*}
a(t) &= \dfrac{dv}{dt}\\
&= 9
\end{align*}$$
#### 2: Dada sua aceleração ou velocidade, podemos encontrar a equação do movimento encontrando sua [[Primitivas|primitiva]]. 
Por exemplo, digamos que $t = 0 \Rightarrow a = 4, v(3) = 20, x(10) = 500$
$$\begin{align*}
v(t) &= \int 4dt\\
&= 4t + C\\
v(3) &= 20 \Rightarrow C  = 8\\
x(t) &= \int v(t)dt\\
&= D + 8t + \frac{4t^{2}}{2}\\
x(10) &= 500  \\
&= D + 80 + 200 \Rightarrow D = 220\\
x(t) &= 220 + 8t + 2t^{2}
\end{align*}$$
#### 3: Em um gráfico de velocidade em relação o tempo, sua area([[Integrais definidos|integral definida]]) é o deslocamento total.


## Referencias
1. [[Princípios de Física 1 - Mecânica Clássica e Relatividade - Serway.pdf]]. Capitulo 2 (pag. 37)

