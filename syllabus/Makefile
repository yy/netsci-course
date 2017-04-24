MAIN := syllabus_summer

all: $(MAIN).pdf

upload: $(MAIN).pdf
	scp syllabus_summer.pdf yongyeol.com:~/yongyeol.com/teaching/netsci_syllabus_2017_summer.pdf

$(MAIN).pdf: $(MAIN).tex
	latexmk -pdf $<

monitor: $(MAIN).tex
	latexmk -pvc -pdf $<
