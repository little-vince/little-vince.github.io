---
title: 19BSDM
permalink: 19BSDM
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tasks}
\usepackage{amssymb}
% -----------------

\DeclareInstance{tasks}{multiplechoice}{default}{label= $\Box$,label-width=15pt}

Cochez les gaz rares
\begin{tasks}[style=multiplechoice](2)
  \task Hydrogène
  \task Hélium
  \task Oxygène
  \task Néon
\end{tasks}
```
