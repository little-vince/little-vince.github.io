---
title: PIs31c
permalink: PIs31c
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{minted}
% -----------------

\usemintedstyle{bw}
\begin{minted}[linenos=true,
bgcolor=lightgray, frame=lines]
{python}
from random import *

def somme_deux_des():
    a = randint(1,6)
    b = randint(1,6)
    return a+b
\end{minted}
```