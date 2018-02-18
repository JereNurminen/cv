# Rendering with Pandoc:
## To PDF (You need to have LaTeX installed):
`pandoc README.md -V geometry:margin=1in -V urlcolor=cyan -f markdown -o cv.pdf`
## To DOCX:
`pandoc README.md -f markdown -t docx -o cv.docx`