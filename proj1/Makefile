PAPER=proj1.tex 

all:  ## Compile paper
	latex $(PAPER)
	latex $(PAPER)
	dvips -t a4 proj1.dvi
	ps2pdf proj1.ps

clean:  ## Clean output files
	rm proj1.pdf *.dvi *.dvi