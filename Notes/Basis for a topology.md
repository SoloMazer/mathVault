13-01-2025 13:24
Status: #pending
#### Motivation:
#### See Also:
[[Topological Spaces]]
### def: 
Let $X$ be a set. The *basis* for a topology on $X$ is a collection $\mathcal{B}$ of subsets of $X$ (called *basis elements*) such that:
1. for each $x \in X$, $\exists\:$ at least one $B\in \mathcal{B}\text{ st. }x \in B$.
2. If $x \in B_{1}\cap B_{2}$ ,where $B_{1},B_{2}\in \mathcal{B}$, then $\exists\:B_{3}\in \mathcal{B}\text{, st. }x \in B_{3}\text{ and } B_{3}\subseteq B_{1}\cap B_{2}$.

The *topology $\mathcal{T}$ generated by $\mathcal{B}$* is the collection of all subsets $U\in X$ satisfying:
	for each $x \in U,\:\exists\:\text{ a basis element }B\in \mathcal{B}\text{ st. }x \in B\text{ and }B\subset U$.
#### Examples:
1. Let $X=\mathbb{R}$, then the collection of all open intervals $(a,b)$, where $a,b \in \mathbb{R}$, and $a<b$ is a basis and the topology generated by it is the standard topology on $\mathbb{R}$.
	(1) is satisfied since for every $x \in \mathbb{R},\exists\:$at least one interval containing $x$, eg. $(x+1,x-1)$.
	(2) is satisfied since if $x \in(a_{1},b_{1})\cap(a_{2},b_{2})$, then the intersection itself is an interval: $$
(a_{1},b_{1})\cap(a_{2},b_{2})=(max(a_{1},a_{1}),min(b_{1},b_{2}))$$
	which is also an open interval, which means we can take $B_{3}=(a_{1},b_{1})\cap(a_{2},b_{2})$, which belongs to $\mathcal{B}$.
2. If $X$ is any set, the collection of all one-point subsets of $X$ is a basis for the discrete topology on $X$.
#### Lemmas:
1. Let $X$ be a set, let $\mathcal{B}$ be a basis for a topology $\mathcal{T}$ on $X$. Then $\mathcal{T}$ equals the collection of all unions of elements of $\mathcal{B}$.
	**Proof:** Given a collection of elements of $\mathcal{B}$, they are also elements of $\mathcal{T}$. Because $\mathcal{T}$ is a topology, their union is in $\mathcal{T}$. Conversely, given $U\in \mathcal{T}$, choose for each $x \in U$ an element $B_{x}\text{ of }\mathcal{B}\text{ st. }x \in B_{x}\subset U$. Then $U=\bigcup_{x \in U}B_{x}$, so $U$ equals a union of elements of $\mathcal{B}$. $\blacksquare$
2. Let $X$ be a topological space. Suppose that $\mathcal{C}$ is a collection of open sets of $X$ such that for each open set $U$ of $X$ and each $x$ in $U$, there is an element $C$ of $\mathcal{C}$ such that $x \in C\subset U$. Then $\mathcal{C}$ is a basis for the topology of $X$.
	**Proof:** We must show that $\mathcal{C}$ is a basis. The first condition for a basis is easy: Given $x \in X$, since $X$ is itself an open set, there is by hypothesis an element $C\text{ of }\mathcal{C}\text{ st. }x \in C\subset X$. To check the second condition, let $x$ belong to $C_{1}\cap C_{2}$, where $C_{1}\text{ and }C_{2}$ are elements of $\mathcal{C}$. Since $C_{1}\text{ and }C_{2}$ are open, so is $C_{1}\cap C_{2}$. Therefore, there exists by hypothesis an element $C_{3}$ in $\mathcal{C}\text{ st. }x \in C_{3}\subset C_{1}\cap C_{2}$.
	Let $\mathcal{T}$ be the collection of open sets of $X$; we must show that the topology $\mathcal{T'}$ generated by $\mathcal{C}$ equals the topology $\mathcal{T}$. First, note that if $U$ belongs to $\mathcal{T}$ and if $x \in U$, then there is by hypothesis an element $C$ of $\mathcal{C}$ such that $x \in C\subset U$. It follows that $U$ belongs to the topology $\mathcal{T'}$, by definition. Conversely, if $W$ belongs to the topology $\mathcal{T'}$, then $W$ equals a union of elements of $\mathcal{C}$, by the preceding lemma. Since each element of $C$ belongs to $\mathcal{T}\text{ and }\mathcal{T}$ is a topology. $W$ also belongs to $\mathcal{T}$. $\blacksquare$
3. Let $\mathcal{B}\text{ and }\mathcal{B}$ be bases for the topologies $\mathcal{T}\text{ and }\mathcal{T'}$, resp, on $X$. Then the following are equivalent:
	(a) $\mathcal{T'}$ is finer than $\mathcal{T}$.
	(b) For each $x \in X$ and each basis element $B \in \mathcal{B}\text{ containing }x$, there is a basis element $B' \in \mathcal{B'}\text{ st. }x \in B'\subset B$.
	**Proof:** 
	$(2)\implies(1)$: Given an element $U$ of $\mathcal{T}$, we wish to show that $U \in \mathcal{T'}$. Let $x \in U$. Since $\mathcal{B}$ generates $\mathcal{T}$, there is an element $B\in \mathcal{B}\text{ st. }x \in B\subset U$. Condition $(2)$ tells us there exists an element $B'\in \mathcal{B'}\text{ st. }x \in B'\subset B$. Then $x \in B'\subset U$, so $U\in \mathcal{T}$, by definition.
	$(1)\implies(2)$: We are given $x \in X$ and $B \in \mathcal{B}$, with $x \in B$. Now $B$ belongs to $\mathcal{T}$ by definition and $\mathcal{T}\subset \mathcal{T'}$ by condition $(1)$; therefore, $B\in \mathcal{T'}$. since $\mathcal{T'}$ is generated by $\mathcal{B'}$, there is an element $B'\in \mathcal{B'}\text{ st. }x \in B'\subset B$. $\blacksquare$
	
#### Note: 
1. Each basis element is itself an element of $\mathcal{T}$.
2. Lemma (1) states that every open set $U$ in $X$ can be expressed as a union of basis elements. This expression for $U$ is not, however, unique. 
#### Exercises: