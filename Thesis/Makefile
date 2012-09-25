NAME=thesis

all: *.tex *.bib
	xelatex $(NAME) 
	bibtex $(NAME)
	xelatex $(NAME)
	xelatex $(NAME)
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
	rm -f *.lo*
	rm -f chapters/*.aux chapters/*.toc chapters/*. chapters/*.bbl chapters/*.blg  chapters/*.log
	rm -f chapters/*.nav chapters/*.out chapters/*.snm chapters/*.vrb chapters/*.lo*
	rm -f minichapters/*.aux minichapters/*.toc minichapters/*. minichapters/*.bbl minichapters/*.blg  minichapters/*.log
	rm -f minichapters/*.nav minichapters/*.out minichapters/*.snm minichapters/*.vrb minichapters/*.lo*
	rm -f appendix/*.aux appendix/*.toc appendix/*. appendix/*.bbl appendix/*.blg  appendix/*.log
	rm -f appendix/*.nav appendix/*.out appendix/*.snm appendix/*.vrb appendix/*.lo*
	rm -f thesis.acn thesis.ist thesis.glo

check:
	aspell -l en -c -t *.tex

clean:
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
	rm -f *.lo*
	rm -f chapters/*.aux chapters/*.toc chapters/*. chapters/*.bbl chapters/*.blg  chapters/*.log
	rm -f chapters/*.nav chapters/*.out chapters/*.snm chapters/*.vrb chapters/*.lo*
	rm -f minichapters/*.aux minichapters/*.toc minichapters/*. minichapters/*.bbl minichapters/*.blg  minichapters/*.log
	rm -f minichapters/*.nav minichapters/*.out minichapters/*.snm minichapters/*.vrb minichapters/*.lo*
	rm -f appendix/*.aux appendix/*.toc appendix/*. appendix/*.bbl appendix/*.blg  appendix/*.log
	rm -f appendix/*.nav appendix/*.out appendix/*.snm appendix/*.vrb appendix/*.lo*
	rm -f thesis.acn thesis.ist thesis.glo

edit:
	mate regedor.bib *.tex chapters/ tables/ minichapters/ appendix/
open:
	open $(NAME).pdf

