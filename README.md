# ML-HANDS_ON
Claro, aquí tienes una descripción breve que puedes agregar al archivo `README.md` de tu repositorio:

---

# Predicción de Precios de Viviendas

Este proyecto tiene como objetivo predecir el precio de viviendas en California utilizando el dataset "California Housing". A través de un flujo completo de Machine Learning, el modelo entrenado estima el valor de una vivienda basado en características como el número de habitaciones, tamaño, población, ubicación y otros factores.

## Tecnologías utilizadas
- **Python**
- **Scikit-Learn** (para la creación y evaluación de modelos)
- **RandomForestRegressor**
- **Joblib** (para guardar y cargar el modelo)
- **Matplotlib / Seaborn** (para la visualización de datos)
- **Jupyter Notebook** (para la implementación y análisis)

## Pasos del proyecto
1. **Carga y preprocesamiento de datos**: Importación y limpieza del dataset, manejo de valores faltantes, escalado de características.
2. **Análisis exploratorio**: Análisis de la relación entre características y precios, visualización de distribuciones y correlaciones.
3. **Entrenamiento del modelo**: Creación de varios modelos de regresión, incluida la regresión aleatoria de bosques (Random Forest).
4. **Evaluación del modelo**: Métricas de rendimiento como RMSE y R² para determinar la precisión del modelo.
5. **Predicción**: Estimación del precio de nuevas viviendas.
6. **Guardado del modelo**: El modelo entrenado se guarda para su uso posterior con `joblib`.

## Requisitos
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- joblib

## Instrucciones de uso
1. Clona el repositorio.
2. Instala las dependencias necesarias:  
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta el notebook `california_housing_prediction.ipynb` para realizar el análisis y las predicciones.
