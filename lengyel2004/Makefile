PAPER := lengyel2004_repairs_v10

.PHONY: all check clean

all:
	mkdir -p build
	latexmk -pdf -interaction=nonstopmode -halt-on-error -outdir=build $(PAPER).tex

check:
	sha256sum -c SHA256SUMS

clean:
	latexmk -c -outdir=build $(PAPER).tex
