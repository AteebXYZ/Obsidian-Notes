There are 6 functions:
- ${}\sin x{}$
- ${}\cos x{}$
- ${}\tan x{}$
- ${}\cot x{}$
- ${}\sec x{}$
- ${}\csc x{}$

The main ones are ${}\sin{}$, ${}\tan{}$ and ${}\sec{}$. It feels counter-intuitive but sin, tan and sec are the 3 functions that are not complementary, co-sine, co-tangent and co-sec are all complementary functions of sin, tan and sec.

Complementary means:
$$
\text{Sum of angles} = 90\degree
$$
So:
$$
30+60 = 90 \therefore \sin 30=\cos 60
$$
Same with ${}\sin 60=\cos 30{}$ and all other complementary functions

### Identities

There are 2 sources where new identities are derived from:
$$
\begin{gather} 
&\text{Reciprocal} && \text{Pythagorean} \\ \\
&\tan x=\frac{\sin x}{\cos x}&& \sin ^{2}x+\cos ^{2}x=1 \\ \\
&\cot x=\frac{1}{\tan x} = \frac{\cos x}{\sin x}&& 1+\cot ^{2}x=\csc ^{2}x \\ \\
&\sec x=\frac{1}{\cos x}&& 1+\tan ^{2}x=\sec ^{2}x \\ \\
&\csc x=\frac{1}{\sin x}
\end{gather}
$$

When doing identities in A2, 90% of the time you want to get rid of functions like tan, sec, cosec and cot and stick to the simpler functions.

Examples:
$$
\begin{gather}
& (1+\sec x)(1-\cos x)\equiv \sin x\tan x \\
& \text{Replace sec x} \\ \\
& \left( 1+\frac{1}{\cos x} \right)(1-\cos x) \\ \\
& \frac{\cos x+1}{\cos x}(1-\cos x)\implies \frac{1-\cos ^{2}x}{\cos x} \\ \\
& \text{With AS identity:}  \\
& \frac{\sin ^{2}x}{\cos x}\implies \frac{\sin x}{\cos x}(\sin x) = {\color{green}\sin x\tan x}
\end{gather}
$$



$$
\begin{gather}
&(1+\sec x)(\csc x-\cot x)\equiv \tan x \\
&\left( 1+\frac{1}{\cos x} \right)\left( \frac{1}{\sin x}-\frac{1}{\tan x} \right) \\
& \\
& \left( \frac{\cos x+1}{\cos x} \right)\left( \frac{1}{\sin x}-\frac{\cos x}{\sin x} \right) \\
&  \\
& \frac{\cos x+1}{\cos x}\times \frac{1-\cos x}{\sin x}\implies \frac{1-\cos ^{2}x}{\cos x\sin x} \\ \\
& \frac{\sin ^{2}x}{\cos x\sin x} \implies \frac{\sin x}{\sin x}\left( \frac{\sin x}{\cos x} \right) = {\color{green}\tan x}
\end{gather}
$$




$$
\begin{gather}
& (\cot x+\tan x)(\cot x-\tan x)\equiv \csc ^{2}x-\sec ^{2}x \\
&  \\
&  \cot ^{2} x-\tan ^{2}x \\
&  \text{Identity: }1+\cot ^{2}x=\csc ^{2}x \\
&  (\csc ^{2}-1)-(\sec ^{2}-1) \implies {\color{green}\csc ^{2}x-\sec ^{2}x} 
\end{gather}
$$
