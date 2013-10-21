ubcthesis
=========

LaTeX template satisfying all the requirement of the UBC faculty of graduate studies

Hello,
I have set up this template as I didn't like the ones provided on FoGS website (https://www.grad.ubc.ca/current-students/dissertation-thesis-preparation/style-guides-computer-tools). Moreover, I wanted to have something that complies with FoGS guidelines, yet is as simple as possible. Therefore I use the class ''report'' of LaTeX and the package tocloft. You won't need to install any special package.

This template is composed of 4 LaTeX files :

1) thesis.tex : this is the "base" file (the file you will compile) with the different packages you need.If you want to add chapters, preface and so on just create the corresponding file and include it in thesis.tex with the command : \input{myfile} where ''myfile'' is the name of the file (as it is done for chapter1 for example).
The packages : amsfonts,amsmath,amssymb,amsthm are there to be able to typeset mathematical symbols (and you will probably need them).
The package : hyperref is only useful if you want to make hypertext links with your document. 

2) title.tex : for the title.

3) abstract.tex : for the abstract.

4) chapter1.tex : for the first chapter.

Finally you will also need to create the file "biblio.bib" with your bibliography and compile the whole with BibTeX. (Note that you can also erase the last part and do the bibliography by hand, but I don't recommend that since BibTeX is easy (just use http://www.ams.org/mathscinet to find the references) and gives a really nice result).
All the thesis guidelines can be found under : https://www.grad.ubc.ca/current-students/dissertation-thesis-preparation
