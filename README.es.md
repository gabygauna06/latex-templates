# Biblioteca De Plantillas LaTeX

Repositorio central de plantillas LaTeX reutilizables y esqueletos de proyecto (apto para impresión y para Git).

## Objetivos
- Mantener plantillas mínimas, profesionales y fáciles de reutilizar.
- Priorizar estructura modular (main + src + lang + assets + references).
- Evitar artefactos de compilación en el control de versiones.

## Estructura
- `templates/` — Plantillas autocontenidas (cada una debe compilar sola)
- `shared/` — Recursos compartidos opcionales (usar con criterio)

## Convenciones
- Nombres: minúsculas + guiones, sin espacios.
- Cada carpeta debe incluir `README.md` y `README.es.md`.
- No versionar salida de compilación (`out/`, `.aux`, `.log`, etc).

## Compilación
Cada plantilla incluye entrypoints `main-es.tex` y `main-en.tex`.
Directorio de salida recomendado: `out/latex/`.
