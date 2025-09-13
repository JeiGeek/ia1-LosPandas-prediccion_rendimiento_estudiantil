# 📘 IA1 - Predicción y Análisis de Rendimiento Estudiantil

**Curso:** *Inteligencia Artificial I - 2025-2 C1*  
**👥 Equipo:** *LosPandas*  
**Integrantes:**  
- Nombre1 *(código UIS)*  
- Nombre2 *(código UIS)*  
- Jeison Fernando Guarguati Anaya - *2221930*  

---

## 🗂️ Contenidos
- [Dataset](#dataset)
- [Preguntas a responder](#preguntas-a-responder)
  - [Antes del EDA (conceptual)](#antes-del-eda-conceptual)
  - [Después del EDA (resumen)](#despues-del-eda-resumen)
- [Tecnologías](#tecnologías-a-utilizar)
- [Flujo del proyecto](#flujo-del-proyecto)

---

## 📊 Dataset
- **Nombre:** *Student Performance Factors*  
- **Enlace:** [🔗 Ver dataset](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)  
- **Tamaño:** `6607 registros × 20 columnas`  

---

## ❓ Preguntas a responder

### 🔹 Antes del EDA (conceptual)

> **Problema y relevancia:**  
> Identificar los factores que más afectan `Exam_Score` y construir un modelo predictivo para detectar estudiantes en riesgo. Esto es importante porque permite intervenciones tempranas (tutorías, apoyo familiar, recursos) que mejoran resultados académicos y reducen brechas.

> **Objetivo del análisis:**  
> La fase de EDA explorará relaciones entre variables, calidad y limpieza de datos, sesgos y distribuciones para definir features y métricas para el modelo predictivo en entregas posteriores.

> **Métricas o indicadores:**  
> - Correlaciones y análisis bivariado con `Exam_Score`  
> - Comparaciones de medias por categorías  
> - Métricas de modelo: **MAE/RMSE** (regresión) y **AUC/F1/Recall** (clasificación de riesgo)  
> Estas métricas permiten evaluar precisión y utilidad educativa de la solución.

> **Motivación de la elección:**  
> Elegimos este problema por su impacto social: mejorar rendimiento escolar influye en oportunidades futuras. Además los datos son tabulares y permiten aplicar desde EDA hasta modelos supervisados vistos en el curso.

---

### 🔹 Después del EDA (resumen)

📌 **Datos utilizados (máx.50 palabras):**  
Tabla con variables numéricas y categóricas relacionadas con factores académicos, demográficos y contextuales. Fuente: *Student Performance Factors (CSV).*  

📌 **Información contenida (máx.100 palabras):**  
El dataset incluye horas de estudio, asistencia, participación parental, acceso a recursos, actividades extracurriculares, horas de sueño, puntajes previos, motivación, acceso a Internet, tutorías, ingresos familiares, calidad del docente, tipo de colegio, influencia de pares, actividad física, discapacidades de aprendizaje, nivel educativo parental, distancia al colegio, género y la variable objetivo `Exam_Score`. Estas variables permiten analizar correlaciones e interacciones que afectan el rendimiento.  

📌 **Desafíos asociados a los datos (máx.100 palabras):**  
- Valores faltantes y ruido en encuestas autoinformadas  
- Sesgo de selección (muestra no representativa)  
- Categorías con pocas observaciones  
- Variables ordinales mal codificadas  
- Outliers en `Exam_Score` y `Previous_Scores`  
- Multicolinealidad entre variables  
- Contexto local que limita la generalización  

---

## 🛠️ Tecnologías a utilizar
- **Lenguaje:** Python 🐍  
- **Librerías:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Entorno:** Jupyter Notebook / Google Colab  

---

## 🚀 Flujo del proyecto
1. **Carga y exploración inicial de datos**  
2. **EDA (gráficos, correlaciones, limpieza, outliers)**  
3. **Preprocesamiento y selección de features**  
4. **Modelado predictivo (regresión / clasificación)**  
5. **Evaluación y métricas**  
6. **Conclusiones y recomendaciones educativas**  

---

> 🔔 **Nota:** Puedes añadir badges de Python o de GitHub Actions para darle aún más estilo visual al README.

