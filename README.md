# AI_DataScience_NeuralSight

Este README proporciona una descripción detallada del proyecto de clasificación de imágenes deportivas utilizando una Convolutional Neural Network (CNN). El proyecto se basa en el uso de un conjunto de datos de imágenes deportivas llamado "100 Sports Image Classification".

Al cual se puede acceder a través de la siguiente liga: [100 Sports Image Classification](https://www.kaggle.com/datasets/gpiosenka/sports-classification/?select=test).

A continuación, se presenta una estructura que detalla los aspectos clave de este proyecto.

## :arrow_right: Contenido del repositorio 

 _Archivos/Scripts_: 
- `CNN_Image_Classification.ipynb`: En este programa ...
- `CNN_base_model.ipynb`: En este programa ...
- `Reporte sobre el  desempeño del los modelos de CNN` :

# Dataset :information_source:

__Nombre del dataset__: 100 Sports Image Classification


__Variables__: Las imágenes del conjunto de datos tienen un formato de 224x224 píxeles y 3 canales (RGB). El conjunto de datos está dividido en directorios de entrenamiento, prueba y validación.
Este conjunto de datos comprende una variada colección de imágenes deportivas que abarcan 100 deportes diferentes.

Inicialmente esta es la distribución de las carpetas

- _Train_: **13635** imágenes pertenecientes a 100 clases
- _Test_: **510** imágenes pertenecientes a 100 clases
- _Validation_: **500** imágenes pertenecientes a 100 clases


Las imágenes se obtuvieron a través de búsquedas en Internet y se sometieron a un proceso de eliminación de duplicados para garantizar la integridad de los conjuntos de entrenamiento, prueba y validación. Todas las imágenes se redimensionaron a 224x224 píxeles y se convirtieron al formato JPG.

# Objetivo :dart:
El objetivo principal de este proyecto es desarrollar una Convolutional Neural Network (CNN) capaz de clasificar imágenes deportivas de las 100 categorías de deportes presentes en el conjunto de datos.

La clasificación automática de imágenes de deportes tiene múltiples aplicaciones útiles. Un modelo de CNN entrenado en un amplio conjunto de datos de imágenes de deportes puede utilizarse para clasificar y etiquetar automáticamente nuevas imágenes y videos de forma precisa.

Desarrollar un modelo preciso de clasificación de imágenes de deportes mediante deep learning representa una contribución valiosa para la investigación en procesamiento de imágenes y sus diversas aplicaciones en el ámbito deportivo. Este proyecto constituye un ejemplo práctico del potencial de los algoritmos de aprendizaje profundo para extraer información útil automáticamente a partir de datos visuales.

## Resultados y Evaluación Inicial :chart:

EL modelo de CNN fue entrenado y evaluado en el conjunto de datos "100 Sports Image Classification". A continuación, presentamos los resultados obtenidos:

Modelo de CNN: El modelo de CNN utilizado para la clasificación de imágenes deportivas se compone de capas de convolución, capas de max-pooling y capas completamente conectadas.

Precisión en el conjunto de prueba: El modelo logró una precisión de prueba de aproximadamente el 35.4%, lo que significa que acertó en la categorización del deporte en alrededor del 35.4% de las imágenes de prueba.

Métricas adicionales: Durante el entrenamiento, se observaron métricas como la pérdida (loss) y la precisión (accuracy). Por ejemplo, la pérdida fue de aproximadamente 2.94 y la precisión de entrenamiento alcanzó el 25.25%. En el conjunto de validación, la pérdida fue de 2.52 y la precisión fue de 33.73%.

## Resultados y Evaluación al mejorar el modelo :writing_hand:

# Conclusiones :triangular_flag_on_post:

En conclusión, el proyecto de clasificación de imágenes deportivas ha logrado desarrollar una CNN capaz de clasificar imágenes de las 100 categorías deportivas. Sin embargo, se observa margen para mejorar la precisión del modelo, lo que podría lograrse mediante la optimización de hiperparámetros y la exploración de arquitecturas de redes neuronales más avanzadas. Además, se debe considerar la calidad y diversidad del conjunto de datos para futuros trabajos.

## :small_blue_diamond: Uso

Para utilizar estos scripts, siga estos pasos generales:

1. Clona este repositorio en tu entorno local:

   ```bash
   git clone https://github.com/Jaime-prog/AI_DataScience_NeuralSight.git
   ```
2. Modifique los scripts según sea necesario para adaptarlos a su equipo específico. Por ejemplo, la ubicación de los archivos.
3. Ejecute los scripts deseados desde la línea de comandos, utilizando Python para los scripts Python y bash para el script shell.
  
   ```
    Load_Model.py
   ```

