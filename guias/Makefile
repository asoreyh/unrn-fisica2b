base=moderna-a-2015
version=guia-01
name=${base}-${version}
all:
	pdflatex ${name}.tex

full:
	make clean
	pdflatex ${name}.tex
	pdflatex ${name}.tex
	make clean

clean:
	rm -f *.aux *.log *.gz *.bak *.bbl *.blg *.out
