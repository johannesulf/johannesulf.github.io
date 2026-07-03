all:
	bibm export bibliography.bib
	pdflatex cv
	biber cv
	pdflatex cv
	pdflatex cv
	rm -f *.log
	rm -f *.bbl
	rm -f *.bcf
	rm -f *.blg
	rm -f *.aux
	rm -f *.xml
	rm -f *.out

clean:
	rm -f *.pdf
	rm bibliography.bib

