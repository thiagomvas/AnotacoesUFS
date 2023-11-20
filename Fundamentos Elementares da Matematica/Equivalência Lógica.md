# Equivalência Lógica
Dizemos que uma [[Calculo Proposicional#Proposição|Proposição]] $P$ é logicamente equivalente a $Q$ se elas possuem a mesma tabela-verdade.

## Notação
$$P \equiv Q$$
## Exemplo
- $(p \Rightarrow p \land q) \equiv p \Rightarrow q$ 
$$\begin{bmatrix}
p & q & p \land q & p \Rightarrow p \land q & p \Rightarrow q \\
V & V & V & V & V \\
V & F & F & F & F \\
F & V & F & V & V \\
F & F & F & V & V 
\end{bmatrix}$$
É perceptível como os valores lógicos de $p \Rightarrow p \land q$ são idênticos a $p \Rightarrow q$, logo, são **equivalentes**


## Propriedades

## Exemplo:
- $\lnot (p \lor q) \equiv \lnot p \land \lnot q$
$$\begin{bmatrix}
p & q & p \lor q & \lnot (p \lor q) & \lnot p & \lnot q & \lnot p \land \lnot q \\
V & V & V & F & F & F & F \\
V & F & V & F & F & V & F \\
F & V & V & F & V & F & F \\
F & F & F & V & V & V & V 
\end{bmatrix} $$
Logo, essa equivalência está correta.