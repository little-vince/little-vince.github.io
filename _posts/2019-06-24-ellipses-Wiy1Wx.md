---
title: Wiy1Wx
permalink: Wiy1Wx
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{multirow}
\usepackage{graphics}
\usepackage{amssymb}
% -----------------

\newcommand{\prop}[1]
  {\multirow{2}{*}{\rotatebox[origin=c]{-90}
   {\LARGE$\curvearrowright$} #1}}
\renewcommand{\arraystretch}{2}

\begin{tabular}{|l|c|c|r}            \cline{1-3}
Volume & 1 & 3 & \prop{$\times 2$}\\ \cline{1-3}
Poids  & 2 & 6 &                  \\ \cline{1-3}
\end{tabular}
```