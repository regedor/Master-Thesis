NAME=CORTA2011_regedor

all: *.tex *.bib
	pdflatex $(NAME) 
	bibtex $(NAME)
	pdflatex $(NAME)
	pdflatex $(NAME)
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
check:
	aspell -l en -c -t *.tex

clean:
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
