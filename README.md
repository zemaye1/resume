# Resume Project

This repository contains a LaTeX-based resume for Nina Zhang, a Computer Science professional with experience in distributed systems, C++ development, and financial technology.

## Files

- **`output.tex`** - Main LaTeX source file for the resume
- **`output.pdf`** - Compiled PDF output of the resume
- **`output_fixed.tex`** - Alternative version with additional LaTeX packages (requires `enumitem` package)
- **`README.md`** - This file

## Requirements

To compile the resume, you need:
- A LaTeX distribution (TeX Live, MiKTeX, etc.)
- Basic LaTeX packages (article, longtable, array, booktabs, geometry, setspace, hyperref)

## Compilation

To generate the PDF from the LaTeX source:

```bash
pdflatex output.tex
```

This will create:
- `output.pdf` - The final resume
- `output.aux` - Auxiliary file for references
- `output.log` - Compilation log
- `output.out` - Hyperref output file

## Features

The resume includes:
- **Contact Information**: Email, GitHub, Website, Phone
- **Education**: Bachelor of Science in Computer Science from University of Michigan
- **Technical Skills**: Programming languages and software tools
- **Work Experience**: 
  - Intercontinental Exchange (C++ Developer)
  - Open Source Exploration
  - Bloomberg Terminal (Infrastructure Engineer)
  - Plex Systems (IoT Engineer)

## Customization

To modify the resume:
1. Edit `output.tex` in any text editor
2. Recompile using `pdflatex output.tex`
3. The PDF will automatically update with your changes

## Notes

- The main file `output.tex` uses only basic LaTeX packages and should compile without issues
- `output_fixed.tex` requires the `enumitem` package and may not compile on all systems
- The resume is formatted for A4 paper with 0.5-inch margins
- Uses a three-column layout for contact information at the top

## Contact

For questions about this resume template or LaTeX formatting, please refer to the LaTeX documentation or contact the resume owner.
