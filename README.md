# Segmentación de Clientes con Clustering

Proyecto de análisis y segmentación de clientes a partir de datos transaccionales, utilizando técnicas de aprendizaje no supervisado para identificar grupos con comportamientos de compra diferenciados.

## Objetivo

El objetivo de este proyecto es detectar segmentos relevantes de clientes, identificar posibles clientes atípicos o de alto valor y analizar patrones de comportamiento comercial a partir de variables como revenue, profit, edad y cantidad de pedidos.

## Contenido del proyecto

Este notebook incluye:

- carga y exploración inicial de datos
- limpieza y validación de variables
- transformación de variables con logaritmos
- análisis exploratorio de revenue y profit
- análisis por categoría de producto
- detección de clientes atípicos mediante DBSCAN
- segmentación de clientes mediante K-Means
- visualización de clusters con PCA
- interpretación final de segmentos desde una perspectiva de negocio

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Metodología

El flujo general del proyecto fue el siguiente:

1. Carga y limpieza del dataset
2. Análisis exploratorio de variables relevantes
3. Transformación de variables sesgadas
4. Identificación de outliers o clientes atípicos
5. Aplicación de clustering con K-Means
6. Reducción de dimensionalidad con PCA para visualización
7. Perfilado e interpretación de los clusters obtenidos

## Archivo principal

- `segmentacion_clientes_clustering.ipynb`: notebook principal del proyecto

## Principales técnicas aplicadas

### DBSCAN
Se utilizó DBSCAN para detectar clientes atípicos dentro del conjunto de datos, especialmente aquellos con comportamientos poco frecuentes o de alto valor.

### K-Means
Se utilizó K-Means para agrupar clientes en segmentos según similitudes en sus características de compra y comportamiento.

### PCA
Se aplicó PCA para reducir dimensionalidad y visualizar los segmentos de clientes en un espacio bidimensional.

## Posibles insights de negocio

A partir de este análisis pueden identificarse, por ejemplo:

- clientes con alto valor de compra
- clientes frecuentes con bajo ticket promedio
- segmentos con mayor rentabilidad
- grupos con comportamientos diferenciados para campañas de marketing
- clientes atípicos que merecen análisis específico

## Cómo ejecutar el proyecto

1. Abrir el notebook en Google Colab o Jupyter Notebook.
2. Verificar que las dependencias estén instaladas.
3. Ejecutar las celdas en orden.
4. Asegurarse de que la fuente de datos esté disponible, ya que el notebook utiliza un archivo cargado desde Google Drive.
