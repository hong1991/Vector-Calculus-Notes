A [[matrix]] is in **echelon form** if
1. In every row, the first nonzero entry is $1$, called a **pivotal** 1.
2. The pivotal $1$ of a lower row is always to the right of the pivotal $1$ of a higher row.
3. In every column that contains a pivotal $1$, all other entries are $0$.
4. Any rows consisting entirely of $0$'s are at the bottom.

**Theorem**
1. Given any matrix $A$, there exists a matrix $\tilde{A}$ in echelon form that can be obtained from $A$ by [[row operations]].
2. The matrix $\tilde{A}$ is unique.