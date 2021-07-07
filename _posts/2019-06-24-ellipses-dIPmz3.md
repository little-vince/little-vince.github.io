---
title: dIPmz3
permalink: dIPmz3
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
\usepackage{tkz-tab}
% -----------------

\begin{tikzpicture}
  \tkzTabInit[lgt=1.4,espcl=2.2]{$x$/1,$f'(x)$/1,$f$/1}
             { $-\infty$   , $-1$   , $0$                   , $+\infty$}
  \tkzTabLine{   ,-        , , -    , d, -                  , 0}
  \tkzTabVar {+/$+\infty$  , R/     ,-D+/$-\infty$/$+\infty$,-/0}

  % ajoute 0 pour l'element n°2 sur la flèche 1->3
  \tkzTabIma[draw]{1}{3}{2}{$0$}
\end{tikzpicture}
\end{codell}
\end{minipage}
```