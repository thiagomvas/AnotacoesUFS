Todas as propriedades são referentes à [[Calculo Proposicional]] e [[Equivalência Lógica]]
## Propriedades Fundamentais
$$\begin{align*}
p \Rightarrow q &\equiv \lnot p \lor q\\
p \Leftrightarrow q &\equiv (p \Rightarrow q) \land (q \Rightarrow p)  \equiv (\lnot p \lor q) \land (\lnot q \lor p)\\
\end{align*}$$
## Conjunção:
$$\begin{align*}
p \land p &\equiv p\\
p \land q &\equiv q \land p\\
p \land (q \land r) &\equiv (p \land q) \land r\\
p \land T &\equiv p\\
p \land C &\equiv C
\end{align*}$$
## Disjunção
$$\begin{align*}
p \lor p &\equiv p\\
p \lor q &\equiv q \lor p\\
p \lor (q \lor r) &\equiv (p \lor q ) \lor r\\
p \lor C &\equiv p\\
p \lor T &\equiv T
\end{align*}$$
## Negações
$$\begin{align*}
p \downarrow q &\equiv \lnot p \land \lnot q \equiv \lnot(p \lor q)\\
p \uparrow q &\equiv \lnot p \lor \lnot q \equiv \lnot(p \land q)\\
\lnot(p \Rightarrow q) &\equiv p \land \lnot q\\
\lnot (p \Leftrightarrow q) &\equiv (p \lor \lnot q) \land (\lnot q \lor p)
\end{align*}$$
## Distributiva
- $p \lor (q \land r) \equiv (p \land q) \lor (p \land r)$
## Absorção
- $p \land (p \lor q) \equiv p$
- $p \lor (p \land q) \equiv p$
## De Morgan
- $\lnot (p \land q) \equiv \lnot  p \lor \lnot q$
- $\lnot (p \lor q) \equiv \lnot p \land \lnot q$
## Equivalência da Implicação
- $p \rightarrow q \equiv \lnot p \lor q$
