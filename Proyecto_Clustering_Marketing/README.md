# 📊 Marketing Customer Clustering Analysis

Este proyecto implementa un análisis completo de clustering de clientes usando datos de marketing para segmentar la base de clientes y generar insights accionables.

## 🎯 Objetivo

Segmentar clientes basándose en sus patrones de compra, características demográficas y comportamiento para:
- Identificar grupos de clientes con características similares
- Desarrollar estrategias de marketing personalizadas
- Optimizar campañas y esfuerzos de retención
- Entender mejor el comportamiento del cliente

## 📁 Estructura del Proyecto

```
Marketing/
├── data/
│   ├── marketing_campaign.csv              # Datos originales
│   ├── marketing_campaign_cleaned.csv      # Datos limpios
│   ├── marketing_campaign_with_clusters.csv # Datos con clusters asignados
│   ├── cluster_profiles.csv                # Perfiles de clusters
│   └── clustering_model_info.json          # Información del modelo
├── notebooks/
│   ├── data_cleaning.ipynb                 # Limpieza y preprocesamiento
│   ├── data_visualization.ipynb            # Visualizaciones exploratorias
│   └── clustering_model.ipynb              # Modelo de clustering
├── README.md
└── requirements.txt
```

## 🚀 Instalación y Configuración

### Prerequisitos
- Python 3.8 o superior
- Jupyter Notebook o JupyterLab

### Instalación de Dependencias

1. Clona o descarga este proyecto
2. Instala las dependencias requeridas:

```bash
pip install -r requirements.txt
```

## 📖 Uso

### 1. Limpieza de Datos
Ejecuta el notebook `notebooks/data_cleaning.ipynb` para:
- Cargar y explorar los datos originales
- Limpiar valores faltantes y duplicados
- Crear características derivadas
- Generar el dataset limpio

### 2. Análisis de Clustering
Ejecuta el notebook `notebooks/clustering_model.ipynb` para:
- Preparar datos para clustering
- Determinar el número óptimo de clusters
- Implementar algoritmos K-Means y Clustering Jerárquico
- Analizar y visualizar los resultados
- Generar perfiles de segmentos de clientes

### 3. Visualización (Opcional)
Usa `notebooks/data_visualization.ipynb` para exploraciones adicionales

## 📊 Características del Análisis

### Algoritmos Implementados
- **K-Means Clustering**: Rápido y eficiente para clusters esféricos
- **Clustering Jerárquico**: Más robusto para formas irregulares
- **Análisis PCA**: Visualización en 2D de los clusters

### Métricas de Evaluación
- **Método del Codo**: Para determinar número óptimo de clusters
- **Análisis de Silhouette**: Para evaluar calidad del clustering
- **Dendrograma**: Para clustering jerárquico

### Características Utilizadas
- Datos demográficos (edad, ingresos, hijos)
- Patrones de gasto por categoría de producto
- Comportamiento de compra (frecuencia, recencia)
- Canales de compra preferidos

## 📈 Resultados

El análisis genera:

### Segmentos de Clientes
- **High Spenders**: Clientes de alto valor con gran potencial
- **Medium Spenders**: Clientes regulares con potencial de crecimiento
- **Low Spenders**: Clientes que requieren estrategias de activación

### Insights Clave
- Distribución de clientes por segmento
- Características distintivas de cada grupo
- Patrones de comportamiento de compra
- Recomendaciones de marketing

### Archivos de Salida
- `marketing_campaign_with_clusters.csv`: Dataset con clusters asignados
- `cluster_profiles.csv`: Perfiles estadísticos por cluster
- `clustering_model_info.json`: Metadatos del modelo

## 🎨 Visualizaciones

- **Análisis PCA**: Visualización 2D de clusters
- **Heatmaps**: Comparación de características por cluster
- **Box Plots**: Distribución de métricas clave
- **Análisis de Silhouette**: Calidad del clustering
