all: fig-sas.png fig-sas.pdf fig-right.png fig-right.pdf fig-345.png fig-345.pdf

fig-right.pdf : fig-right.tex
	rm -f fig-right.pdf
	pdflatex fig-right.tex

fig-right.png : fig-right.pdf 
	convert -density 100 -alpha Remove fig-right.pdf fig-right.png

view-right: fig-right.png
	start fig-right.png

fig-sas.pdf : fig-sas.tex
	rm -f fig-sas.pdf
	pdflatex fig-sas.tex

fig-sas.png : fig-sas.pdf 
	convert -density 100 -alpha Remove fig-sas.pdf fig-sas.png

view-sas: fig-sas.png
	start fig-sas.png

fig-345.pdf : fig-345.tex
	rm -f fig-345.pdf
	pdflatex fig-345.tex

fig-345.png : fig-345.pdf 
	convert -density 100 -alpha Remove fig-345.pdf fig-345.png

view-345: fig-345.png
	start fig-345.png

view: view-345
