## Definition
Let $X$ be a set. A metric is a map $d:X\times X \to \mathbb{R}_{\geq 0}$  that satisfies the following conditions:
1. $d$ is positive definite, or $d(x,y)=0$ if and only if $x=y$
2. $d$ is symmetric, or $d(x,y) = d(y,x)$ for all $x,y\in X$
3. The triangle inequality holds. $d(x,y) \leq d(x,z)+d(z,y)$

## Examples

### Absolute Value 
$A:\mathbb{R} \times \mathbb{R} \to \mathbb{R}_{\geq 0}, (x,y) \mapsto |x-y|$
#### Proof 

### Discrete Metric
Let $X$ be a set. $d:X\times X \to \mathbb{R}_{\geq 0}, (x,y) \mapsto \begin{cases} 0, \text{ if x=y}\\1, \text{ if x=y}\end{cases}$
#### Proof

### Taxicab Metric
On $\mathbb{R}^2: d:\mathbb{R}^2 \times \mathbb{R}^2 \to \mathbb{R}_{\geq 0}, (x,y) \mapsto |y_1 -x_1|+|y_2-x_2|$  
On $\mathbb{R}^n: d:\mathbb{R}^n \times \mathbb{R}^n \to \mathbb{R}_{\geq 0}, (x,y) \mapsto \sum_{i=1}^{n} |y_i -x_i|$

#### Proof

### Euclidean Metric 
