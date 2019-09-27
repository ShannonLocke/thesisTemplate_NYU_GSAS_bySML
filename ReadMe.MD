## Thesis Template Instructions

The basic layout of this template is the content of your thesis is added to the separate latex files (.tex) constituting one section (e.g., abstract, project 1, etc.).
You can find the tex files for each section in the _Contents_ folder. This is where the bulk of your time editing.
It is also handy to place figures in their relevant section folders to keep the files orderly.

The main tex file, _compileThesis.tex_, will then put all the sections together in the right order. 
If you want to see the pdf of your thesis, you will need to compile this tex file.
There are a few things you will need to tweak in this main file, such as the title page and copyright, but should otherwise be right to go.
If you have a long title, you may want to insert line breaks (\\\\) and change the spacing at the indicated point.
You may also want to delete elements that you don't want to use (e.g., dedication, list of tables, etc.).
If you are having trouble getting your table of contents or list of figures/tables to load, run the compiler a couple of times.
If your references aren't appearing, make sure your compiling your bibliography (_refs.bib_) and then compile _compileThesis.tex_ again.
Each reference must be added to this bib file and then called appropriately in the text. 
There is an example in this template, however, there is plenty online to help you get this right.

If you are requested to hand in an abstract page, see the separate _compileSeparateAbstract.tex_ document. 
It will read your abstract from the contents folder, so you won't have to worry about that.
Just make sure to edit the details about your name, thesis title, and advisor's name in _compileSeparateAbstract.tex_.

Happy thesis writing, you've got this!

Shannon M. Locke   
09/28/19
