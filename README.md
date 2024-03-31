# Quarto Templates

This repository contains a collection of personal [Quarto](https://quarto.org) PDF templates. The templates share a similar style, using [Pandoc Markdown](https://pandoc.org/getting-started.html), [Libertine](https://libertine-fonts.org/) and [Inconsolata](https://fonts.google.com/specimen/Inconsolata) fonts, British English spelling, coloured links, double spacing, back references, and numbered sections. Future updates will include templates for CVs, syllabi, cover letters, presentations, and academic posters.

Every folder contains a PDF file displaying the template's output. Check them out to see how the documents look like. Comments and suggestions are most welcome.

To compile the PDFs, you need to install [Quarto](https://quarto.org/docs/get-started/) and [TinyTex](https://quarto.org/docs/output-formats/pdf-engine.html). If you prefer TeX Live, you can find instructions for installing it here: <https://tug.org/texlive/>.

The templates require [Python](https://www.python.org/downloads/) and [Jupyter](https://jupyter.org/install) for optimal functionality, thus installing these is advised. [R](https://www.r-project.org/) users should remove the `jupyter: python` line from the YAML header within the templates and install both the [`quarto-r`](https://quarto-dev.github.io/quarto-r/) and [`rmarkdown`](https://rmarkdown.rstudio.com/lesson-1.html) packages in addition to the [Quarto-cli](https://quarto.org/docs/get-started/).