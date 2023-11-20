# Sistemas Lineares

## Definição
É um sistema de equações lineares do tipo $a_{11}x_{1}+a_{12}x_{2}+\cdots+a_{1n}x_{n}=b_{1}$ onde $a_{ij}\in \mathbb{R}$ são ditas **coeficientes** e $b_{j}$ termos constantes. Cada uma dessas equações são ditas lineares que não são produtos entre as incógnitas $x_{1}, x_{2}, \cdots, x_{n}$. Por exemplo
$$\left\{ \begin{align*} x - 3y + z &= 1\\ x^{2}+3y-z&= 2\\ x-y+2z&= 3 \end{align*} \right .$$

 é não-linear. O elemento $x_{1}, x_{2}, \cdots, x_{n}$ tem que ser solução do sistema satisfazendo todas as equações. 
$$\left\{ \begin{align*}
2x-y&= 2\\
x + 3y &= -1
\end{align*} \right.$$
Uma forma de determinar a solução seria $l_{1}\leftarrow l_{1}-2l_{2}$ donde $-7y = 4$, ou seja, $y = \frac{-4}{7} \Rightarrow x = \frac{5}{7}$

## Operações
Ao executarmos as seguintes operações num sistema linear, seu conjunto solução não muda:
1. Multiplicar uma equação por uma constante $c \neq 0$
2. Somar uma equação com outra que é resultado do item anterior.
3. Permutar equações

## Método de escalonamento (ou eliminação Gaussiana)
Cada primeiro elemento nã-nulo numa linha é chamado **pivô**. Um sistema estará escalonado se cada pivô está à direita do pivô na linha anterior e abaixo dela só há zeros. Note que os simbolos das incógnitas exercem papeis figurativos. 

#### Exemplo:
$$\left\{ \begin{align*}
&x + z - 2w = -3\\
&2x - y + 2z -w = -5\\
&-6y - 4z + 2w = 2\\
&x + 3y + 2z + w = 1\\
\end{align*} \right.$$
$$\begin{pmatrix} 1 & 0 & 1 & -2 \\ 2 & -1 & 2 & -1 \\ 0 & -6 & -4 & 2 \\ 1 & 3 & 2 & -1\end{pmatrix}\begin{pmatrix}-3 \\ -5 \\ 2 \\ 1\end{pmatrix} \quad \begin{align*} l_{2}&\leftarrow l_{2}-2l_{1}\\ &\Longrightarrow\\ l_{4}&\leftarrow l_{4}-l_{1} \end{align*} \quad \begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & -6 & -4 & 2 \\ 0 & 3 & 1 & 1\end{pmatrix}\begin{pmatrix}-3 \\ 1 \\ 2 \\ 4\end{pmatrix}$$
$$\begin{align*}
l_{3}&\leftarrow l_{3}-6l_{2}\\
&\Longrightarrow\\
l_{4}&\leftarrow l_{4}+3l_{2}
\end{align*} \quad \begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & 0 & -4 & -16 \\ 0 & 0 & 1 & 10\end{pmatrix}\begin{pmatrix}-3 \\ 1 \\ -4 \\ 7\end{pmatrix}$$
$$\begin{align*}
l_{4}&\leftarrow l_{4} - \frac{1}{4}l_{3}\\
&\Longrightarrow
\end{align*}\begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & 0 & -4 & -16 \\ 0 & 0 & 0 & 14\end{pmatrix}\begin{pmatrix}-3 \\ 1 \\ -4 \\ 8\end{pmatrix}$$
Assim, esse sistema tem solução dada por:
$$\begin{align*}
l_{4}&:14w =8\Rightarrow &w=\frac{4}{7}\\
l_{3}&: -4z -16w=-4\Rightarrow z+4w=1\Rightarrow &z =\frac{-9}{7}\\
l_{2}&:-y+3w=1\Rightarrow &y=\frac{5}{7}\\
l_{1}&: x + z - 2w=-3 \Rightarrow x - \frac{9}{7} - \frac{8}{7}=-3\Rightarrow &x = \frac{-4}{7}
\end{align*}$$

Tome
$$A = \begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & 0 & -4 & -16 \\ 0 & 0 & 0 & 14\end{pmatrix}, U = \begin{pmatrix}1 & 0 & 1 & -2 & -3 \\ 0 & -1 & 0 & 3 & 1 \\ 0 & 0 & -4 & -16 & -4 \\ 0 & 0 & 0 & 14 & 8\end{pmatrix}$$
Chamamos de **Matriz Elementar** uma matriz obtida da matriz identidade por operações elementares.
$$I = \begin{pmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1\end{pmatrix}$$
$$E_{1} = \begin{pmatrix}1 & 0 & 0 & 0 \\ -2 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1\end{pmatrix}$$
$$E_{1}A=\begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & -6 & -4 & 2 \\ 1 & 3 & 2 & -1\end{pmatrix}$$
$$E_{2}= \begin{pmatrix}1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ 1 & 0 & 0 & 1\end{pmatrix}$$
$$E_{2}(E_{1}A)=\begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & -6 & -4 & 2 \\ 0 & 3 & 1 & 1\end{pmatrix}$$
Seguindo esse modo
$$E_{5}\Bigg(E_{4}\bigg(E_{3} \Big(E_{2} \big( E_1A\big) \Big)  \bigg)\Bigg) = U$$
Cada matriz $E_{j}$ tem inversa denotada por $L_{j}$
$$A = E^{-1}_{1}E_{2}^{-1}E_{3}^{-1}E_{4}^{-1}E_{5}^{-3}U = LU$$
A matriz $L$ é obtida guardando em cada posição em que se zera pelo oposto do escalar correspondente. Neste caso:
$$L = \begin{pmatrix}1 & 0 & 0 & 0 \\ 2 & 1 & 0 & 0 \\ 0 & 6 & 1 & 0  \\ 1 & -3 & \frac{1}{4} & 1\end{pmatrix}$$
Portanto $Ax = b$ tal que $LUx = b$. Fazendo $Ux = y$ temos que $Ly = b$

$$\begin{matrix}\begin{pmatrix}1 & 0 & 0 & 0 \\ 2 & 1 & 0 & 0 \\ 0 & 6 & 1 & 0  \\ 1 & -3 & \frac{1}{4} & 1\end{pmatrix}\end{matrix}\begin{pmatrix}y_1 \\ y_2 \\ y_3 \\ y_4\end{pmatrix} = \begin{pmatrix}-3 \\ -5 \\ 2 \\ 1 \\ \end{pmatrix}$$
$$\begin{align*}
&&y_{1}&=-3\\
2y_{1}+y_{2}&=-5 \Rightarrow &y_2&=1\\
6y_{2}+y_{3}&=2 \Rightarrow &y_{3}&= -4\\
y_{1}-3y_{2} + \frac{y_{3}}{4}+y^{4}&= 1 \Rightarrow &y_{4} &= 8
\end{align*}$$
Donde
$$\begin{pmatrix}1 & 0 & 1 & -2 \\ 0 & -1 & 0 & 3 \\ 0 & 0 & -4 & -16 \\ 0 & 0 & 0 & 14\end{pmatrix}\begin{pmatrix}x \\ y \\ z \\ w \\ \end{pmatrix} = \begin{pmatrix}-3 \\ 1 \\ -4 \\ 8\end{pmatrix}$$
