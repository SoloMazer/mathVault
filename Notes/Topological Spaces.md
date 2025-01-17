13-01-2025 11:02
Status: #pending
#### Motivation:
#### See Also:
### def: (Topology)
A *topology* on a set $X$ is a collection $\mathcal{T}$, of subsets of $X$ having the following properties:
1. $\emptyset \text{ and }X\text{ are in }\mathcal{T}$.
2. The union of the elements of any sub-collection of $\mathcal{T}$ is in $\mathcal{T}$.
3. The intersection of the elements of any finite sub-collection of $\mathcal{T}$ is in $\mathcal{T}$.
A set $X$ for which a topology $\mathcal{T}$ has been specified is called a *topological space*. Properly speaking, a topological space is an ordered pair $\{X,\mathcal{T}\}$ consisting of a set $X$ and a topology $\mathcal{T}$ on $X$.

If $X$ is a topological space with topology $\mathcal{T}$, we say that the subset $U\text{ of }X$ is an *open set* of $X$ if $U$ belongs to the collection $\mathcal{T}$.
### Alternate def: (Topology)
A topological space is a set $X$ together with a collection of subsets of $X$, called open sets, such that $\emptyset \text{ and }X$ are both open, and such that arbitrary unions and finite intersections of open sets are open.
#### Examples:
1. If $X$ is any set, the collection of all subsets of $X$ is a topology on $X$; it is called *discrete topology*. 
2. The collection consisting of $X$ and $\emptyset$ only is also a topology on $X$; we shall call it the indiscrete topology, or the *trivial topology*.
3. If $X \subset \mathbb{R}$, then the *standard topology* is the topology whose open sets are the unions of sets of the type $(a,b)\cap X$, with $a,b\in R \text{ and } a<b$.

#### def: (Fine and Coarse Topologies):
Suppose that $\mathcal{T}\text{ and }\mathcal{T'}$ are two topologies on a given set $X$. If $\mathcal{T}\subseteq \mathcal{T'}$, we say that $\mathcal{T'}$ is *finer* than $\mathcal{T}$; if $\mathcal{T}\subset \mathcal{T'}$ we say that $\mathcal{T'}$ is *strictly finer* than $\mathcal{T}$. We also say that $\mathcal{T}$ is *coarser* than $\mathcal{T'}$, or *strictly coarser*, in these two respective situations. We say that $\mathcal{T}$ is *comparable* with $\mathcal{T'}$ if either $\mathcal{T}\subset \mathcal{T'}$ or $\mathcal{T'}\subset \mathcal{T}$.
#### Note:
#### Lemma/Properties:
#### Exercises: