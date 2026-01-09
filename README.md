# Glossalatex

Files needed for the Glossa style in Latex:

1. glossa.cls: the document class file. Put this in a location where latex can find it (eg ~/Library/texmf/tex/latex)
2. glossa-template.tex: an example of an article in the Glossa style
3. sample.bib: the sample bibliography file used for the example article in 2
4. glossa.bst: the bibliography style. Put this in a location where latex can find it (eg ~/Library/texmf/bibtex)
5. biblatex-gl.bbx 
6. gl-authoryear-comp.cbx
7. cgloss.sty (needed for glosses in the Glossa document class; not standardly included in the tex-distribution; put this in a location where latex can find it, eg ~/Library/texmf/tex/latex)

Files 5 and 6 are needed for use with biblatex; put these in a location where latex can find them (eg ~/Library/texmf/tex/latex/biblatex); ignore if you use bibtex.

The Charis SIL font has recently changed its name to Charis. As of Jan 2026, the template incorporates this change. For the template to work with this font, Charis needs to be installed on your system (download it from [https://software.sil.org/charis/](https://software.sil.org/charis/)).