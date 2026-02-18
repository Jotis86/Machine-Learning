# 🌡️ Proyecto de Análisis y Predicción del Clima

Este proyecto realiza un análisis de datos climáticos utilizando técnicas de Machine Learning y análisis de series temporales para predecir la temperatura.

## 📊 Descripción del Proyecto

El proyecto consiste en tres notebooks principales que cubren todo el pipeline de análisis de datos:

1. **📋 Análisis Exploratorio (EDA)** - Exploración y comprensión de los datos
2. **📈 Visualizaciones** - Gráficos y análisis visual de patrones
3. **🤖 Machine Learning** - Modelos predictivos para series temporales

## 🗂️ Estructura del Proyecto

```
Clima/
├── data/
│   ├── train.csv          # Datos de entrenamiento (2013-2016)
│   └── test.csv           # Datos de prueba (2017)
├── notebooks/
│   ├── 01_EDA.ipynb              # Análisis Exploratorio de Datos
│   ├── 02_Visualizaciones.ipynb  # Visualizaciones y Gráficos
│   └── 03_Machine_Learning.ipynb # Modelos de ML y Series Temporales
├── README.md
└── requirements.txt
```

## 📈 Variables del Dataset

El dataset contiene las siguientes variables climáticas:

- **`date`**: Fecha (formato YYYY-MM-DD)
- **`meantemp`**: Temperatura media diaria (°C) - Variable objetivo
- **`humidity`**: Humedad relativa (%)
- **`wind_speed`**: Velocidad del viento
- **`meanpressure`**: Presión atmosférica media

## 🔍 Análisis Realizados

### 01_EDA.ipynb - Análisis Exploratorio
- ✅ Carga y exploración inicial de datos
- ✅ Análisis de estructura y tipos de datos
- ✅ Estadísticas descriptivas completas
- ✅ Detección de outliers (método IQR)
- ✅ Análisis de correlaciones entre variables
- ✅ Análisis temporal por años y meses
- ✅ Identificación de valores faltantes

### 02_Visualizaciones.ipynb - Análisis Visual
- 📊 Series temporales de todas las variables
- 🌡️ Análisis estacional con patrones mensuales
- 📈 Distribuciones e histogramas con curvas de densidad
- 🔗 Matriz de correlación interactiva
- 🔍 Análisis visual de outliers
- ⚖️ Comparación entre datos de entrenamiento y prueba
- 🎯 Resumen visual de insights principales

### 03_Machine_Learning.ipynb - Modelos Predictivos
- 🤖 **Modelos implementados:**
  - Modelo Naive (baseline)
  - Regresión Lineal y Ridge
  - Random Forest y Gradient Boosting
  - ARIMA para series temporales
- ⚙️ **Técnicas aplicadas:**
  - Feature engineering temporal (lags, rolling means)
  - Análisis de estacionaridad
  - Validación temporal
  - Análisis de importancia de características
- 📊 **Evaluación rigurosa** con métricas (RMSE, MAE, R²)


## 💡 Insights Clave

1. **🌡️ Temperatura altamente predictible** usando variables climáticas múltiples
2. **📊 Random Forest superior** a ARIMA para este tipo de datos
3. **🔗 Variables correlacionadas** (humedad, presión, viento) son cruciales
4. **📅 Características temporales** (lags, promedios móviles) mejoran la predicción
5. **🌍 Patrones estacionales** claramente identificables

## 🚀 Instalación y Uso

### 1. Clonar/Descargar el proyecto
```bash
# Descargar los archivos en una carpeta local
```

### 2. Instalar dependencias
```bash
pip install -r requirements.txt
```

### 3. Ejecutar los notebooks
```bash
jupyter lab
# o
jupyter notebook
```

### 4. Orden de ejecución recomendado:
1. `01_EDA.ipynb` - Comprender los datos
2. `02_Visualizaciones.ipynb` - Explorar patrones visuales  
3. `03_Machine_Learning.ipynb` - Entrenar modelos predictivos


---

*Desarrollado con ❤️ para análisis de datos climáticos*