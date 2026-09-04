# Documentación de Justina

Documentación técnica de la arquitectura de software de **Justina**, robot de servicio
del Laboratorio de Bio-Robótica de la UNAM, escrita en LaTeX y organizada por módulo
(Planning, Supervisor, Executor, Knowledge, HRI, Vision, Navigation, Manipulation, Hardware).

Cada módulo documenta sus paquetes, nodos, tópicos, servicios y acciones, contrastado
contra el código fuente real.

## Estructura

- `doc.tex` — documento principal
- `img/` — diagramas e imágenes referenciadas

## Compilar

```bash
latexmk -pdf doc.tex
```

## Estado

Documento vivo: se actualiza conforme cambia el código fuente de Justina. Puede no
estar 100% sincronizado con la última versión del repositorio de software.
