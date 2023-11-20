# Continuidade
## Definição
Uma função $f$ é continua em $a$ quando o [[Limite]] $\underset{x \to a}{\lim} f(x) = f(a)$. Para que isso aconteça, deverá atender 3 pré-requisitos:
- $a$ precisa estar no domínio de $f$, ou seja, $f(a)$ deve existir
- O [[Limite]] $\underset{x \to a}{\lim} f(x) = L$ deverá existir
- $f(a) = L$
Na falha de uma das condições acima, dizemos que $f$ é descontinua em $a$.

## Exemplo
Considere a função $f(x) = \dfrac{x^2 - x - 2}{x - 2}$
$$f(1) = \dfrac{1^2 - 1 - 2}{1 - 2} =2 \Rightarrow \lim_{x \to 1} f(x) = 2 = f(1)$$
Logo, $f$ é continua em $x = 1$

## Continuidade lateral
A continuidade lateral possui a mesma ideia de **Continuidade**, porém tendo em mente a noção de [[Limites Laterais]]. Uma função é continua em uma das laterais quando seu respectivo limite for $f(a)$. Ou seja:
$$\lim_{x \to a^+} f(x) = f(a) \mbox{ ou } \lim_{x \to a^-} f(x) = f(a)$$