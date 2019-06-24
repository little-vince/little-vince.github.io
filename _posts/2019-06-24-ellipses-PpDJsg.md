---
title: PpDJsg
permalink: PpDJsg
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}[x=0.5cm]
\foreach \x in {0,1,...,8} {
\draw (\x,1mm) node{$\bullet$} node[above]{\x};
}
\end{tikzpicture}
```