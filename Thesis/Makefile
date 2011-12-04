NAME=thesis

all: *.tex *.bib
	pdflatex $(NAME) 
	bibtex $(NAME)
	pdflatex $(NAME)
	pdflatex $(NAME)
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
	rm -f *.lo*
	rm -f chapters/*.aux chapters/*.toc chapters/*. chapters/*.bbl chapters/*.blg  chapters/*.log chapters/*.nav chapters/*.out chapters/*.snm chapters/*.vrb chapters/*.lo*

check:
	aspell -l en -c -t *.tex

clean:
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
	rm -f *.lo*
	rm -f chapters/*.aux chapters/*.toc chapters/*. chapters/*.bbl chapters/*.blg  chapters/*.log chapters/*.nav chapters/*.out chapters/*.snm chapters/*.vrb chapters/*.lo*

