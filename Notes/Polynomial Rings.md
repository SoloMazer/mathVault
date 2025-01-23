22-01-2025 17:28
Status: #pending 
#### Motivation:
#### See Also:
[[Monic polynomials]]
### def:
*Polynomial ring*, denoted as $R[x]$, is the set of all polynomials over a ring $R$. Formally,$$
R[x]=\{a_{n}x^n+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}\:|\:n\in \mathbb{N}\text{ and }a_{i}\in R\}
$$
The *degree* of $f(x)$ is the largest $n$, such that $a_{n}\neq 0$. 

- Addition on $R[x]$ is defined as follows, let 
$$f=a_{n}x^n+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$$
$$g=b_{n}x^n+b_{n-1}x^{n-1}+\dots+b_{1}x+b_{0}$$
	be two elements of $R[x]$, now we define,
$$f+g=(a_{n}+b_{n})x^{n}+(a_{n-1}+b_{n-1})x^{n-1}+\dots+(a_{1}+b_{1})x+(a_{0}+b_{0})$$

- Multiplication on $R[x]$ is defined as follows, let
$$f=a_{n}x^n+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$$
$$g=b_{m}x^m+b_{m-1}x^{m-1}+\dots+b_{1}x+b_{0}$$
	be two elements of $R[x]$, now we define,
$$f\cdot g=P_{m+n}x^{m+n}+P_{m+n-1}x^{m+n-1}+\dots+P_{1}x+P_{0}$$
	where, $P_{k}=\sum_{i+j=k}a_{i}b_{j}$
With the above defined operations $R[x]$ becomes a ring since it is an abelian group under addition (easy to follow since $x$'s act as "placeholders" and we only deal with coefficients which are already part of group), multiplication is associative and the set also has distributivity. Note that there exists a multiplicative identity (namely 1) and commutativity as well. 
#### Examples:
#### Note:
Let $f,g\in R[x]$ with the leading term of $f$ being the unit of $R$ then we can divide $g\text{ by }f\implies\exists\:!$ polynomials $q(x)\text{ and }r(x)\text{ st. }$ $$
g(x)=q(x)f(x)+r(x)\text{ and either }r(x)=0\text{ or }deg(r(x))<deg(f(x)).
$$
The reason for leading term to be unit stems from the fact that polynomial division will not be contained in $R[x]$, if we try otherwise.
#### Lemma/Properties:
#### Exercises: