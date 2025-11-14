# 🧠 Modelo Supervisado de Clasificación Múltiple – Bombas de Agua
### Autor: **Jonás De Martín Rodríguez**

Este proyecto desarrolla un modelo **supervisado de clasificación múltiple** cuyo objetivo es predecir el **estado de funcionamiento de bombas de agua**, utilizando diferentes técnicas de *Machine Learning* y un proceso completo de preprocesado, entrenamiento, evaluación y comparación de modelos.

El trabajo incluye análisis de datos, tratamiento de nulos, conversión de variables categóricas, escalado, ingeniería de características, comparativa de modelos (Random Forest, LightGBM y XGBoost) y generación del archivo final `submission.csv` para su evaluación.

---

## 📂 Contenido del Proyecto

El notebook contiene el flujo completo de creación del modelo:

### **1. Preprocesado de Datos**
- Exploración inicial del dataset  
- Análisis descriptivo  
- Detección de valores nulos  
- Análisis de cardinalidad  
- Conversión de variables categóricas a numéricas  
- Escalado de variables  

---

### **2. Entrenamiento y Validación de Modelos**

Se entrenaron y compararon varios modelos supervisados:

#### 🔹 **Random Forest**
- Entrenamiento del modelo básico  
- Evaluación inicial  
- Matriz de confusión  
- Identificación de clases con baja representatividad  
- Revisión de importancia de variables  

#### 🔹 **LightGBM**
- Entrenamiento mediante gradient boosting  
- Evaluación y comparativa frente a Random Forest  
- Análisis de características más relevantes  

#### 🔹 **XGBoost**
- Entrenamiento del tercer modelo basado en gradient boosting  
- Resultados y discusión  
- Generación de predicciones finales  

---

### **3. Generación de Archivos de Envío**

Cada modelo genera un archivo:


El cual contiene las predicciones finales listas para ser evaluadas.

---

## 📊 Métricas y Evaluación

El análisis incluye:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- Matriz de confusión
- Importancia de variables

También se evalúa el rendimiento en clases minoritarias y el equilibrio general del modelo.

---

## 🧩 Conclusiones

En el notebook se presentan conclusiones detalladas sobre:

- Comportamiento de los modelos comparados  
- Variables más influyentes  
- Limitaciones del conjunto de datos  
- Recomendaciones para trabajos futuros  

Además, se entregó un archivo **PDF** con reflexiones finales y documentación ampliada.

---

## 🛠️ Tecnologías Utilizadas

- Python  
- pandas  
- numpy  
- scikit-learn  
- LightGBM  
- XGBoost  
- matplotlib  
- seaborn  

---

## 📁 Estructura Sugerida del Repositorio


---

## ▶️ Cómo Ejecutar el Proyecto

1. Clonar este repositorio:
   ```bash
   git clone <URL_DEL_REPO>

python -m venv venv
source venv/bin/activate     # Linux / Mac
venv\Scripts\activate        # Windows

pip install -r requirements.txt


---

Si quieres, también puedo generarte el archivo **`requirements.txt`** automáticamente según las librerías que usa tu notebook. ¿Deseas que lo genere?


