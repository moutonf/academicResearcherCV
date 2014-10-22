# What is this

This is a repository that contains the up-to-date academic research CV template.

This template integrates the following packages:

* biblatex (with modifications)
* moderncv
* moderntimeline
* pdfpages
* xpatch

# How to build

pdflatex main.tex
biber main.bcf
pdflatex main.tex
pdflatex main.tex

# HTML Version

The pdf can be compiled into an HTML version, using [pdf2htmlex](https://github.com/coolwanglu/pdf2htmlEX). Once you have 'pdf2htmlex' installed you can convert the pdf to html using the following command:

pdf2htmlex main.pdf
