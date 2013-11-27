.PHONY: all

all: COMBINE-symposium-2013-program.pdf

%.pdf: %.tex
	pdflatex $<

clean:
	\rm -rf ./*.aux ./*.out ./*.nav ./*.snm ./*.toc ./*.fls ./*.log
