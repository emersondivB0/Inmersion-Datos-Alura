# Proyecto de Data Science: Predicción de precios de inmuebles

Este proyecto tiene como objetivo aplicar técnicas de ciencia de datos para predecir el precio de futuros inmuebles. Se utiliza un conjunto de datos de ventas de inmuebles que incluye información sobre precios, áreas, localidades, cantidad de baños, habitaciones, así como datos socioeconómicos de las personas de las zonas donde se encuentran estos inmuebles.

Tecnologías utilizadas
En este proyecto se utilizaron las siguientes herramientas y tecnologías:

Google Drive
Google Colaboratory
Python 3
Pandas
Matplotlib
Seaborn
Scikit-learn

Estructura del repositorio
El repositorio está organizado de la siguiente manera:

data/: Carpeta que contiene los archivos CSV con los datos de ventas de inmuebles
notebooks/: Carpeta que contiene el archivo Jupyter Notebook utilizado para analizar y procesar los datos, así como para crear y entrenar el modelo de regresión lineal.
README.md: Este archivo, que brinda información general sobre el proyecto.
Proceso de análisis y modelado
Carga de datos: Los datos se cargaron desde los archivos CSV a Google Colaboratory.

Análisis exploratorio: Se utilizó pandas, matplotlib y seaborn para analizar los datos, identificar valores atípicos y explorar las relaciones entre las variables.

Preprocesamiento de datos: Se realizaron tareas de limpieza y transformación de los datos, incluyendo la eliminación de valores faltantes, la normalización de variables y la creación de nuevas variables derivadas.

Modelado: Se utilizó la biblioteca scikit-learn para crear y entrenar un modelo de regresión lineal que predice el precio de los inmuebles en función de las variables predictoras.

Validación del modelo: Se evaluó la precisión del modelo utilizando métricas como el error cuadrático medio (MSE) y el coeficiente de determinación (R2).

Resultados y conclusiones
El modelo de regresión lineal logró predecir con poca precisión, por ahora, el precio de futuros inmuebles en función de las variables predictoras utilizadas. Se identificaron las variables más importantes para la predicción del precio, lo que puede ser útil para la toma de decisiones en el mercado inmobiliario.

