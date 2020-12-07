---
template: guide.htm
---
Vous pouvez utiliser la syntaxe de LaTeX pour écrire des formules de math:

```latex
\begin{aligned}
F(\textbf{w})
&= \sum_{k=1}^{K} \frac{n_k}{N} F_{k}(\textbf{w}) \\
&= \sum_{k=1}^{K} \frac{n_k}{N} \frac{1}{n_k} \sum_{i \in \mathcal{P}_{k}} l(\textbf{x}_{i}, \textbf{y}_{i}; \textbf{w})
\end{aligned}
```

Aussi, la syntaxe _inline_ est supportée $$x = \frac{1}{2}$$.
