MAIN := syllabus

all: $(MAIN).pdf

upload: $(MAIN).pdf
	scp syllabus.pdf yyahn@yongyeol.com:~/yongyeol.com/teaching/2018SP_netsci_syllabus.pdf

$(MAIN).pdf: $(MAIN).tex
	latexmk -pdf $<

monitor: $(MAIN).tex
	latexmk -pvc -pdf $<
