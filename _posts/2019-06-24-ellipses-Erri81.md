---
title: Erri81
permalink: Erri81
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{chemfig}
% -----------------

\begin{tikzpicture}
  \coordinate(O) at (0,0);
  \coordinate(A) at (45:3);
  \coordinate(B) at ({3*cos(45)},0);

  \draw (O)--(A)--(B);
  \draw[fill=white] (A) circle(0.2);
  \draw (A) node{$\bullet$};
  \draw[fill=lightgray](45:1) --++(135:0.4)
               --++(-135:0.4) --++(-45:0.4) --cycle;
  \draw[fill=gray](A) ++(0.1,-1) --++(0.2,0)
                    --++(0,-0.2) --++(-0.2,0) --cycle;
  \draw[thick] (45:1)++(135:0.2)--++(45:2) arc (135:0:0.2) --++(0,-1);
  \end{tikzpicture}
```