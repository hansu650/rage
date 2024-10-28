# *function*
<!--
\[
\begin{align}
\end{align}
\]
-->
## equivalent infinitesimal
### defination
$$
\lim_{x \to x_0} \frac {f(x)} {g(x)} = 1
$$

### properties
\[
\begin{align}
\lim_{x \to x_0} f(x)h(x) &= \lim_{x \to x_0} g(x)h(x) \\
\lim_{x \to x_0} \frac {f(x)} {h(x)} &= \lim_{x \to x_0} \frac {g(x)} {h(x)}
\end{align}
\]

### example
\[
\begin{align}
(1+x)^n &\sim nx+1 \\
sin(x) &\sim x
\end{align}
\]

where $x \mapsto 0$

## Landau symbols
### defination
$$
|f(x)| \le M|g(x)|
$$

then $f(x) = O (g(x))$

### explanation
Big O notation means that sometimes(for an infinite quantity) we don't care about the accurate function, but how rapidly it grows
Whether it can be controlled by $x$, $log x$ or $e^x$
Small O notation means that f(x) is much more smaller than g(x) when approaching to $x_0$
Why do we define it? Aadditivity&multiplicity

### properties

## Upper limit & Lower limit
### Defination
\[
\begin{align}
\exists \ x_n ,\  x_n \to x_0  \\
s.t. f(x_n) \to \alpha \\
then \ \ E = \{x| x=\alpha \} \\
limsup_{x \to x_0} = supE \\
liminf_{x \to x_0} = infE
\end{align}
\]

### Properties
$$
supE \in E
$$

In other words, the upper limit is the biggist limit point

$$
E = \{\alpha: \forall \varepsilon ,\exists \delta \ s.t. x \in N_{\delta}(x_0), f(x) < \alpha + \varepsilon \}
$$

then $infE = \limsup_{x \to x_0} f(x)$