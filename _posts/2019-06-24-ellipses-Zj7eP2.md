---
title: Zj7eP2
permalink: Zj7eP2
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% ########### TODO #################
\noindent\hspace{0.64cm}\begin{minipage}[c]{0.95\textwidth}
\begin{lstlisting}[numbers=left,language=TeX, frame=lines,basicstyle=\footnotesize\ttfamily]
\documentclass{book}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[french]{babel}

\usepackage{makeidx}
\usepackage{imakeidx} % Pour avoir [intoc]
\makeindex[intoc]     % intoc ajoute l'index au sommaire

\begin{document}
\frontmatter %------------------------
\tableofcontents
\chapter{Préambule}
\chapter{Introduction}

\mainmatter %-------------------------
\part{Première partie}
\chapter{Premier chapitre}
\section{Section 1}
\section{Section 2}

\part{Seconde partie}
\chapter{Second chapitre}
\section{Section 1}
\section{Section 2}

\appendix %--------------------------
\chapter{Notes}
\chapter{Références}

\backmatter %------------------------
\chapter{Postface}
\printindex

\end{document}
\end{lstlisting}
\end{minipage}
```