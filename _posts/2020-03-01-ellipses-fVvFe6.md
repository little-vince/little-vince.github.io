---
title: fVvFe6
permalink: fVvFe6
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Dans le préambule
% -----------------
\usepackage{xsim}
\usepackage{tasks,amssymb}
\DeclareExerciseType{exo}{
	exercise-env = exo ,
	solution-env = solexo ,
	exercise-name = Exercice ,
	solution-name = Solution ,
	exercise-template = runin ,
	solution-template = runin }
\DeclareExerciseType{probleme}{
	exercise-env = pblm ,
	solution-env = solpblm ,
	exercise-name = Problème ,
	solution-name = Solution ,
	exercise-template = runin ,
	solution-template = runin }
\xsimsetup{pblm/the-counter = \Alph{pblm}}
% -----------------

\begin{exo}
  Les \blank[width=2cm]{sanglots}
  longs des violons de l'automne.
\end{exo}
\begin{solexo}
  Les \blank[width=2cm]{sanglots}
  longs des violons de l'automne.
\end{solexo}

\begin{pblm}
  Factoriser $B=7x+14$
\end{pblm}
\begin{solpblm}
  $B=7(x+2)
\end{solpblm}

\begin{exo}
  Le Chlore est un halogène
  \begin{tasks}[style=multiplechoice](2)
  \task Vrai \task Faux
  \end{tasks}
\end{exo}
\begin{solexo}
  \begin{tasks}[style=multiplechoice](2)
  \task[$\blacksquare$] Vrai \task Faux
  \end{tasks}
\end{solexo}
```