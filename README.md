# [**Natural Language Processing - Prueba Técnica.**](#indice)

## [Introducción:](#indice)

En la carpeta se encuentran los notebooks en los cuales se implemento el analisis y desarrollo de la prueba tecnica para el caso "1.Natural Language Processing ", en los cules se abarcan las consideraciones del enunciado de la prueba:

Entrenamiento de un Modelo de Aprendizaje Profundo para Detectar Mentiras en Mensajes del Juego Diplomacy

Este proyecto se basa en el conjunto de datos de Diplomacy (https://sites.google.com/view/qanta/projects/diplomacy?pli=1) para entrenar un modelo de aprendizaje profundo que prediga si un mensaje es una mentira o no.

En la carpeta encontrara tres archivos los cuales se describen mas abajo.

Requisitos:

El modelo debe entrenarse utilizando la técnica de transferencia de aprendizaje utilizando un marco de Python.
La arquitectura del modelo debe ser un transformer, y no se puede utilizar la biblioteca AllenNLP, ya que se utilizó en el código del artículo ACL'20 (Peskov et al.).
Comparación con Benchmark:

Se requiere comparar el rendimiento del modelo entrenado con el benchmark proporcionado en el artículo ACL'20 (Peskov et al.).


# [Indice](#indice)
A continuación listamos los elementos por los que está compuesto este documento, luego de leer la introducción:

- [Introducción](#introducción)
- [deception_diplomacy_EDAS](#Notebook-con-el-Analisis-Exploratorio-de-datos)
- [deception_diplomacy_tensorflow](#TransferLearning-Tensorflow)
- [deception_diplomacy_pytorch](#TransferLearning-Pytorch)
    


# [deception_diplomacy_EDAS](#Notebook-con-el-Analisis-Exploratorio-de-datos)
En este archivo se encuetra el EDAs inicial, donde se transforman, se curan y analizan los datos, para comprender sus principales caracteristicas asi como, tener un panorama claro de como abordar el problema. Este archivo contiene los siguientes temas:

- Importar librerías
- Importar Datos
- Convertir en DataFrame y Observar estructura de celdas
- Analisis Exploratorio de Datos
- CONCLUSIONES RELEVANTES

# [deception_diplomacy_tensorflow](#TransferLearning-Tensorflow)
En este archivo se encuetra la experimentacion y transferlearning usando TenseroFlow, donde se implementa arquitectura tipo GRU y modelo "Universal Sentence Encoder". Este archivo contiene los siguientes temas::

- Importar librerías
- Funciones para datos iniciales
- Importar y Preparar Datos
- Preparando Datos para el modelo
- Preparando Embeddings
- Modelado
- Evaluacion de los modelos
- Comparacion de modelo

# [deception_diplomacy_pytorch](#TransferLearning-Pytorch)
En este archivo se encuetra la experimentacion y transferlearning usando TenseroFlow, donde se implementa arquitectura tipo GRU y modelo "Universal Sentence Encoder". Este archivo contiene los siguientes temas::

- Importar librerías
- Funciones para datos iniciales
- Importar y Preparar Datos
- Preparando Datos para el modelo
- Modelado , modelo usado BERT_Arch con Weighted CrossEntropy Loss
- Entrenamiento del modelo
- Comparacion de modelo

# [Autores:](#indice)
Esta aplicación fue construída por **Juan Sebastian Paniagua Alvarez (jpaniagu)**, para la prueba técnica.

# [Historial de Cambios:](#indice)

A continuación, una tabla en la que se deben registrar los cambios:

| Fecha      | Versión | Descripción | Autores                         |
|------------|---------|-------------|---------------------------------|
| 26/12/2023 | 1.0.0   | Creación    | Juan Sebastian Paniagua Alvarez |

