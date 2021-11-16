chapters = intro.tex logic.tex numbers.tex

manual.pdf : manual.tex $(chapters)
	latexmk -pdf manual

clean:
	rm *.pdf