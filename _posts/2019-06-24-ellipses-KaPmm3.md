---
title: KaPmm3
permalink: KaPmm3
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% ########### TODO #################
\noindent\hspace{0.0cm}\begin{minipage}[c]{0.95\textwidth}
\begin{codell}
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}[xscale=0.9,yscale=2.7, samples=300]
\fill[color=gray!40]
plot [domain=1:3] (\x, {sin(pi*\x r)/((\x*\x)+1)} )
-- plot [domain=3:1] (\x, {1/((\x*\x)+1)} ) -- cycle;
\foreach \x in {1,2,3}
\draw[thick] (\x,0.5mm)--(\x,-0.5mm);
\foreach \y in {0.2,0.4,...,1}
\draw[thick] (1mm,\y)--(-1mm,\y) node[left]{$\pgfmathprintnumber\y$};

\draw[->] (-0.5,0) -- (3.5,0);
\draw[->] (0,-0.4) -- (0,1.1);
\draw (1mm,1) -- (-1mm,1) node[left] {$1$};
\draw[domain=0:3.5] plot (\x, {sin(pi*\x r)/((\x*\x)+1)} );
\draw[domain=0:3.5] plot (\x, {1/((\x*\x)+1)} );
\end{tikzpicture}
\end{codell}
\end{minipage}
```