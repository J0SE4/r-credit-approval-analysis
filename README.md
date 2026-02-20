# Análisis de aprobación de crédito (R)

Práctica de análisis de datos en R sobre el dataset de aprobación de crédito.

## Tecnologías
- R
- R Markdown
- ggplot2, caret, corrplot

## Archivos
- `analysis.Rmd`: informe principal.
- `crx.data`, `crx.names`, `credit.names`: dataset y metadatos.

## Ejecución
```bash
Rscript -e "install.packages(c('rmarkdown','ggplot2','caret','corrplot'), repos='https://cloud.r-project.org')"
Rscript -e "rmarkdown::render('analysis.Rmd')"
```

## Qué incluye
- Limpieza y transformación de variables.
- Visualización y análisis exploratorio.
- Flujo reproducible desde R Markdown.

## Trabajo en equipo
Práctica realizada en equipo. No se asigna un rol individual concreto en este repositorio.

## Nota
Uso académico/educativo.
