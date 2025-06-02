---
aliases:
  - differentiable
---

Let $U\subset\mathbb{R}^n$ be an [[open set|open]] subset and let $\mathbf{f}:U\to\mathbb{R}^m$ be a mapping; let $\mathbf{a}$ be a point in $U$. If there exists a [[linear transformation]] $L:\mathbb{R}^n\to\mathbb{R}^m$ such that $$\lim_{\vec{\mathbf{h}}\to\vec{0}}\frac{1}{|\vec{\mathbf{h}}|}((\mathbf{f}(\mathbf{a}+\vec{\mathbf{h}})-\mathbf{f}(\mathbf{a}))-(L(\vec{\mathbf{h}})))=\vec{\mathbf{0}},$$then $\mathbf{f}$ is [[derivative|differentiable]] at $\mathbf{a}$, and $L$ is **unique** and is the [[derivative]] of $\mathbf{f}$ at $\mathbf{a}$, denoted $[\mathbf{Df}(\mathbf{a})]$.

**Proof Uniqueness:** The [[linear transformation]] $L$ is represented by the matrix ([[matrix and linear transformation]]) whose $i$th column is $L(\vec{\mathbf{e}}_i)$, so we need to show that $$L(\vec{\mathbf{e}}_i)=\overrightarrow{D_i\mathbf{f}}(\mathbf{a})$$where $\overrightarrow{D_i\mathbf{f}}(\mathbf{a})$ is by definition the $i$th column of the [[Jacobian matrix]] $[\mathbf{J(f(a)}]$.