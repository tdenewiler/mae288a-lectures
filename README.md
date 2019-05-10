# MAE 288A Lectures

| Service | Status |
| ------- | ------ |
| Linters | [![Travis-CI](https://api.travis-ci.org/tdenewiler/mae288a-lectures.svg?branch=master)](https://travis-ci.org/tdenewiler/mae288a-lectures/branches) |

This repository contains lecture notes completed for [MAE 288A](http://maeresearch.ucsd.edu/mceneaney/mae288a/mae288a.html)
at UC San Diego during Fall quarter 2009 and taught by Prof McEneaney.

You can compile using

```
pdflatex mae288a_lectures.tex
bibtex mae288a_lectures.aux
pdflatex mae288a_lectures.tex
pdflatex mae288a_lectures.tex
```

After running those commands initially, further changes can be compiled just running a single `pdflatex` command.
