When solving for a polynomial with ${}x{}$ with a degree of more than 2, we usually separate the polynomial into a (linear ${}\times{}$ linear) or (quadratic ${}\times{}$ linear) etc, so we can solve all necessary factors.

$$
\begin{gather}
& \text{Dividend } \div \text{Divisor} = \text{Quotient}\\
& \downarrow  \\
& \text{Dividend} = \text{Quotient} \times \text{Divisor} \\ \\
& \text{Cubic} = (\text{Quadratic})(\text{Linear}) 
\end{gather}
$$

A factor of the polynomial is initially given in the question but in the case that it is not given, in A2, one of the factors will almost always be ${}x = \{1, 2, 3, -1, -2, -3\}{}$ so trial and error will be sufficient.

To solve the question that asks us to find the remaining factor(s), we divide the initial polynomial by the factor which will give us another factor, we can achieve this via:
- Polynomial long division
- Comparing terms (expanding the factor on one side to match the polynomial, e.g, ${}2x^{2}+6x+4 = (x+1)(ax+b){}$ then expand)
- Synthetic division (only works when there's a linear factor involved)

#### Example with all methods:

Long division:
$$
\begin{gather}
& \text{The polynomial }x^{4} + 4x^{2} +x+a \text{ is denoted by }p(x).  \\
& \text{ It is given that }(x^{2}+x+2) \text{ is a factor of } p(x)  \\
& \text{Find the value of } a\text{ and the other quadratic factor of }p(x) \\
&  \\
& \begin{array}{r}
	x^{2} -x+3\\
x^{2}+x+2 \enclose{longdiv}{x^{4}+4x^{2}+x+a} \\
	\underline{-(x^{4}+x^{3}+2x^{2})}  \\
	\underline{-x^{3}+2x^{2}+x} \\
	\underline{-(-x^{3}-x^{2}-2x)} \\
	\underline{3x^{2}+3x+a} \\
	\underline{-(3x^{2}+3x+6)} \\
	\underline{a-6}
	  \\
\end{array}\\ \\
&\text{The remainder must be zero because we are told that the divisor is a factor} \\
&a-6=0 \therefore {\color{cyan}a = 6} \\
&\text{and the other quadratic factor is }{\color{cyan}x^{2}-x+3}
\end{gather}
$$

>[!important]
>Long division gets complicated if a coefficient of ${}x{}$ is an unknown.

Comparing:
$$
\begin{gather}
&x^{4}+4x^{2}+x+a=(x^{2}+x+2)(px^{2}+bx+c) \\
&x^{4}+4x^{2}+x+a=px^{4}+bx^{3}+cx^{2}+px^{3}+bx^{2}+cx+2px^{2}+2bx+2c \\
&x^{4}+4x^{2}+x+a=px^{4}+x^{3}(b+p)+x^{2}(c+b+2p)+x(c+2b)+2c \\
& \\
&p=1  \\
&b+p=0\implies b+1=0\implies\color{cyan}b=-1 \\
&c+b+2p=4 \implies c-1+2=4\implies\color{cyan}c=3\\
&c+2b=1 \implies 1=1\\
&2c=a\implies \color{cyan}a=6 \\
& \therefore\\
&{\color{cyan}x^{2}-x+3} \text{ is a factor and } {\color{cyan}a=6} 
\end{gather}
$$

### Remainder Theorem

**If a polynomial is divided by a linear divisor ${}(x-a){}$ then ${}f(a)=R{}$**

The reason for this is because:
$$
\begin{gather}
&\text{Dividend} = \text{Divisor}\times \text{Quotient} +\text{Remainder} \\ \\
&4x^{3}+x^{2}-3x+7=(x+2)(ax^{2}+bx+c) +R \\
& \\
&\text{Now if we set }x\text{ in a way that }(x+2)(ax^{2}+bx+c) \text{ becomes 0, we can find} \\
&\text{the remainder.} \\
& \\
&x+2=0 \implies x=-2 \\
&4(-2)^{3}+(-2)^{2}-3(-2)+7=R\implies {\color{cyan}R=-15}

\end{gather}

$$

### Factor Theorem

This is the same as the remainder theorem, but ${}x{}$ to the factor will return a remainder of 0, e.g, if the factor is ${}x+2{}$, setting ${}x{}$ to ${}-2{}$ would return a remainder of 0.

