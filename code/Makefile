.PHONY: all build clean

all: build clean

prg: build_prg run

build:
	pdflatex code.tex
	pdflatex code.tex
	pdflatex code.tex

build_prg:
	gcc -Wall -Wparentheses main.c -o main
run:
	./main

clean:
	rm -f *.aux
	rm -f *.log
