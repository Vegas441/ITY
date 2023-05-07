PAPER=proj5

all:
	pdflatex $(PAPER).tex
	
over: all
	pdftk vzor.pdf multibackground $(PAPER).pdf output overlay.pdf

pack: 
	zip -r xsvaty01.zip *.eps Makefile $(PAPER).tex *.sty img/

clean:  
	rm $(PAPER).pdf *.dvi *.log *.gz *.aux *.out *.fls *.fdb*