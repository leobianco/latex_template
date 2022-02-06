# Example LaTeX Project

Here you will find the basic frame that can be used for any LaTeX project.

Run `cp ExampleProject path_new_project` and then open `main.tex`, press `ctrl+j` (if in `vim`) to edit the title and author fields, choose whether you want an abstract and ToC or not. To get citations working, remember you must run `pdflatex main.tex` once, then `bibtex main`, then `pdflatex main.tex` twice.

Edit (and compile) sections individually in the folder `/sections`. Edit (and compile) tikz diagrams individually in the folder `/images/tikz`. If you are going to compile these individually, I recommend you put them in a separate folder of same name, as pdflatex creates numerous cache files I did not want to mess around with.

The file `main.pdf` shows the initial state of your project.
