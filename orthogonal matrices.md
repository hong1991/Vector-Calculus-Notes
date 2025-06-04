An $n\times n$ [[matrix]] is called orthogonal if it satisfies one of the following equivalent conditions:
1. $AA^T=A^TA=I$, i.e., $A^T=A^{-1}$
2. The columns of $A$ form an [[orthonormal set|orthonormal basis]] of $\mathbb{R}^n$
3. The matrix $A$ preserves [[dot product of vector|dot product]]s: for any $\vec{\mathbf{v}},\vec{\mathbf{w}}\in\mathbb{R}^n$, we have $$A\vec{\mathbf{v}}\cdot A\vec{\mathbf{w}}=\vec{\mathbf{v}}\cdot \vec{\mathbf{w}}.$$

**Proof:**
1. A left [[matrix inverse|inverse]] of a square matrix is also a right inverse, so $A^TA=I$ implies $AA^T=I$.
2. Let $A=[\vec{\mathbf{v}}_1,...,\vec{\mathbf{v}}_n]$. Then $$(A^TA)_{i,j}=\vec{\mathbf{v}}_i\cdot\vec{\mathbf{v}}_j=\begin{cases}1&\text{if }i=j \\ 2 & \text{if } i\ne j\end{cases}$$if and only if the $
