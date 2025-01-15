07-01-2025 21:40
Status: #pending 
#### Motivation:
#### See Also:
[[Relations]]
#### References/Sources:
James Munkres - Topology
#### Equivalence Relation:
An equivalence relation on a set $A$ is a relation $C$ on $A$ having the following three:
1. (Reflexivity): $xCy\text{, for every }x \in A$.
2. (Symmetry): If $xCy, \text{ then }yCx$.
3. (Transitivity): If $xCy\text{ and }yCz, \text{ then }xCz$.
#### Note:
A "Tilde" symbol $\sim$, is commonly used to denote an equivalence relation.
#### Equivalence Class:
Given an equivalence relation '$\sim$' on a set $A$ and an element $x\text{ of }A$, we define a certain subset $E\text{ of }A$, called the Equivalence class determined by x, by the equation,$$
E_{x}=\{y | y\sim x\}
$$
#### lemma:
Two Equivalence classes $E_{x}\text{ and }E'_{x}$ are either disjoint or equal.
#### Proof:
Let the $E_{x}\text{ and }E'_{x}$ be two equivalence classes, s.t. $\exists$ $x\sim y$, and $x'\sim y$, i.e. $y\in E\cap E'$.
Now, using the symmetry property from equivalence relation $y\sim x$ and $y\sim x'$ and transitivity gives us $x\sim x'$.
now for every $w\in E$, we have $w\sim x$, by transitivity, $w\sim x'$, therefore $E\in E'$.
Using a symmetric argument we can show that $E'\in E$ is also true.
Hence it concludes that $E=E'$.
#### Examples:
#### Note:
#### Exercises: