
# ⚗️ AnimeScore
### Predicción del éxito de animes mediante técnicas de Machine Learning

AnimeScore es un proyecto de aprendizaje automático (Machine Learning) enfocado en analizar y predecir el éxito de diferentes animes a partir de sus características, popularidad y calificaciones.

El proyecto utiliza un conjunto de datos obtenido de Kaggle ([Anime and Manga Dataset 2026](https://www.kaggle.com/datasets/patelris/anime-and-manga-dataset-2026)) y desarrolla dos enfoques principales de aprendizaje supervisado: **clasificación y regresión**.

## 🎯 Objetivo

Analizar los datos de diferentes animes para identificar patrones y desarrollar modelos capaces de clasificar su nivel de éxito y predecir sus calificaciones (`score`).

## 🧠 Metodología

El proyecto se divide en dos etapas principales:

### 1. Clasificación
Se implementan y comparan cuatro algoritmos para clasificar los animes en tres categorías según su calificación:

- **Bajo:** score inferior a 5.5.
- **Promedio:** score entre 5.5 y 6.9.
- **Alto (Éxito):** score igual o superior a 7.0.

Modelos utilizados:
- Gaussian Naive Bayes.
- Decision Tree.
- Random Forest.
- Support Vector Machine (SVM).

### 2. Regresión
Se implementan modelos para predecir directamente la calificación numérica (`score`) de los animes.

Modelos utilizados:
- Bayesian Ridge.
- Decision Tree Regressor.
- Random Forest Regressor.
- Support Vector Regression (SVR).

## 🛠️ Herramientas y tecnologías

- **Python:** Lenguaje de programación.
- **Pandas y NumPy:** Manipulación y procesamiento de datos.
- **Matplotlib y Seaborn:** Visualización y análisis exploratorio.
- **Scikit-learn:** Implementación, entrenamiento y evaluación de modelos de Machine Learning.
- **Jupyter Notebook / Google Colab:** Entorno de desarrollo.

## 📊 Evaluación de los modelos

Para evaluar y comparar el rendimiento de los algoritmos se utilizan diferentes métricas:

**Clasificación:**
- Accuracy.
- Precision.
- Recall.
- F1-Score (Macro).

**Regresión:**
- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).
- Coeficiente de determinación (R²).

También se utiliza validación cruzada de 5 particiones (5-Fold Cross Validation) para analizar la estabilidad de los modelos.

## 📁 Estructura del proyecto

- `anime_proyecto_final.ipynb`: Notebook principal con el análisis de datos, preparación, entrenamiento, comparación y evaluación de los modelos.

## 👥 Proyecto académico

Proyecto desarrollado con fines académicos para aplicar conceptos de análisis de datos, estadística y aprendizaje automático, explorando sus posibilidades en el análisis de la industria del anime.


## 👥 Autores

Proyecto desarrollado por:

| Nombre | Código estudiantil |
|---|---|
| Juan José Arias Camelo | 2252008 |
| Tomás Ramírez | 2251788 |

---
**AnimeScore** · Proyecto académico de Machine Learning.

