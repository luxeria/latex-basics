.PHONY: all build clean

all: build clean

handout: build_handout clean

build:
	pdflatex pres.tex
	pdflatex pres.tex
	pdflatex pres.tex

build_handout:
	pdflatex pres_handout.tex
	pdflatex pres_handout.tex
	pdflatex pres_handout.tex

clean:
	rm -f *.acn
	rm -f *.acr
	rm -f *.alg
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.dvi
	rm -f *.fdb_latexmk
	rm -f *.glg
	rm -f *.glo
	rm -f *.gls
	rm -f *.idx
	rm -f *.ilg
	rm -f *.ind
	rm -f *.ist
	rm -f *.lof
	rm -f *.log
	rm -f *.lol
	rm -f *.lot
	rm -f *.maf
	rm -f *.mtc
	rm -f *.mtc0
	rm -f *.nav
	rm -f *.nlo
	rm -f *.out
	rm -f *.pdfsync
	rm -f *.ps
	rm -f *.snm
	rm -f *.swp
	rm -f *.synctex.gz
	rm -f *.toc
	rm -f *.vrb
	rm -f *.xdy
	rm -f *.tdo
