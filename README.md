# Bank-customer-churn-prediction
Proyecto de Analítica de Datos en Python utilizando la metodología CRISP-DM  y el data set "Bank Customer Churn" disponible en Kaggle
Predicción de Fuga de Clientes Bancarios (Churn Prediction)
# 📝 Descripción General del Proyecto
Este proyecto tiene como objetivo desarrollar un modelo de Machine Learning capaz de predecir qué clientes de un banco tienen una alta probabilidad de cancelar sus cuentas (churn). Identificar a estos clientes de manera proactiva permite a la institución tomar medidas de retención personalizadas, reduciendo así la pérdida de ingresos y mejorando la lealtad del cliente.

El análisis se estructura siguiendo la metodología estándar de la industria CRISP-DM (Cross-Industry Standard Process for Data Mining), cubriendo desde la comprensión del problema de negocio hasta la planificación del despliegue del modelo.

# 🎯 Problema de Negocio
La adquisición de nuevos clientes es significativamente más costosa que la retención de los existentes. Una alta tasa de churn no solo impacta directamente en los ingresos, sino que también puede ser un indicador de problemas subyacentes en el servicio o producto. Este proyecto busca mitigar este problema proporcionando una herramienta analítica que permita al equipo de retención enfocar sus esfuerzos en los clientes con mayor riesgo de abandono.

El criterio principal de éxito es maximizar el Recall en la clase positiva (Churn = 1), ya que el costo de no identificar a un cliente que se va (Falso Negativo) es mucho mayor que el de contactar a un cliente que no pensaba irse (Falso Positivo).

# 📊 Dataset
El conjunto de datos utilizado para este proyecto contiene información demográfica y transaccional anonimizada de los clientes de un banco.

Fuente: El dataset es una versión modificada del disponible en Kaggle: Bank Customer Churn Prediction.

Características Principales: CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary.

Variable Objetivo: Churn (1 si el cliente canceló, 0 si no).

# 🛠️ Metodología (CRISP-DM)
El proyecto se desarrolla siguiendo las 6 fases de la metodología CRISP-DM:

Comprensión del Negocio: Definición de objetivos y criterios de éxito.

Comprensión de los Datos: Análisis Exploratorio de Datos (EDA) para identificar patrones y relaciones.

Preparación de los Datos: Limpieza, codificación de variables categóricas y escalado de características.

Modelado: Entrenamiento y comparación de varios algoritmos de clasificación.

Evaluación: Medición del rendimiento del modelo final con métricas clave y análisis de resultados.

Despliegue: Planificación de la integración del modelo en los procesos del banco.

# 🚀 Resultados y Conclusiones
Se entrenaron y evaluaron cuatro modelos de clasificación: Regresión Logística, K-Nearest Neighbors (KNN), Árbol de Decisión y Random Forest.

El modelo con mejor rendimiento fue el Random Forest, optimizado mediante GridSearchCV.

Métricas del Modelo Final:

Accuracy: 86.4%

Precision (Clase 1): 76.8%

Recall (Clase 1): 81.9%

F1-Score (Clase 1): 79.3%

AUC-ROC: 0.86

El modelo final cumple con el criterio de éxito establecido, superando el umbral del 80% de Recall para la clase objetivo.

# Variables Más Predictivas
El análisis de importancia de variables reveló que los factores más influyentes para predecir el churn son:

Edad (Age)

Número de Productos (NumOfProducts)

Saldo en la cuenta (Balance)

Si es un Miembro Activo (IsActiveMember)
