ALL: P133_PSet1.pdf P133_PSet2.pdf P133_PSet3.pdf P133_Final.pdf P133_PSet4.pdf

P133_PSet1.pdf: P133_PSet1.tex
	pdflatex P133_PSet1

P133_PSet2.pdf: P133_PSet2.tex
	pdflatex P133_PSet2

P133_PSet3.pdf: P133_PSet3.tex
	pdflatex P133_PSet3

P133_PSet4.pdf: P133_PSet4.tex
	pdflatex P133_PSet4

P133_Final.pdf: P133_Final.tex
	pdflatex P133_Final

.PHONY: clean, del

clean:
	rm *out *log *aux

del:
	rm *out *log *aux *synctex* *fls *latexmk *bbl *blg 
