all: pdf clean

PROJ = proj3

pdf:
	latex  $(PROJ).tex 
	latex  $(PROJ).tex 
	dvips $(PROJ).dvi
	ps2pdf  $(PROJ).ps $(PROJ).pdf

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).out $(PROJ).ps