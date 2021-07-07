---
title: I2AAm8
permalink: I2AAm8
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz,tkz-base}
% -----------------

\begin{tikzpicture}[scale=2]
\tkzInit[xmin=37.2,xmax=37.4,xstep=0.1];
\tkzAxeX[label={temp.}];
\tkzDefPoint(37.35,0){T}
\draw(T) node {$\bullet$} node[above]{t};
\end{tikzpicture}
```