# Durham University Thesis Class \& Template

Unofficial thesis template. This is based on the original class written by Chas Nelson available [here](https://github.com/ChasNelson1990/durham-university-thesis-class). It contains a few changes to make it easier to compile in a modern LaTeX environment; as well as a few style changes.

## Compiling the document

```
latexmk -pdf -shell-escape thesis
```

The flag `-shell-escape` is necessary to run a few commands (EPS to PDF conversion for figures and glossary generation).

## Where to start

The main LaTeX document file is called `thesis.tex`.

## License

This code is licensed to you under GPLv3.

