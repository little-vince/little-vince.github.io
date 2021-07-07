---
title: nxqkFI
permalink: nxqkFI
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}[xscale=0.2]
  \draw[->,>=latex] (-7,0) -- (11,0);
  \draw[->,>=latex] (0,-0.5) -- (0,0.5);
\foreach \x/\label in
   {-2/-2\pi, -1/-\pi, 1/\pi, 2/2\pi, 3/3\pi} {
  \draw[thick] (\x*3.14,2mm) -- (\x*3.14,-2mm)
                       node[below] {$\label$}; };
\foreach \x in {-12,...,18} {
  \draw (\x*3.14/6,1mm) -- (\x*3.14/6,-1mm);
};
\end{tikzpicture}
```