The length of a $n\times m$ [[matrix]] $A$, denoted $|A|$, has $$|A|^2:=\sum_{i=1}^{n}\sum_{j=1}^ma_{i,j}^2.$$
We see that two matrices $|A|$ and $|B|$ are close if $|A-B|$ is small.


**Proposition:** 
Let $A$ be an $n\times m$ matrix, $B$ an $m\times k$ matrix, and $\vec{\mathbf{a}}$ a [[points and vectors|vector]] in $\mathbb{R}^m$. Then 
$$|A\vec{\mathbf{b}}|\le|A||\vec{\mathbf{b}}|$$
$$|AB|\le|A||B|$$
**Proof:**  If $A$ consists of a single row ($A=\vec{\mathbf{a}}^T$), by [[Schwarz's inequality]], $|A\vec{\mathbf{b}}|=|\vec{\mathbf{a}}\cdot\vec{\mathbf{b}}|\le|\vec{\mathbf{a}}||\vec{\mathbf{b}}|=|A||\vec{\mathbf{b}}|$. Consider the rows of $A$ as transposes of vectors $\vec{\mathbf{a}}_1,...,\vec{\mathbf{a}}_n$. Since the $i$th row of $A$ is $\vec{\mathbf{a}}_i^T$, the $i$th entry $(A\vec{\mathbf{b}})_i$ of $A\vec{\mathbf{b}}$ is the dot product $\vec{\mathbf{a}}_i\cdot\vec{\mathbf{b}}$. This leads to $$|A\vec{\mathbf{b}}|^2=\sum_{i=1}^n(A\vec{\mathbf{b}})_i^2=\sum_{i=1}^n(\vec{\mathbf{a}}_i\cdot\vec{\mathbf{b}})^2.$$
Proof unfinished [[TODO]]
