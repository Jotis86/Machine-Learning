# 🏡 House Price Prediction Project

## 📖 Descripción
Proyecto educativo de **Machine Learning** para predecir precios de casas utilizando **regresión lineal**. El proyecto está estructurado en 3 notebooks educativos que cubren todo el pipeline de ML desde la limpieza de datos hasta la predicción final.

## 🎯 Objetivo
Construir un modelo de regresión lineal que prediga precios de casas basándose en:
- 💰 **Ingreso promedio del área**
- 🏠 **Edad promedio de las casas**
- 🚪 **Número de habitaciones**
- �️ **Número de dormitorios**
- 👥 **Población del área**

## � Estructura del Proyecto

### 📂 Notebooks Educativos
1. **01_Data_Cleaning_EDA.ipynb** - Limpieza y análisis exploratorio de datos
2. **02_Data_Visualization.ipynb** - Visualizaciones y correlaciones
3. **03_Machine_Learning.ipynb** - Modelo de ML completo

### � Datos
- **USA_Housing.csv** - Dataset original con información de 5000 casas

## 🛠️ Tecnologías Utilizadas
- **Python** - Lenguaje de programación
- **Pandas & NumPy** - Manipulación de datos
- **Matplotlib & Seaborn** - Visualizaciones
- **Scikit-learn** - Machine Learning

## 📊 Resultados del Modelo
- **Precisión (R²)**: 91.5% de la varianza explicada
- **Error promedio**: ±$100,000 aproximadamente
- **Sin overfitting**: Funciona bien en datos nuevos

## � Cómo Usar el Proyecto

### 1. Instalar dependencias
```bash
pip install -r requirements.txt
```

### 2. Ejecutar notebooks en orden
1. Abrir `01_Data_Cleaning_EDA.ipynb`
2. Continuar con `02_Data_Visualization.ipynb`
3. Finalizar con `03_Machine_Learning.ipynb`

### 3. Hacer predicciones
```python
# Ejemplo de predicción
precio = predecir_precio_casa(
    avg_area_income=70000,
    avg_area_house_age=5,
    avg_area_number_of_rooms=6,
    avg_area_number_of_bedrooms=3,
    area_population=35000
)
```

---


