---
title: JJ3mp2
permalink: JJ3mp2
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
\matrix[nodes={draw,circle}, row sep=0.5cm,
                             column sep=0.5cm] {
  \node (a){1}; &\node (c){3}; &             ;\\
  \node (b){2}; &            ; &\node (d){4} ;\\ };

\tikzstyle{fleche} = [draw,thick,->,>=latex]
\draw[fleche] (b) -- (a);
\draw[fleche] (c) -- (a);
\draw[fleche] (b) -- (c);
\draw[fleche] (c) to[bend right] (d);
\draw[fleche] (d) to[bend right] (c);
\end{tikzpicture}
```