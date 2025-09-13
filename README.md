# IA1 - Predicción y análisis de rendimiento estudiantil
**Curso:** Inteligencia Artificial I - 2025-2 C1  
**Equipo:** TeamName  
**Integrantes:** Nombre1 (código UIS), Nombre2 (código UIS), Nombre3 (código UIS)

## Datos
**Dataset:** Student Performance Factors  
**Enlace:** [poner enlace al dataset aquí]  
**Tamaño:** (indicar número de filas y columnas, p. ej. 10.000 registros, 20 columnas)

## Preguntas a responder

### Antes del EDA (conceptual)
**Problema y relevancia (máx.100 palabras):**  
Identificar los factores que más afectan `Exam_Score` y construir un modelo predictivo para detectar estudiantes en riesgo. Esto es importante porque permite intervenciones tempranas (tutorías, apoyo familiar, recursos) que mejoran resultados académicos y reducen brechas.

**Objetivo del análisis (máx.75 palabras):**  
La fase de EDA explorará relaciones entre variables, calidad y limpieza de datos, sesgos y distribuciones para definir features y métricas para el modelo predictivo en entregas posteriores.

**Métricas o indicadores (máx.75 palabras):**  
Correlaciones y análisis bivariado con `Exam_Score`, comparaciones de medias por categorías, y métricas de modelo: MAE/RMSE (regresión) y AUC/F1/recall (clasificación de riesgo). Estas métricas ayudan a evaluar precisión y utilidad clínica/educativa de la solución.

**Motivación de la elección (máx.50 palabras):**  
Problema de alto impacto social y buena disponibilidad de datos; permite aplicar técnicas vistas en el curso (EDA, limpieza, modelos supervisados) y proponer intervenciones prácticas.

### Después del EDA (resumen)
**Datos utilizados (máx.50 palabras):**  
Tabla numérica/categórica con variables demográficas, académicas y contextuales (horas de estudio, asistencia, recursos, motivación, etc.). Fuente: dataset Student Performance Factors (CSV).

**Información contenida (máx.100 palabras):**  
El dataset incluye horas de estudio, asistencia, nivel de involucramiento parental, acceso a recursos, actividades extracurriculares, horas de sueño, puntajes previos, motivación, acceso a Internet, sesiones de tutoría, ingresos familiares, calidad del docente, tipo de colegio, influencia de pares, actividad física, discapacidades de aprendizaje, nivel educativo parental, distancia al colegio, género y la variable objetivo `Exam_Score`. Estas variables permiten analizar correlaciones directas e interacciones que afectan el rendimiento.

**Desafíos asociados a los datos (máx.100 palabras):**  
Posibles valores faltantes y ruido en encuestas autoinformadas, sesgos por selección (muestra no representativa), categorías con pocas observaciones, variables ordinales mal codificadas y outliers en `Exam_Score` o `Previous_Scores`. También puede haber correlación entre variables (multicolinealidad) y dependencia de contexto local (limitaciones en generalizar resultados).
