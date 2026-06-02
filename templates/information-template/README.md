# Information Template

Minimal, print-friendly LaTeX template with bilingual bodies (ES/EN).

## Build
- Spanish: compile `main-es.tex`
- English: compile `main-en.tex`

Recommended output directory:
- `out/latex/`

## Design
- Cover: minimal accent color (print-friendly).
- Body pages: black & white.
- Header: left = document title, right = category/course (as configured in the template).

## Structure
- `main-es.tex`, `main-en.tex` — entrypoints
- `template.tex` — global layout and styling
- `lang/` — bilingual bodies
- `assets/` — figures/diagrams/tables used by the document
- `references.tex` — manual references at the end (thebibliography)
- `output/` — optional final PDFs you choose to keep

## Edit
- Metadata: edit the METADATA block (as defined in the template).
- Content: `lang/<es|en>/`
- References at the end: `references.tex`
- Assets: `assets/`
