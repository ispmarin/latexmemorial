# Memorial in Latex

A template for an academic memorial. Master file is memorial.tex. 

Uses the format:
```latex
\documentclass[11pt,a4paper,DIV=calc, BCOR=12mm, toc=flat]{scrbook} % KOMA-Script book

\usepackage{fontenc}
\usepackage{polyglossia}
\usepackage{lipsum}
\usepackage{hyperref}
\usepackage{amsfonts}
\usepackage{amssymb}
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage{listing}
\usepackage{}
%\usepackage{microtype} %necessary?
\setkomafont{disposition}{\bfseries} %change the fonts in chapter from ss to s
\setdefaultlanguage{brazil}
\hypersetup{linktocpage=true,
bookmarksnumbered=true,
pageanchor=true,
hypertexnames=false,
naturalnames=true,
plainpages=false}

\setmainfont{TeX Gyre Pagella}
\newfontfamily\arial{Arial}
```
Please, if you use these files separatedely or all of them, just link to this repository ou give proper authorship.

