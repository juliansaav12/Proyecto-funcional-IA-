# Hospitalización por Dengue en Colombia: Un Análisis a partir de Factores Sociodemográficos y Territoriales

<p align="center">
  <img src="assets/banner_800x300.png" alt="Banner del Proyecto" width="800" height="300">
</p>

## Autores
Oscar Julián Saavedra (2241931), Jair Andres Lagos Pereira (2204130), Roberto Jose Tamara Corredor (2269109)

## Objetivo
Predecir la necesidad de hospitalización (`PAC_HOS`) en pacientes con dengue en Colombia a partir de factores sociodemográficos, territoriales y síntomas clínicos, priorizando la exhaustividad (Recall) para reducir falsos negativos.

## Dataset
Registros epidemiológicos oficiales de vigilancia en salud pública (SIVIGILA - Dengue, Colombia), organizados en tres conjuntos depurados: cohorte nacional 2025 (`120.564` registros, `35` variables), consolidado multianual 2022–2025 (`501.720` registros en 2022–2024 para generalización temporal) y conjunto clínico con síntomas de Medellín (`53.813` registros, `28` variables predictoras con `16` síntomas binarizados y `20.97%` de prevalencia hospitalaria).

- **Enlace de descarga del dataset:** [Descargar Datasets SIVIGILA](https://drive.google.com/drive/folders/14BLk4EUQeCIBEAWmkMLMtcvApb0oUdtg?usp=sharing)

## Modelos
Gaussian Naive Bayes, Regresión Logística, Árbol de Decisión, Random Forest, Support Vector Machine (Linear, RBF, Poly, Sigmoid), Red Neuronal Multicapa (MLP / Deep Neural Network), GridSearchCV, RandomizedSearchCV, Stratified K-Fold Cross-Validation, PCA, t-SNE, K-Means, Método del Codo, Clustering Jerárquico Aglomerativo (Ward), DBSCAN.

## Enlaces
- **Repositorio:** [GitHub - Proyecto Dengue IA I](PEGA_AQUI_EL_LINK_DE_TU_REPO_DE_LA_BARRA_DEL_NAVEGADOR)
- **Código (Notebooks):**
  - [Notebook 1: Dataset 2025](notebooks/01_modelos_dataset_2025.ipynb)
  - [Notebook 2: Generalización Temporal 2022–2025](notebooks/02_generalizacion_2022_2025.ipynb)
  - [Notebook 3: Dataset Clínico de Síntomas y No Supervisado](notebooks/03_dataset_sintomas_entrega_3.ipynb)
- **Presentación (Diapositivas):** [Ver Diapositivas PDF](docs/diapositivas_finales.pdf)
- **Video en YouTube (Máx. 5 min):** [Ver Video Sustentación](PEGA_AQUI_EL_LINK_DE_YOUTUBE_CUANDO_LO_TENGAN)
- **Archivo de Video (.mp4):** [Descargar Archivo de Video](PEGA_AQUI_EL_LINK_DE_DRIVE_DEL_MP4)
