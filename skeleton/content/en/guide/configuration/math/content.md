---
template: 'guide.htm'
---
You can use the LaTeX syntax to write math formulas:

```latex
\begin{aligned}
F(\textbf{w})
&= \sum_{k=1}^{K} \frac{n_k}{N} F_{k}(\textbf{w}) \\
&= \sum_{k=1}^{K} \frac{n_k}{N} \frac{1}{n_k} \sum_{i \in \mathcal{P}_{k}} l(\textbf{x}_{i}, \textbf{y}_{i}; \textbf{w})
\end{aligned}
```

The _inline_ syntax is also supported $$x = \frac{1}{2}$$.
