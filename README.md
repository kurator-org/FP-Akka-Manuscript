# FP-Akka-Manuscript
Draft and resources for manuscript about FP-Akka

Known to compile with pdflatex with texlive installation

Known to NOT compile with pdftex with texlive installation


1. Install pdflatex:
Install a latex package that contains pdflatex.  One such latex package is TexLive. To install TexLive on Ubuntu or Debian you can follow http://xmodulo.com/how-to-install-latex-on-ubuntu-or-debian.html. For Windows see https://www.tug.org/texlive/acquire-netinstall.html.  TeXLive  contains bibibtex, the bibliography application.

2. run pdflatex: 
  a. In the directory you pulled this git project, do `pdflatex FP-Akka.tex` If pdflatex completes, do `bibtex FP-Akka.aux`
If pdflatex does not complete, you have fatal LaTex errors in one of the TeX files.
  b. If bibtex completes, repeat `pdflatex FP-Akka.tex` TWICE

```bash
pdflatex FP-Akka.tex
bibtex FP-Akka.aux
pdflatex FP-Akka.tex
pdflatex FP-Akka.tex
```

3. If you are unfamiliar with TeX, do not worry about non-fatal errors from pdflatex. This project will simply be for manuscript submission, not as a final published form.
