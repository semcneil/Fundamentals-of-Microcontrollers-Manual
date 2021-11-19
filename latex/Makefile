chapters = intro.tex logic.tex numbers.tex

manual.pdf : manual.tex $(chapters)
	latexmk -pdf manual
	mv manual.pdf ../docs/Fundamentals-of-Microcontrollers.pdf

clean:
	rm *.pdf