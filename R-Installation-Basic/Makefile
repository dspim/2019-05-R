RMD=$(wildcard *.Rmd)
HTML=$(RMD:.Rmd=.html)

all : $(HTML)

%.html : %.Rmd
	Rscript -e "rmarkdown::render('$<')"
