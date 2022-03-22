# Notes template

Made to be simple and very straightforward, it consists of one main file and a content file (even though more content files can be added as needed by the user).

The structure of the repository is very simple:

- **notes.tex** is the core of the document where all the configurations and content files are included.
- **content.tex** is a sample file to demonstrate how to include other content files inside the one mentioned above. It also is an example on how these files should look like when used.
- The **images** folder is intended to be used to store all the images used in the document, though it can be configured to the users liking.
- The **examples** folder contains examples, as expected.

## Compilation

As all other `.tex`, `.bib` files are either included or inputted into `notes.tex`, to compile this template run:

```
pdflatex notes.tex
```

Alternatively, `lualatex` or `xelatex` can be used to compile the source files.

IMPORTANT: Rerunning the aforementioned command will be necessary for the output to be correct.

## License

MIT License: https://mit-license.org/ or see the 
[`LICENSE`](https://github.com/rnsavinelli/notes-template/blob/master/LICENSE) file.
