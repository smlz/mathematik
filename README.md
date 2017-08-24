# Arbeitsblätter Mathematik

## Format

The files are written in Markdown with math equations written in LaTeX.

## Convert to HTML

Use [Atom](https://atom.io) with the [Markdown Preview Enhanced package](http://atom-packages.directory/package/markdown-preview-enhanced/).

*Ctrl-Shift-m* for preview. Right-click in the preview pane and *HTML -> HTML (cdn hosted)* to generate the HTML.

## N-up PDFs

Use print function in browser to create a PDF file. Then the following `pdfjam` commands.

Portrait 2-up
```
pdfjam --suffix 4up --nup 2x1 --landscape in.pdf '1,1,2,2' --outfile out.pdf
```

Landscape 4-up
```
pdfjam --suffix 4up --nup 2x2 --frame true --landscape --scale 0.9 --delta "2cm 2cm" in.pdf '1,1,1,1,2,2,2,2' --outfile out.pdf
```

## License

Everything in this repository is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
