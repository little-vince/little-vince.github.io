---
title: ZghL2w
permalink: ZghL2w
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% ########### TODO #################
\noindent\hspace{0.64cm}\begin{minipage}[c]{0.95\textwidth}
\begin{lstlisting}[numbers=left,language=TeX, frame=lines,basicstyle=\footnotesize\ttfamily]
\documentclass[a4paper,11pt]{article}
\usepackage[left=2cm,right=3cm,top=3.2cm,bottom=2.9cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{graphicx}                    % Pour insert° images
\usepackage{amsmath, amssymb, amsfonts}  % Pour les maths
\usepackage[french]{babel}               % Typo Française
\setlength{\parindent}{0mm}              % Pas de retrait de paragraphe
\newcommand{\R}{\mathbb{R}}              % L'ens. des réels

\usepackage{fancyhdr} \pagestyle{fancy}  % En-tete de page
 \fancyhead[L]{Épreuve de Bac Blanc}     %
 \setlength{\headheight}{14pt}           % épaiss. ligne en-tete

\begin{document}

%% ======================================================
\textbf{\textsc{Exercice 1} \hfill 6 points}

On note, pour tout réel $x$
\[f_{1}(x) = \dfrac{1}{1 + \text{e}^{- x}} \]
La représentation graphique $\mathcal{C}_{1}$ de la fonction $f_{1}$
dans le repère $(O,\vec\imath,\vec\jmath\,)$ est donnée ci-dessous.

\begin{center}                                      % Début centrage
  \includegraphics[scale=0.6]{graphe3}              % Insertion image
\end{center}                                        % Fin centrage

\begin{enumerate}
\item Démontrer que, pour tout réel
      $x, f_{1}(x) = \dfrac{\text{e}^{x}}{1 +  \text{e}^{x}}$.
\item On appelle $f'_{1}$ la fonction dérivée de $f_{1}$ sur $\R$.
      Calculer, pour tout réel $x,\: f'_{1}(x)$.\\
      En déduire les variations de la fonction $f_{1}$ sur $\R$.
\end{enumerate}

\bigskip

%% ======================================================
\textbf{Exercice 2  \hfill 5 points}

Reproduire et compléter le tableau suivant en indiquant les restes
de la division euclidienne de $7^n$ par $10$.

\begin{center}                                     % Début centrage
\begin{tabular}{|c|c|c|c|c|c|c|c|c|}               % Définition tableau
\hline
$n$: &  1 &2&3&4&5&6&7&8\\
\hline
reste&7&9& $\cdots$& $\cdots$& $\cdots$& $\cdots$& $\cdots$& $\cdots$\\
\hline
\end{tabular}
\end{center}                                        % Fin centrage

\end{document}
\end{lstlisting}
\end{minipage}
```