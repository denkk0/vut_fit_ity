all: pdf clean

PROJ = proj1

pdf:
	latex  $(PROJ).tex 
	dvips -t a4 $(PROJ).dvi
	ps2pdf  $(PROJ).ps $(PROJ).pdf

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).out $(PROJ).ps