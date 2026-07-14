# Predicción de lluvia al día siguiente con weatherAUS

## Evaluación Final Transversal — BIY7121 Minería de Datos

Proyecto de minería de datos orientado a predecir si lloverá al día siguiente
en distintas ubicaciones de Australia, utilizando el dataset `weatherAUS.csv`.

---

## Ejecutar el notebook

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DIECASZU/BIY7121-weatherAUS/blob/main/BIY7121_ET_Notebook_Final_weatherAUS_Diego_Casanova_Jose_Soto.ipynb)

El notebook puede ejecutarse directamente desde el navegador. La fuente de
datos se carga automáticamente desde este repositorio.

---

## Objetivo del proyecto

Desarrollar una solución de minería de datos que permita anticipar si lloverá
al día siguiente a partir de información meteorológica histórica.

La variable objetivo es `RainTomorrow`, por lo que corresponde a un problema
de clasificación binaria:

- **Yes:** lloverá al día siguiente.
- **No:** no lloverá al día siguiente.

---

## Archivos disponibles

- [Notebook ejecutable](BIY7121_ET_Notebook_Final_weatherAUS_Diego_Casanova_Jose_Soto.ipynb)
- [Dataset weatherAUS.csv](weatherAUS.csv)
- [Informe final en PDF](01_BIY7121_ET_Informe_Final_weatherAUS_Diego_Casanova_Jose_Soto_profesional.pdf)
- [Presentación PowerPoint](BIY7121_ET_Presentacion_weatherAUS_Diego_Casanova_Jose_Soto_profesional.pptx)

---

## Metodología CRISP-DM

El proyecto se desarrolló mediante las seis etapas de CRISP-DM:

1. **Comprensión del negocio:** definición del problema y su utilidad.
2. **Comprensión de los datos:** revisión de estructura, tipos, nulos y patrones.
3. **Preparación de los datos:** limpieza, imputación y transformación.
4. **Modelamiento:** regresión logística, árbol de decisión y clustering.
5. **Evaluación:** comparación mediante accuracy, precision, recall, F1 y ROC-AUC.
6. **Despliegue:** propuesta de automatización, monitoreo y alertas.

---

## Resultados principales

| Indicador | Resultado |
|---|---:|
| Registros analizados | 142.193 |
| Columnas originales | 24 |
| Días con lluvia al día siguiente | 22,42% |
| Modelo seleccionado | Regresión logística |
| Accuracy | 0,796 |
| Precision | 0,531 |
| Recall | 0,780 |
| F1-score | 0,632 |
| ROC-AUC | 0,873 |

La regresión logística obtuvo el mejor equilibrio entre la detección de días
lluviosos y el control de falsas alertas.

---

## Principales técnicas utilizadas

- Análisis exploratorio de datos.
- Tratamiento de datos faltantes.
- One-Hot Encoding.
- Estandarización de variables.
- Regresión logística.
- Árbol de decisión.
- Matriz de confusión.
- Clustering meteorológico.
- Análisis por ubicación y temporalidad.

---

## Integrantes

- Diego Casanova
- José Soto

**Asignatura:** BIY7121 — Minería de Datos  
**Sección:** BIY7121-004D  
**Dataset:** weatherAUS.csv  
**Metodología:** CRISP-DM
