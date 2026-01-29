# 💤 Estilo de Vida y la Calidad del Sueño: Machine Learning y Deep Learning con Python

Este proyecto realiza un análisis exhaustivo y multietapa sobre los factores que influyen en la calidad y duración del sueño. A través de tres entregas progresivas, se explora desde la limpieza de datos (ETL) y el análisis exploratorio (EDA), hasta la implementación de arquitecturas avanzadas de Deep Learning como Redes Neuronales Convolucionales (CNN) y Transformers.

---

## 📋 Descripción del Proyecto
El sueño es un pilar fundamental de la salud. Este estudio utiliza un conjunto de datos que vincula variables demográficas (edad, género), biométricas (frecuencia cardíaca, presión arterial) y de estilo de vida (estrés, actividad física) para predecir y entender los determinantes del descanso.

### Objetivos Principales
- Identificar la relación entre el estrés diario y la duración del sueño.  
- Determinar si el nivel de actividad física es un predictor confiable de la calidad del descanso.  
- Comparar la eficacia de modelos tradicionales frente a arquitecturas de Deep Learning para la predicción de métricas de salud.  

---

## 📊 Conjunto de Datos
El dataset cuenta con **374 registros y 12 columnas**, incluyendo:

- **Variables Categóricas:** Género, Profesión, Categoría de IMC, Trastornos del Sueño.  
- **Variables Numéricas:** Edad, Duración del sueño, Calidad del sueño, Nivel de actividad física, Nivel de estrés, Frecuencia cardíaca y Pasos diarios.  

---

## 📂 Estructura del Proyecto
El desarrollo se divide en tres notebooks que representan la evolución del análisis:

### 1. Entrega 1: Fundamentos y Exploración Inicial
- **Definición de Hipótesis:** Relación inversa entre estrés/sedentarismo y horas de sueño.  
- **Análisis Exploratorio (EDA):** Visualización de distribuciones por edad y género.  
- **Preguntas de Negocio:** Análisis de horas de sueño por profesión (ej. Doctores vs. Ingenieros de Software).  

### 2. Entrega 2: ETL y Refinamiento Estadístico
- **Procesamiento de Datos (ETL):** Limpieza de variables, normalización de categorías de IMC y tratamiento de valores nulos en trastornos del sueño.  
- **Ingeniería de Características:** Descomposición de variables complejas (como la presión arterial) y codificación de variables categóricas.  
- **Correlaciones:** Mapas de calor para identificar dependencias críticas entre variables biométricas.  

### 3. Entrega 3: Modelado Avanzado con Deep Learning
- **CNN (Convolutional Neural Networks):** Captura de patrones locales en los datos de salud.  
- **Transformers:** Uso de mecanismos de atención para modelar dependencias complejas y secuencias en variables de estilo de vida.  
- **Evaluación y Comparativa:** Análisis de curvas de entrenamiento y error (Loss/Accuracy) para determinar la capacidad de generalización de cada modelo.  

---

## 🚀 Tecnologías Utilizadas
- **Lenguaje:** Python 3.x  
- **Entorno:** Google Colab  
- **Librerías principales:**  
  - Pandas y NumPy → Manipulación de datos y ETL  
  - Matplotlib y Seaborn → Visualización avanzada  
  - Scikit-learn → Preprocesamiento y métricas  
  - TensorFlow / Keras → Construcción de modelos CNN y Transformers  

---

## 📈 Conclusiones Clave
- **Modelo Transformer:** Más robusto para capturar dependencias complejas, con curva de entrenamiento estable y predicciones coherentes.  
- **CNN:** Efectivo para tendencias generales, pero con mayor variabilidad en predicciones extremas frente al Transformer.  
- **Hallazgos Biométricos:** El nivel de estrés y la frecuencia cardíaca fueron los factores con mayor peso predictivo sobre la calidad del sueño percibida.  


