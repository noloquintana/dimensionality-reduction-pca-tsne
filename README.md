# ESPAÑOL

# 📊 Reducción de Dimensionalidad con PCA y t-SNE

---

## 📌 Descripción

Este proyecto tiene como objetivo aplicar técnicas de reducción de dimensionalidad, específicamente **PCA (Análisis de Componentes Principales)** y **t-SNE**, sobre un dataset de alta dimensionalidad.

El análisis se basa en el dataset **Human Activity Recognition (HAR)**, el cual contiene información proveniente de sensores de smartphones y presenta más de 500 variables, lo que lo convierte en un caso ideal para aplicar estas técnicas.

El propósito es simplificar la estructura de los datos, mejorar su interpretabilidad y evaluar su utilidad tanto para la visualización como para el modelado predictivo.

---

## 🎯 Objetivos

- Reducir la dimensionalidad del dataset
- Analizar la varianza explicada mediante PCA
- Visualizar los datos en 2 dimensiones
- Identificar patrones y agrupaciones
- Comparar el desempeño de PCA y t-SNE
- Evaluar el uso de estas técnicas en modelos predictivos

---

## 🧠 Tecnologías utilizadas

- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

**Nombre:** Human Activity Recognition (HAR)  
**Fuente:** https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones  

El dataset contiene **561 variables** y miles de observaciones, lo que lo hace adecuado para aplicar técnicas de reducción dimensional.

---

## ⚙️ Metodología

1. Carga y exploración del dataset  
2. Escalamiento de datos con StandardScaler  
3. Aplicación de PCA  
   - Análisis de varianza explicada  
   - Selección del número óptimo de componentes  
4. Aplicación de t-SNE  
   - Visualización en 2D  
   - Ajuste de parámetros  
5. Comparación entre PCA y t-SNE  
6. Reflexión final  

---

## 📊 Resultados

- **PCA** permite reducir la dimensionalidad manteniendo la mayor parte de la varianza, siendo útil para procesos de modelado.
- **t-SNE** logra una mejor visualización de los datos, revelando clusters bien definidos y patrones no lineales.

---

## 🧩 Conclusiones

- PCA es una técnica eficiente para reducción dimensional en pipelines de machine learning.
- t-SNE es ideal para exploración visual y análisis de patrones.
- La combinación de ambas técnicas permite obtener un análisis más completo del dataset.

---

## 📁 Estructura del proyecto

├── dimensionality_reduction_pca_tsne.ipynb
├── X_train.txt
├── y_train.txt
├── activity_labels.txt
├── README.md

# ENGLISH

# 📊 Dimensionality Reduction with PCA and t-SNE

---

## 📌 Description

This project aims to apply dimensionality reduction techniques, specifically **PCA (Principal Component Analysis)** and **t-SNE**, on a high-dimensional dataset.

The analysis is based on the **Human Activity Recognition (HAR)** dataset, which contains data collected from smartphone sensors and includes more than 500 features, making it ideal for applying these techniques.

The goal is to simplify the structure of the data, improve interpretability, and evaluate its usefulness for both visualization and predictive modeling.

---

## 🎯 Objectives

- Reduce the dimensionality of the dataset  
- Analyze the explained variance using PCA  
- Visualize the data in 2 dimensions  
- Identify patterns and clusters  
- Compare the performance of PCA and t-SNE  
- Evaluate the use of these techniques in predictive models  

---

## 🧠 Technologies Used

- Python 🐍  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📂 Dataset

**Name:** Human Activity Recognition (HAR)  
**Source:** https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones  

The dataset contains **561 features** and thousands of observations, making it suitable for dimensionality reduction techniques.

---

## ⚙️ Methodology

1. Data loading and exploration  
2. Data scaling using StandardScaler  
3. PCA application  
   - Explained variance analysis  
   - Selection of optimal number of components  
4. t-SNE application  
   - 2D visualization  
   - Parameter configuration  
5. Comparison between PCA and t-SNE  
6. Final reflection  

---

## 📊 Results

- **PCA** reduces dimensionality while preserving most of the variance, making it suitable for modeling tasks.  
- **t-SNE** provides better data visualization, revealing well-defined clusters and non-linear patterns.  

---

## 🧩 Conclusions

- PCA is an efficient technique for dimensionality reduction in machine learning pipelines.  
- t-SNE is ideal for exploratory analysis and visualization of patterns.  
- Combining both techniques provides a more comprehensive understanding of the dataset.  

---

## 📁 Project Structure

├── dimensionality_reduction_pca_tsne.ipynb
├── X_train.txt
├── y_train.txt
├── activity_labels.txt
├── README.md
