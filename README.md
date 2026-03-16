## 🚗 Análisis Exploratorio de Fraude en Seguros
## 📄 Descripción del Proyecto

Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) sobre un dataset de fraude en seguros con el objetivo de comprender su estructura, evaluar la calidad de los datos e identificar patrones relevantes relacionados con posibles casos de fraude.

El análisis examina características de las pólizas, información del conductor, tipo de vehículo y registros de fraude. Los resultados obtenidos sirven como base para futuros modelos predictivos de detección de fraude.

El dataset analizado contiene 15,420 registros y 34 variables, combinando datos numéricos y categóricos relacionados con pólizas de seguro y siniestros.

## 🔑 Puntos Clave del Proyecto

· El dataset contiene 15,420 registros y 34 variables.

· Se identificaron valores faltantes en las columnas:
MaritalStatus y AccidentArea

· No se detectaron registros duplicados, lo que indica una buena consistencia estructural.

· Se identificaron valores atípicos (outliers) principalmente en:
Deductible y DriverRating

· La distribución de edades muestra que la mayoría de asegurados se encuentran entre 25 y 50 años, rango típico de población económicamente activa.

· Los accidentes se concentran mayormente en zonas urbanas, lo cual es consistente con una mayor densidad vehicular.

· La calidad general de los datos es adecuada para análisis y modelado, aunque se recomienda tratar valores nulos y validar outliers.

## 🛠️ Herramientas Utilizadas

· Python

· Pandas – Manipulación y análisis de datos

· NumPy – Operaciones numéricas

· Matplotlib – Visualización de datos

· Seaborn – Análisis visual y gráficos estadísticos

· Jupyter Notebook – Desarrollo del análisis

## 📊 Estrategias Propuestas

A partir del análisis exploratorio realizado, se proponen las siguientes estrategias para mejorar el análisis y el desarrollo de modelos predictivos:

1. Tratamiento de valores faltantes

· Imputar valores en MaritalStatus y AccidentArea mediante técnicas como:
· Moda y Agrupación por variables relacionadas

2. Manejo de valores atípicos

· Validar los outliers en Deductible y DriverRating para determinar si corresponden a casos reales o errores de registro.

· Aplicar técnicas de normalización o transformación si afectan el desempeño de modelos predictivos.

3. Preparación para modelos de detección de fraude

· Codificación de variables categóricas (One-Hot Encoding o Label Encoding).

· Escalado de variables numéricas.

4. Desarrollo de modelos de Machine Learning

· Implementar modelos de clasificación para detectar fraude, como:

· Logistic Regression

· Random Forest

· Gradient Boosting
