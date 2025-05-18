---
aliases:
  - differentiable
---

Let $U\subset\mathbb{R}^n$ be an [[open set|open]] subset and let $\mathbf{f}:U\to\mathbb{R}^m$ be a mapping; let $\mathbf{a}$ be a point in $U$. If there exists a [[linear transformation]] $L:\mathbb{R}^n\to\mathbb{R}^m$ such that $$\lim_{\vec{\mathbf{h}}\to\vec{0}}\frac{1}{|\vec{\mathbf{h}}|}((\mathbf{f}(\mathbf{a}+\vec{\mathbf{h}})-\mathbf{f}(\mathbf{a}))-(L(\vec{\mathbf{h}})))=\vec{\mathbf{0}},$$then $\mathbf{f}$ is [[derivative|differentiable]] at $\mathbf{a}$, and $L$ is unique and is the [[derivative]] of $\mathbf{f}$ at $\mathbf{a}$, denoted $[\mathbf{Df}(\mathbf{a})]$.