DOC := camshaft-design

.PHONY: all clean distclean

all: $(DOC).pdf

$(DOC).pdf: $(DOC).tex references.bib
	latexmk -pdf -interaction=nonstopmode -halt-on-error $(DOC).tex

clean:
	latexmk -c $(DOC).tex
	rm -f $(DOC).bbl $(DOC).run.xml

distclean: clean
	rm -f $(DOC).pdf
