# Importaciones Bogotá

Análisis académico sobre el Data Set público 'Importaciones Bogotá', en el que se extrae la información mediante la API de Datos Abiertos de Bogotá. Se realiza un reconocimiento y limpieza de los datos, seguido de un proceso de análisis avanzado para la toma de decisiones organizacionales.

## Descripción del Proyecto

**Título:** Optimización del Portafolio de Importaciones de Bogotá - Modelo basado en datos para la toma de decisiones organizacionales.

Este repositorio contiene el desarrollo de un proyecto académico para la asignatura de **Toma de Decisiones Organizacionales**. El dominio de aplicación es Logística y Supply Chain.

El análisis abarca:
1. **Extracción y Preparación de Datos:** Consumo de la API de Datos Abiertos de Bogotá para obtener los registros de importaciones.
2. **Análisis Exploratorio de Datos (EDA):** Identificación de patrones, principales países de origen y categorías de productos.
3. **Modelamiento y Clustering:** Uso de técnicas de aprendizaje no supervisado (K-Means, PCA) para segmentar y agrupar comportamientos de importación.
4. **Optimización Matemática:** Implementación de modelos de programación lineal (usando la librería PuLP) para optimizar el portafolio de importaciones.

## Autores
* Johan Nicolás Valderrama Serrato
* Paola Andrea Castro
* Mariana Prada Riaño


## Estructura del Repositorio
* `Proyecto_Importaciones_Bogota.ipynb`: Notebook principal con todo el código fuente en Python (extracción, EDA, clustering y optimización).
* `Articulo_Importaciones_Bogota_Toma_Decisiones.pdf`: Documento académico detallando la metodología, resultados y conclusiones del proyecto.
* `Presentación_Importaciones en Bogotá 2025_ diagnóstico, optimización y resiliencia.pdf`: Presentación de soporte para la sustentación del proyecto.
* `Overleaf/`: Archivos fuente de LaTeX correspondientes al documento tipo articulo.

## Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías principales:** pandas, numpy, matplotlib, seaborn, plotly, scikit-learn (KMeans, PCA), pulp, requests.
