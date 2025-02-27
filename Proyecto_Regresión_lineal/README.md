# Proyecto de Regresión Lineal para Predicción de Gasto Anual de Clientes de Ecommerce

Este proyecto tiene como objetivo desarrollar un modelo de regresión lineal para predecir el gasto anual de clientes de una empresa de comercio electrónico, basado en diversas características de su comportamiento en la plataforma.

## Descripción del Proyecto

Se analizó un conjunto de datos que contiene información sobre clientes de ecommerce, incluyendo datos demográficos, tiempo de uso de la aplicación y el sitio web, duración de la membresía y gasto anual. El objetivo principal es construir un modelo que permita predecir el gasto anual de un cliente a partir de estas características.

## Estructura del Proyecto

El proyecto se organiza en los siguientes directorios y archivos:

* `data/`: Contiene los datos originales y procesados.
    * `raw/`: Datos originales en formato CSV.
    * `processed/`: Datos procesados y preparados para el modelo.
* `models/`: Contiene el modelo entrenado y otros archivos relacionados con el modelo.
    * `modelo_entrenado.joblib`: Modelo de regresión lineal entrenado.
    * `df_num_scaled.csv`: Datos numéricos escalados y normalizados.
* `notebooks/`: Contiene los notebooks de Jupyter para el análisis y desarrollo del modelo.
    * `eda.ipynb`: Notebook para el análisis exploratorio de datos (EDA).
    * `procesamiento.ipynb`: Notebook para el procesamiento y preparación de datos.
    * `mod_reg_lineal.ipynb`: Notebook para el entrenamiento y evaluación del modelo de regresión lineal.
* `.gitignore`: Archivo para ignorar archivos y directorios en Git.
* `README.md`: Este archivo, que describe el proyecto.
* `requirements.txt`: Lista de dependencias del proyecto.

## Dependencias

El proyecto utiliza las siguientes bibliotecas de Python:

* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`
* `joblib`

Puedes instalar las dependencias usando `pip`:

```bash
pip install -r requirements.txt