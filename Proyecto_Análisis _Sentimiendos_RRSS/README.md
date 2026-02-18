# 🎭 Análisis de Sentimientos en Redes Sociales

Un proyecto completo de Machine Learning para análizar sentimientos en posts de redes sociales utilizando técnicas de procesamiento de lenguaje natural (NLP) y algoritmos de clasificación.

## 📊 Descripción del Proyecto

Este proyecto implementa un sistema completo de análisis de sentimientos que:
- Procesa y limpia datos de texto de redes sociales
- Realiza análisis exploratorio de datos (EDA) comprehensivo
- Entrena y compara múltiples modelos de Machine Learning
- Proporciona visualizaciones claras e interpretables
- Incluye un pipeline completo para predicciones en tiempo real

## 🎯 Características Principales

### ✨ Análisis Exploratorio de Datos (EDA)
- **Simplificación inteligente de sentimientos**: Reduce automáticamente 279+ categorías a 4 principales (Positive, Negative, Neutral, Mixed)
- **Visualizaciones optimizadas**: Gráficos legibles con matplotlib y seaborn
- **Análisis multi-dimensional**: 
  - Distribución temporal y geográfica
  - Análisis por plataforma (Twitter, Instagram, Facebook)
  - Métricas de engagement (likes, retweets)
  - Análisis de hashtags y palabras frecuentes

### 🤖 Machine Learning
- **3 algoritmos optimizados**:
  - Regresión Logística con TF-IDF
  - Naive Bayes con Count Vectorizer  
  - Random Forest con TF-IDF
- **Preprocesamiento robusto**: Tokenización, lemmatización, eliminación de stopwords
- **Ingeniería de features**: Características de texto, metadatos y análisis VADER
- **Evaluación comprehensiva**: Cross-validation, matrices de confusión, métricas detalladas

### 📈 Resultados y Visualización
- Comparación visual de modelos
- Análisis de errores y ejemplos
- Pipeline de predicción completo
- Reportes detallados de rendimiento

```

## 🚀 Instalación y Configuración

### 1. Clonar el Repositorio
```bash
git clone <url-del-repositorio>
cd "Social Media Sentiments Analysis"
```

### 2. Crear Entorno Virtual (Recomendado)
```bash
# Con conda
conda create -n sentiment-analysis python=3.9
conda activate sentiment-analysis

# O con venv
python -m venv sentiment-env
# Windows
sentiment-env\Scripts\activate
# macOS/Linux
source sentiment-env/bin/activate
```

### 3. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 4. Descargar Recursos NLTK
```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('vader_lexicon')
nltk.download('omw-1.4')
```

## 📖 Uso del Proyecto

### 🔍 1. Análisis Exploratorio de Datos
```bash
jupyter notebook "notebooks/01_EDA_Limpieza_Sentimientos_Fixed.ipynb"
```

**Funcionalidades principales:**
- Carga y limpieza automática de datos
- Simplificación inteligente de sentimientos (279 → 4 categorías)
- Visualizaciones interactivas y análisis temporal
- Top 5 países y plataformas más activas
- Análisis de hashtags y palabras frecuentes

### 🤖 2. Entrenamiento de Modelos ML
```bash
jupyter notebook "notebooks/02_ML_Entrenamiento_Modelos.ipynb"
```

**Funcionalidades principales:**
- Preprocesamiento robusto de texto con manejo de errores
- Entrenamiento y comparación de 3 algoritmos principales
- Optimización automática de hiperparámetros
- Análisis detallado de errores y rendimiento
- Pipeline completo para predicciones nuevas


---

