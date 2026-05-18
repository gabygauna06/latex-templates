# Plantilla De Trabajo De Facultad

Plantilla LaTeX mínima y apta para impresión para trabajos con bodies bilingües (ES/EN).

## Compilación
- Español: compilar `main-es.tex`
- Inglés: compilar `main-en.tex`

Directorio de salida recomendado:
- `out/latex/`

## Diseño
- Portada: acento de color mínimo (apta para imprimir).
- Cuerpo: blanco y negro.
- Encabezado: izquierda = título, derecha = materia.
- Hoja de entrega: autores + docente + fecha en página 2.

## Estructura
- `main-es.tex`, `main-en.tex` — entrypoints
- `src/` — fuentes principales
- `lang/` — bodies bilingües
- `assets/` — logo y figuras

## Qué Se Edita
- Metadatos: `src/metadata.tex`
- Contenido: `lang/<es|en>/body.tex`
- Referencias al final: `src/references.tex`
- Logo de portada: `assets/faculty-logo.png`
