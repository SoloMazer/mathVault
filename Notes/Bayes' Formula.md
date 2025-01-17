15-01-2025 16:45
Status: #pending
#### Motivation:
#### See Also:
### def:
Let $E$ and $F$ be events. We may express $E$ as $$
E = (E\cap F)\cup(E\cap F^{c})
$$
because in order for a point to be in $E$, it must either be in both $E\text{ and }F$, or it must be in $E$ and not in $F$. Since $E\cap F$ and $E\cap F^{c}$ are mutually exclusive, we have that $$
P(E)=P(E\cap F)+P(E\cap F^{c})=(E|F)P(F)+P(E|F^{c})P(F^{c})=P(E|F)P(F)+P(E|F^{c})(1-P(F))
$$
The equation states that the probability of the event $E$ is a weighted average of the conditional probability of $E$ given that $F$ has occurred and the conditional probability of $E$ given that $F$ has not occurred, each conditional probability being given as much weight as the event on which it is conditioned has of occurring.

#### Examples:
#### Note:
#### Lemma/Properties:
#### Exercises: