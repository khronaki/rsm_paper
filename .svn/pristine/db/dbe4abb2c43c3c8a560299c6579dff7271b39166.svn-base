CC=pdflatex -interaction=nonstopmode

makepaper:
	$(CC) paper.tex
	$(CC) paper.tex
	bibtex paper 
	$(CC) paper.tex
	$(CC) paper.tex
	
clean:
	rm *.aux *.log *.blg *.bbl

clear:
	rm *.aux *.log *.blg *.bbl *.pdf
