# An Introduction to Mathematica's Manipulate[] function

The Mathematica notebook offers a few simple examples using the Manipulate[] function. This is extremely useful for visualising the behaviour of certain functions, as parameters are varied in an interactive manner.

The Mathematica notebook is self-contained and includes 3 examples. 

### Example 1: Elliptic curves

The first use of the Manipulate[] function is an application of 'Seiberg-Witten' geometry, which is one of the research areas I am interested in. We are dealing with a family of elliptic curves, described by a cubic equation:
$$ y^2 = 4x^3 - g_2(U) x - g_3(U)~.$$
Here $U$ parametrizes the so-called 'vacuum moduli space', being thus of central interest. Meanwhile, $g_2$ and $g_3$ are polynomial functions in $U$, and might also depend on other parameters. We define the discriminant of the curve as:
$$ \Delta(U) = g_2(U)^3 - 27 g_3(U)^2~,$$
and we are looking for the zeros of this function. In simple cases, these can be solved analytically, but this is not usually the case. The examples we will look at is the local Hirzebruch $\mathbb{F}_0$ geometry, which engineers a five-dimensional superconformal field theory. Explicitly, we have:
$$ \begin{aligned}
g2(U) & = \frac{4}{3} \left(1 + U^4 - \lambda + \lambda^2 - 2 U^2 (1 + \lambda)\right)~, \\
g3(U) & = -\frac{4}{27} \left(-2 + 2 U^6 + 3 \lambda + 3 \lambda^2 - 2 \lambda^3 - 6 U^4 (1 + \lambda) + 3 U^2 (2 + \lambda + 2 \lambda^2)\right);
\end{aligned}$$

