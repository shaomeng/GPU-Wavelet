all: main

main: *.tex *.bib
	pdflatex main.tex
	bibtex main 
	touch main.tex
	pdflatex main.tex
	pdflatex main.tex
	cp main.pdf ~/Google\ Drive/Chromebox

short: *.tex *.bib
	pdflatex main.tex
	cp main.pdf ~/Google\ Drive/Chromebox

clean:
	if (rm -f *.log *.aux *.bbl *.blg *.toc *.dvi *.ps *.brf *.lbl *pdf) then :; fi
