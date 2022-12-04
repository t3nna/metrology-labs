SOURCES=\
	main.tex\
	theory.tex\
	WUST-ECE-Metrology-Report.sty\
	images


report.pdf: $(SOURCES)
	mkdir -p build
	latexmk\
		-emulate-aux-dir\
		-aux-directory=build\
		-pdf main.tex


.PHONY: clean
clean:
	latexmk -c
	rm -r build
