# Linear-Regression-Using-the-World-Happiness-Report-Dataset

Este repositorio contiene un análisis de datos utilizando el conjunto de datos del World Happiness Report. El proyecto fue desarrollado como parte de las actividades para la materia de Analítica y Visualización de Datos en la Escuela Superior de Cómputo (ESCOM - IPN).

Descripción del Proyecto
El objetivo principal de este proyecto es explorar los factores socioeconómicos que influyen en el índice de felicidad global (Score) y construir modelos de aprendizaje automático capaces de predecirlo. Para ello, se implementó un flujo completo de ciencia de datos que abarca desde la limpieza y el análisis exploratorio (EDA) hasta el modelado estadístico con regresión lineal y técnicas de regularización para evitar el sobreajuste.

Tecnologías y Librerías Utilizadas
El proyecto está desarrollado en Python utilizando un Jupyter Notebook (.ipynb). Las principales librerías utilizadas son:
>Pandas & NumPy: Manipulación, limpieza y estructuración de datos.
>Matplotlib & Seaborn: Visualización de datos y análisis de correlaciones.
>Scikit-Learn:
  train_test_split para la partición de datos.
  StandardScaler y Pipeline para el preprocesamiento estandarizado.
  LinearRegression, Ridge y Lasso para los modelos de regresión y regularización.
  KFold y cross_validate para la validación cruzada.
  GridSearchCV para la optimización de hiperparámetros.

Estructura del Modelo y Fases
Análisis Exploratorio de Datos (EDA): Revisión de nulos, estadísticas descriptivas, distribuciones y matriz de correlación entre los factores (PIB per cápita, apoyo social, esperanza de vida, libertad, generosidad y percepción de corrupción).
Preparación y División de Datos: Separación de variables predictoras (X) y objetivo (y), dividiendo el conjunto en entrenamiento (80%) y prueba (20%).
Modelado Baseline (Regresión Lineal): Implementación inicial evaluada mediante validación cruzada K-Fold (5 particiones) para garantizar la estabilidad de las métricas.
Regularización (Ridge y Lasso): Optimización del parámetro de penalización mediante búsqueda en malla (GridSearchCV) para mejorar la generalización del modelo.
Evaluación Final: Métricas de rendimiento obtenidas en el conjunto de prueba (MSE, MAE y R^2 Score).

Cómo ejecutar el proyecto
1. Clona este repositorio en tu máquina local:
   git clone https://github.com/tu-usuario/nombre-de-tu-repositorio.git
2. Asegúrate de tener instalado Jupyter Notebook y las dependencias necesarias:
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
3. Abre el archivo principal del notebook desde tu entorno de preferencia para visualizar o reejecutar el flujo completo.

*Desarrollado con fines académicos ESCOM - IPN.*



