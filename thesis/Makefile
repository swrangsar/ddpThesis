# makefile for dvips

ddpThesis.pdf: ddpThesis.tex
	pdflatex ddpThesis.tex
	bibtex ddpThesis
	makeglossaries ddpThesis
	pdflatex ddpThesis.tex
	pdflatex ddpThesis.tex
Mac: ddpThesis.pdf
	open -a preview ddpThesis.pdf
clean:
	rm ddpThesis.pdf