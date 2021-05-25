---
title: 2XcvRH
permalink: 2XcvRH
layout: post
date: 2019-06-24 19:04:10
category: ellipses
---

```latex
% Présentation générale et mise en page :
\documentclass[a4paper,11pt]{article}
% Marges personnalisees (cf 3.7) :
\usepackage[left=1cm,right=1cm,top=2.2cm,bottom=1.9cm]{ geometry}

% Chargement automatique des packages selon le type de compilation :
\usepackage{iftex}
\ifXeTeX % Commpilation XeLaTeX (cf 2.6)
\usepackage{fontspec}
\else % Compilation (Pdf) LaTeX (cf 2.6)
\usepackage[latin1]{inputenc} % Latin1, utf8 ou mactex (cf 2.3)
\usepackage[T1]{fontenc}
\fi

\usepackage{lmodern}           % Police Latin Modern
\usepackage{graphicx}          % Pour insérer des images (cf 3.11)
\usepackage{amsmath ,amsfonts} % Spécial math (cf 7.15)
\usepackage{amssymb ,amsthm}
\usepackage[french]{babel}     % Typo. française (cf 3.3)
\setlength {\parindent}{0mm}   % Pas de retrait de paragraphe

% En - têtes et pieds de pages personnalisés (cf 3.15)
\usepackage{fancyhdr ,lastpage}
\pagestyle{fancy}
\fancyhead[L]{Titre du document}
\fancyhead[R]{\today}
\setlength\headheight{14pt}
\renewcommand\headrulewidth{2pt}
\fancyfoot[C]{Page \thepage /\ pageref{LastPage }}

\begin{document}
Le corps du document
\end{document}
```
