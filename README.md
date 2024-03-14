# Final degree thesis $\LaTeX$ template

Non-official template for a $\LaTeX$ based final degree thesis at the [Faculty of Sciences, Technology and Engineering](https://mon.uvic.cat/fcte) of the [UVic-UCC](https://www.uvic.cat).

## Files

The template contains a collection of files that can be of use to organize the material, but they also show the way to split the document into several subfiles as needed. Check each file content to understand its use.
* `report.tex`: main document containing the text and the call to other needed files
* `includes.tex`: add here all packages that are needed to compile your $\LaTeX$ project.
* `notations.tex`: a handy file to include your specific definitions for your keywords through the writing of the report.
* `refenereces.bib`: all your references go in this library, that you can create by explorting from your favorite reference manager (`Zotero`, `Mendeley`, etc)  
* `figures/` folder: a place to leave your figures in `*.jpg`, `*.png`, `*.eps`, `*.pdf` or any other image format accepted by the latex compiler.

Recall this is just an initial simple template. Feel free to adapt it to your needs, as long as they are in accordance with the final expceted formal format in your degree thesis.

## Compiling a PDF file

To compile, [run](https://ctan.org/pkg/latexmk):
```
latexmk report.tex
```

If any modification to the way you complie needs to be done, it is advisable to edit the `latexmkrc` file provided in this repo.

## Bugs, corrections, improvements, questions...

Feel free to generate a trunk of this repo and to submit [issues](https://github.com/Biocomputing-Teaching/Template_TFG/issues) of [pull requests](https://github.com/Biocomputing-Teaching/Template_TFG/pulls) to help improving the template. 

To learn how to edit $\LaTeX$ files there are a myriad of resources in the web. Simply google you specific question and you will get the answer. Additionally, AI tools like ChatGPT can help a lot in building $\LaTeX$ code if you get stuck with some commands or errors reported by the compiler.

## Disclaimer

This template has been created and will be maintained as a help to your writing, but it assumes you will do the proper installation of your $\LaTeX$ environment and editing tools. In addition, the `non-official` character of the template states precisely this, so its use needs to be validated by your degree thesis supervisor.

