# 🚢 Análisis del Dataset del Titanic

Este proyecto es un análisis de datos exploratorio (EDA) del famoso dataset del Titanic, enfocado en entender los factores que influyeron en la supervivencia de los pasajeros.

## 💾 Dataset

Se utiliza el dataset público del Titanic que contiene información sobre los 891 pasajeros a bordo. Las columnas principales incluyen:

- **PassengerId**: Identificador único del pasajero
- **Survived**: Supervivencia (0 = No, 1 = Sí)  
- **Pclass**: Clase del ticket (1 = Primera, 2 = Segunda, 3 = Tercera)
- **Name**: Nombre del pasajero
- **Sex**: Sexo del pasajero
- **Age**: Edad del pasajero
- **SibSp**: Número de hermanos/cónyuges a bordo
- **Parch**: Número de padres/hijos a bordo
- **Ticket**: Número del ticket
- **Fare**: Precio del pasaje
- **Cabin**: Número de cabina
- **Embarked**: Puerto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton)

## 📈 Análisis y Visualizaciones Realizadas

A lo largo del proyecto, se han realizado los siguientes análisis:

### 1. Distribución de Precios de Pasajes
Se analizó la distribución de los costos de los tickets para entender la estructura económica del Titanic.

**Visualización**: Histograma general de precios y histogramas separados por clase de pasaje, incluyendo líneas de precio promedio por clase.

### 2. Análisis de Precios por Clase y Puerto de Embarque
Se investigó cómo variaban los precios según la clase del pasajero y su puerto de embarque.

**Visualización**: Gráfico de barras agrupado mostrando el precio promedio por clase y ciudad de embarque.

### 3. Clasificación de Pasajeros
Se crearon nuevas categorías para analizar mejor los datos:
- **Classification**: Si la edad es conocida o desconocida
- **Who**: Clasificación en niño (< 18 años), hombre o mujer (≥ 18 años)

### 4. Análisis de Supervivencia
Se examinaron las tasas de supervivencia según diferentes variables demográficas.

**Visualizaciones**: 
- Gráfico de barras de supervivientes vs no supervivientes
- Análisis de supervivencia por género con porcentajes

### 5. Distribución Demográfica
**Visualización**: Gráfico de torta mostrando la distribución de pasajeros por clase.

### 6. Supervivencia por Grupos de Edad
**Visualización**: Gráfico de líneas mostrando cómo la tasa de supervivencia varía según los grupos de edad.

### 7. Dashboard Integral
**Visualización**: Panel con 4 gráficos combinados:
- Histograma de edades por supervivencia
- Barras de supervivencia por clase  
- Dispersión edad vs precio coloreado por supervivencia
- Boxplot de distribución de precios por clase

## 🔍 Hallazgos Principales

- La **clase del pasaje** fue un factor determinante en la supervivencia
- Las **mujeres** tuvieron tasas de supervivencia significativamente más altas que los hombres
- Los **niños** también mostraron mejores tasas de supervivencia
- Los **precios de los pasajes** variaron considerablemente entre clases, con la primera clase pagando hasta 10 veces más
- El **puerto de embarque** también influyó en el precio promedio del pasaje

## 🛠️ Herramientas Utilizadas

- **Lenguaje**: Python
- **Librerías**:
  - **Pandas** para la carga, limpieza y manipulación de datos
  - **Matplotlib** para la generación de visualizaciones
  - **NumPy** para operaciones matemáticas y manejo de arrays
- **Entorno**: Jupyter Notebook
- **Control de Versiones**: Git y GitHub

## 📁 Estructura del Proyecto

```
titanic_add/
│
├── analisis_dD_titanic.ipynb   # Notebook principal con el análisis
├── titanic.csv               # Dataset del Titanic
└── README.md                 # Este archivo
```

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio
2. Asegúrate de tener Python instalado con las librerías necesarias (pandas, matplotlib, numpy)
3. Abre el archivo `analisis_dD_titanic.ipynb` en Jupyter Notebook
4. Ejecuta las celdas secuencialmente para reproducir el análisis

## 📊 Resultados

Este análisis proporciona una comprensión profunda de los factores que determinaron la supervivencia en el Titanic, demostrando cómo las variables socioeconómicas y demográficas influyeron en las posibilidades de supervivencia durante esta tragedia histórica.