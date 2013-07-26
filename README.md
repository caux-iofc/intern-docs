This repository contains non-sensitive interns documentation for [Caux](http://caux.ch).

## Compiling

Flowcharts can be compiled using graphviz, for example:

    dot -T pdf wifi-flowchart.gv > compiled/wifi-flowchart.pdf

I recommend compiling documents using xelatex, it will give you a PDF:

    xelatex -output-directory compiled getting-mac-addresses.tex
