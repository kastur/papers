PAPER=override

all:
	pdflatex $(PAPER) && \
	bibtex $(PAPER) && \
	pdflatex $(PAPER) && \
	pdflatex $(PAPER) && \
	rm -rf *.aux *.log *.bbl *.blg

clean:
	rm -rf *.aux *.log *.bbl *.blg
