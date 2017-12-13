MAIN := syllabus

all: $(MAIN).pdf

upload: $(MAIN).pdf
	scp syllabus.pdf yongyeol.com:~/yongyeol.com/teaching/netsci_syllabus_2018S.pdf

$(MAIN).pdf: $(MAIN).tex
	latexmk -pdf $<

monitor: $(MAIN).tex
	latexmk -pvc -pdf $<
