N=slides
$N.pdf: $N.tex 
	pdflatex $N.tex
	pdflatex $N.tex
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb
check:
	aspell -l en -c -t *.tex

clean:
	rm -f *.aux *.toc *. *.bbl *.blg  *.log *.nav *.out *.snm *.vrb

