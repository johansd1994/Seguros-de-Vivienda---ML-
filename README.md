# 🤖 Seguro de Vivienda – Machine Learning

Este repositorio contiene un **Jupyter Notebook** enfocado en la **aplicación de modelos de Machine Learning** para la **predicción de la contratación de un seguro de vivienda**, utilizando un **dataset de clientes y características asociadas al riesgo y comportamiento**.

Este notebook representa la **fase final del proyecto**, donde los datos previamente procesados y analizados se emplean para construir, entrenar y evaluar modelos predictivos orientados al sector asegurador.

---

## 📌 Contenido del Notebook

El archivo principal del repositorio es:

* `Machine Learning.ipynb`

En él se desarrollan las siguientes etapas:

---

## 1️⃣ Importación de librerías

Se utilizan librerías estándar de Machine Learning en Python:

* `pandas` y `numpy` para manipulación de datos
* `scikit-learn` para modelado y evaluación
* `matplotlib` y `seaborn` para visualización de resultados

---

## 2️⃣ Preparación de los datos

En esta etapa se realizan tareas clave antes del entrenamiento de los modelos:

* Selección de variables predictoras
* Definición de la variable objetivo (`Seguro_Vivienda`)
* Separación del dataset en conjuntos de entrenamiento y prueba
* Escalado de variables numéricas cuando es necesario

Esta fase garantiza que los datos estén en condiciones óptimas para el aprendizaje automático.

---

## 3️⃣ Entrenamiento de modelos

Se entrenan distintos algoritmos de Machine Learning supervisado para comparar su desempeño, tales como:

* Regresión Logística
* K-Nearest Neighbors (KNN)
* Árboles de Decisión
* Otros modelos incluidos en el notebook

Cada modelo se ajusta utilizando el conjunto de entrenamiento.

---

## 4️⃣ Evaluación de modelos

El desempeño de los modelos se evalúa utilizando métricas comunes en problemas de clasificación:

* Accuracy
* Matriz de confusión
* Precision, Recall y F1-score

Estas métricas permiten analizar la capacidad predictiva de cada modelo.

---

## 5️⃣ Comparación y resultados

Se comparan los resultados obtenidos por los distintos modelos para:

* Identificar el algoritmo con mejor desempeño
* Analizar fortalezas y debilidades de cada enfoque
* Evaluar la viabilidad del uso de Machine Learning en la predicción de seguros de vivienda

---

## 🎯 Objetivo del proyecto

El objetivo principal de este notebook es **aplicar técnicas de Machine Learning supervisado** para:

* Predecir la contratación de un seguro de vivienda
* Comparar distintos modelos de clasificación
* Integrar análisis de datos y modelado predictivo en un flujo completo de Data Science aplicado al sector asegurador

---

## 🛠️ Requisitos

Para ejecutar el notebook se requiere:

* Python 3.8 o superior
* Jupyter Notebook o Jupyter Lab
* Librerías:

  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:

   ```bash
   git clone <url-del-repositorio>
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd <nombre-del-repositorio>
   ```

3. Abre el notebook:

   ```bash
   jupyter notebook
   ```

4. Ejecuta las celdas en orden para entrenar y evaluar los modelos.

---

## 📚 Dataset

El dataset utilizado corresponde a **datos de clientes de seguros de vivienda**, e incluye variables demográficas, contractuales y de comportamiento utilizadas para predecir la variable objetivo.

---

## ✍️ Autor

**Johan Suarez**

---

## 📄 Licencia

Este proyecto se comparte con fines educativos y académicos. Puedes reutilizarlo y adaptarlo libremente citando la fuente.

---

⭐ Si este repositorio te resulta útil, considera darle una estrella en GitHub.
