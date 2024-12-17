FILE = cv

all: 
	rm -f $(FILE).aux $(FILE).bbl $(FILE).blg $(FILE).log $(FILE).dvi $(FILE).ps $(FILE).out $(FILE).thm
	pdflatex $(FILE)
	pdflatex $(FILE)
	cp cv.pdf ..

clean:
	rm -f $(FILE).aux $(FILE).bbl $(FILE).blg $(FILE).log $(FILE).dvi $(FILE).ps $(FILE).out

view: all
	open -a Preview $(FILE).pdf &