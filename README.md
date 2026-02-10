# Proyectos de Machine Learning: Regresión y Termografía

Este repositorio contiene dos implementaciones de aprendizaje automático orientadas a la predicción de variables cuantitativas mediante diferentes metodologías de regresión.

## Contenido del Repositorio

1. **Ejemplo_Practico1.ipynb**: Implementación de un modelo de Regresión Lineal para la predicción de precios de bienes raíces. El enfoque se centra en la relación entre características físicas (metros cuadrados, habitaciones, antigüedad) y el valor comercial de los inmuebles.

2. **Infrared_Thermography_Temperature.ipynb**: Análisis y procesamiento de datos provenientes del UCI Machine Learning Repository sobre termografía infrarroja. Este notebook se enfoca en la estimación de temperaturas mediante el uso de datos sensores y procesamiento técnico.

## Requerimientos de Software

Para asegurar la reproducibilidad de ambos proyectos, se deben utilizar las siguientes librerías. Las versiones indicadas corresponden a las capturas técnicas del entorno:

* numpy (v1.26.x)
* pandas (v2.1.x)
* scikit-learn
* matplotlib
* seaborn (v0.13.x)
* ucimlrepo (v0.0.7)

## Entorno de Ejecución Recomendado

Se recomienda encarecidamente la ejecución de estos notebooks en **Google Colab**. Este entorno facilita la gestión de dependencias y proporciona los recursos de computación necesarios para el procesamiento de los datasets, especialmente para la ingesta de datos externa mediante `ucimlrepo`.

## Flujo de Trabajo Común

Ambos archivos siguen una estructura de pipeline de datos estándar:
1. Adquisición y carga de datos.
2. Análisis exploratorio y limpieza.
3. División de conjuntos de entrenamiento y prueba (Train/Test split).
4. Ajuste del modelo de regresión.
5. Evaluación de métricas de desempeño y visualización de resultados.
