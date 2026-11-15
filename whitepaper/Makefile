DOC := camshaft-whitepaper

.PHONY: all clean distclean

all: $(DOC).pdf

# The bibliography is shared with the design report.
$(DOC).pdf: $(DOC).tex ../design/references.bib
	latexmk -pdf -interaction=nonstopmode -halt-on-error $(DOC).tex

clean:
	latexmk -c $(DOC).tex
	rm -f $(DOC).bbl $(DOC).run.xml

distclean: clean
	rm -f $(DOC).pdf
