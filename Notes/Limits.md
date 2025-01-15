15-01-2025 19:22
Status: #pending
(currently made for complex analysis)
#### Motivation:
#### See Also:
### def: (Limits)
The function $f(x)$ is said to have the limit $A$ as $x$ tends to a, $$
\lim_{ x \to a } f(x)=A \tag{1}$$
if and only if the following is true:
	for every $\epsilon>0\:\exists\:$ a number $\delta>0$ with the property that $|f(x)-A|$ for all values of $x$ such that $|x-a|<\delta$ and $x\neq a$.
#### Examples:
#### Note:
1. In case of complex numbers there is only one infinite limit, which corresponds to going as far as as possible from the origin in any direction. 
#### Properties:
1. If $\lim_{ x \to a }f(x)=F\text{ and }\lim_{ x \to a }g(x)=G$ then following is true in complex domain:
	a) $\lim_{ x \to a }(f(x)+g(x))=\lim_{ x \to a }f(x)+\lim_{ x \to a }g(x)=F+G$.
	b) $\lim_{ x \to a }(f(x)\cdot g(x))=\lim_{ x \to a }f(x)\cdot \lim_{ x \to a }g(x)=F\cdot G$.
	c) $\lim_{ x \to a }\frac{f(x)}{g(x)}=\frac{{\lim_{ x \to a }f(x)}}{\lim_{ x \to a }g(x)}=\frac{F}{G}$ provided G is non-zero.
2. The equation (1) is evidently equivalent to $$
\lim_{ x \to a }\overline{f(x)}=\bar{A} 
$$
3. From (1) and (2) we obtain, $$
\lim_{ x \to a }\mathrm{Re}(f(x))=\mathrm{Re}(A) 
$$
$$
\lim_{ x \to a }\mathrm{Im}(f(x))=\mathrm{Im}(A) 
$$


#### Exercises: