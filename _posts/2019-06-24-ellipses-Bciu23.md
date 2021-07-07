---
title: Bciu23
permalink: Bciu23
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{siunitx}
% -----------------

\begin{frame}

\[ \frac{E}{m} = \SI{9,0e16}{\meter^2\per\second^2} \]

\visible<2->{
  et donc :
  \begin{align*}
    \sqrt\frac{E}m &= \SI{3,0e8}{\meter\per\second} \\
      \visible<3->{&= c}
  \end{align*}
}
\end{frame}
```