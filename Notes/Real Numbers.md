11-01-2025 16:30
Status: #pending #revisit 
#### Motivation:
#### See Also:
[[Basic Set Theory]]
[[Order Relations]]
#### def: (Real Numbers)
We assume there exists a set $\mathbb{R}$, called the set of *real numbers*, two binary operations $+\text{ and }\cdot \text{ on }\mathbb{R}$, called addition and multiplication operations, resp, and an order relation $<$ on $\mathbb{R}$, such that the following properties hold: 
*Algebraic Properties*
1. $(x+y)+z=x=(y+z)\text{ and } (x\cdot y)\cdot z=x\cdot(y\cdot z)\:\forall\:x,y\in \mathbb{R}$.
2. $x+y=y+x\text{ and }x\cdot y=y\cdot x\:\forall\:x,y\in \mathbb{R}$.
3. There exists a unique element of $\mathbb{R}$ called zero, denoted by $0$, such that $x+0=x\:\forall\:x \in \mathbb{R}$. There exists a unique element of $\mathbb{R}$ called one, different from $0$, and denoted by $1$, such that $x\cdot1=x,\:\forall\: x \in \mathbb{R}$
4. For each $x \in \mathbb{R}$, there exists a unique $y$ in $\mathbb{R}$ such that $x+y=0$. For each $x$ in $\mathbb{R}$ different from $0$, there exists a unique $y$ in $\mathbb{R}$ such that $x\cdot y=1$.
5. $x\cdot(y+z)=(x\cdot y)+(x\cdot z)\:\forall\:x,y,z\in \mathbb{R}$
*A mixed Algebraic and Order Property*
6. If $x>y$, then $x+z>y+z$. If $x>y$ and $z>0$, then $z\cdot z>y\cdot z$.
*Order Properties*
7. The order relation $<$ has the least upper bound property.
8. If $x<y$, there exists an element $z\text{ st. }x<z\text{ and }z<y$.

Any set with an order relation satisfying (7) and (8) is called a linear continuum (by topologists).
#### def: (Inductive Set)
A subset of $A$ of the real numbers is said to be inductive if it contains the number 1, and if for every $x$ in $A$, the number $x+1$ is also in $A$. Let $\mathcal{A}$ be the collection of all inductive subsets of $\mathbb{R}$. Then the set $\mathbb{Z}_{+}$ of positive integers is defined by the equation $$
\mathbb{Z}_{+}=\bigcap_{A\in \mathcal{A}}A
$$
Note that the set $\mathbb{R_{+}}$ of positive real numbers is inductive, for it contains 1 and the statement $x>0$ implies the statement $x+1>0$. Therefore, $\mathbb{Z_{+}}\subset \mathbb{R_{+}}$, so the elements of $\mathbb{Z_{+}}$ are indeed positive. 
#### Exercises:
