---
title: p48XnR
permalink: p48XnR
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{pstricks-add}
% -----------------

\begin{pspicture}(0,0)(3,2)
\pnode(1,1){A} \pnode(3,1){B}
\psdots(A) \uput[90](A){$A$}
\psdots(B) \uput[0](B){$B$}
\end{pspicture}
```