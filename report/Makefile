all: report

report: report.out

report.out: report.tex
	pdflatex report.tex

.PHONY: clean
clean:
	rm -rf *.aux *.out *.pdf *.log *.toc
