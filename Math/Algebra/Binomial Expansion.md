In the expansion ${}(a+b)^{n}{}$ ,n can be:
- ${}\pm{}$Integer
- ${}\pm{}$Fraction

$$
^{n}C_r = \frac{n!}{r!(n-r)!}
$$
A negative factorial is impossible as:
$$
\begin{gather}
&n! = n(n-1)(n-2)(n-3)\dots \\ \\
&(-2)! = -2(-3)(-4)(-5)\dots \implies-\infty
\end{gather}
$$
But, this doesn't imply that a negative binomial coefficient is impossible:
$$

\begin{gather} \\
&^{-6}C_{2} = -\frac{6!}{2!(-6-2)!} \\ \\
& \frac{6!}{2!(-8)!} \implies \frac{(-6)(-7)\cancel{ (-8)(-9)(-10) }\dots}{2\cancel{ (-8)(-9)(-10)(-11) }\dots} \\ \\
& \frac{(-6)(-7)}{2} = 21

\end{gather}
$$

The formula for a binomial expansion is:
$$
(1+b)^{n} = 1 + \binom{n}{1}b^{1} + \binom{n}{2}b^{2} + \binom{n}{3}b^{3}\dots
$$
If we account for when n can be positive or negative, the formula becomes:
$$
(1+b)^{n} = 1+nb+\frac{n(n-1)}{2!}b^{2}+\frac{n(n-1)(n-2)}{3!}b^{3} \dots
$$
>[!important]
>This formula only works when its in the format ${}(1+b)^{n}{}$

Example expanding up to ${}x^{3}{}$:
$$
\begin{gather}
& (1+2x)^{-2} \\ \\
& 1 + (-2)(2x) + \frac{(-2)(-3)}{2!}(2x)^{2} + \frac{(-2)(-3)(-4)}{3!}(2x)^{3} \\ \\
& =1-4x+12x^{2}-32x^{3}\dots

\end{gather}
$$


