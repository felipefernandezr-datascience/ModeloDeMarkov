# 🦠 Simulación Epidemiológica con Cadenas de Markov

Modelo de propagación para una enfermedad infecciosa


Este repositorio contiene un notebook en Python que implementa una simulación epidemiológica utilizando un Modelo de Markov. El objetivo es mostrar cómo las cadenas de Markov permiten modelar la evolución de una enfermedad infecciosa a lo largo del tiempo, analizando el comportamiento de distintos estados de salud dentro de una población.

---

## 📌 Descripción del Proyecto

La simulación se basa en un modelo epidemiológico simplificado que divide la población en cinco estados:

- Sanos (S)
- Infección Leve (L)
- Infección Grave (G)
- Recuperados (R)
- Fallecidos (F)

Cada estado tiene asociadas probabilidades de transición que indican la posibilidad de cambiar de un estado a otro cada día. Utilizando estos valores, se construye una matriz de transición, que se aplica de forma iterativa al vector poblacional inicial.


El notebook permite:

- Definir la población base
- Simular la evolución durante un número determinado de días
- Visualizar gráficamente la progresión de cada estado
- Obtener un resumen de los resultados finales

---

## 🧮 Metodología

- Definición de probabilidades de transición: Se establecen probabilidades como: Sano → Leve, Leve → Grave, Leve → Recuperado, etc.
- Construcción de la matriz de transición: Esta matriz define cómo evoluciona cada estado en cada iteración del modelo.
- Vector inicial de población: Se parte de 1,000,000 personas sanas.
- Aplicación iterativa de la matriz (N días): Se calcula la evolución poblacional en cada uno de los estados.
- Visualización: Se genera una gráfica que muestra la evolución temporal.

---

## 📊 Resultados

La simulación permite observar cómo se distribuye la población a medida que avanza el tiempo, mostrando fenómenos como:

- El aumento de personas infectadas en etapas tempranas.
- La transición hacia estados graves o recuperación.
- El crecimiento acumulado de personas fallecidas.
- El equilibrio final al que tiende el modelo.

Estos resultados facilitan la comprensión del comportamiento dinámico de una epidemia bajo un enfoque probabilístico.

---

## 🎯 Objetivo Educativo

Este proyecto busca reforzar conceptos de:

- Cadenas de Markov
- Modelos epidemiológicos básicos
- Simulación estocástica
- Interpretación de datos
- Visualización de procesos dinámicos en Python

Su propósito es servir como herramienta de aprendizaje para estudiantes o personas interesadas en el modelado matemático de fenómenos reales.

---

## 🛠️ Tecnologías Utilizadas

- Python 3
- NumPy
- Matplotlib
- JupyterLab (Anaconda)

---

## 📁 Estructura del Repositorio

📦 ModeloDeMarkov
- ├── Modelo_de_Markov.ipynb     # Notebook principal
- └── README.md                  # Documentación del proyecto

--- 

👨‍💻 Autor
Felipe Fernández Rodriguez
Estudiante de Ingeniería en Software y Datos
Tecnólogo en Desarrollo de Software
Apasionado por la programación, análisis de datos y la creación de modelos computacionales.
