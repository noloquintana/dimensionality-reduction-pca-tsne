# ESPAÑOL

# Reducción de dimensionalidad con PCA y t-SNE

Descripción

Este proyecto analiza técnicas de reducción de dimensionalidad utilizando PCA y t-SNE aplicadas a un dataset de alta dimensionalidad.

El objetivo es simplificar la estructura de los datos manteniendo patrones relevantes para facilitar su visualización e interpretación.

📂 Dataset

Nombre: Human Activity Recognition (HAR)

Fuente: UCI Machine Learning Repository

Variables: 561

Observaciones: 7352

Los datos provienen de sensores de smartphones (acelerómetro y giroscopio).

⚙️ Metodología

Carga y exploración de datos

Escalamiento con StandardScaler

Aplicación de:

PCA

t-SNE

Visualización en 2D

Comparación de resultados

📈 Resultados

PCA muestra la estructura global de los datos.

t-SNE permite observar agrupaciones más claras.

🧠 Conclusión

Para la presentación de insights, t-SNE resulta más adecuado, ya que permite identificar patrones y segmentos de manera más clara.

# ENGLISH

# Dimensionality Reduction with PCA and t-SNE

Overview

This project explores dimensionality reduction techniques using Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) applied to a high-dimensional dataset.

The objective is to transform a dataset with a large number of variables into a lower-dimensional representation while preserving meaningful patterns, enabling better visualization and interpretation.

📂 Dataset

Name: Human Activity Recognition (HAR) Dataset

Source: UCI Machine Learning Repository

Features: 561 numerical variables

Observations: 7352 samples

The dataset contains features extracted from smartphone sensors (accelerometer and gyroscope) during different human activities.

🛠️ Tools & Technologies

Python

NumPy

Pandas

Scikit-learn

Matplotlib

⚙️ Methodology

Data loading and inspection

Data scaling using StandardScaler

Dimensionality reduction with:

PCA (linear method)

t-SNE (non-linear method)

Visualization in 2D

Comparison of results

📈 Results

PCA preserves the global structure of the data but does not clearly separate clusters.

t-SNE reveals well-defined clusters, making it easier to identify patterns and groupings.

🧠 Key Insights

High-dimensional datasets benefit significantly from dimensionality reduction techniques.

PCA is efficient and useful for general structure analysis.

t-SNE is more effective for identifying clusters and local patterns.

⚖️ Conclusion

For presenting insights (e.g., to a marketing team), t-SNE is the preferred method due to its ability to highlight groupings clearly. However, PCA remains valuable as a preprocessing step due to its speed and interpretability.

