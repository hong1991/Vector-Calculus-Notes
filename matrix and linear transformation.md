1. Any $m\times n$ [[matrix]] $A$ defines a [[linear transformation]] $T:\mathbb{R}^n\rightarrow\mathbb{R}^m$ by matrix multiplication:$$T(\vec{v})=A\vec{v}.$$
2. Every [[linear transformation]] $T:\mathbb{R}^n\rightarrow\mathbb{R}^m$ is given by multiplication by the matrix $m\times n$ [[matrix]] $[T]$:$$T(\vec{v})=[T]\vec{v},$$where the $i$th column of $[T]$ is $T(\vec{e_i})$.

Proof:
1. This follows immediately from the rules of matrix multiplication.
2. Start with a [[linear transformation]] $T:\mathbb{R}^n\rightarrow\mathbb{R}^m$, and manufacture the matrix $[T]=[T\vec{e}_1,...,T\vec{e}_n]$. We may write any vector $\vec{v}\in\mathbb{R}^n$ in terms of the [[standard basis vectors]]: $\vec{v}=v_1\vec{e}_1+...+v_n\vec{e}_n,$ or, with sum notation, $\vec{v}=\sum_{i=1}^{n}v_i\vec{e}_i$. Then, by linearity,$$T(\vec{v})=T\sum_{i=1}^nv_i\vec{e}_i=\sum_{i=1}^nv_iT(\vec{e}_i)$$which is precisely the the column vector $[T]\vec{v}$.