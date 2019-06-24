---
title: 34sIPZ
permalink: 34sIPZ
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{pstricks-add}
% -----------------

\psset{unit=1.5}
\begin{pspicture*}(-1,-1)(1,1)
\pscircle(0,0){1}
\multido{\nC=0+30}{12}{
  \pscircle(1;\nC){1}
}
\end{pspicture*}
```