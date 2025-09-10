###### If $S$ is a nonempty set and $X \subset S$, show that $T(X) = \lbrace f \in A(S)|f(X)\subset X \rbrace$ is a subgroup of $A(S)$ if X is finite.

In order to show that $T(X)$ is a subgroup of $A(S)$, we must show closure. In other words, we must show that for $f, g \in A(S)$, then $fg \in A(S)$. 

If we are to show that $fg \in A(S)$, then we must therefore show that $f(g(x)) \subset X$. 

Since $g \in A(S)$, then we know that $g(X) \subset X$. If $g(X) \subset X$, then $g(X) \subset S$ (because we are given that $X \subset S$). This then implies that $f(g(X)) \subset X$, so we know that $T(X)$ has closure and is therefore a subgroup of $A(S)$. 

