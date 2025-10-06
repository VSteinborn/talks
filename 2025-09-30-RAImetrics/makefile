REQUIRED_FILES = preamble_beamer.tex	\
	2025-09-30-RAImetrics.tex	\
	2025-09-30-RAImetrics.bib	\

2025-09-30-RAImetrics.pdf:$(REQUIRED_FILES)
	latexmk -pdf 2025-09-30-RAImetrics.tex && latexmk -c 2025-09-30-RAImetrics.tex

clean:
	latexmk -C
