SOURCES=\
	main.tex\
	theory.tex\
	experiment.tex\
	conclusion.tex\
	WUST-ECE-Metrology-Report.sty\
	images


.ONESHELL:
report.pdf: $(SOURCES)
	latexmk\
		-interaction=nonstopmode\
		-xelatex\
		main.tex

.PHONY: clean
clean:
	latexmk -c
	rm -r build
