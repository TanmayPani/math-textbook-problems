###### If $G$ is a group and $a, x \in G$ , prove that $C(x^{-1}ax) = x^{-1}C(a)x$ . 

###### Answer:

We know,

$$C(a) = \{g \in G | ga = ag\}$$ and for $H \subset G$, $H$ being a group itself, For $a\in G$, let $a^{-1}Ha = \{a^{-1}ha|h\in H\}$. 

Then for arbitrary $y\in C(x^{-1}ax)$, 

$$yx^{-1}ax = x^{-1}axy$$
$$xyx^{-1}axx^{-1} = xx^{-1}axyx^{-1}$$ 
$$\implies (xyx^{-1})a = a(xyx^{-1})$$ 
$$\implies xyx^{-1} \in C(a)$$ $$\implies y \in x^{-1}C(a)x$$ So, $$C(x^{-1}ax) \subset x^{-1}C(a)x\tag{1}$$ 

for arbitrary $z\in x^{-1}C(a)x$, 
$$xzx^{-1}a = axzx^{-1}$$
$$\implies z(x^{-1}ax) = (x^{-1}ax)z$$
$$\implies z \in C(x^{-1}ax)$$
So, $$x^{-1}C(a)x \subset C(x^{-1}ax)\tag{2}$$ So, from (1) and (2), 

$$C(x^{-1}ax) = x^{-1}C(a)x$$ 