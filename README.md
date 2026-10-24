# proyecto-2

Proyecto 2 — Visualización reproducible en Python (Seaborn y Plotly) a partir del
*World Happiness Report 2024* (Data for Figure 2.1).

**Pregunta analítica:** ¿En qué dimensiones del bienestar —económica, de salud y socioinstitucional— se
observan las mayores diferencias entre los países con mayor y menor evaluación de vida en el
World Happiness Report 2024?

**Subpregunta:** ¿qué países se apartan del patrón de su grupo?

## Estructura

- `proyecto2.ipynb` — Notebook del análisis (ejecutado).
- `data/WHR24_Data_Figure_2.1.xls` — archivo oficial original (no se modifica).
  Fuente: https://files.worldhappiness.report/WHR24_Data_Figure_2.1.xls
- `resultados/` — archivos generados por el Notebook:
  - `Proyecto2_visualizaciones_interactivas.html` — informe interactivo con los gráficos de Plotly (se abre en cualquier navegador, sin conexión).
- `recursos/plantilla_reporte.html` — maqueta del informe; el Notebook la completa con las cifras calculadas.
  - `g1_distribucion.png` … `g4_correlaciones.png` — gráficos de Seaborn.
  - `whr24_preparado.csv` — datos preparados (columnas renombradas, cuartiles e indicador socioinstitucional).
- `docs/Proyecto2_Audiencia_Pregunta_corregido.tex` — audiencia, pregunta y variables (versión corregida).
- `docs/` — guía del proyecto y propuesta original.

## Cómo reproducir

```
pip install -r requirements.txt
jupyter notebook proyecto2.ipynb      # o abrirlo en VS Code y ejecutar todo
```

En Google Colab, quitar el comentario de la primera celda de código para clonar el repositorio.
`xlrd` es necesario porque el archivo oficial está en formato `.xls`.
