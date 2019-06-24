---
title: n04dgS
permalink: n04dgS
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}
\draw[->] (-1,0)--(3.5,0);
\foreach \x in {-1,...,3} {
  \draw[thick] (\x,2mm)--(\x,-2mm)
    node[below]{$\x$};    };
\foreach \x in {-1,-0.75,...,3} {
  \draw (\x,1mm)--(\x,-1mm);    };
\foreach \y in {0,0.1,...,1} {
  \draw (-1mm,\y)--(1mm,\y); };
\end{tikzpicture}
```