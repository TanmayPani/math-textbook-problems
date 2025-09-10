##### If $A$ and $B$ are subgroups of an abelian group $G$, let $AB = \lbrace ab | a \in A, b \in B \rbrace$. Prove that $AB$ is a subgroup of $G$. 

Alright, so if $G$ is abelian, then that implis that for two elements of $G$ $g, a$, $ga = ag$. In other words, all elements of $G$ commute with one another. 

If $A$ and $B$ are subgroups of $G$, then elements $a \in A$ are also in $G$, and same for $B$: $a, b \in G$. This also implies that all $a, b \in G$ commute with one another. 

Now, to show that $AB$ is a subgroup of $G$, then we must show closure. Specifically, we must show that for two elements of $AB$, let's call them $a_1b_1$ and $a_2b_2$, then: 
$$a_1b_1a_2b_2 \in AB \tag{1}$$

Since we know that all $a, b$ commute with each other (since they are elements of the abelian group $G$), we can rewrite equation (1) as:

$$a_1b_1a_2b_2 = a_1a_2b_1b_2 \tag{2}$$
By associative property and closure in subgroups $A$ and $B$, we know that $(a_1a_2) \in A$ and $(b_1b_2)\in B$. This implies (given the condition of $AB$) that $a_1b_1a_2b_2 \in AB$, so closure is satisfied and $AB$ is indeed a subgroup of $G$. Yay!




