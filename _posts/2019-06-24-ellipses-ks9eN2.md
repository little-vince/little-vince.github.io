---
title: ks9eN2
permalink: ks9eN2
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{ifthen}
% -----------------

\newcommand{\bareme}[1]{
  \ifthenelse
    {\equal{#1}{bonus}}
    {\bfseries BONUS}{\point{#1}}
}
\bareme{1}, \bareme{2.5}, \bareme{bonus}
```