# Biblioteca De Plantillas LaTeX

Repositorio central de plantillas LaTeX reutilizables y esqueletos de proyecto (apto para impresión y para Git).

## Objetivos Del Repositorio
- Mantener plantillas limpias, mínimas y profesionales.
- Priorizar proyectos modulares (main + template + metadata + bodies + assets).
- Facilitar copiar una plantilla a un proyecto nuevo sin refactorizaciones.

## Estructura (recomendada)
- `templates/` — Plantillas listas para usar. Cada plantilla debe ser autocontenida.
- `shared/` — Snippets/assets compartidos (opcional, usar con criterio).

Una carpeta de plantilla típicamente incluye:
- `main-es.tex`, `main-en.tex`
- `template.tex`, `metadata.tex`, `references.tex`
- `lang/es/body.tex`, `lang/en/body.tex`
- `assets/` y `assets/figures/`
- `README.md` + `README.es.md` dentro de la carpeta de la plantilla

## Compilación
- Español: compilar `main-es.tex`
- Inglés: compilar `main-en.tex`

Directorio de salida recomendado para VS Code LaTeX Workshop:
- `out/latex/`

## Convenciones
- Nombres de archivos/carpetas: minúsculas + guiones (sin espacios).
- No versionar artefactos de compilación (`out/`, `.aux`, `.log`, etc).
- Cada carpeta debe incluir `README.md` y `README.es.md`.

## Agregar Una Nueva Plantilla
1. Crear carpeta en `templates/<nombre-plantilla>/`
2. Agregar el esqueleto autocontenido (mains, template, metadata, bodies, assets).
3. Agregar `README.md` y `README.es.md` en esa carpeta.
4. Commit con mensaje claro: `feat: add <nombre-plantilla> template`

