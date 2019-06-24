---
title: FP2jx5
permalink: FP2jx5
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz,tkz-base}
% -----------------

\begin{tikzpicture}[scale=0.2]
\tkzInit[xmin=-2,xmax=2,ymin=-2,ymax=2]
\tkzDrawXY   % Trace les axes avec les graduations
             %           mais sans les coordonnées
% La courbe
\draw[domain= -2:-0.2] plot (\x, {1/\x} );
\draw[domain=0.2:2   ] plot (\x, {1/\x} );
\end{tikzpicture}
```