# An RMarkdown report boilerplate

This project is meant to serve as a "quick start" for short [RMarkdown](https://rmarkdown.rstudio.com/) PDF reports, such as those done for coursework.
It's aimed at those of us that want to write a report without much fuss but still be able to have advanced features like citations and code listings.

## Contents

* `Report.Rmd`: The main report file.
* `bibliography.bibtex`: What the name says, a BibTex file to add your references.
* `setup.sty`: A setup file with additional LaTeX setup. It's included in the generated TeX file's header automatically.

## How to

1. Clone this repo.
2. Edit the files.
3. Compile your report using RStudio.

## FAQ

### The bibliography style is commented and there's no CSL. Why is this?

There's many good CSL files over at <https://github.com/citation-style-language>, but they are licensed with a CreativeCommons ShareAlike license.
I don't really want to license this project under that, since it's meant to be used as a starter for various projects, so you'll have to download it yourself.
