# DataCamp: Data Analyst in R Career Track 🎓

Este repositorio contiene mis proyectos desarrollados durante la certificación de Analista de Datos en R de DataCamp. Cada carpeta representa un análisis de datos real donde aplico técnicas de limpieza, manipulación y visualización.

## 🚀 Proyectos Incluidos

### 1. Stack Overflow Language Popularity
* **Carpeta:** `Analyze the popularity of programming languages`
* **Descripción:** Análisis del volumen de preguntas de programación desde 2008 hasta 2020.
* **Habilidades:** Filtrado avanzado con `dplyr`, agregación de datos y series temporales con `ggplot2`.
* **Insight clave:** Identificación de los 5 lenguajes con mayor crecimiento en el periodo 2015-2020.
#### 🛠️ Tecnologías y Herramientas
* **Lenguaje:** R
* **Librerías principales:** `tidyverse` (dplyr, ggplot2, readr, tidyr)
* **Entorno:** RStudio / Jupyter Notebooks

---

### 2. Hypothesis Test: Goals in International Soccer
* **Carpeta:** `Hypothesis Testing with Men's and Women's Soccer Matches`
* **Descripción:** Análisis comparativo de goles promedio en partidos internacionales femeninos y masculinos usando datos oficiales de la FIFA desde 2002.
* **Habilidades:** Limpieza de datos, filtrado por torneo y fecha, cálculo de goles totales, prueba de hipótesis t de una cola, interpretación de p-valor.
* **Insight clave:** Determina estadísticamente si los partidos femeninos registran más goles que los masculinos.
#### 🛠️ Tecnologías y Herramientas
* **Lenguaje:** R
* **Librerías principales:** `tidyverse` (dplyr, ggplot2, readr), `gridExtra`
* **Entorno:** RStudio / Jupyter Notebooks
* **Detalles del análisis:**  
  - Hipótesis nula (H0): La media de goles en partidos femeninos es igual a la de partidos masculinos.  
  - Hipótesis alternativa (H1): La media de goles en partidos femeninos es mayor que en los masculinos.  
  - Nivel de significancia: 10%  
  - Se almacenan resultados en `result_df` con `p_val` y `result` (“reject” o “fail to reject”).

