22-01-2025 16:33
Status: #pending 
#### Motivation:
#### See Also:
### def: 
Let $R$ be a ring, an element $a\in R$ is called a *unit* if it has a multiplicative inverse. A ring that with identity $1$, where $1\neq{0}$, is called a *division ring* (or skew ring) if every nonzero element $a\in R$ has a multiplicative inverse.
#### Examples:
1. The ring of integers $\mathbb{Z}$, has twp units namely $+1\text{ and }-1$.
2. For rings like $\mathbb{C},\mathbb{R},\text{and }\mathbb{Q}$ all the elements are units. (these type of structures are also called a [[Fields]])
#### Note:
#### Lemma:
1. The ring of gaussian integers, $\mathbb{Z}[i]=\{a+ib\:|\:a,b\in \mathbb{Z}\}$ has no other units except for 1, -1, i and -i. Alternatively, both $a\neq 0$ and $b\neq 0$ cannot hold simultaneously for an element to be unit.
	**proof**: Let $a+ib\in \mathbb{Z}[i]$, be a unit of the ring. Now $\exists\:c+id\text{ st. }(a+ib)(c+id)=1$.
	$\implies (ac-bd)+i(ad-bc)=1$
	$\implies ac-bd=1\text{ and }ad+bc=0$          (1)
	now if $a=0:$ $bd=-1\text{ and }bc=0 \implies c=0\text{ and }b=1\text{ or}-1\implies a+ib=i\text{ or }-i$.
	Similarly, if $b=0$, then we get $a+ib=1\text{ or }-1$.
	
	when both $a\neq 0\text{ and }b\neq 0$, then we get
	$c= \frac{a}{a^2+b^2}$ and $d=-\frac{b}{a^2+b^2}$ 
	let $n=a^2+b^2$, since $a\neq 0, b\neq 0\implies n\geq{2}$.
	$c=\frac{a}{n}\implies a=nc\implies a^2=n^2c^2$
	$d=\frac{b}{n}\implies b=nd\implies b^2=n^2d^2$
	which gives us, 
	$a^2+b^2=n=n^2(c^2+d^2)\implies 1=n(c^2+d^2)$, this absurd since n becomes a fraction which is not part of $\mathbb{Z}$ and hence cannot be equal to $a^2+b^2$. hence by contradiction, we prove the statement. $\blacksquare$
#### Exercises: