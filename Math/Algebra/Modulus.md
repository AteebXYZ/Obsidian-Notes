A modulus gives the absolute value of whatever is inside it, e.g, ${}|-4| = 4{}$. Modulus ${}x{}$ will give us a graph that looks like this:
```desmos-graph
left=-40.32; right=40.33; top=43.91; bottom=-12.55
---
y= \abs(x)
```

A modulus function can be solved like this:
$$
|x-2|=4\\
x-2=\pm 4\\
{\color{cyan}x=6\quad x=-2}
$$
We can check by doing, ${}|6-2| = 4{}$ and ${}|-2-2| = 4{}$ which are both true.

Another example:
$$
\begin{gather}
&|x+2|=|3x| \\
&x+2 = 3x \implies {\color{cyan}x=1}  \\
&x+2=-3x \implies {\color{cyan}c=-\frac{1}{2}} \\
& \\
&\text{Check: } \\
&|1+2|=|3|\implies {\color{green}3=3} \\
&|-\frac{1}{2}+2|=|3\times-\frac{1}{2}|\implies {\color{green} \frac{3}{2} = \frac{3}{2}}
\end{gather}
$$

Checking is always important because sometimes solutions can include imaginary solutions:

$$
\begin{gather}
&2x=|x-3|  \\
&x-3=2x \implies x=-3 \\
&x-3=-2x \implies x=1 \\
& \\
&\text{Check:} \\
&2(-3)=|-3-3| \\
& {\color{red}-6=6} \implies x\neq-3 \\
& 2(1)=|1-3|  \\
& {\color{green}2=2}\implies {\color{cyan}x=1}
&\end{gather}
$$

#### Solving inequalities containing modulus functions

$$
\begin{gather}
&|2x-1| > |3-x| \\
&(2x-1)^{2}>(3-x)^{2} \\
&4x^{2}-4x+1>x^{2}-6x+9 \\
&3x^{2}+2x-8>0 \\
&3x^{2}+6x-4x-8\implies(3x-4)(x+2)
 
\end{gather}
$$
```desmos-graph
left=-3.244; right=2.705; top=11.93; bottom=-10.74
---
y=3x^{2}+2x-8
(-2,0)|LABEL
(4/3,0)|LABEL
```
$$
{\color{cyan}x<-2\\}
{\color{cyan}x> \frac{4}{3}}

$$