---
title: nDfKnQ
permalink: nDfKnQ
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}[bend angle=20]
  \tikzstyle{db}=[circle, draw, inner sep=0pt,
                  minimum width=6pt]
  \node[db](A) at(0,0)  {}; \node[db](B) at(1,1) {};
  \node[db](C) at(0,1.5){}; \node[db](D) at(-1,1){};
  \draw (A) to[bend right] (B) to[bend right] (A);
  \draw (A) to[bend right] (D) to[bend right] (A);
  \draw (A) -- (C);
  \draw (B) to[bend right=60] (C);
  \draw (D) to[bend left=60] (C);
\end{tikzpicture}
```