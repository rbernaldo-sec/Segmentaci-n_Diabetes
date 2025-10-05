# Segmentacion_Diabetes
# Segmentación y detección de anomalías en pacientes con diabetes

Este proyecto aplica técnicas avanzadas de aprendizaje no supervisado para segmentar pacientes crónicos y detectar perfiles atípicos, usando el dataset de diabetes de Kaggle. El objetivo es identificar agrupamientos naturales y casos clínicos inusuales que podrían representar diagnósticos tardíos, errores o condiciones emergentes.

## 🧠 Técnicas aplicadas

### 🔄 Preprocesamiento y reducción de dimensionalidad

- Escalamiento de variables
- PCA, t-SNE y UMAP para visualización en espacios de baja dimensión

### 📊 Segmentación (clustering)

- DBSCAN y HDBSCAN
- Evaluación con Índice de Silueta y Davies-Bouldin

### 🚨 Detección de anomalías

- Isolation Forest
- One-Class SVM
- Comparación de pacientes detectados como atípicos

### 🔍 Análisis cruzado

- Coincidencias entre clústeres raros y anomalías
- Discusión sobre interpretabilidad y utilidad clínica

## 📁 Archivos

- `segmentacion_diabetes.ipynb`: notebook principal con todo el flujo
- `diabetes.csv`: dataset original (enlace a Kaggle)
- `README.md`: descripción del proyecto

## 📌 Dataset

[Kaggle — Diabetes Data Set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

## 📝 Requisitos

- Python 3.10+
- pandas, scikit-learn, matplotlib, seaborn
- umap-learn, hdbscan

## 🚀 Ejecución

Puedes abrir el notebook en Jupyter o Colab y ejecutar cada celda. El código está comentado y las visualizaciones permiten interpretar los resultados clínicos.

## 🎯 Reflexión final

Este proyecto busca mostrar cómo técnicas no supervisadas pueden aportar valor clínico sin depender de etiquetas médicas explícitas, ayudando a visualizar patrones y detectar casos que merecen atención especial.


