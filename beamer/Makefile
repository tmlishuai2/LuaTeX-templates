MAIN=main
ARTICLE=article
BEAMER=beamer

main : ${MAIN}.tex
	@latexmk -lualatex ${MAIN}.tex

.PHONY : clean cleanall

cleanall : 
	@latexmk -C

clean : 
	@latexmk -c


