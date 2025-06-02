Represent the system $A\vec{\mathbf{x}}=\vec{\mathbf{b}}$, involving $m$ linear equations in $n$ unknowns, by the $m\times(n+1)$ [[matrix]] $[\tilde{A}|\tilde{\mathbf{b}}]$. Then
1. If the row-reduced vector $\tilde{\mathbf{b}}$ contains a pivotal $1$, the system has no solutions.
2. If $\tilde{\mathbf{b}}$ does not contain a pivotal $1$, then solution are uniquely determined by the values of the non-pivotal variables:
	1. If each column of $\tilde{A}$ contains a pivotal $1$ (so there are no non-pivotal variables), the system has unique solution.
	2. If at least one column of $\tilde{A}$ is non-pivotal, there are infinitely many solutions: exactly one for each value of the non-pivotal variables.