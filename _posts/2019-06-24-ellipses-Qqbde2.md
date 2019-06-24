---
title: Qqbde2
permalink: Qqbde2
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
\newsavebox{\mybox}
\savebox{\mybox}{%
\begin{minipage}{\0.75\linewidth}
Du texte juste pour remplir.
Du texte juste pour remplir.
\end{minipage}
}

\usebox{\mybox}
\begin{center}
  \usebox{\mybox}
\end{center}
```