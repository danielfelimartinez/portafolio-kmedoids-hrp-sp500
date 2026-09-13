# Portafolio Inteligente: K-Medoids + Smart Selection + HRP

Proyecto de Inversiones Alternativas — construcción de un portafolio de 15 acciones
del S&P 500 combinando segmentación no supervisada (K-Medoids/PAM), un criterio de
selección basado en desempeño individual (Smart Selection), y ponderación de capital
mediante Hierarchical Risk Parity (HRP).

## Contenido
- `Proyecto_Final_SmartSelection_HRP_v2.ipynb`: notebook completo con el análisis,
  desde la limpieza de datos hasta la validación out-of-sample con ventanas móviles.
- `BASE__SP_500.xlsx`: base de datos de precios (Bloomberg, 2020-2026), índice
  S&P 500 y datos fundamentales de cada empresa.

## Resultados principales
Validado con 3 ventanas móviles out-of-sample: Sharpe Ratio empatado con el S&P 500
(1.15), Índice de Treynor superior (0.229 vs. 0.166), y Alfa de Jensen positivo (+4.1%).

## Cómo correr el notebook
Diseñado para Google Colab: al ejecutar la primera celda, se abre un botón para
subir manualmente el archivo `BASE__SP_500.xlsx`.

---
*Desarrollado con asistencia de Claude para la implementación de código
y visualizaciones. Diseño metodológico, interpretación de resultados y conclusiones
desarrollados y validados por el autor.*
