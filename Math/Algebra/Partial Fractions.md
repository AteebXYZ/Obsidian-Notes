
Rules:
$$
\begin{gather}
&\text{As many constants as brackets in denominator:} \\
&\frac{x+3}{(x+1)(x+2)} = \frac{A}{x+1} + \frac{B}{x+2} \\ \\
&\frac{(3x^{2}+2x+1)}{(x+1)(x+2)(x+3)} = \frac{A}{x+1}+\frac{B}{x+2}+\frac{C}{x+3} \\
& \\
&\text{Repeated linear factors:} \\
& \frac{x-3}{(x-a)(x-b)^{2}} = \frac{A}{(x-a)} + \frac{B}{(x-b)} + \frac{C}{(x-b)^{2}} \\ \\
& \frac{x+4}{x^{2}(x-6)} = \frac{A}{x}+\frac{B}{x^{2}}+\frac{C}{x-6} \\ \\
& \text{Quadratic factor in denominator that cannot be factorised} \\
& \frac{x+6}{(x-10)(x^{2}+4)} = \frac{A}{x-10} + \frac{Bx+C}{x^{2}+4}

\end{gather}

$$

These rules only apply to proper fractions though, to determine if a fraction is improper or proper, we look at the power of ${}x{}$ in the numerator and denominator. If the degree of x in the numerator is higher than or equal to the degree of ${}x{}$ in the denominator, it's considered an improper fraction.

For example this is an improper fraction:
$$
\frac{2x^{2}+5x-11}{x^{2}+2x-3} \implies \frac{2x^{2}+5x-11}{(x-1)(x+3)} = A + \frac{B}{x-1}+\frac{C}{x+3}
$$

Dividing polynomials:
$$

\begin{gather}
&(2x^{2}+3x+5) \div  (2x+3) \\
&\downarrow\\ 

& \begin{array}{r}
	x \\
2x+3 \enclose{longdiv}{2x^2+3x+5} \\
	\underline{-(2x^2+3x)} \\
	\underline{0+5} \\
	\underline{5}
\end{array} \\  \\
&\text{The answer is }x\text{ remainder 5, which is written as:} \\ \\
&x+\frac{5}{2x+3}

\end{gather}

$$

We first did ${}\frac{2x^{2}}{2x}{}$ which equals ${}x{}$, so we write x at the top. Then, multiply ${}x{}$ with ${}2x+3{}$ to get ${}2x^{2}+3x{}$ which we subtract from the equation. Then do long division as normal.

Another example:
$$
\begin{gather} \\

&\begin{array}{r}
	2 \\
x^{2}+2x-3 \enclose{longdiv}{2x^{2}+5x-11} \\
	\underline{-(2x^{2}+4x-6)} \\
	\underline{x-5}
	 \\
\end{array}\\ \\
  & \text{We write this as:} \\ \\
  & 2+\frac{x-5}{x^{2}+2x-3} \\ \\
  & \text{After factorising the denominator:} \\ \\
  & 2 + \frac{x-5}{(x-1)(x+3)}  \\ \\
  &  \text{You can turn this into a partial fraction by solving as a proper fraction}
 
\end{gather}
$$

![[Partial Fractions-1792424441305.webp]]


$$
\begin{flalign}
&\text{$f(x)$ is a proper fraction} \\ \\
&\frac{x}{(3-2x)(2-x)} = \frac{A}{(3-2x)} + \frac{B}{(2-x)} \\ \\
&x = A(2-x) + B(3-2x) \\ \\
&x = 2 \implies 2 = A(0) + B(-1) \\ \\
&B = -2 \\ \\
&x = \frac{3}{2} \implies \frac{3}{2} = A\left( 2-\frac{3}{2} \right) - 2\left( 3-2\left( \frac{3}{2} \right) \right) \\ \\
&A = 3 \\ \\
&f(x) = \frac{3}{(3-2x)} - \frac{2}{(2-x)} \\ \\ \\ \\
&f(x) = 3(3-2x)^{-1} - 2(2-x)^{-1} \\ \\
&3(3-2x)^{-1} = 3 \cdot 3^{-1}\left(1 - \frac{2}{3}x\right)^{-1} = \left(1 - \frac{2}{3}x\right)^{-1} \\ \\
&\left(1 - \frac{2}{3}x\right)^{-1} = 1 + (-1)\left(-\frac{2}{3}x\right) + \frac{(-1)(-2)}{2!}\left(-\frac{2}{3}x\right)^{2} + \dots \\ \\
&= 1 + \frac{2}{3}x + \frac{4}{9}x^{2} \\ \\ \\ \\
&-2(2-x)^{-1} = -2 \cdot 2^{-1}\left(1 - \frac{x}{2}\right)^{-1} = -\left(1 - \frac{x}{2}\right)^{-1} \\ \\
&-\left(1 - \frac{x}{2}\right)^{-1} = -\left( 1 + (-1)\left(-\frac{x}{2}\right) + \frac{(-1)(-2)}{2!}\left(-\frac{x}{2}\right)^{2} + \dots \right) \\ \\
&= -\left(1 + \frac{1}{2}x + \frac{1}{4}x^{2}\right) = -1 - \frac{1}{2}x - \frac{1}{4}x^{2} \\ \\ \\ \\
&f(x) = \left(1 + \frac{2}{3}x + \frac{4}{9}x^{2}\right) + \left(-1 - \frac{1}{2}x - \frac{1}{4}x^{2}\right) \\ \\
&= \frac{1}{6}x + \frac{7}{36}x^{2} \\ \\
& \text{To find the range of value for which the expansion is valid:} \\ \\ 
&(1+u)^{n} \rightarrow |u| < 1 \\ \\ 
&\left( 1-\frac{2}{3}x \right)^{-1} \rightarrow|-\frac{2}{3}x|<1 \rightarrow \frac{2}{3}|x| < 1 \therefore -\frac{2}{3}<x< \frac{2}{3} \\ \\
&\text{Doing the same for }\left( 1-\frac{x}{2} \right)\text{ gives us} -2<x<2 \\ \\ 
&-\frac{2}{3}<x< \frac{2}{3} \text{ is the stricter range }

\end{flalign}


$$

