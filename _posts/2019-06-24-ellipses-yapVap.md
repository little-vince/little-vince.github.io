---
title: yapVap
permalink: yapVap
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
\draw(0,0) circle(2);
\draw(0,0) circle(2.5);

% segments en coordonnees polaires :
\foreach \k in {0,...,360}
  \draw(10*\k:2)--(15*\k:2.5);
\end{tikzpicture}
```