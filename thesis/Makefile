# makefile for dvips

ddpThesis.pdf: ddpThesis.tex
	pdflatex ddpThesis
	bibtex ddpThesis
	makeglossaries ddpThesis
	pdflatex ddpThesis
	pdflatex ddpThesis
ddpThesisSoft.pdf: ddpThesisSoft.tex
	pdflatex ddpThesisSoft
	bibtex ddpThesisSoft
	makeglossaries ddpThesisSoft
	pdflatex ddpThesisSoft
	pdflatex ddpThesisSoft

mac: ddpThesis.pdf ddpThesisSoft.pdf
	open -a preview ddpThesis.pdf
ubuntu: ddpThesis.pdf ddpThesisSoft.pdf
	evince ddpThesis.pdf 
clean:
	rm -f ddpThesis.pdf ddpThesisSoft.pdf
