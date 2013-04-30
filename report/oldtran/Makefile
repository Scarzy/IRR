

all:
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main

clean:
	rm -rf *.aux *.pdf *.toc *.log *.bbl *.blg

.PHONY: all
