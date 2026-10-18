![[Definitions#^fc649a]]

![[Definitions#^5f3bb0]]

![[Definitions#^add89e]]

![[Definitions#^39ed92]]

## Gravitational Field Strength

G.F Strength is defined as:
$$
g = \frac{w}{m}
$$
Where
	g = gravitational field strength, e.g, Earth's gravitational field strength is 9.81
	w = force due to gravity, or weight
	m = mass

This equation is rewritten as ${}w = mg{}$ , an easy weight formula.

G.F strength can be represented by lines, where a uniform strength would have parallel lines pointing down, and around a point mass would be toward its center.

All planets have a radial G.F strength, but as you get closer to the surface, the lines for field strength are almost parallel, so it is approximated with a uniform field strength.

>[!important]
>An object can be considered a point mass when:
>
> - It has an even mass distribution
> - The distance being considered is larger than the object's size.

## Newton's law of gravitation

Definition states:
$$
\begin{aligned}
&\text{gravitational force between 2 point masses} = k(m_{1}m_{2}) \\
&\text{gravitational force between 2 point masses} = \frac{k}{d^{2}}
\end{aligned}
$$

Where
	${}m_{1}{}$ and ${}m_{2}{}$ are the masses of the 2 point masses
	d is the distance between those 2 point masses
	k would be a constant

The actual equation aligns with this:

$$
F_{G} = \frac{Gm_{1}m_{2}}{r^{2}}
$$
Where
	${}F_{G}{}$ is gravitational force between the 2 masses
	G is Newton's gravitational constant, ${}6.67\times 10^{-11}{}$
	r is the distance from the centers of both point masses

![[Gravitational Fields-1792170459481.webp]]

$$
\begin{aligned}
&m_{1} = 6500 \\
&\text{satellite distance from earth surface} = 2000\text{km} \\
&F_{G} = 37000 \\
&\text{radius of earth} = 6400 \\
& \\
&37000 = \frac{(6.67\times 10^{-11})(6500)(m_{2})}{(6400000 + 2000000)^{2}} \\
&\implies m_{1} = 6.02\times 10^{24}
\end{aligned}
$$

## Circular Orbits in G.F

Centripetal force for celestial bodies is defined by:
$$
F_{G} = F_{\text{circ}}
$$
Lets equate the equations for centripetal force and G.F:
$$
\begin{align}  \\
& \frac{GMm}{r^2} = \frac{mv^{2}}{r} \\
& \frac{GM}{r^{2}} = \frac{v^{2}}{r} \\
& v^{2}r^{2} = GMr \\
&v^{2}r = GM \\
&v = \sqrt{ \frac{GM}{r} }
\end{align}
$$
Where
	v is the velocity of the smaller mass orbiting the larger body, this makes sense as in circular motion, v defines the velocity of the object that's in circular motion.
	G is the constant ${}6.67\times 10^{-11}{}$
	M is the mass of the larger body
	r is the orbital radius, or radius of the circular path.

This is proof that all satellites orbit at a fixed speed given that the radius is fixed. Because of this, all rules of circular motion apply to orbits.

![[Gravitational Fields-1792173379002.webp|365x340]]


$$
\begin{flalign}
&\text{(a)}\\ \\
&F = mr\omega^{2} \\ \\ 
&F = \frac{Gm_{1}m_{2}}{r^2}\\ \\
&M_{1}R_{1}\omega^{2} = \frac{GM_{1}M_{2}}{(R_{1}+R_{2})^2}\\
&R_{1}\omega^{2}=\frac{GM_{2}}{(R_{1}+R_{2})^{2}} \\ \\
&\omega^{2} = \frac{GM_{2}}{R_{1}(R_{1}+R_{2})^{2}} \\ \\
&\omega = \sqrt{ \frac{GM_{2}}{R_{1}(R_{1}+R_{2})^{2}} }&
\end{flalign}
$$

$$
\begin{flalign}
&\text{(b)}\\ \\
&\omega = \frac{2\pi}{T} \\ \\
&T = \frac{2\pi}{\omega} \\ \\
&T = \frac{2\pi}{\sqrt{ \frac{GM_{2}}{R_{1}(R_{1}+R_{2})^{2}} }} \\ \\
&T = 2\pi \sqrt{ \frac{R_{1}(R_{1}+R_{2})^{2}}{GM_{2}}}&
\end{flalign}
$$

## Geostationary Orbits

Used for:
- Telecommunication transmissions
- Since geostationary orbits of satellites are fixed, dishes on the ground can be fixed too.

## Deriving G.F Strength (g)

Since ${}F = mg{}$ , and, ${}F = \frac{Gm_{1}m_{2}}{r^{2}}{}$:
$$
\begin{flalign}
&m_{1}g = \frac{Gm_{1}m_{2}}{r^{2}}\\ \\
&g = \frac{Gm_{2}}{r^{2}} &
\end{flalign}
$$

Where
	g = G.F strength (9.81 for Earth)
	G = constant ${}6.67\times 10^{-11}{}$
	${}m_{2}{}$ = mass of the larger body producing the gravitational field strength
	r = distance between both bodies

$$
g \propto \frac{1}{r^{2}}
$$
So, small changes in r would result in a very small change in g. When the distance between the planet's surface and the object is less than the planet's radius, we can consider ${}R+h \approx R{}$.
![[Gravitational Fields-1792240947313.webp]]

$$
\begin{align}
&\text{Radius of the earth: 6370000} \\
&m = 5.97\times 10^{24} \\ \\
& \\
&g = \frac{GM}{r^2} \\
&g = 6.67\times \frac{10^{-11}(5.97\times 10^{24})}{6370000^{2}} \implies 9.813440652 \\
&g = 6.67\times \frac{10^{-11}(5.97\times 10^{24})}{(6370000 + 8850)^{2}} \implies 9.786229257 \\
& \frac{G_{everest}}{G_{e}} = 0.9972 \\
& 1-0.9972 = 0.00277 \\
& 0.00277 \times 100 = 2.77\% \\
& 2.77\% < 3\%


\end{align}
$$
