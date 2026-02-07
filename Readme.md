# Análisis Exploratorio de Datos para Decisiones Comerciales  
## Proyecto Módulo 4 – EDA

---

##  Descripción del proyecto
Este repositorio contiene el desarrollo completo del **Proyecto del Módulo 4: Análisis Exploratorio de Datos (EDA)**, cuyo objetivo es aplicar técnicas de análisis estadístico y visualización de datos para apoyar la toma de decisiones comerciales en un contexto de comercio electrónico.

El proyecto se desarrolla en el contexto de la empresa ficticia **ComercioYA**, enfocándose en el análisis de **precios y descuentos de productos e-commerce**, utilizando Python y librerías estándar de ciencia de datos.

---

##  Objetivo
Aplicar técnicas de **Análisis Exploratorio de Datos (EDA)** para:
- comprender la estructura y distribución de los datos,
- identificar patrones y relaciones entre variables,
- detectar valores atípicos,
- generar conclusiones útiles para la toma de decisiones comerciales.

---

## Estructura del repositorio
MODULO_4_EDA/
│
├── data/
│ └── Sports_ECommerce_Products_Data.csv
│
├── notebooks/
│ └── 01_EDA_ComercioYA.ipynb
│
├── figures/
│ ├── relacion_precios.png
│ └── distribucion_descuentos.png
│
├── report/
│
└── README.md

---

## Dataset
- **Fuente:** Kaggle  
- **Tipo:** Datos de productos de comercio electrónico  
- **Descripción:** Dataset que contiene información de productos, precios originales, precios con descuento y porcentaje de descuento.  
- **Uso en el proyecto:** Análisis de estrategias de precios y promociones en e-commerce.

---

## 🛠️ Herramientas y tecnologías utilizadas
- **Lenguaje:** Python 3.11  
- **Entorno:** Visual Studio Code + Jupyter Notebook  
- **Librerías:**
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - statsmodels  

---

## Contenidos desarrollados

El notebook `01_EDA_ComercioYA.ipynb` incluye las siguientes etapas:

### 🔹1 – Análisis Inicial de Datos (IDA)
- Carga del dataset
- Identificación de tipos de variables
- Revisión de calidad de datos
- Primeros hallazgos documentados

### 🔹2 – Estadística Descriptiva
- Medidas de tendencia central y dispersión
- Histogramas y boxplots
- Identificación de valores atípicos
- Interpretación de resultados

### 3 – Correlación
- Scatterplots
- Correlación de Pearson
- Heatmap de correlaciones
- Análisis e interpretación de relaciones entre variables
- Consideración de correlaciones no causales

### 🔹4 – Regresión Lineal
- Modelo de regresión lineal simple
- Uso de `statsmodels`
- Interpretación de coeficientes
- Evaluación del modelo (R², MSE, MAE)
- Visualización del modelo

### 5 – Visualización Avanzada
- Pairplot
- Violinplot
- Jointplot
- Análisis visual multivariado

### 🔹 6 – Visualización Final y Conclusiones
- Gráficos finales exportables
- Conclusiones generales del proyecto
- Cierre metodológico del análisis

---

##  Resultados principales
- Se identificó una **relación consistente** entre el precio original y el precio con descuento.
- El porcentaje de descuento presenta **alta variabilidad**, lo que sugiere estrategias comerciales diferenciadas.
- El análisis exploratorio demuestra el valor del EDA como apoyo a la **toma de decisiones comerciales** en e-commerce.

---

##  Entregables
- Notebook Jupyter con el desarrollo completo del análisis
- Visualizaciones exportadas en formato PNG
- Informe técnico (carpeta `report/`)
- Repositorio GitHub documentado

---

## Autora
**Carolina Tapia Bahamonde**  
Ingeniera Civil en Informática  
Proyecto académico – Ciencia de Datos



