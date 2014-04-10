all:
	latex documento.tex
	latex documento.tex
	bibtex documento
	latex documento.tex
	latex documento.tex
	dvips -o documento.ps documento.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true documento.ps documento.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl
