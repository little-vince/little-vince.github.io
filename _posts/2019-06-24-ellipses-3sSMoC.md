---
title: 3sSMoC
permalink: 3sSMoC
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{calc}
% -----------------

\newcounter{na}    \newcounter{nb}
\setcounter{na}{6} \setcounter{nb}{3}
\newcounter{nc}
\setcounter{nc}{\value{na} + \value{nb}} \thenc,
\setcounter{nc}{\value{na} - \value{nb}} \thenc,
\setcounter{nc}{\value{na} * \value{nb}} \thenc,
\setcounter{nc}{\value{na} / \value{nb}} \thenc.
```