PAPER=proj3

all:
	latex $(PAPER).tex
	latex $(PAPER).tex
	dvips -sPAPERSIZE=a4 $(PAPER).dvi
	ps2pdf $(PAPER).ps

over: all
	pdftk vzor.pdf multibackground $(PAPER).pdf output overlay.pdf

pack: 
	zip -r xsvaty01.zip *.eps Makefile proj3.tex

clean:  
	rm $(PAPER).pdf *.dvi *.log *.gz *.aux *.out *.fls *.fdb*