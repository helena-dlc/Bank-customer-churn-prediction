
# 🏦 Bank Customer Churn Prediction  
**Proyecto de Analítica y Machine Learning con la metodología CRISP-DM**

---

## 📘 Descripción del Proyecto  
Este proyecto analiza y predice la **pérdida de clientes (churn)** en una institución bancaria, utilizando el dataset público de Kaggle **“Bank Customer Churn Prediction”**.  
El trabajo se desarrolló en **Python** usando **Google Colab**, aplicando técnicas de **análisis exploratorio, visualización de datos y modelamiento predictivo** con algoritmos de aprendizaje supervisado.  

---

## 🎯 Objetivos  

- Analizar la **tasa de abandono** según variables **demográficas** (género, edad, país).  
- Explorar cómo las **variables financieras** (balance, salario estimado, número de productos, tarjeta de crédito) influyen en el churn.  
- Construir un **modelo de clasificación Random Forest** que identifique clientes con riesgo de abandonar el banco.  
- Detectar **patrones y factores clave** que ayuden a diseñar estrategias de retención personalizadas.

---

## 🧭 Metodología (CRISP-DM)

1. **Comprensión del Negocio** 💡  
   - Definición del problema y de los objetivos analíticos.  
   - Planteamiento de criterios de éxito orientados al negocio.  

2. **Comprensión de los Datos** 🔍  
   - Exploración de estructura, tipos de variables, valores faltantes y duplicados.  
   - Identificación de correlaciones y distribución del churn.  

3. **Preparación de los Datos** 🧹  
   - Limpieza, codificación de variables categóricas y normalización de escalas.  
   - Separación de conjuntos de entrenamiento y prueba.  

4. **Modelado** 🤖  
   - Entrenamiento de un **Random Forest Classifier**.  
   - Optimización de hiperparámetros y validación cruzada.  

5. **Evaluación y Conclusiones** 📈  
   - Análisis del desempeño mediante métricas:  
     - Accuracy  
     - Precision  
     - Recall  
     - F1-score  
     - Matriz de confusión  
   - Interpretación de la importancia de variables y recomendaciones finales.  

---

## 🧠 Tecnologías y Librerías Utilizadas

| Categoría | Herramientas |
|------------|---------------|
| Entorno | Google Colab |
| Lenguaje | Python 3.10+ |
| Librerías Principales | `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` |

---

## 📊 Exploración y Visualización (EDA)
- Análisis descriptivo de las variables numéricas y categóricas.  
- Comparaciones gráficas entre clientes activos y desertores.  
- Visualizaciones con `seaborn` y `matplotlib` para detectar patrones en edad, país, balance y productos contratados.  

---

## 🤖 Modelamiento Predictivo: Random Forest  
El modelo **Random Forest** fue seleccionado por su capacidad de manejar datos mixtos y reducir el sobreajuste.  
- Entrenamiento con datos balanceados.  
- Evaluación con métricas de clasificación.  
- Interpretación de **feature importance** para identificar los factores que más influyen en el abandono.  

📌 *Entre las variables más relevantes se destacaron la edad, el saldo promedio y la cantidad de productos contratados.*  

---

## 📈 Resultados Principales
- Se logró un modelo con **alta capacidad de clasificación** y buena interpretabilidad.  
- Se identificaron los perfiles de clientes con mayor probabilidad de churn.  
- Los hallazgos permiten orientar estrategias de **retención proactiva** basadas en datos.  

---

## 💻 Ejecución del Proyecto

1. Abre el archivo `.ipynb` en **Google Colab**.  
2. Sube el dataset `Bank_Customer_Churn_Prediction.csv`.  
3. Ejecuta las celdas secuencialmente.  
4. Observa los resultados gráficos y el rendimiento del modelo Random Forest.

---


---

## 👩‍💻 Autora  

**Helena De La Cruz Vergara**  
📚 Estudiante de Ingeniería Comercial  
💡 Interesada en Analítica de Datos, Machine Learning y Visualización de Información  
📍 Chile  

---

✨ *“Convertir datos en conocimiento útil es la clave para entender el comportamiento del cliente.”* ✨


