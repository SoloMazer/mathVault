22-01-2025 14:03
Status: #pending 
#### Motivation:
#### See Also:
[[Groups]]
[[Subgroups]]
### def:
A ring $R$ is a set together with two binary operations $+\text{ and }\times$ ( called multiplication and addition ) satisfying the following axioms:
1. $(R,+)$ is an abelian group,
2. $\times$ is associative: $(a\times b)\times c=a \times(b \times c)\:\forall\:a,b,c \in R$,
3. the $distributive$ laws hold in $R$: $\forall\:a,b,c\in R$:
	$(a+b)\times c=(a\times c)+(b\times c)\text{ and }a\times(b+c)=(a\times b)+(a\times c)$.
#### Examples: 
1. Consider a set $\mathbb{Z}[i]=\{a+ib\:|\:a,b\in \mathbb{Z}\}$ along with the usual operations of $+\text{ and }\times$ on integers. This set is a ring since, 
	$(a)$ $\mathbb{Z}[i]$ forms an abelian group under addition, it has associativity, inverses and zero element.
	$(b)$ Associativity holds for all elements of $\mathbb{Z}[i]$.
	$(c)$ Distributivity holds for all elements of $\mathbb{Z}[i]$.
2. Matrix Rings: eg, $3\times 3$ square matrices with real entries.
3. Zero Ring: the with zero being its only element.
4. The quotient group $\mathbb{Z}/{n\mathbb{Z}}$ is a commutative ring with the identity (the element $\bar{1}$) under the operations of addition and multiplications of residue classes for $n\geq2$.
5. Let $R=\{f:\mathbb{R}\to \mathbb{R}\}$, where $f$ is continuous, then $R$ forms a ring structure under the following definitions of addition and multiplication:
	$+:$ for $f,g\in R\text{ , then we define } f+g:\mathbb{R}\to \mathbb{R}\text{ and } (f+g)(a)=f(a)+g(a)\text{ for any }a\in \mathbb{R}$.
	$\times:$ for $f,g\in R$, then we define $fg:\mathbb{R}\to \mathbb{R}\text{ and }(fg)(a)=f(a)g(a)\text{ for any }a\in \mathbb{R}$.
	clearly $f+g\text{ and }fg\in R$, multiplication has an identity, ie. the function $f:\mathbb{R}\to1$ and associativity and commutativity follows from the properties of $\mathbb{R}$. 
	$R$ forms an abelian group under $+$, since associativity and commutativity follow from the definition of the functions $f\text{ and }g$ and the way we defined $+$. The existence of zero element is also defined since it is the function $0:\mathbb{R}\to 0$ and it belongs to $R$ since it is continuous. We can also find a $-f$ for every $f\in R\text{ st. }f(a)+(-f(a))=0(a)=0$, so inverses are defined.
#### Note:
1. The ring $R$ is *commutative* if multiplication is commutative.
2. The ring $R$ is said to have an *identity* (or contain a 1), if there is an element $1 \in R$ with $$
1\times a=a\times 1=a \:\forall\:a\in R
$$
#### Lemma/Properties:
#### Exercises: