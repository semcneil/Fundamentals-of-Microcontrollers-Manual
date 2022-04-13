chapters = intro/intro.tex logic/logic.tex numbers/numbers.tex information/information.tex control/control.tex

manual.pdf : manual.tex $(chapters)
	latexmk -pdf manual
	mv manual.pdf ../docs/Fundamentals-of-Microcontrollers.pdf

clean:
	rm *.pdf
	find .. -type f -name '*.aux' -delete
	rm ../docs/*.pdf
