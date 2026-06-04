# Information Template

Plantilla LaTeX mínima y apta para impresión con bodies bilingües (ES/EN).

## Compilación
- Español: compilar `main-es.tex`
- Inglés: compilar `main-en.tex`

Directorio de salida recomendado:
- `out/latex/`

## Diseño
- Portada: acento de color mínimo (apta para imprimir).
- Cuerpo: blanco y negro.
- Encabezado: izquierda = título, derecha = categoría/materia (según configuración del template).

## Estructura
- `main-es.tex`, `main-en.tex` — entrypoints
- `template.tex` — layout y estilo global
- `lang/` — bodies bilingües
- `assets/` — figuras/diagramas/tablas del documento
- `references.tex` — referencias manuales al final (thebibliography)
- `out/` — PDFs finales opcionales que se quieran guardar

## Qué Se Edita
- Metadatos: editar el bloque METADATA (según esté definido en el template).
- Contenido: `lang/<es|en>/`
- Referencias al final: `references.tex`
- Assets: `assets/`
