# Cellular Programs - Course Assignments

This repository contains assignments and related materials for the Cellular Programs course (SoSe25).

## Repository Structure

```
cellular_programs/
├── assignment01/          # Assignment 1 materials
├── assignment02/          # Assignment 2 materials  
├── assignment03/          # Assignment 3 materials
├── assignment04/          # Assignment 4 materials
├── assignment06/          # Assignment 6 materials
└── Papers/               # Reference papers and literature
    ├── 1-12/            # Numbered paper collection
    └── New_Papers/      # Additional recent papers (A-N)
```

## Assignment Structure

Each assignment directory typically contains:
- **Assignment PDF**: The original assignment instructions
- **Solution PDF**: Completed assignment submission
- **LaTeX Files**: Source files for the assignment
  - `main.tex` - Main document
  - `preamble.tex` - Document setup and packages
  - `format.tex` - Formatting definitions
  - `commands.tex` - Custom commands
  - `references.bib` - Bibliography entries

## LaTeX Compilation

To compile the LaTeX documents:

```bash
cd assignmentXX/
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or use `latexmk` for automatic compilation:
```bash
latexmk -pdf main.tex
```

## Reference Papers

The `Papers/` directory contains:
- **Core Papers (1-12)**: Key literature for the course covering topics like:
  - Circadian regulation and macromolecular complexes
  - Neural differentiation and cognitive functions
  - Cell cycle regulation and development
  - Phosphorylation landscapes and cellular processes

- **New Papers (A-N)**: Recent publications in cellular biology and related fields

## File Management

This repository is maintained clean of LaTeX auxiliary files. Only essential source files and final PDFs are tracked. Auxiliary files (`.aux`, `.log`, `.fdb_latexmk`, etc.) are automatically cleaned up.

## Course Information

- **Course**: Cellular Programs
- **Term**: SoSe25 (Summer Semester 2025)
