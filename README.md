# LaTeX Templates Library

Central repository of reusable LaTeX templates and project skeletons (print-friendly, Git-friendly).

## Repository Goals
- Keep templates clean, minimal, and professional.
- Prefer modular projects (main + template + metadata + bodies + assets).
- Make templates easy to copy into new projects without refactoring.

## Structure (recommended)
- `templates/` — Ready-to-use templates. Each template is self-contained.
- `shared/` — Optional shared snippets/assets (use sparingly to avoid tight coupling).

A template folder should typically look like:
- `main-es.tex`, `main-en.tex`
- `template.tex`, `metadata.tex`, `references.tex`
- `lang/es/body.tex`, `lang/en/body.tex`
- `assets/` and `assets/figures/`
- `README.md` + `README.es.md` inside the template folder

## Build
- Compile Spanish: `main-es.tex`
- Compile English: `main-en.tex`

Recommended output directory for VS Code LaTeX Workshop:
- `out/latex/`

## Conventions
- Keep file/folder names: lowercase + hyphen (no spaces).
- Avoid committing build artifacts (`out/`, `.aux`, `.log`, etc).
- Each folder should include both `README.md` and `README.es.md`.

## Adding a New Template
1. Create a new folder under `templates/<template-name>/`
2. Add the self-contained project skeleton (mains, template, metadata, bodies, assets).
3. Add `README.md` and `README.es.md` in that template folder.
4. Commit with a clear message: `feat: add <template-name> template`

