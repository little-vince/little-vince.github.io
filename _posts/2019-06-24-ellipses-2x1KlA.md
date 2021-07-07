---
title: 2x1KlA
permalink: 2x1KlA
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
\newsavebox{\mybox}
\savebox{\mybox}{
\begin{minipage}{\0.75\linewidth}
Du texte juste pour remplir.
Du texte juste pour remplir.
\end{minipage}
}
\newlength\hauteur
\settoheight\hauteur{\usebox{\mybox}}
\newlength\profondeur
\settodepth\profondeur{\usebox{\mybox}}
\addtolength\hauteur{\profondeur}

\begin{center}
  \rule[-\profondeur]{4pt}{\hauteur}
  \usebox{\mybox}
\end{center}
```
