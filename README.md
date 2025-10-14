# Introducción a Machine Learning 🤖

---

## 📋 Descripción del Módulo

Este repositorio contiene ejemplos prácticos y ejercicios del módulo de **Elementos de Machine Learning**, diseñado para proporcionar una introducción teórica y práctica al aprendizaje automático utilizando Python.

## 🎯 Objetivos del Módulo

- Comprender los conceptos fundamentales de Machine Learning
- Diferenciar entre IA, ML, DL y Ciencia de Datos
- Implementar algoritmos de aprendizaje supervisado y no supervisado
- Desarrollar proyectos end-to-end de Machine Learning
- Aplicar técnicas de Deep Learning a problemas reales

## 📚 Contenido del Módulo

### Introducción Teórica y Práctica
- Conceptos fundamentales de Machine Learning
- DS vs AI vs ML vs DL
- Tipos de aprendizaje: Supervisado, No Supervisado, Por Refuerzo
- Etapas de un proyecto de Data Science y ML


## 🚀 Cómo Usar Este Repositorio

### Opción 1: Google Colab (Recomendado)

Todos los notebooks están diseñados para ejecutarse en Google Colab sin necesidad de instalación local:

1. Abre cualquier notebook directamente en Colab
2. Ejecuta las celdas secuencialmente
3. Experimenta y modifica el código

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

### Opción 2: Instalación Local

```bash
# Clonar el repositorio
git clone https://github.com/armandocodigos/Intro-ML-2025-UCA.git
cd Intro-ML-2025-UCA

# Crear entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Iniciar Jupyter Notebook
jupyter notebook
```

## 📦 Dependencias Principales

```
numpy
pandas
matplotlib
scikit-learn
ucimlrepo
```

### Instalación rápida:

```bash
pip install numpy pandas matplotlib scikit-learn ucimlrepo
```

## 💡 Ejemplo: Infrared Thermography Temperature

Uno de los ejemplos principales utiliza el dataset de **Infrared Thermography Temperature** del UCI ML Repository:

```python
from ucimlrepo import fetch_ucirepo 

# Obtener dataset
infrared_thermography = fetch_ucirepo(id=925) 

# Datos y metadata
X = infrared_thermography.data.features 
y = infrared_thermography.data.targets 

print(infrared_thermography.metadata) 
print(infrared_thermography.variables)
```

**Dataset**: [UCI ML Repository - Infrared Thermography](https://archive.ics.uci.edu/dataset/925/infrared+thermography+temperature+dataset)

## 📖 Recursos Adicionales

### Herramientas Recomendadas
- **Anaconda**: Distribución completa de Python para Data Science
- **JupyterLab**: Entorno de desarrollo interactivo
- **Google Colab**: Notebooks en la nube con GPU gratuita

### Librerías Principales
- **NumPy**: Computación numérica
- **Pandas**: Manipulación de datos
- **Matplotlib**: Visualización de datos
- **Scikit-Learn**: Algoritmos de Machine Learning
- **UCI ML Repository**: Acceso a datasets

### Referencias
- Géron, A. (2023). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*
- Mitchell, T. (1997). *Machine Learning*
- Samuel, A. (1959). *Some Studies in Machine Learning Using the Game of Checkers*


## 🙏 Agradecimientos

- Universidad Centroamericana José Simeón Cañas (UCA)
- UCI Machine Learning Repository
- La comunidad de Data Science y Machine Learning

---

⭐ **¡Bienvenidos al mundo del Machine Learning!**
