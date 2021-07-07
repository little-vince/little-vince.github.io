---
title: yF7tW6
permalink: yF7tW6
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{tkz-euclide}
\usetkzobj{all}
% -----------------

\begin{tikzpicture}
% Les points M, P et Q et le triangle
\tkzDefPoint(0,0){M} \tkzDefPoint(1.5,3){P}
\tkzDefPoint(4,0){Q} \tkzDrawPolygon(M,P,Q)
% Deux bissectrices
\tkzDrawBisector(M,P,Q) \tkzGetPoint{P'}
\tkzDrawBisector(Q,M,P) \tkzGetPoint{M'}
% L'intersection I des bissectrices
\tkzInterLL(M,M')(P,P') \tkzGetPoint{I}
% Le cercle inscrit
\tkzDefPointBy[projection=onto M--P](I)
                        \tkzGetPoint{I'}
\tkzDrawCircle(I,I')
% Marquage des points et étiquettes
\tkzDrawPoints(M,P,Q,P',M',I,I')
\tkzLabelPoints(M,Q,I,I',P')
\tkzLabelPoints[right](P,M')
\end{tikzpicture}
```