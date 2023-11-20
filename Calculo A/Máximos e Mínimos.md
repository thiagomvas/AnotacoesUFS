# Máximos e Mínimos

Considere $f$ uma função com gráfico
![[Pasted image 20230925212118.png]]
- Maior valor em $f(3) = 5, x = 3$
- Menor valor em $f(6) = 2, x = 6$

Teremos então o **Máximo Absoluto** de $f$ em $[1, 8]$ como sendo $5$ e o **Mínimo Absoluto** como $2$

## Definição
Considere $c$ no domínio $D$ em $f$, diz-se que $f(c)$ é
#### Valor Máximo Absoluto
de $f$ em $D$ quando $\forall x \in D, f(c) \geq f(x)$ 

#### Valor Mínimo Absoluto
de $f$ em $D$ quando $\forall x \in D, f(x) \geq f(c)$

#### Valor Máximo Local
de $f$ quando $\forall x \in X, f(c) \geq f(x)$, onde $X$ é um intervalo aberto que contém $c$ e valores próximos a ele que satisfaça a inequação

#### Valor Mínimo Local
de $f$ quando $\forall x \in X, f(x) \geq f(c)$, $X$ atendendo as mesmas condições que [[Máximos e Mínimos#Valor Máximo Local |Máximo Local]]
 
## Teoremas
### 1.1: Teorema de Valores Extremos
Se $f$ é continua em um intervalo fechado $[a, b]$ então existem $c, d \in [a, b]$ tal que
- $f(c)$ é [[Máximos e Mínimos#Valor Mínimo Absoluto |mínimo absoluto]] de $[a, b]$
- $f(d)$ é [[Máximos e Mínimos#Valor Máximo Absoluto |máximo absoluto]] de $[a, b]$

**OBS: A função $f$ não pode deixar de ser continua nem o intervalo deixar de ser fechado**

### 2.1: Teorema de Fermat
Se $f$ tiver um máximo ou mínimo local em $c$ e $f(c)$ existe, então sua [[Derivadas|derivada]] $f'(c) = 0$. 

Graficamente
![[Pasted image 20230925212130.png]]
$$f'(l) = 0, f'(n) = 0, f'(p) = 0$$
**OBS: O teorema só vale em uma direção. Máximo ou mínimo e $f'$ existir implica $f'(c) = 0$ e não o contrário**
## Exemplos e Exercícios
- $f(x) = x^{3}$
$$\begin{align*}
f'(x) &= 3x^{2}\\
f'(x) &= 0 \Rightarrow x = 0
\end{align*}$$
Nesse gráfico, $f'(0) = 0$ não implica máximo ou mínimo, logo não possui um.


## Ponto Critico
Um numero critico de uma função $f$ é um numero $c$ no domínio de $f$ tal que uma das condições seja atendida:
- $f'(c)$ não existe
- $f'(c) = 0$
