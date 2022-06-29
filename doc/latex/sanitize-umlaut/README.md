# The LaTeX package sanitize-umlaut - version 1.2.0 (2022/06/29)


> Copyright (c) 2016-2022 by Prof. Dr. Dr. Thomas F. Sturm <thomas dot sturm at unibw dot de>

> This work may be distributed and/or modified under the
> conditions of the LaTeX Project Public License, either version 1.3
> of this license or (at your option) any later version.
> The latest version of this license is in
>   http://www.latex-project.org/lppl.txt
> and version 1.3 or later is part of all distributions of LaTeX
> version 2005/12/01 or later.

> This work has the LPPL maintenance status `author-maintained`.

> This work consists of all files listed in README.md


`sanitize-umlaut` sanitizes umlauts to be used directly in index entries for
MakeIndex and friends with pdflatex. This means, that inside `\index` an umlaut
can be used as `"U` or directly. In both cases, the letter is written as `"U` into
the raw index file for correct processing with MakeIndex and pdflatex.


## Contents of the package

-  `README.md`                 this file
-  `CHANGES.md`                log of changes (history)
-  `sanitize-umlaut.sty`       LaTeX package file (style file)
-  `sanitize-umlaut.pdf`       Documentation
-  `sanitize-umlaut.tex`       Source code of the documentation (main file)
-  `*.doc.*`                   Source code of the documentation (include files)
-  `german.ist`                MakeIndex style


## Installation

Copy the contents of the `sanitize-umlaut.tds.zip` from CTAN to your local TeX file tree.

Alternatively, put the files to their respective locations within the TeX installation:

-  `sanitize-umlaut.sty`       ->  /tex/latex/sanitize-umlaut
-  all other files             ->  /doc/latex/sanitize-umlaut
