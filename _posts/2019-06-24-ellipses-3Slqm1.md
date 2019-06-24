---
title: 3Slqm1
permalink: 3Slqm1
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{calc}
% -----------------

\newcounter{na} \setcounter{na}{6}
\newlength{\la} \setlength{\la}{6pt}
\setcounter{na}{\value{na} * \real{1.875}} \thena,
\setlength{\la}{      \la  * \real{1.875}} \the\la.
```