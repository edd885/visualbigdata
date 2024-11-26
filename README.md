### **README.md Actualizado con la Documentación de los Challenges**

# **Visualización de Grandes Bases de Datos**

## **Descripción**
Este repositorio contiene evidencia y materiales desarrollados en el marco de la asignatura **"Visualización de Grandes Bases de Datos"**, parte del plan de estudios de la **Maestría en Ciencia de los Datos** de la **Universidad de Guadalajara**. El repositorio incluye actividades prácticas diseñadas para explorar el uso de **PySpark** en la manipulación y análisis de grandes bases de datos, con un enfoque en el aprendizaje progresivo a través de tres desafíos: básico, intermedio y avanzado.

---

## **Objetivo Final del Producto**
El objetivo principal de este repositorio es consolidar y demostrar los conocimientos adquiridos en la asignatura mediante la resolución de tres desafíos prácticos. Cada challenge permite aplicar habilidades específicas en la visualización y análisis de datos, usando enfoques reproducibles y eficientes en un entorno de Big Data. Estos desafíos reflejan una progresión en la complejidad de las tareas y las herramientas utilizadas:

1. Familiarización con PySpark y Koalas.
2. Aplicación de algoritmos de machine learning con Spark ML.
3. Análisis avanzado utilizando APIs avanzadas de PySpark, relacionado con temas de investigación de tesis.

---

## **Justificación y Relevancia**
La capacidad de manejar grandes volúmenes de datos es fundamental en la era del Big Data. Este repositorio demuestra la relevancia de dominar herramientas como PySpark para abordar problemas reales en ciencia de datos. Los desafíos aquí documentados reflejan la importancia de traducir conceptos teóricos en aplicaciones prácticas y escalables, destacando la preparación de los estudiantes para enfrentar retos en la industria y la academia.

---

## **Contenido del Repositorio**
### **Challenge 1: Introducción a PySpark y Koalas**
- **Descripción**: Este primer desafío introduce a los estudiantes al uso de PySpark y Koalas para trabajar con grandes bases de datos, emulando la sintaxis de pandas en un entorno distribuido.
- **Objetivo**: Realizar un análisis exploratorio utilizando la **Global Terrorism Database** obtenida de Kaggle.
- **Actividades**:
  - Descargar y cargar los datos en Databricks.
  - Realizar transformaciones básicas con Koalas.
  - Crear visualizaciones simples usando PySpark y librerías de Python como Matplotlib y Plotly.
- **Métricas de evaluación**:
  - Corrección en la carga de datos (20%).
  - Uso adecuado de Koalas (30%).
  - Visualizaciones básicas (30%).
  - Limpieza y organización del código (20%).

---

### **Challenge 2: Modelado con Spark ML**
- **Descripción**: En este desafío, los estudiantes aplican técnicas de machine learning con Spark ML para resolver un problema de clasificación.
- **Objetivo**: Construir un modelo predictivo que clasifique la calidad del vino utilizando el **Wine Quality Dataset** del UCI Machine Learning Repository.
- **Actividades**:
  - Descargar y preparar los datos.
  - Entrenar un modelo de regresión logística con Spark ML.
  - Documentar los resultados en GitHub.
- **Métricas de evaluación**:
  - Limpieza y preparación de los datos (20%).
  - Selección adecuada del modelo (20%).
  - Exactitud y calidad de la evaluación (30%).
  - Documentación clara (30%).

---

#### **Challenge 3: Análisis Avanzado con PySpark y Visualización de Datos Categóricos**

- **Descripción**:  
  Este notebook se centra en el análisis y la visualización de una gran base de datos categóricos relacionados con la salud de pacientes, utilizando PySpark y herramientas avanzadas de visualización. El objetivo principal es identificar patrones relevantes en los datos, enfocándose en atributos que requieren atención médica. Los resultados son comunicados a través de gráficos detallados que facilitan la interpretación de los hallazgos.

- **Objetivo del Challenge**:  
  Desarrollar un análisis avanzado que permita:
  1. Procesar y entender grandes bases de datos categóricos.
  2. Implementar visualizaciones efectivas para comunicar resultados clave.
  3. Integrar herramientas de Big Data (PySpark) y librerías modernas de visualización como **Altair** para generar insights aplicados.

- **Actividades Realizadas**:
  - Análisis descriptivo para determinar:
    - Distribución de valores normales (`0`) y fuera de rango (`1`) en cada atributo.
    - Identificación de los atributos más relevantes para la atención médica (`'Flavonoides'`, `'Campo_magnetico_constante'`, `'Vit_E'`).
  - Exploración a nivel de paciente para identificar filas con más características fuera de rango.
  - Creación de gráficos interactivos y representaciones visuales usando **Altair**.
  - Optimización del código para trabajar con grandes volúmenes de datos.

- **Resultados Técnicos Esperados**:
  - Dominio de PySpark en el manejo de datos categóricos.
  - Capacidad para interpretar y visualizar datos a nivel macro (por atributo) y micro (por paciente).
  - Habilidad para utilizar herramientas de visualización avanzada para comunicar hallazgos complejos.

- **Impacto en el Alumno**:  
  Este challenge refuerza habilidades críticas en el análisis y visualización de datos categóricos, relevantes tanto en contextos académicos como en aplicaciones del mundo real. Los estudiantes desarrollan competencias avanzadas para trabajar con grandes volúmenes de datos categóricos en un entorno distribuido y comunicar resultados de manera efectiva.

---

Este README.md documenta no solo los contenidos, sino también el propósito de cada actividad, destacando su impacto en el aprendizaje y desarrollo profesional de nosotros como estudiantes. 

