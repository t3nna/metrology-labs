SOURCES=\
	main.tex\
	theory.tex\
	experiment.tex\
	conclusion.tex\
	WUST-ECE-Metrology-Report.sty\
	images


report.pdf: $(SOURCES)
	mkdir -p build
	latexmk\
		-interaction=nonstopmode\
		-emulate-aux-dir\
		-aux-directory=build\
		-pdf main.tex


.PHONY: clean
clean:
	latexmk -c
	rm -r build
