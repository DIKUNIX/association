.PHONY: all clean

mkfilepath := $(abspath $(lastword $(MAKEFILE_LIST)))
dirpath := $(dir $(mkfilepath))

all: vedtægter.pdf

%.pdf: %.tex
	@$(dirpath)latexrun $<

clean:
	rm -f *.pdf
