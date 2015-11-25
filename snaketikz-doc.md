Description
===========

snakeTi*k*Z is a simple LaTeXpackage using Ti*k*Z for drawing a path
from the end of a line to the next one. It could be used in study of
latin poetry.

Output exemple
==============

Examples with different interlines height :

0.94mm

0.95mm

0.96mm

Installation
============

-   Copy `snaketikz.sty` in your working directory, or copy source code
    in a new `snaketikz.sty` file.

-   load snake package `\usepackage{sneaktikz}`

Minimal working exemple
=======================


    \documentclass{article}\usepackage{snaketikz}

    \begin{document}% begin snake environnment with 2 arguments :% width and interline height\begin{snake}{0.9\textwidth}{4mm}% the snL command take 3 arguments:% 1 : type of line. s=snake e=end% 2 : line number% 3 : verse line\snL{s}{770}{membra natant sanie, surae fluxere, sine ullo}\snL{s}{771}{tegmine poples erat, femorum quoque musculus omnis}\snL{e}{772}{liquitur, et nigra destillant inguina tabe.}\end{snake}
    \end{document}

Snake package source
====================
