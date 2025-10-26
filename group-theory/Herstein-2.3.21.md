###### If $A$, $B$ are subgroups of $G$ such that $b^{-1}Ab \subset A$ for all $b \in B$, Show that $AB$ is a subgroup of $G$

For arbitrary $x = a_0b_0 \in AB$ and $y = a_1b_1 \in AB$,

$$
xy = a_0b_0a_1b_1 = a_0b_0a_1b_0^{-1}b_0b_1 
$$
From the assumptions, $b_0a_1b_0^{-1} \in A$, so with $a_2 = a_0(b_0a_1b_0^{-1}) \in A$ and $b_2 = b_0b_1$ as $A$ and $B$ are groups themselves,
$$xy = a_2b_2 \implies xy \in AB$$ 
now, given $x = ab \in AB$,
$$
x^{-1} = b^{-1}a^{-1} = b^{-1}a^{-1}bb^{-1} = a^{\prime}b^{\prime} \in AB
$$
where, $a^{\prime} = b^{-1}a^{-1}b \in A$ and $b^{\prime} = b^{-1} \in B$. 

the identity, 
$$
e = e  e \in AB
$$
as $e \in A$ and $e \in B$ 