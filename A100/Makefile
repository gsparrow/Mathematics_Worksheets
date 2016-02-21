SRCC=A100_Binder.tex
EXEC=$(SRCC:.tex=.pdf)

all: compile view

compile:
		 pdflatex $(SRCC)

view:
		 evince $(EXEC) &

clean:
		rm -f *.aux *.log *.pdf
