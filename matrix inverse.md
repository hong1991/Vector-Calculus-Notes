---
aliases:
  - invertible matrix
---

Let $A$ be a matrix, I be an [[identity matrix]]. If there is matrix $B$ such that $BA=I$, then $B$ is **left inverse** of $A$. If there is a matrix $C$ such that $AC=I$, then $C$ is a **right inverse** of $A$.

An **invertible matrix** is a [[matrix]] that has both a left inverse and a right inverse.

**Proposition:**
- An **invertible matrix** has only one left inverse and one right inverse, and they are identical; such a matrix is called the **inverse** of $A$, denoted $A^{-1}$.
	**Proof:** 
- If $A$ and $B$ are invertible, then $AB$ is invertible, and $$(AB)^{-1}=B^{-1}A^{-1}$$
Computing: [[computing matrix inverse]].