all:
	pdflatex report.tex

bib:
	bibtex report
	pdflatex report.tex

push:
	git add report.tex report.pdf report.bib Makefile figures
	git commit -m "report more"
	git push

clean:
	rm -rf *.log *.aux *.vim
