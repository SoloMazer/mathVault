11-01-2025 17:24
Status: #pending
#### Motivation:
#### See Also:
#### thm: (Well-ordering Property)
Every nonempty subset of $\mathbb{Z}_{+}$ has a smallest element.
#### Proof:
We first prove that, for each $n\in \mathbb{Z}_{+}$, the following statement holds: *Every nonempty subset of $\{1,\dots,n\}$ has a smallest element*.
Let $A$ be the set of all positive integers $n$ for which this statement holds. Then $A$ contains 1, since if $n=1$, the only nonempty subset of $\{1,\dots,n\}$ is the set $\{1\}$ itself. Then, supposing $A$ contains $n$, we show that it contains $n+1$. So let $C$ be a nonempty subset of the set $\{1,\dots,n+1\}$. If $C$ consists of the single element $n+1$, then the element is the smallest element of $C$. Otherwise, consider the set $C\cap \{1,\dots,n\}$, which is nonempty. Because $n\in A$, this set has a smallest element, which will automatically be the smallest element of $C$ also. Thus $A$ is inductive, so we conclude that $A=\mathbb{Z}_{+}$; hence the statement is true for all $n\in \mathbb{Z}_{+}$.
Now we prove the theorem. Suppose that $D$ is a nonempty subset of $\mathbb{Z}_{+}$. Choose an element $n$ of $D$. Then the set $A=D\cap \{1,\dots,n\}$ is nonempty, so that $A$ has a smallest element k. The element k is automatically the smallest element of $D$ as well.
#### Alternate proof:
#### Equivalent Statement:
#### Note:
#### Exercises:

