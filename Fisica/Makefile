formulari_T4: formulari_T4.tex formulari_t4.tex
	pdflatex formulari_t4.tex
	pdflatex formulari_T4.tex
silentformulari_T4: formulari_T4.tex formulari_t4.tex
	pdflatex -halt-on-error formulari_t4.tex > /dev/null
	pdflatex -halt-on-error formulari_T4.tex > /dev/null
clean:
	rm *.aux *.log *.out *.auxlock *.toc formulari_t4.pdf
