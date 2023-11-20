# Argumentos e retas de Inferência
Sejam $P_{1}, P_{2},P_{3},...,P_{n}$ e $Q$ [[Calculo Proposicional#Proposição|proposições]] qualquer. Um argumento de inferência é uma afirmação em que as proposições $P_{1}, P_{2},..., P_{n}$ tem como consequência ou acarretam $Q$.

## Notação
$$P_{1,}P_{2}, P_{3},..., P_{n} \mapsto Q$$
## Definição:
$P_{1,}P_{2}, P_{3},..., P_{n} \mapsto Q$ é valido se e somente se $Q$ é verdadeiro sempre que suas premissas são verdadeiras. Isto é, $P_{1}\land P_{2}\land ... \land P_{n}\Rightarrow Q$ é tautologia

## Regras de Inferência
1. **Adição (AD) :** $p \mapsto p \lor q$
2. **Simplificação (Simp.) :** $p \land q \mapsto p$ ou $p \land q \mapsto q$
3. **Conjunção (Conj.) :** $p, q \mapsto p \land q$
4. **Modus Ponens (MP) :** $p \Rightarrow q, p \mapsto q$
5. **Modus Tollens (MT) :** $p \Rightarrow q, \lnot q \mapsto \lnot p$
6. **Absorção (ABS) :** $p \Rightarrow q \mapsto p \Rightarrow (p \land q)$
7. **Silogismo Disjuntivo (SD) :** $p \lor q, \lnot q \mapsto p$
8. **Silogismo Hipotético (SH) :** $p \Rightarrow q, q \Rightarrow r \mapsto p \Rightarrow q$
9. **Dilema Construtivo (DC) :** $p \Rightarrow q, r \Rightarrow s, p \lor r \mapsto q\lor s$
10. **Dilema Destrutivo (DD) :** $p \Rightarrow q, r \Rightarrow s, \lnot q \lor \lnot s \mapsto \lnot p \lor \lnot s$

## Exemplos
### Prove que as seguinte expressões são validas:
-  $p \Rightarrow q, r \lor \lnot q, \lnot r, \mapsto \lnot p$
	1) $p \Rightarrow q$
	2) $r \lor \lnot q$
	3) $\lnot r$
	4) $q \Rightarrow r$ ($\equiv 2$)
	5) $p \Rightarrow r$ (1, 4: SH)
	6) $\lnot p$ (3, 5: MT)
- $p \Rightarrow q, q \Rightarrow (r \lor s), (r \lor s) \Rightarrow t, (p \Rightarrow t) \Rightarrow u \mapsto u$
	1) $p \Rightarrow q$
	2) $q \Rightarrow (r \lor s)$
	3) $(r \lor s) \Rightarrow t$
	4) $(p \Rightarrow t) \Rightarrow u$
	5) $p \Rightarrow (r \lor s)$ (1, 2: SH)
	6) $p \Rightarrow t$ (3, 5: SH)
	7) $u$ (4, 6: MP)
- $(p \to q) \to r, \lnot r, (\lnot p \lor \lnot q) \lor s \mapsto s$
	1. $(p \to q) \to r$
	2. $\lnot r$
	3. $(\lnot p \lor \lnot q) \lor s$
	4. $\lnot  (p \to q)$
	5. $\lnot (p \land q) \lor s$
	6. $(p \land q) \to s$ 