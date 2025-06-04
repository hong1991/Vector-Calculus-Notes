A set of [[points and vectors|vectors]] $\vec{\mathbf{v}}_1,...,\vec{\mathbf{v}}_k$ is **orthonormal** if each vector in the set is [[angle between two vectors|orthogonal]] to every other vector in the set, and all vectors have [[length of vector|length]] $1$: $$\vec{\mathbf{v}}_i\cdot\vec{\mathbf{v}}_j=0\text{ for } i\ne j and |\vec{\mathbf{v}}_i|=1 \text{ for all } i\le k.$$
An orthonormal set is an **orthonormal basis** of the [[subspace of Rn|subsapce]] $V\subset\mathbb{R}^n$ that it [[span]]s. 

**Propositions:** 
1. An orhogonal set of nonzero vectors $\vec{\mathbf{v}}_1,...,\vec{\mathbf{v}}_k$ is [[linear independence|linearly independent]].
	**Proof:** [[TODO]]
2. **(Properties of orthonormal bases)** Let $\vec{\mathbf{v}}_1,...,\vec{\mathbf{v}}_k$ be an orthonormal basis of $\mathbb{R}^n$.
	1. Any vector $\vec{\mathbf{x}}\in\mathbb{R}^n$ can be written $\vec{\mathbf{x}}=\sum_{i=1}^n(\vec{\mathbf{x}}\cdot\vec{\mathbf{v}}_i)\vec{\mathbf{v}}_i$.
	2. If $\vec{\mathbf{x}}=a_1\vec{\mathbf{v}}_1+\cdots+a_n\vec{\mathbf{v}}_n$, then $|\vec{\mathbf{x}}|^2=a_1^2+\cdots+a_n^2$.