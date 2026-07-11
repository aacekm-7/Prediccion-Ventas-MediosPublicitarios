# 📊 Predicción de Ventas a partir de Inversión Publicitaria

Proyecto de **regresión lineal** que predice el volumen de ventas de una empresa a partir de su inversión en tres canales publicitarios: **TV, Radio y Newspaper**.

## 🎯 Pregunta de negocio
¿Qué canal publicitario tiene mayor impacto real en las ventas, y en cuál debería invertir más una empresa para maximizar su retorno?

## 🗂️ Dataset
[Advertising Dataset](https://www.kaggle.com/) — 200 registros de inversión publicitaria (en miles de USD) por canal, junto con las ventas resultantes (en miles de unidades). Dataset limpio, sin valores nulos, ampliamente usado como referencia en modelado de regresión lineal.

## 🛠️ Herramientas
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

## 🔍 Proceso
1. Análisis exploratorio de datos (EDA) con visualización de correlaciones
2. División train/test (80/20) y escalado de variables (`StandardScaler`)
3. Entrenamiento de un modelo de regresión lineal múltiple (`LinearRegression`)
4. Evaluación con MAE, RMSE y R² sobre el conjunto de prueba
5. Análisis de residuos para validar los supuestos del modelo
6. Función interactiva de predicción con validación de inputs y alerta de extrapolación

## 📈 Resultados
- **R² = 0.91** en el conjunto de test (sin señales de overfitting: R² train ≈ R² test)
- **MAE = 1.27** (miles de unidades)
- **TV** resultó ser el canal con mayor poder predictivo, seguido de **Radio**; **Newspaper** mostró una relación casi nula con las ventas.

## Proyecto

- [Proyecto](https://github.com/aacekm-7/Prediccion-Ventas-MediosPublicitarios/blob/main/proyecto_v2.ipynb)
