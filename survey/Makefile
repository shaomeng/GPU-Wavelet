all: main

main: *.tex *.bib
	pdflatex main.tex
	bibtex main 
	touch main.tex
	pdflatex main.tex
	pdflatex main.tex

short: *.tex *.bib
	pdflatex main.tex

clean:
	if (rm -f *.log *.aux *.bbl *.blg *.toc *.dvi *.ps *.brf *.lbl *pdf) then :; fi
