---
title: pTraxA
permalink: pTraxA
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz,tkz-base}
% -----------------

\begin{tikzpicture}
\clip (-3.2,-1.2) rectangle (1.6,2.2);
\draw[step=.25cm,lightgray,very thin]
   (-3,-1) grid (1,2);
\tkzInit[xmin=-3,xmax=1,
         ymin=-1,ymax=1.5]
\tkzAxeXY[label={}]
\draw plot[mark=*,mark size=0.6mm,smooth]
     coordinates {(-3,0) (-2,1.5) (0,0) (1,1)};
\end{tikzpicture}
```