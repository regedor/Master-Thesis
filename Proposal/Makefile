NAME=regedor_thesis_proposal

all: *.tex *.bib
	pdflatex $(NAME) 
	bibtex $(NAME)
	pdflatex $(NAME)
	pdflatex $(NAME)
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
	rm -f *.lo*

check:
	aspell -l en -c -t *.tex

clean:
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
	rm -f *.lo*
