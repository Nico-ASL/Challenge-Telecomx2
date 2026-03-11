# Challenge-Telecomx2
curso Alura
Descripción

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning capaces de predecir la cancelación de clientes (churn) en Telecom X. El análisis permite identificar los factores que influyen en el abandono del servicio y proponer estrategias de retención.

Objetivos

Preparar y limpiar los datos para el modelado.

Analizar la relación entre variables y cancelación.

Entrenar modelos de clasificación para predecir churn.

Evaluar el desempeño de los modelos.

Identificar las variables más importantes en la cancelación.

Modelos utilizados

Se entrenaron dos modelos de clasificación:

Regresión Logística (con normalización de datos)

Random Forest

Estos modelos permiten comparar un enfoque interpretable con uno basado en árboles de decisión.

Resultados principales
Modelo	Accuracy	Precision	Recall	F1-score
Regresión Logística	0.798	0.641	0.545	0.589
Random Forest	0.784	0.615	0.501	0.552

El modelo de Regresión Logística obtuvo el mejor desempeño general.

Factores que más influyen en la cancelación

Las variables más relevantes identificadas fueron:

Tiempo como cliente

Tipo de contrato

Cargo mensual

Cargo total

Tipo de servicio de internet

Método de pago

Los clientes con contratos mensuales, menor antigüedad y mayor costo mensual presentan mayor probabilidad de cancelar.

Estrategias de retención sugeridas

Incentivar contratos de largo plazo.

Implementar programas de fidelización para clientes nuevos.

Ofrecer promociones personalizadas a clientes con alto gasto mensual.

Mejorar la experiencia en servicios de internet de fibra óptica.

Tecnologías utilizadas

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Google Colab

Estructura del proyecto
TelecomX/
│
├── telecomx_limpio.csv
├── analisis_churn.ipynb
└── README.md
