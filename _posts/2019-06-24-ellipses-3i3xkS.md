---
title: 3i3xkS
permalink: 3i3xkS
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{lcg}
\usepackage{tikz,tkz-base}
% -----------------

\reinitrand[counter=H, first=1,last=6]

\begin{tikzpicture}[scale=0.6]
\tkzInit[xmin=0, xmax=6,
         ymin=0, ymax=6]
\tkzAxeXY[label={}]
\foreach \x in {1,2,...,5} {
  \rand
  \draw (\x,0) rectangle (\x+0.5,\theH);
}
\end{tikzpicture}
```