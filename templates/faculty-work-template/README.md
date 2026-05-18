# Faculty Work Template

Minimal, print-friendly LaTeX template for faculty assignments with bilingual bodies (ES/EN).

## Build
- Spanish: compile `main-es.tex`
- English: compile `main-en.tex`

Recommended output directory:
- `out/latex/`

## Design
- Cover: minimal accent color (print-friendly).
- Body pages: black & white.
- Header: left = document title, right = course name.
- Submission page: authors + instructor + date on page 2.

## Structure
- `main-es.tex`, `main-en.tex` — entrypoints
- `src/` — core sources
- `lang/` — bilingual bodies
- `assets/` — logo and figures

## Edit
- Assignment metadata: `src/metadata.tex`
- Content: `lang/<es|en>/body.tex`
- References at the end: `src/references.tex`
- Cover logo: `assets/faculty-logo.png`
