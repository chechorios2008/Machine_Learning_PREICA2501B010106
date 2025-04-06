# Proyectos de Machine Learning: Regresión Lineal y KNN para Análisis de Clientes

Este repositorio contiene dos proyectos de Machine Learning enfocados en el análisis de clientes: uno de regresión lineal para predecir el gasto anual de clientes de ecommerce, y otro de clasificación KNN para predecir la fuga de clientes (Churn).

## Descripción General

Se analizan conjuntos de datos que contienen información sobre clientes, incluyendo datos demográficos, comportamiento en plataformas digitales y uso de servicios. El objetivo es construir modelos predictivos que permitan a las empresas comprender mejor a sus clientes y tomar decisiones informadas.

# Clasificación de Dígitos con Redes Neuronales (MNIST).
Este proyecto implementa un modelo de red neuronal para la clasificación de imágenes manuscritas del dataset MNIST, utilizando dos enfoques:

Construcción manual del perceptrón multicapa (MLP) con NumPy.
Construcción usando librerías especializadas como TensorFlow/Keras.


Este repositorio contiene dos proyectos de Machine Learning enfocados en el análisis de clientes: uno de regresión lineal para predecir el gasto anual de clientes de ecommerce, y otro de clasificación KNN para predecir la fuga de clientes (Churn) y finalmente la creación de redes neuronares de manera manual y haciendo uso de bibliotecas

## Estructura del Repositorio

El repositorio se organiza en los siguientes directorios y archivos:

* `regresion_lineal/`: Contiene el proyecto de regresión lineal.
* `knn/`: Contiene el proyecto de clasificación KNN.
* `data/`: Contiene los datos originales y procesados (compartidos entre proyectos).
    * `raw/`: Datos originales en formato CSV.
    * `processed/`: Datos procesados y preparados para los modelos.
* `.gitignore`: Archivo para ignorar archivos y directorios en Git.
* `README.md`: Este archivo, que describe los proyectos.
* `requirements.txt`: Lista de dependencias del proyecto.

## Dependencias

Los proyectos utilizan las siguientes bibliotecas de Python:

* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`
* `joblib`

Puedes instalar las dependencias usando `pip`:

```bash
pip install -r requirements.txt