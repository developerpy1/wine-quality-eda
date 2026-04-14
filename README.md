# Análisis Exploratorio de Datos: Calidad del Vino

## Descripción del Proyecto

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre el dataset de calidad del vino con el objetivo de identificar patrones, relaciones y variables clave que influyen en la calidad del vino. El análisis sirve como base para futuros modelos de machine learning.

---

## Dataset

* Fuente: https://www.kaggle.com/datasets/yasserh/wine-quality-dataset
* Nombre: Wine Quality (Vino Tinto)
* Número de registros: 1,143 (antes de limpieza)
* Variables: Propiedades fisicoquímicas del vino
* Variable objetivo: `quality` (puntaje entero de 0 a 10)

---

## Objetivos

* Comprender la estructura del dataset
* Identificar problemas de calidad de datos (duplicados, outliers)
* Analizar la distribución de las variables
* Explorar relaciones entre variables
* Determinar los factores más importantes que afectan la calidad del vino

---

## Limpieza de Datos

* Verificación de valores faltantes (no se encontraron)
* Eliminación de registros duplicados
* Revisión de tipos de datos

---

## Análisis Exploratorio

### Análisis Univariado

* Evaluación de la distribución de cada variable
* Identificación de asimetrías y posibles outliers

### Análisis Bivariado

* Relación entre variables independientes y la calidad del vino
* Uso de gráficos como boxplots y scatterplots

### Matriz de Correlación

* Identificación de relaciones lineales entre variables
* Detección de variables con mayor influencia sobre la calidad

---

## Hallazgos Principales

* El alcohol presenta una correlación positiva con la calidad del vino
* La acidez volátil muestra una correlación negativa con la calidad
* La mayoría de los vinos tienen una calidad entre 5 y 6 (dataset desbalanceado)

---

## Problemas Identificados

* Desbalance en la variable objetivo
* Presencia de valores atípicos en múltiples variables
* Distribuciones no normales en varias características


## Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Conclusión

Este análisis permitió identificar las variables más relevantes que afectan la calidad del vino y proporciona una base sólida para el desarrollo de modelos predictivos.
