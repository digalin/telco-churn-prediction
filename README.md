# Telco Customer Churn — Predicción de Abandono de Clientes

> Proyecto de Machine Learning · Clasificación supervisada

---

## Descripción del problema

Una empresa de telecomunicaciones quiere identificar proactivamente qué clientes tienen mayor probabilidad de abandonar el servicio (*churn*), para poder tomar acciones de retención antes de que se vayan.

**Pregunta guía:** ¿Qué características están más asociadas al abandono de clientes y qué modelo permite justificar mejor la decisión?

**Objetivo general:** Predecir si un cliente abandonará el servicio a partir de características demográficas, contractuales y
de uso.

**Objetivos específicos:**
* Identificar y clasificar las variables del dataset en numéricas y categóricas,
  analizando su relación con el abandono mediante análisis exploratorio.
* Aplicar técnicas de preprocesamiento incluyendo limpieza de datos, codificación
  One-Hot Encoding y escalado de variables numéricas.
* Entrenar y optimizar dos modelos de clasificación (Regresión Logística y Árbol
  de Decisión) mediante búsqueda de hiperparámetros con validación cruzada.
* Comparar el rendimiento de ambos modelos usando métricas apropiadas para
  clases desbalanceadas.
* Identificar las variables con mayor influencia en la predicción del churn
  a través de los coeficientes del modelo lineal y la importancia de features
  del árbol de decisión.


---

## Dataset

**Telco Customer Churn** — IBM Watson Analytics  
- **Fuente:** [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Archivo esperado:** `data/raw/WA_Fn-UseC_-Telco-Customer-Churn.csv`  
- 7.043 clientes · 21 variables (demográficas, contractuales y de uso)  
- Variable objetivo: `Churn` (Yes/No)

---

> Proyecto académico desarrollado para el curso *Tópicos D* (Machine Learning) — [Universidad de Magallanes, Punta Arenas, Chile], 2026.