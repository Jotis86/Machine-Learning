# 🧠 Análisis de Datos y Machine Learning para Alzheimer

## 📋 Descripción del Proyecto

Este proyecto utiliza **ciencia de datos** y **machine learning** para analizar factores relacionados con el Alzheimer y desarrollar un modelo predictivo para apoyo al diagnóstico. 

### 🎯 Objetivos Principales

- **Análisis exploratorio** completo de datos de pacientes con/sin Alzheimer
- **Identificación de patrones** y factores de riesgo asociados
- **Desarrollo de modelos predictivos** usando Random Forest

## 🗂️ Estructura del Proyecto

```
Alzheimer/
│
├── Data/
│   ├── alzheimers_disease_data.csv          # Dataset original
│   └── alzheimers_disease_data_cleaned.csv  # Dataset procesado
│
├── Notebooks/
│   ├── 01_data_exploratory.ipynb           # Análisis exploratorio de datos
│   ├── 02_data_visualization.ipynb         # Visualización y gráficos
│   ├── 03_data_statistics.ipynb            # Análisis estadístico
│   └── 04_Machine_Learning.ipynb           # Modelado con ML
│
├── README.md                                # Este archivo
└── requirements.txt                         # Dependencias del proyecto
```

## 📊 Contenido de los Notebooks

### 📈 01_data_exploratory.ipynb
**Análisis Exploratorio de Datos (EDA)**
- Carga y exploración inicial del dataset
- Identificación de valores faltantes y duplicados
- Detección de outliers usando método IQR
- Transformación de variables numéricas a categóricas
- Preparación de datos para análisis posteriores

**Insights clave:**
- Dataset limpio sin valores faltantes
- Variables transformadas a rangos clínicamente relevantes
- Identificación de outliers en variables específicas

### 📊 02_data_visualization.ipynb
**Visualización de Datos**
- Distribución de diagnósticos en la población
- Análisis por grupos etarios y factores demográficos
- Relación entre estilo de vida y Alzheimer
- Correlaciones entre variables clínicas
- Patrones en síntomas y biomarcadores

**Visualizaciones incluidas:**
- Countplots por diagnosis y factores demográficos
- Análisis de BMI, actividad física, calidad de sueño
- Mapas de calor de correlaciones
- Distribuciones por género y etnia

### 🔬 03_data_statistics.ipynb
**Análisis Estadístico Riguroso**
- Estadísticas descriptivas avanzadas
- Análisis de distribuciones (skewness, kurtosis)
- Correlaciones múltiples (Pearson, Spearman, Kendall)
- Pruebas de hipótesis (t-test, Chi-cuadrado)
- Medidas de variabilidad

**Técnicas aplicadas:**
- Análisis de normalidad de distribuciones
- Pruebas de independencia entre variables categóricas
- Comparación de medias entre grupos
- Cuantificación de relaciones estadísticas

### 🤖 04_Machine_Learning.ipynb
**Modelado Predictivo con Random Forest**
- Pipeline completo de machine learning
- Selección automática de características
- Optimización de hiperparámetros con GridSearch
- Evaluación exhaustiva del modelo
- Interpretación de importancia de características

**Componentes técnicos:**
- Pipeline con SelectKBest y RandomForestClassifier
- Validación cruzada para robustez
- Métricas médicas (precisión, recall, F1-score)
- Curva ROC y análisis de rendimiento
- Interpretabilidad para uso clínico


### 🧮 Técnicas Utilizadas

#### **Análisis Exploratorio:**
- Estadística descriptiva completa
- Detección de outliers (método IQR)
- Transformaciones categóricas

#### **Análisis Estadístico:**
- Pruebas de normalidad
- Correlaciones múltiples
- Pruebas de hipótesis (t-test, χ²)
- Medidas de variabilidad

#### **Machine Learning:**
- Random Forest con optimización
- Selección automática de features
- Validación cruzada (5-fold)
- Métricas de evaluación médica


## 🛠️ Instalación y Uso

### Prerrequisitos
- Python 3.8 o superior
- Jupyter Notebook o JupyterLab
- Librerías especificadas en `requirements.txt`

### Instalación
```bash
# Clonar o descargar el proyecto
cd Alzheimer

# Instalar dependencias
pip install -r requirements.txt

# Iniciar Jupyter
jupyter notebook
```

### Uso
1. Ejecutar notebooks en orden secuencial (01 → 02 → 03 → 04)
2. Cada notebook está documentado con explicaciones educativas
3. Los resultados se guardan automáticamente entre notebooks


---
