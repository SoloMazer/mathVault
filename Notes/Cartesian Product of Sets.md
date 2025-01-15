11-01-2025 14:05
Status: #pending
#### Motivation:
Cartesian Product of sets is a way of creating new sets from old ones, which in turn lets us create relations and functions.
#### See Also:
[[Relations]]
[[Collections of sets]]
[[Basic Set Theory]]
[[Functions]]
[[Injective-Surjective-Bijective Functions]]
#### References/Sources:
James munkres - topology
#### Cartesian Product of Sets:
Given two set $A\text{ and }B$, we define their cartesian product $A\times B$, to be the set of all ordered pair $(a,b)$ for which $a\in A$ and $b\in B$. Formally,
$$
A\times B=\{(a,b)|a\in A\text{ and }b\in B\}
$$
#### Note:
The concept of ordered pair can be taken as a primitive concept, or it can be given as a definition in terms of the set operations as: $$(a,b)=\{\{a\},\{a,b\}\}$$
where if $a\neq b\text{ then }(a,b)$ is a collection of two sets. The first coordinate of the ordered pair is defined to be the element belonging to both sets and second coordinate is the element belonging to only one of the sets. 
and if $a=b$ then $(a,b)$ is a collection containing only one set $\{a\}$, in this case its first and second co-ordinate both equal to the element in this single set.
#### Def:
Let $\mathcal{A}$ be a nonempty collection of sets. An *indexing function*  for $\mathcal{A}$ is a surjective function $f$ from some set $J$, called the *index set*, to $\mathcal{A}$. The Collection $\mathcal{A}$, together with the indexing function $f$, is called an *indexed family of sets*. Given $\alpha \in J$, the set $f(\alpha)$ is denoted by the symbol $A_{\alpha}$ and the indexed family itself by the symbol $\{A_{\alpha}\}_{\alpha \in J}$, which is read as "the family of all $A_{\alpha}$, as $\alpha \text{ ranges over } J$"
Note that although an indexing function is required to be surjective, it is not required to be injective. It is entirely possible for $A_{\alpha}$ and $A_{\beta}$ to be the same set of $\mathcal{A}$, even though $\alpha\neq\beta$.
#### Note: 
Suppose that $f:J\to \mathcal{A}$ is an indexing function for $\mathcal{A}$; let $A_{\alpha}$ denote $f(\alpha)$. Then we define $$
\bigcup_{\alpha \in J}A_{\alpha} =\{x|\text{ for at least one }\alpha \in J,x \in A_{\alpha}\}
$$
$$
\bigcap_{\alpha \in J}A_{\alpha}=\{x|\text{ for every }\alpha \in J,x \in A_{\alpha}\}
$$
#### Lemma/Properties:
#### Exercises: