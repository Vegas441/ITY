PAPER=proj2

all:
	latex $(PAPER).tex
	latex $(PAPER).tex
	dvips -t a4 $(PAPER).dvi
	ps2pdf $(PAPER).ps

over: all
	pdftk vzor.pdf multibackground $(PAPER).pdf output overlay.pdf

clean:  
	rm $(PAPER).pdf *.dvi *.log *.gz *.aux *.out *.fls *.fdb*