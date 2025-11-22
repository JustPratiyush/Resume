# Resume

LaTeX resume for Abhinav Kuchhal.

## Requirements

- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Required packages:
  - `tabularx`
  - `enumitem`
  - `supertabular`
  - `titlesec`
  - `multicol`
  - `multirow`
  - `biblatex`
  - `hyperref`
  - `fontawesome5`
  - `xcolor`
  - `geometry`
  - `graphicx`

## Compilation

To compile the resume to PDF:

```bash
pdflatex resume.tex
```

If using bibliography (citations.bib), compile with:

```bash
pdflatex resume.tex
biber resume
pdflatex resume.tex
pdflatex resume.tex
```

Or use your preferred LaTeX editor (Overleaf, TeXstudio, etc.) to compile.

## Files

- `resume.tex` - Main LaTeX source file
- `citations.bib` - Bibliography file (if using publications section)

## License

Personal use only.
