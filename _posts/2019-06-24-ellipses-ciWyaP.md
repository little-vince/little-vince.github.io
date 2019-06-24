---
title: ciWyaP
permalink: ciWyaP
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{pstricks-add}
% -----------------

\psset{unit=0.5}
\begin{pspicture}(-1,-1)(5,4)
\cnodeput(0,0){a}{A}   \cnodeput(1,3){b}{B}
\cnodeput(3,0){c}{C}   \cnodeput(4,3){d}{D}
\ncline{a}{b} \ncline{a}{c}
\ncline{a}{d} \ncline{b}{c}
\end{pspicture}
```