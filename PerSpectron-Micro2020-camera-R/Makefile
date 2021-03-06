TEX		=	latexmk
TEXFLAGS	=	-f -pdf

all: main 	

main: abstract.tex  
		$(TEX) $(TEXFLAGS) main.tex

clean:
		rm -rf *.log *.blg *.aux *.dvi *.fls *.fdb* *.out
