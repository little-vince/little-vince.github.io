---
title: fJuE2A
permalink: fJuE2A
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% ########### TODO #################
\noindent\hspace{0.64cm}\begin{minipage}[c]{0.95\textwidth}
\begin{lstlisting}[numbers=left,language=TeX, frame=lines,basicstyle=\footnotesize\ttfamily]
\documentclass[a4paper,12pt]{article} %-- Début préambule
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[french]{babel}
\usepackage{adforn}                   %   Ornements : \adfflatleaf...
\usepackage{multicol}                 %   Colonnes
                                      %-- Fin préambule
\begin{document}

\begin{center}
  \textbf{\LARGE \adfflatleafleft~1995~\adfflatleafright}
  \bigskip

  \textbf{\Large Liste de fournitures}
\end{center}

\begin{multicols}{2}                  % Début 2 colonnes
  \textsc{\large Pour le bureau}
  \begin{itemize}
    \item Pot à crayons,
    \item Agrafeuse et agrafes
  \end{itemize}

\columnbreak                          % Force le changement de colonne

  \textsc{\large Pour l'ordinateur}
  \begin{itemize}
    \item Boîte à disquettes
    \item Boule de souris de rechange
  \end{itemize}
\end{multicols}                       % Fin 2 colonnes

\end{document}
\end{lstlisting}
\end{minipage}
```