### Power Rule

When differentiating, it's possible that there are 2 functions that are multiplied with each other, e.g:

$$
\frac{dy}{dx}=x^{4}(x^{2}+2)
$$

We could expand, or, we can use the product rule:
$$
y=vu\\
\frac{dy}{dx}=vu'+uv'
$$
With our example:
$$
\begin{gather}
&u=x^{4}\quad v=(x^{2}+2)\quad u'=4x^{3}\quad v'=2x \\
& \\
& \frac{dy}{dx}=(x^{2}+2)(4x^{3}) + x^{4}(2x)\implies 4x^{5}+8x^{3}+2x^{5}={\color{cyan}6x^{5}+8x^{3}} 
\end{gather}
$$
And we can prove this by expanding like normal
$$
\begin{gather}
&y=x^{6}+2x^{4} \\ \\
& {\color{green}\frac{dy}{dx}=6x^{5}+8x^{3} }

\end{gather}
$$

A harder example:
$$
\begin{gather}
&\text{Differentiate } y=x^{2}(2x-3)^{5} \\
&u=x^{2}\quad v=(2x-3)^{5}\quad u'=2x\quad v'=10(2x-3)^{4} \\
& \\
& \frac{dy}{dx}=(2x-3)^{5}(2x) + (x^{2})(10(2x-3)^{4})  \\
&  \\
& \frac{dy}{dx}=2x(2x-3)^{5}+10x^{2}(2x-3)^{4} \\
& = 2x(2x-3)^{4}((2x-3)+5x)\implies {\color{cyan}2x(2x-3)^{4}(7x-3)}
\end{gather}
$$



### Quotient Rule

If 2 functions are divided with each other:
$$
y=\frac{2x^{3}}{(5x-3)^{2}}
$$
We use the quotient rule:
$$
\frac{dy}{dx}=\frac{vu'-uv'}{v^{2}}
$$
With the example:
$$
\begin{gather}
&u=2x^{3} \quad v=(5x-3)^{2}\quad u'=6x^{2}\quad v'=10(5x-3) \\
&\frac{dy}{dx}=\frac{(5x-3)^{2}(6x^{2})-2x^{3}(10(5x-3))}{(5x-3)^{4}} \\
& \\
& =\frac{6x^{2}(5x-3)^{2}-20x^{3}(5x-3)}{(5x-3)^{4}} \implies\frac{(2x^{2}(5x-3)(3(5x-3)-10x))}{(5x-3)^{4}} \\
&  \\
& =\frac{(2x^{2}(5x-3)(5x-9))}{(5x-3)^{4}}\implies {\color{cyan}\frac{2x^{2}(5x-9)}{(5x-3)^{3}}}
\end{gather}

$$

![[Logarithmic Functions-1792510515936.webp]]
$$
\begin{gather}
&u=e^{2x} \quad v=x^{3} \quad u'=2e^{2x}  \quad v'=3x^{2}  \\ \\
&\frac{dy}{dx}=\frac{x^{3}\cdot 2e^{2x}-e^{2x}\cdot 3x^{2}}{x^{6}}\implies \frac{2x^{3}e^{2x}-3x^{2}e^{2x}}{x^{6}} \\
& \\
&=\frac{x^{2}e^{2x}(2x-3)}{x^{6}}\implies \frac{e^{2x}(2x-3)}{x^{4}} \\
&\frac{e^{2x}(2x-3)}{x^{4}}=0\implies e^{2x}(2x-3)=0 \\
& {\color{red}e^{2x}=0}\therefore \text{rej.} \\
&2x-3=0\implies {\color{cyan}x=1.5} \\
& \\
&\text{Test x = 1 and x = 2 to derermine nature} \\
& \frac{e^{2}(2-3)}{1^{4}}=-7.38\dots <0\text{ (Decreasing)}\\
&  \\
& \frac{e^{4}(4-3)}{2^{4}}=3.41\dots >0 \text{ (Increasing)}\\ \\
& \therefore {\color{cyan}\text{Point is a local minimum}}
& 
\end{gather}
$$
