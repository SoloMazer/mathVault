15-01-2025 16:58
Status: #pending 
#### Motivation:
#### See Also:
[[Functions]]
[[Probability Defined on Events]]
### def: (Random Variables)
Real valued functions defined on the sample space, are known as *random variables*.
#### Examples:
1. Letting $X$ denote the random variable that is defined as the sum of two fair dice; then
	$P\{X=2\}=P\{1,1\}=\frac{1}{36}$,
	$P\{X=3\}=P\{(1,2),(2,1)\}=\frac{2}{36}$,
	$P\{X=4\}=P\{(1,3),(2,2),(3,1)\}=\frac{3}{36}$,
	$P\{X=5\}=P\{(1,4),(2,3),(3,2),(4,1)\}=\frac{4}{36}$,
	$P\{X=6\}=P\{(1,5),(2,4),(3,3),(4,2),(5,1)\}=\frac{5}{36}$,
	$P\{X=7\}=P\{(1,6),(2,5),(3,4),(4,3),(5,2),(6,1)\}=\frac{6}{36}$,
	$P\{X=8\}=P\{(2,6),(3,5),(4,4),(5,3),(6,2)\}=\frac{5}{36}$,
	$P\{X=9\}=P\{(3,6),(4,5),(5,4),(6,3)\}=\frac{4}{36}$,
	$P\{X=10\}=P\{(4,6),(5,5),(6,4)\}=\frac{3}{36}$,
	$P\{X=11\}=P\{(5,6),(6,5)\}=\frac{2}{36}$,
	$P\{X=12\}=P\{(6,6)\}=\frac{1}{36}$
	in other words, the random variable $X$ can take on any integral value between two and twelve. Since $X$ must take on one of the values two through twelve, we must have $$
1=P\left\{ \bigcup_{i=2}^{12}\{X=n\} \right\}=\sum_{n=2}^{12}P\{X=n\}
$$

### def: (Cumulative distribution function)
The cumulative distribution function (cdf) $F(\cdot)$, of the random variable $X$ is defined for any real number $b$, $-\infty<b<\infty$, by $$
F(b)=P\{X\leq b\}
$$
In words, $F(b)$ denotes the probability that the random variable $X$ takes on a value that is less than or equal to $b$.
#### Properties:
Let $F(b)$ be some cdf then,
	1. $F(b)$ is a nondecreasing function of b,
	2. $\lim_{ b \to \infty }F(b)=F(\infty)=1$,
	3. $\lim_{ b \to -\infty }F(b)=F(-\infty)=0$.
	4. $F(a)-F(b)=P\{a<X\leq b\}$ for all $a<b$.
Property 1 follows since for $a<b$ the event $\{X\leq a\}$ is contained in the event $\{X\leq b\}$, and so it must have a smaller probability. 
Properties 2 and 3 follow since $X$ must take on some finite value.
Property 4 follows since we may calculate $P\{a<X\leq b\}$ by first computing the probability that $X\leq b$ (that is, $F(b)$) and then subtracting from this the probability that $X\leq a$ (that is, $F(a)$).
#### Exercises: