###### If G has no proper subgroups, prove that G is cyclic of order p, where p is a prime number.

###### Answer:

Say, $\mathcal{O}(G) = n \in \mathbb{N}$

Then, the following two statements follow.

1) given $a \in G$, every integral power of a HAS to be in $G$. i.e.,

$$ \lbrace a, a^2, a^3,...\rbrace = \lbrace a^i\rbrace_{i\in\mathbb{N}}\subset G \tag{1} $$

2) since $\mathcal{O}(G) = n$, all powers of $a$ cant be in $G$. 

The only way statements 1 and 2 can be reconciled, is if  $a^{n^\prime} = e, n^\prime \leq n$, thus making a subset in $G$ look like:

$$G^\prime = \lbrace e, a, a^2, \ldots, a^{n^\prime-1}\rbrace = \lbrace e\rbrace \cup \lbrace a^i\rbrace_{i=1}^{n^\prime-1} \tag{2}$$

But, $G^\prime$ is a cyclic group of order $n^\prime$. This makes $G^\prime$ a proper subgroup for $n^\prime < n$ (contradiction!!).

Thus $n^\prime = n \implies G^\prime=G$. $G$ is cyclic of order $n$.

$$G = \lbrace e, a, a^2, \ldots, a^{n-1}\rbrace = \lbrace e\rbrace \cup \lbrace a^i\rbrace_{i=1}^{n-1} \tag{3}$$

Now lets make one assumption:

1) $n$ is not prime.

if $n$ is not prime, then there are at-least two numbers $n_1 \in \mathbb{N}, n_2 \in \mathbb{N}$ and $1 < n_1 < n, 1 < n_2 < n$ such that, $n_1n_2 = n$ 

in that case, say $b=a^{n_1}$, then consider the set,

$$\lbrace b^i\rbrace_{i=1}^{n_2} = \lbrace b, b^2, b^3, \ldots, b^{n_2-1}, b^{n_2}\rbrace = \lbrace a^{n_1},a^{2n_1}, a^{3n_1},\ldots, a^{(n_2-1)n_1}, a^{n_2n_1}\rbrace\subset G\tag{3}$$

Now as $a^{n_2n_1} = a^{n} = e$, 

$$\lbrace a^{n_1},a^{2n_1}, a^{3n_1},\ldots, a^{(n_2-1)n_1}, a^{n_2n_1}\rbrace = \lbrace e, a^{n_1},a^{2n_1}, a^{3n_1},\ldots, a^{(n_2-1)n_1}\rbrace = \lbrace e, b, b^2, \ldots, b^{n_2-1}\rbrace \tag{4}$$

Now lets rewrite this set in a different syntax: 

$$\lbrace e, b, b^2, \ldots, b^{n_2-1}\rbrace = \lbrace e\rbrace \cup \lbrace b^i\rbrace_{i=1}^{n_2-1} = G_{1}\subset G\tag{5}$$

Comparing equations (3) and (5), we see that $G_1$ is itself a group of order $n_2<n$, i.e., $(\mathcal{O}(G_1) = n_1 < n = \mathcal{O}(G))$ . And since $G_1\subset G$, $G_1$ is a proper subgroup of $G$ !! 

So, the assumption statement (4) being true contradicts assumption statement (3). So they both can't be true together! So, 

**If $G$ has no proper subgroups, then $n$ has to be prime.** 