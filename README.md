# proyecto-2

Proyecto 2 — Visualización reproducible en Python (Seaborn y Plotly) a partir del
*World Happiness Report 2024* (Data for Figure 2.1).

**Pregunta analítica:** ¿En qué dimensiones del bienestar —económica (PIB per cápita), de salud
(esperanza de vida saludable) y socioinstitucionales (apoyo social, libertad para tomar decisiones y
percepción de corrupción)— se concentran las mayores diferencias entre los países del cuartil superior
y del cuartil inferior de evaluación de vida en el WHR 2024, y qué países se apartan del patrón de su grupo?

## Estructura

- `proyecto2.ipynb` — Notebook del análisis.
- `data/WHR24_Data_Figure_2.1.xls` — archivo oficial original (no se modifica).
  Fuente: https://files.worldhappiness.report/WHR24_Data_Figure_2.1.xls
- `docs/Proyecto2_Audiencia_Pregunta_corregido.tex` — audiencia, pregunta y variables (versión corregida).
- `docs/` — guía del proyecto y propuesta original.

## Requisitos

```
pip install pandas xlrd seaborn plotly
```

`xlrd` es necesario porque el archivo oficial está en formato `.xls`.
