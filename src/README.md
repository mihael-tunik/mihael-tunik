## About
This is my workspace for editing CV.
You can download latest build .pdf file from repository or build it from source on your own.
 
## Requirements
pdflatex with packages like moderncv, geometry, color (full list you can find in .tex header).

## Build [Linux]
The easiest way to install TeX ecosystem on
your computer is to install everything with command
(however it requires quite a lot of memory):
```
sudo apt-get install texlive-full
```
Then you can simply build .pdf from .tex source:
```
pdflatex -output-directory=../build ./CV_en.tex
```
