---
tags:
  - algorithm
---
To bring a [[matrix]] to [[echelon form]],
1. Find the first column that is not all $0$'s; call this the first ivotal column and call its first nonzero entry a pivot. If the pivot is not in the first row, move the row containing it to first row position.
2. Divide the first row by the pivot, so that the first entry of the first pivotal column is $1$.
3. Add appropriate multiples of the first row to the other rows to make all other entries of the first pivotal column $0$. The $1$ in the first column is now a pivotal $1$.
4. Choose the next column that contains at least one nonzero entry beneath the first row, and put the row containing the new pivot in second row position. Make the pivot a pivotal $1$: divide by the pivot, and add appropriate multiples of this row to the other rows, to make all other entries of the column $0$.
5. Repeat until the matrix is in echelon form. Each time choose the first column that has a nonzero entry in a lower row than the lowest row containing a pivotal $1$, and put the row containing that entry directly below the lowest row containing a pivotal $1$.

**Proof Uniqueness:** [[TODO]]