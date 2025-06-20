Let $f:\mathbb{R}^n\to\mathbb{R}$ be [[bounded]] with bounded [[support of a function|support]]. The $N$th **upper** and **lower sums** of a [[function]] $f$ are $$\underset{N\text{th upper sum}}{U_N(f)}:=\sum_{C\in\mathcal{D}_N}M_C(f)\operatorname{vol}_nC\text{, }\underset{N\text{th lower sum}}{L_N(f)}:=\sum_{C\in\mathcal{D}_N}m_C(f)\operatorname{vol}_nC.$$where $M_C(f), m_C(f)$ see [[supremum infimum and oscillation of function]], $\operatorname{vol}_n$ see [[dyadic paving]].
As $N$ increases, the [[sequence]] $N\mapsto U_N(f)$ decreases, and the sequence $N\mapsto L_N(f)$ increases.

We call $$U(f):=\lim_{N\to\infty}U_N(f) \text{ and } L(f):=\lim_{N\to\infty}L_N(f)$$the **upper** and **lower integrals** of $f$.

If $f,g$ are bounded functions with bounded support and $f\le g$, then $$U(f)\le U(g)\text{ and }L(f)\le L(g).$$
