30-01-2025 15:34
Status: #pending #overlap #finished
#### Motivation:
#### See Also:
### def:
A set $A$ is said to be finite is there is a bijective correspondence of $A$ with some section of the positive integers. That is, $A$ is finite if it is empty or there is a bijection $$
f:A\to \{1,\dots,n\}
$$
for some positive integer $n$. In the former case, we say that $A$ has cardinality $0$; in the latter case, we say that $A$ has cardinality $n$.
#### Examples:
#### Note:
#### Lemma:
1. Let $n$ be a positive integer. Let $A$ be a set; let $a_{0}$ be an element of $A$. Then $\exists\:$ a bijective correspondence $f$ of the set $A$ with the set $\{1,\dots,n+1\}$ iff $\exists\:$ a bijective correspondence $g$ of the set $A-\{a_{0}\}$ with the set $\{1,\dots,n\}$
	**Proof:** 
	a) First we prove the forward implication by assuming that there is a bijective correspondence $$
g:A-\{a_{0}\}\to \{1,\dots,n\}
$$
	we then define a function $f:A\to \{1,\dots,n+1\}$ by setting $$
f(x) = g(x) \text{ for }x \in A-\{a_{0}\},
$$$$
f(a_{0})=n+1
$$
	clearly now, $f$ is a bijective map.
	b) Now in case of reverse implication, we assume that $\exists\:$ $f:A\to \{1,\dots,n+1\}$.
	If this $f$ maps $a_{0}$ to the number $n+1$, then the restriction $f|A-\{a_{0}\}$ gives the bijective map we are looking for. Otherwise we let $f(a_{0})=m$, and let $a_{1}$ be the point of $A$ such that $f(a_{1})=n+1$. Then $a_{1}\neq a_{0}$. Define a new function $$
h:A\to \{1,\dots,n+1\}
$$
	by setting $h(a_{0})=n+1$, $h(a_{1})=m$, 
	$h(x)=f(x)$ for $x \in A-\{a_{0}\}-\{a_{1}\}$
	Now it is easy to see that $h$ is a bijection, and that the restriction $h|A-\{a_{0}\}$ is the desired bijection of $A-\{a_{0}\}$ with $\{1,\dots,n\}$
#### Exercises: