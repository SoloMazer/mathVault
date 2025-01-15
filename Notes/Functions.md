11-01-2025 11:45
Status: #pending 
#### Motivation:
its functions
#### See Also:
[[Relations]]
#### References/Sources:
James Munkres - Topology
#### Rule of Assignment: 
A rule of assignment is a subset $r$ of the cartesian product $C\times D$ of two sets, having the property that each element of $C$ appears as the first co-ordinate of at most one ordered pair belonging to $r$. Thus, a subset $r$ of $C\times D$ is a rule of assignment if, $$
[(c,d)\in r\text{ and }(c,d')\in r]\implies[d=d']$$
we also define the domain and image of $r$ as follows, 
$$
\text{domain }r=\{c|\exists\:d\in D\text{ st. }(c,d)\in r\}
$$
$$
\text{image }r=\{d|\exists\:c\in C\text{ st. }(c,d)\in r\}
$$
#### Function:
A function $f$ is a rule of assignment $r$, together with a set $B$ that contains the image set of $r$. The domain A of the rule $r$ is also called the domain of the function and the image set of $r$ is also called the image/range of $f$, and the set B is called the codomain of $f$. As a condensed notation a function $f$ is written as $f:A\to B$, along with define $f$ in terms of some variable $x$.
#### Restriction on Function:
If $f:A\to B$ and if $A_{0}$ is a subset of $A$, we define the restriction of $f$ to $A_{0}$ as the function mapping from $A_{0}\text{ to }B$ whose rule is,
$$
f|_{A_{0}}=\{a,f(a)|a\in A_{0}\}
$$
#### Composition of Functions:
Given functions $f:A\to B$ and $g:B\to C$, we define the composite $g o f$ of $f$ and $g$ as the function $gof:A\to C$ defined by the equation $(gof)(a)=g(f(a))$ as in,$$
gof=\{(a,c)|\text{ for some }b\in B, f(a)=b\text{ and }g(b)=c\}
$$
Note that $gof$ is defined only when the range of $f$ equals the domain of $g$.

#### Image under Function:
let $f:A\to B$  be a function and let $A_{0}\subset A$, the set of images of all the points in $A_{0}$, $f(A_{0})$is said to be the image of $A_{0}$ under $f$. More formally,$$f(A_{0})=\{b|b=f(a)\text{ for at least one }a\in A_{0}\}$$
On the other hand, if $B_{0}\subset B$, we denote $f^{-1}(B_{0})$ called preimage is the set of all elements whose images under $f$ lie in $B_{0}$. More formally,
$$f^{-1}(B_{0})=\{a|f(a)\in B_{0}\}$$
#### Note: 
If $f:A\to b$ and if $A_{0}\subset A$ and $B_{0}\subset B$, then
$$A_{0}\subseteq f^{-1}(f(A_{0})) \tag{1}$$and $$f^{-1}(f(B_{0}))\subseteq B_{0} \tag{2}$$
In case of (1), equality holds when $f$ is injective, while in case of (2) it holds when $f$ is surjective.
#### Examples:
#### Exercises: