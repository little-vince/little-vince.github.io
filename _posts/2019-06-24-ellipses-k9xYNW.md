---
title: k9xYNW
permalink: k9xYNW
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tikz}
% -----------------

\begin{tikzpicture}
\foreach \x/ \mois/ \eff in
        {1/Jan/20, 2/Fév/19, 3/Mar/36,
         4/Avr/29, 5/Mai/11, 6/Jui/27 }{
\draw(\x,0) node[below] {\mois};
\draw[fill=red](\x-0.3,0) rectangle
                            (\x+0.3,\eff);
}
\end{tikzpicture}
```