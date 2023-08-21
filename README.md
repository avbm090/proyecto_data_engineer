# Proyecto de Machine Learning (Soy Henry): [Juegos de Steam]


### Descripción

  En este proyecto se presenta, mediante la plataforma render, los resultados de búsqueda de una base de datos de videojuegos de la plataforma steam. Este proyecto, con intenciones de tener una primer aproximación al trabajo de un data engineer, está elaborado en el marco de la institución Soy Henry.

### Funcionalidad

- **Búsqueda**: La aplicación de búsqueda proporciona resultados relevantes basados en algunos criterios y preferencias. Encuentra juegos por título, género, desarrollador y otros criterios más. Cada resultado de búsqueda brinda algunos resultados relevantes acorde al año ingresado.

- **Predicción de precios**: Para la predicción de precios, se compararon algunos algoritmos de machine learning como regresión polinomial, decision tree, random forest, gradient boosting, svr. También se intentó abrodar el problema de utilizar algoritmos como k-means, y pca. El primero con la intención de generar nuevas etiquetas que faciliten la implementación de algoritmos de regresión, y el segundo para reducir la dimensionalidad considerando las características más relevantes, para luego, intentar aplicar algún algoritmo de regrsión sobre los componentes principales hallados. 


### Archivos

1. etl: Muestra la primera etapa de procesamiento de los datos, se cambiaron algunos formatos de las columnas originales del dataframe y se eliminaron algunas columnas que se considero no aportaban al proyecto.
2. eda_ml: Se detalla y justifica lo hecho en el proceso de eda, también se detalla y justifica lo considerado para el proceso de elección del algoritmo de machine learning.
3. eda_ml.pdf: archivo anterior en formato pdf para una visualización más rápida.
4. main: es el archivo principal donde se muestran las funciones vistas en la plataforma render.
5. steam_games.json: es la base de datos original, que contiene la lista de características de los juegos.
6. steam_games.parquet: este archivo se generó con el código escrito en etl.py.
7. gradient_boosting: en este archivo se entrena el dataset limpio con el algoritmo gradient boosting.


## Versión de python utilizada

- Python 3.9.12
