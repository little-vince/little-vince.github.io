---
title: J22Sop
permalink: J22Sop
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{pst-circ}
% -----------------

\begin{pspicture}(0,0)(4.5,3)
\pnodes(0,1){A}(2,0){B}(4,2){C}
\transistor(A)(B)(C)
\transistor(B){emet}{col}
\wire[arrows=-*](col)(col|C)
\end{pspicture}
```