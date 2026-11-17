# Hospitalización por Dengue en Colombia: Factores Sociodemográficos, Territoriales y Clínicos

![Banner del Proyecto](assets/banner_800x300.png)

## Autores
Oscar Julián Saavedra (2241931), Jair Andres Lagos Pereira (2204130), Roberto Jose Tamara Corredor (2269109)

## Objetivo
Predecir la necesidad de hospitalización (`PAC_HOS`) en pacientes con dengue en Colombia a partir de factores sociodemográficos, territoriales y síntomas clínicos, priorizando la exhaustividad (Recall) para reducir falsos negativos.

## Dataset
Registros epidemiológicos de vigilancia en salud pública (SIVIGILA - Dengue, Colombia), organizados en tres conjuntos de trabajo: registros nacionales 2025 (`120.564` registros depurados, `35` variables), consolidado histórico multianual 2022–2025 (`501.720` registros en 2022–2024 para generalización temporal) y conjunto clínico con síntomas de Medellín (`53.813` registros depurados, `28` variables predictoras con `16` síntomas binarizados y prevalencia hospitalaria del `20.97%`).

- **Enlace de descarga del dataset:** [Descargar Datasets SIVIGILA](PEGA_AQUI_EL_LINK_DE_DESCARGA_DRIVE_O_DATOS_GOV)

## Modelos
Gaussian Naive Bayes, Regresión Logística, Árbol de Decisión, Random Forest, Support Vector Machine (Linear, RBF, Poly, Sigmoid), Perceptrón Multicapa (MLP / Deep Neural Network), RandomizedSearchCV, GridSearchCV, Stratified K-Fold Cross-Validation, PCA, t-SNE, K-Means, Método del Codo, Clustering Jerárquico Aglomerativo (Ward), DBSCAN.

## Enlaces
- **Repositorio:** [GitHub - Proyecto Dengue IA I](PEGA_AQUI_EL_LINK_DEL_REPOSITORIO)
- **Código (Notebooks):**
  - [Notebook 1: Dataset 2025](notebooks/01_modelos_dataset_2025.ipynb)
  - [Notebook 2: Generalización Temporal 2022–2025](notebooks/02_generalizacion_2022_2025.ipynb)
  - [Notebook 3: Dataset Clínico de Síntomas y No Supervisado](notebooks/03_dataset_sintomas_entrega_3.ipynb)
- **Presentación (Diapositivas):** [Diapositivas del Proyecto](docs/diapositivas_finales.pdf)
- **Video en YouTube (Máx. 5 min):** [Ver Video Sustentación](PEGA_AQUI_EL_LINK_DE_YOUTUBE_CUANDO_LO_GRABEN)
- **Archivo de Video (.mp4):** [Descargar Video](PEGA_AQUI_EL_LINK_AL_MP4_O_RUTA_EN_REPO)
