# FORM-IC-01 — Arquitecturas distribuidas en la industria

Investigación individual sobre el caso de **Wix** y su arquitectura orientada a eventos (EDA) con Apache Kafka.

## Estructura

```
├── main.tex          # Archivo principal
├── referencias.bib   # Referencias (IEEE, biblatex)
├── capturas/         # Capturas de la fuente principal
└── main.pdf          # PDF compilado
```

## Compilación

- **Compilador:** pdfLaTeX
- **Archivo principal:** `main.tex`
- **Gestor de bibliografía:** biber

Orden de comandos:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

## Dependencias

Distribución LaTeX (TeX Live, MiKTeX u Overleaf) con los paquetes:

`inputenc`, `fontenc`, `babel` (spanish), `geometry`, `graphicx`, `csquotes`, `hyperref`, `biblatex` (estilo `ieee`) y `biber`.
