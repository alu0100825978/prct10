all:
	latex doc_latex.tex
	latex doc_latex.tex
	bibtex doc_latex
	latex doc_latex.tex
	latex doc_latex.tex
	dvips -o doc_latex.ps doc_latex.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true doc_latex.ps doc_latex.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl
