# Capstone project: Identificación de deslizamientos en imágenes de satélite Sentinel-2

El presente repositorio contiene los scripts desarrollados en el marco del capstone project del Postgrado UB Datascience and Machine Learning (  http://www.ub.edu/datascience/postgraduate/ ) por los estudiantes:
- Jesús de Diego Alarcón
- Lluis Serra Domínguez

Una breve explicación del alcance del proyecto puede encontrarse aquí:[Pagina Github Pages](https://serra17.github.io/landslide-susceptibility/)

El trabajo está basado en la propuesta especificada en el siguiente challenge: https://www.iarai.ac.at/landslide4sense/ 

# El contenido

En este repositorio encontrará los siguientes scripts y/o archivos de soporte:
- Carpeta [Testing the dataset](https://github.com/SERRA17/landslide-susceptibility/tree/main/testing%20the%20dataset):
  - Analisis de imágenes.ipynb . El notebook describe un primer análisis de las imágenes utilizadas.
  - DEM and slope denoising.ipynb . Este notebook permite realizar el suavizado de la banda del modelo digital del terreno.
  - parametros_imagenes.csv . Parámetros de las diferentes imágenes y bandas del juego de datos de training.

- Carpeta [logistic and random forest model](https://github.com/SERRA17/landslide-susceptibility/tree/main/logistic%20and%20random%20forest%20model)
  - Raster sampling.ipynb El notebook genera los datos que se utilizarán en los modelos de regresión logística y random forest.
  - Logistic Regression and Random Forest classification.ipynb . Modelo de regresión logística y Random Forest ( Este notebook está implementado en R).
  - data_extraction.zip . Resultado del notebook "Raster Sampling" que es utilizado como input en "Logistic Regresion and Random Forest classification".

- Carpeta [Deep Learning](https://github.com/SERRA17/landslide-susceptibility/tree/main/deep-learning)
  - UNET model.ipynb . Implementación de un modelo secuencial y otro basado en una red convolucional U-Net





