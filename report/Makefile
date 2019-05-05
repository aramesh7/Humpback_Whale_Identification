final-report.pdf: final-report.tex
	pdflatex final-report
	bibtex final-report
	pdflatex final-report
	pdflatex final-report

clean:
	rm -f final-report.pdf *.aux *.blg *.bbl *.log *.tmp *.xref *.idv *.4og *.4ct *.lg *.4tc *~ *.out

osx: final-report.pdf
	open -a preview.app final-report.pdf

open: osx
