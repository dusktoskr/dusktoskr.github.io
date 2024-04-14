By Josiah Russell
## Theorem
$$1^{3}+2^{3}+3^{3}+...+n^{3}=\Big[\frac{n(n+1)}{2}\Big]^{2}\ \ \text{ For all }n\ge 1$$
## Proof
Let $P(n)$ be the property $1^{3}+2^{3}+3^{3}+...+n^{3}=\Big[\frac{n(n+1)}{2}\Big]^{2}\ \ \text{ For all }n\ge 1$
## Basis Step
Show $P(1)$ is true.
### L.H.S.
$1$
### R.H.S.
$$\begin{eqnarray} 
&=&\Big[\frac{1(1+1)}{2}\Big]^2\\\\
&=&\Big[\frac{2}{2}\Big]^2\\\\
&=&1^2\\\\
&=&1
\end{eqnarray}$$
Hence,
$$1=1$$
## Inductive Step
Suppose that for some particular but arbitrarily chosen integer $k\ge1$,  $P(k)$ is true.
$$1^{3}+2^{3}+3^{3}+...+k^{3}=\Big[\frac{k(k+1)}{2}\Big]^{2}\ \ \text{ For all }k\ge 1$$
Show that $P(k+1)$ is also true.
### L.H.S.
$$\begin{eqnarray}
1^{3}+2^{3}+3^{3}+...+k^{3}+(k+1)^3=
\end{eqnarray}$$
By the substitution of the inductive hypothesis,
$$\begin{eqnarray}
\Big[\frac{k(k+1)}{2}\Big]^{2}+(k+1)^3&=&\\ \\
\frac{1}{4}k^{2}(k+1)^{2}+(k+1)^{3}&=& \\ \\
\frac{1}{4}\Big[k^{2}(k^{2}+2k+1)\Big] + (k+1)^{3} &=& \\ \\
\frac{1}{4}\Big[ k^{4}+2k^{3}+k^{2} \Big]+(k+1)^{3} &=& \\ \\
\frac{1}{4}\Big[ k^{4}+2k^{3}+k^{2} \Big]+\Big[k^{3}+3k^{2}+3k+1\Big] &=& \\ \\
\frac{1}{4}\Big[ k^{4}+2k^{3}+k^{2} \Big]+\frac{4}{4}\Big[k^{3}+3k^{2}+3k+1\Big] &=& \\ \\
\frac{1}{4}\Big[ k^{4}+2k^{3}+k^{2} +4k^{3}+12k^{2}+12k+4\Big] &=& \\ \\
\frac{1}{4}\Big[ k^{4}+6k^{3}+13k^{2}+12k+4\Big] &=& \\ \\
\frac{1}{4}(k+1)\Big[k^{3}+5k^{2}+8k+4 \Big]&=& \\ \\
\frac{1}{4}(k+1)^{2}\Big[k^{2}+4k+4 \Big] &=& \\ \\
\frac{1}{4}(k+1)^{2}(k+2)^{2}&=&
\end{eqnarray}$$
By Algebra
### R.H.S
$$\begin{eqnarray}
&=& \left[ \frac{(k+1)\Big[(k+1)+1\Big]}{2} \right]^{2}\\ \\
&=& \left[ \frac{(k+1)(k+2)}{2} \right]^{2}\\ \\
&=& \frac{1}{4}(k+1)^{2}(k+2)^{2}
\end{eqnarray}$$
By Algebra
Hence $$\frac{1}{4}(k+1)^{2}(k+2)^{2}=\frac{1}{4}(k+1)^{2}(k+2)^{2}$$
Thus $P(k+1)$  is true, 
And $P(k) \longrightarrow P(k+1)$
Therefore by the Principle of Mathematical Induction,
$$\large1^{3}+2^{3}+3^{3}+...+k^{3}=\Big[\frac{k(k+1)}{2}\Big]^{2}\ \ \text{ For all }k\ge 1$$
$$\Huge \text{Q.E.D.}\blacksquare $$
