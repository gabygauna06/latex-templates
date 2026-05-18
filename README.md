# LaTeX Templates Library

Central repository of reusable LaTeX templates and project skeletons (print-friendly, Git-friendly).

## Goals
- Keep templates minimal, professional, and easy to reuse.
- Prefer modular layout (main + src + lang + assets + references).
- Avoid build artifacts in version control.

## Layout
- `templates/` — Self-contained templates (each must compile on its own)
- `shared/` — Optional shared resources (use sparingly)

## Conventions
- File/folder names: lowercase + hyphen, no spaces.
- Every folder should include both `README.md` and `README.es.md`.
- Do not commit build output (`out/`, `.aux`, `.log`, etc).

## Build
Each template provides `main-es.tex` and `main-en.tex` entrypoints.
Recommended output directory: `out/latex/`.
