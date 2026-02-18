# 🎬 Sistema de Recomendaciones de Películas con KNN

Un sistema completo de análisis y recomendación de películas utilizando K-Nearest Neighbors (KNN) y análisis exploratorio de datos.

## 📋 Descripción

Este proyecto implementa un sistema de recomendaciones de películas basado en contenido que utiliza machine learning para encontrar películas similares. El sistema incluye análisis exploratorio completo, visualizaciones interactivas y un modelo de recomendaciones mejorado con enfoque híbrido.

## 🎯 Características Principales

### ✅ **Sistema de Recomendaciones Avanzado**
- **Algoritmo KNN mejorado** con filtrado híbrido
- **Pesos balanceados** para diferentes características
- **Filtrado por géneros** para mayor precisión
- **Búsqueda por título parcial** (flexible)

### 📊 **Análisis Completo**
- **EDA (Análisis Exploratorio)** detallado del dataset
- **Visualizaciones interactivas** con matplotlib y seaborn
- **Detección de outliers** y patrones
- **Análisis de correlaciones** entre variables

### 🔧 **Features Engineeradas**
- One-hot encoding para géneros
- Normalización de características numéricas
- Encoding de directores más populares
- Feature de popularidad (rating × log(votos))
- Agrupación por décadas

## 📁 Estructura del Proyecto

```
Movies/
├── data/
│   └── movie.csv                    # Dataset de películas
├── notebooks/
│   ├── EDA.ipynb                   # Análisis Exploratorio de Datos
│   ├── Visualizaciones.ipynb       # Visualizaciones del dataset
│   └── Machine_Learning.ipynb      # Sistema de recomendaciones KNN
├── README.md                       # Documentación del proyecto
└── requirements.txt               # Dependencias del proyecto
```

## 🚀 Instalación y Uso

### 1. **Instalar Dependencias**

```bash
pip install -r requirements.txt
```

### 2. **Ejecutar los Notebooks**

#### **Análisis Exploratorio**
```bash
jupyter notebook notebooks/EDA.ipynb
```
- Carga y exploración inicial del dataset
- Análisis estadístico descriptivo
- Detección de outliers y valores nulos

#### **Visualizaciones**
```bash
jupyter notebook notebooks/Visualizaciones.ipynb
```
- Distribuciones de variables principales
- Análisis de géneros y tendencias temporales
- Matrices de correlación y scatter plots

#### **Sistema de Recomendaciones**
```bash
jupyter notebook notebooks/Machine_Learning.ipynb
```
- Feature engineering completo
- Entrenamiento del modelo KNN
- Sistema de recomendaciones interactivo

### 3. **Uso del Sistema de Recomendaciones**

```python
# Función principal para obtener recomendaciones
recommend_movies("Guardians of the Galaxy", n_recommendations=5)

# Explorar por género
explore_movies_by_genre("Action", n_movies=10)

# Explorar por director
explore_movies_by_director("Christopher Nolan", n_movies=5)
```

## 🎬 Ejemplos de Uso

### **Obtener Recomendaciones**
```python
# Recomendaciones para una película de ciencia ficción
recommend_movies("Guardians of the Galaxy")

# Recomendaciones para un musical
recommend_movies("La La Land")

# Recomendaciones para un thriller
recommend_movies("Split")
```

### **Explorar el Dataset**
```python
# Top películas de acción
explore_movies_by_genre("Action", n_movies=8)

# Películas de Ridley Scott
explore_movies_by_director("Ridley Scott")

# Buscar películas por título
find_movie_by_title("Batman")
```

---

