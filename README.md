# 📘 IA1 - Predicción y Análisis de Rendimiento Estudiantil

![Portada/Banner Placeholder](https://github.com/JeiGeek/ia1-LosPandas-prediccion_rendimiento_estudiantil/blob/main/src/portada.jpg)

**Curso:** *Inteligencia Artificial I - 2025-2 C1*  
**👥 Equipo:** *LosPandas*  
**Integrantes:**  
- Miguel Andres Jaimes Ortiz — *2221895*  
- Thomas Alejandro Rincón Valencia ☠️⚰️🎗️ — *2221915*  
- Jeison Fernando Guarguati Anaya — *2221930*  

---

## 🗂️ Contenidos
- [Dataset](#dataset)
- [Preguntas a responder](#preguntas-a-responder)
  - [Antes del EDA (conceptual)](#antes-del-eda-conceptual)
  - [Después del EDA (resumen)](#después-del-eda-resumen)
- [Hipótesis inicial y modelos planeados](#hipótesis-inicial-y-modelos-planeados)
- [Tecnologías](#tecnologías-a-utilizar)
- [Resumen de modelos utilizados](#resumen-de-modelos-utilizados)
- [Flujo del proyecto](#flujo-del-proyecto)
- [Video](#video)

---

## 📊 Dataset

- **Nombre:** *Student Performance Factors*  
- **Fuente externa:** Kaggle  
  - **Enlace:** https://www.kaggle.com/datasets/lainguyn123/student-performance-factors  
  - **Descarga:**  
    1. Crear cuenta en Kaggle  
    2. Entrar al enlace  
    3. Clic en *Download Dataset*  
    4. Colocar el archivo `.csv` dentro de `/data/`

- **Ubicación dentro de este repositorio:**
  ```
  /Dataset/StudentPerformanceFactors.csv
  ```

- **Tamaño:** `6607 registros × 20 columnas`  

---

## ❓ Preguntas a responder

### Antes del EDA (conceptual)

> **Problema y relevancia:**  
> Identificar los factores que afectan el rendimiento académico para permitir intervenciones tempranas como tutorías, estrategias de estudio y apoyo familiar.

> **Objetivo del análisis:**  
> Observar relaciones entre variables, detectar patrones y preparar datos para modelos predictivos y análisis posteriores.

> **Métricas o indicadores:**  
> - Correlación con *Exam_Score*  
> - Promedios por categoría  
> - MAE / MSE / RMSE para regresión  
> - Accuracy / Recall / F1 / Balanced Accuracy para clasificación  
> - Importancia de características  

> **Motivación de la elección:**  
> Es un problema con impacto social real y permite la aplicación práctica de técnicas de EDA, ML supervisado, no supervisado y reducción de dimensionalidad vistas en el curso.

---

### Después del EDA (resumen)

📌 **Datos utilizados (máx. 50 palabras):**  
> Dataset con información académica y personal de estudiantes, incluyendo hábitos de estudio, asistencia, acceso a recursos, motivación y notas previas. Adecuado para análisis exploratorio, regresión y clasificación del rendimiento académico.

📌 **Información contenida (máx. 100 palabras):**  
> Contiene 20 variables categóricas y numéricas relacionadas con factores académicos (horas de estudio, asistencia, notas previas), personales (género, motivación, discapacidades) y socioeconómicos (ingresos, educación de los padres). La variable objetivo es *Exam_Score*. Permite analizar patrones y construir modelos predictivos para estimar rendimiento y riesgo académico.

📌 **Desafíos asociados a los datos (máx. 100 palabras):**  
> Se identificaron valores atípicos (nota 101). Muchas variables presentan baja correlación con la nota, dificultando el modelado. La distribución de *Exam_Score* está concentrada entre 60 y 80 puntos, complicando predecir extremos. Se requiere transformar variables categóricas (algunas ordinales). Además, aspectos emocionales o sociales no incluidos podrían influir en el rendimiento.

---

## 🧠 Hipótesis inicial y modelos planeados

### ✔ Hipótesis inicial
> Antes del análisis, el equipo asumía que:  
> - **Horas de estudio**,  
> - **Asistencia**,  
> - **Notas previas**, y  
> - **Participación de los padres**  
> serían los factores más relevantes para el rendimiento académico.

También esperábamos que **SVM** y **Random Forest** tuvieran el mejor rendimiento por su capacidad para manejar relaciones no lineales.

### ✔ Modelos planeados inicialmente
- **Regresión:** Regresión Lineal, SVR, Random Forest, Deep Learning  
- **Clasificación:** Naive Bayes, Árboles de Decisión, Random Forest, SVM, Deep Learning  
- **No supervisado:** K-Means, DBSCAN, Agglomerative Clustering  
- **Dimensionalidad:** PCA, t-SNE  

---

## 🛠️ Tecnologías a utilizar
- **Lenguaje:** Python 🐍  
- **Librerías:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
  - TensorFlow / Keras  
- **Entorno:** Google Colab / Jupyter Notebook  

---

## 📦 Resumen de modelos utilizados

| Tipo                | Modelos usados                                                |
|--------------------|---------------------------------------------------------------|
| **Regresión**      | SVR, Random Forest, Decision Tree, Deep Learning              |
| **Clasificación**  | Naive Bayes, SVM, Random Forest, Deep Learning                |
| **No supervisado** | K-Means, DBSCAN, Agglomerative Clustering                     |
| **Dimensionalidad**| PCA, t-SNE                                                    |

---

## 🚀 Flujo del proyecto

```
![Pipeline/Banner Placeholder](https://raw.githubusercontent.com/JeiGeek/ia1-LosPandas-prediccion_rendimiento_estudiantil/main/src/Pipeline.png)
```

---

## 🎥 Video
Video resumen del proyecto (máx. 5 minutos):

🔗 **[Enlace al video]()**  
*(se agregará cuando esté publicado)*

---

