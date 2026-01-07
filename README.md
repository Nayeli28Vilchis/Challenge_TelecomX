📊 Análisis de Evasión de Clientes (Churn) – Telecom
📌 Descripción

Este proyecto analiza la evasión de clientes (Churn) en una empresa de telecomunicaciones utilizando Python.
El objetivo es identificar patrones y factores asociados a la cancelación del servicio mediante limpieza de datos y análisis exploratorio (EDA).

🎯 Objetivo

Identificar perfiles de clientes con mayor probabilidad de evasión a partir del análisis de:

Tipo de contrato

Método de pago

Tiempo de permanencia (tenure)

Comportamiento de gasto (facturación mensual y diaria)

🧹 Preparación de Datos

Carga y revisión del dataset

Tratamiento de valores nulos y formatos incorrectos

Conversión de variables numéricas

Creación de una nueva variable:

Cuentas_Diarias: cálculo del gasto diario a partir de la facturación mensual

📊 Análisis Exploratorio de Datos

Distribución de la variable Churn mediante gráficos de barras y pastel

Análisis de churn por variables categóricas:

Género

Tipo de contrato

Método de pago

Servicio de internet

Comparación de variables numéricas según evasión:

Total gastado

Tiempo de contrato

Cuentas_Diarias

Las visualizaciones se realizaron con Matplotlib para identificar patrones relevantes.

🔍 Principales Hallazgos

Mayor evasión en contratos mensuales

Clientes con menor antigüedad presentan mayor churn

El método de pago y el tipo de servicio influyen en la evasión

Las variables de gasto ayudan a diferenciar el comportamiento de los clientes

🛠️ Herramientas

Python

Pandas

Matplotlib

Google Colab

📁 Estructura del Proyecto
├── Challenge_TelecomX_NV.ipynb
└── README.md

🚀 Conclusión

Este análisis permite comprender los factores asociados a la evasión de clientes y sirve como base para futuras etapas, como modelos predictivos de churn o estrategias de retención basadas en datos.
