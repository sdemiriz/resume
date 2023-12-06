# Sedat Demiriz Resume

## Terms of Use

I own all rights to the content of the documents in this repository. Using as a reference is allowed, copy and use ny anyone other than myself not allowed.

## Description

Made a decision to migrate my resume from Google Docs to something more reproductible and I wanted to try out LaTeX to see how beneficial it would be for me in the future. So I connected the two and produced this resume document using LaTeX and a few common packages.

## How to compile

Have `pdflatex` and `bibtex` installed on your system. Take a a look at the `\usepackage` commands in `resume.tex` to see what packages are required for compilation.

I use the `texlive.combined.scheme-full` environment from `nixpkgs` and everything I used for generating the PDF document worked out of the box.

To produce the PDF document, navigate to directory with the contents of this repository in it. 

Next, run:

```
pdflatex resume
bibtex resume
pdflatex resume
pdflatex resume
```

This should result in a document called `resume.pdf` to be produced.
