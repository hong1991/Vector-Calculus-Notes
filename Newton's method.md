Let $\vec{\mathbf{f}}$ be a [[derivative|differentiable]] map from $U$ to $\mathbb{R}^n$, where $U$ is an open subset of $\mathbb{R}^n$. [[Newton's method]] consists of:
- Staring with some guess $\mathbf{a}_0$ for a solution of $\vec{\mathbf{f}}=\vec{\mathbf{0}}$. 
- Then linearize the equation at $\mathbf{a}_0$: replace the increment to the function, $\vec{\mathbf{f}}(\mathbf{x})-\vec{\mathbf{f}}(\mathbf{a}_0)$, by a linear function of the increment, $[\mathbf{D}\vec{\mathbf{f}}(\mathbf{a}_0)](\mathbf{x}-\mathbf{a}_0)$.
- Now solve the corresponding [[linear equation]]:$$\vec{\mathbf{f}}(\mathbf{a}_0)+[\mathbf{D}\vec{\mathbf{f}}(\mathbf{a}_0)](\mathbf{x}-\mathbf{a}_0)=\vec{\mathbf{0}}.$$
- This is a system of $n$ [[linear equation]]s in $n$ unknowns. We can write it as $$[\mathbf{D}\vec{\mathbf{f}}(\mathbf{a}_0)](\mathbf{x}-\mathbf{a}_0)=-\vec{\mathbf{f}}(\mathbf{a}_0).$$
- If $[\mathbf{D}\vec{\mathbf{f}}(\mathbf{a}_0)]$ is [[invertible]], which will usually be the case, then $$\mathbf{x}=\mathbf{a}_0-[\mathbf{D}\vec{\mathbf{f}}(\mathbf{a}_0)]^{-1}\vec{\mathbf{f}}(\mathbf{a}_0).$$
- Call this solution $\mathbf{a}_1$, use it as your new "guess", and solve $$[\mathbf{D}\vec{\mathbf{f}}(\mathbf{a}_1)](\mathbf{x}-\mathbf{a}_1)=\vec{\mathbf{0}}=-\vec{\mathbf{f}}(\mathbf{a}_1).$$
- Calling the solution $\mathbf{a}_2$, and so on. The hope is that $\mathbf{a}_1$ is a better approximation to a root than $\mathbf{a}_0$, and that the [[sequence]] $i\mapsto \mathbf{a}_i$ [[converges]] to a root of the equation.

There must be as many equations as unknows: the [[dimension]]s of the two [[space]]s must be equal.