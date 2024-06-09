
# Análisis de oraciones en Python

Descripción breve de tu proyecto.

## Este proyecto tiene como objetivo agrupar frases similares utilizando técnicas de procesamiento de lenguaje natural (NLP) y algoritmos de clustering. Además, se proporcionan visualizaciones de los resultados y se explican los motivos de cada agrupación.

Instrucciones de instalación si es necesario.

## Para instalar todas las dependencias necesarias, ejecuta el siguiente comando en tu terminal:
pip install -r requirements.txt

Cómo utilizar tu proyecto.

## Paso 1: Preprocesamiento de Texto
El preprocesamiento incluye la tokenización, lematización y eliminación de stopwords. Esto se realiza para cada frase en el archivo sentences.json.

## Paso 2: Vectorización de Frases
Se utiliza TF-IDF (Term Frequency-Inverse Document Frequency) para convertir las frases en vectores numéricos que pueden ser procesados por los algoritmos de clustering.

## Paso 3: Clustering con KMeans
Se aplica el algoritmo KMeans para agrupar las frases en 5 clusters. Las frases se agrupan en base a sus similitudes vectoriales.

## Paso 4: Reducción de Dimensionalidad y Visualización
Para visualizar los clusters de manera efectiva, se utiliza PCA (Principal Component Analysis) para reducir la dimensionalidad de los vectores a 3 componentes principales, y se genera una visualización 3D interactiva utilizando Plotly.

## Paso 5: Explicación de Agrupaciones
Se proporciona una explicación de los motivos de cada agrupación basada en las características comunes de las frases dentro de cada cluster.

Instrucciones para contribuir a tu proyecto.

## Licencia

Indica la licencia bajo la cual se distribuye tu proyecto, si es aplicable.