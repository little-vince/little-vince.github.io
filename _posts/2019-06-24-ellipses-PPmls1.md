---
title: PPmls1
permalink: PPmls1
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{calc}
% -----------------

\newsavebox{\mybox}
\newcommand{\boiboite}[1]{
\savebox{\mybox}{\begin{minipage}{0.75\linewidth}#1\end{minipage}}
\setlength\profondeur{\depthof{\usebox\mybox}}
\setlength\hauteurtot{
                \totalheightof{\usebox\mybox}}
\begin{center}
\rule[-\profondeur]{4pt}{\hauteurtot}%
\rule[-\profondeur-4pt]{1pt}{\hauteurtot+8pt}
\usebox{\mybox}
\end{center}
}

\boiboite{ bla bla bla bla bla bla bla bla bla bla bla bla bla}
\boiboite{ bli bli bli bli bli bli }
```