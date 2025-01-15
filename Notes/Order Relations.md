11-01-2025 15:10
Status: #pending #revisit
#### Motivation:
#### See Also:
[[Relations]]
#### Def: (Order Relation)
A relation $C$ on a set $A$ is called an order relation (or simple relation, or linear relation) if it has the following properties:
1. (Comparability) for every $x \in A\text{, and }x\neq y\text{ then either }xCy\text{ or }yCx$.
2. (Non-reflexivity) For no $x$ in $A$ does the relation $xCx$ hold.
3. (Transitivity) If $xCy\text{ and }yCz\text{, then }xCz$.
#### Note:
1. Note that property (1) does not by itself exclude the possibility that some pair of elements $x\text{ and }y\text{ of }A$, both the relations $xCy\text{ and }yCx$ hold (since "or" means "one or the other, or both"). But the properties (2) and (3) combined do exclude this possibility; for if both $xCy\text{ and }yCx$ held, transitivity would imply that $xCx$, contradicting nonreflexivity.
2. The "less than" symbol, $<$, is commonly used to denote an order relation
#### Examples:
1. Consider the relation on the real line consisting of all pairs $(x,y)$ of real numbers such that $x<y$. It is an order relation, called the "usual order relation", on the real line.
#### Def: (Open Interval)
If $X$ is a set and $<$ is an order relation on $X$, and if $a<b$, we use the notation $(a,b)$ to denote the set $$
\{x|a<x<b\};$$
it is called an *open interval* in $X$. If this set is empty, we call $a$ the *immediate predecessor* of $b$, and we call $b$ the *immediate successor* of $a$.
#### Def: (Order type)
Suppose $A\text{ and }B$ are two sets with order relations $<_{a}\text{ and }<_{b}$ resp. We say that $A\text{ and }B$ have the same *order type* if there is a bijective correspondence between them that preserves order; that is, if there exists a bijective function $f:A\to B$ such that, $$
a_{1}<_{a}a_{2}\implies f(a_{1})<_{b}f(a_{2})
$$
#### Examples:
1. The interval $(-1,1)$ of real numbers has the same order type as the set $\mathbb{R}$ of real numbers itself, for the function $f:(-1,1)\to \mathbb{R}$ given by:$$
f(x)=\frac{x}{1-x^2}
$$
is an order-preserving bijective correspondence.
#### Def: (Dictionary order relation)
Suppose that $A\text{ and }B$ are two sets with order relations $<_{A}\text{ and }<_{B}$ resp. Define an order relation $<$ on $A\times B$ by defining $$
a_{1}\times b_{1}<a_{2}\times b_{2}
$$
if $a_{1}<_{A}a_{2}\text{, or if }a_{1}=a_{2}\text{ and }b_{1}<_{B}b_{2}$. It is called dictionary order relation on $A\times B$.

#### Lemma/Properties:
#### Exercises: