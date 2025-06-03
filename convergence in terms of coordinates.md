A [[sequence]] $m\mapsto\mathbf{a}_m$ with $\mathbf{a}_m\in\mathbb{R}^n$ [[convergent sequence|converges]] to $\mathbf{a}$ if and only if each coordinate converges.
	**Proof:** $m\mapsto\mathbf{a}_m$ converges to $\mathbf{a}$ implies that for each $j=1,...,n$, the $j$th coordinate of $\mathbf{a}_m$ converges to $a_j$.
	Write $\mathbf{a}_m$ as $\begin{pmatrix}(a_m)_1\\\vdots\\(a_m)_n\end{pmatrix}$. There exists $M$ when $m\gt M$, $|\mathbf{a}_m-\mathbf{a}|\lt\epsilon$ (since $m\mapsto\mathbf{a}_m$ is convergent). The [[length of vector]] $\mathbf{a}_m-\mathbf{a}$ is $$|\mathbf{a}_m-\mathbf{a}|=\sqrt{((a_m)_1-a_1)^2+\cdots+((a_m)_n-a_n)^2},$$so $$|(a_m)_j-a_j|\le|\mathbf{a}_m-\mathbf{a}|\lt\epsilon.$$

Same definition for the [[matrix]] by the [[length of matrix]].