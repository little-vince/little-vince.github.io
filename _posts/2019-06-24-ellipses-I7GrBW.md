---
title: I7GrBW
permalink: I7GrBW
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}[grow'=right,level distance=2cm, sibling distance=0.8cm,->]

\node {A}
  child { node {B}}
  child { node {C}}
  child { node {D}
            child { node {E}}
            child { node {F}}
        };
\end{tikzpicture}
```