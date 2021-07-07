---
title: iQhJxC
permalink: iQhJxC
layout: post
date: 2020-12-30 11:20:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
\usetikzlibrary{positioning}
% -----------------

\renewcommand{\arraystretch}{2}

\tikzstyle{every picture}+=[remember picture]
\begin{tabular}{|l|c|c|r}     \cline{1-3}
Volume&1&3& \tikz\node(A){}; \\ \cline{1-3}
Poids &2&6& \tikz\node(B){}; \\ \cline{1-3}
\end{tabular}

\begin{tikzpicture}[overlay]
  \coordinate[right=3mm of A] (AA);
  \coordinate[right=3mm of B] (BB);
  \draw[->] (A)--(AA)--node[right] {$\times 2$}(BB) --(B);
\end{tikzpicture}
```
