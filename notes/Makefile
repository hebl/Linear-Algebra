all:
	xelatex linalg.tex
	xelatex linalg.tex

clean:
	find . -name '*.aux' -print0 | xargs -0 rm -rf
	find . -name '*.log' -print0 | xargs -0 rm -rf
	rm -rf *.lof *.log *.lot *.out *.toc *.bbl *.blg *.thm *.idx