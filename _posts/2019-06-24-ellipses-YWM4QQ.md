---
title: YWM4QQ
permalink: YWM4QQ
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{pst-tree}
% -----------------

\psset{nodesep=5pt,treesep=1,
       levelsep=1.5cm,arrows=->}
\pstree{\Toval{Bernoulli}}{
  \pstree{\TR{A1} \nbput{$1-p$}}
             {\TR{A2}  \nbput{$1-q$}
              \TR{B2}  \naput{$q$}   }
  \pstree{\TR{B1} \naput{$p$} }
             {\TR{A3}  \nbput{$1-r$}
              \TR{B3}  \naput{$r$}   }
}
```