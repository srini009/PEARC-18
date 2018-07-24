all: journal_paper.tex
	pdflatex journal_paper.tex; bibtex journal_paper; pdflatex journal_paper.tex; pdflatex journal_paper.tex;

clean: *.pdf
	rm -f *.pdf *.bbl *.log *.aux *.blg *.out *.cut *.spl
