all:
	bibm export bibliography.bib
	pdflatex cv
	biber cv
	pdflatex cv

clean:
	rm -f *.log
	rm -f *.bbl
	rm -f *.bcf
	rm -f *.blg
	rm -f *.aux
	rm -f *.xml
	rm -f *.out
	rm -f *.pdf
	rm bibliography.bib

