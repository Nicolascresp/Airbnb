# 🇪🇸 Analítica de Datos - Predicción de Precios de AirBnB en Madrid

## 👥 Integrantes
* Nicolás Crespo
* Nicolás Villalonga
* Joaquín García

---

## 📌 Descripción del Proyecto
Este proyecto integra un pipeline completo de Ciencia de Datos y Machine Learning Supervisado utilizando el dataset público de **Inside AirBnB para la ciudad de Madrid**. 

El objetivo principal es estructurar un modelo predictivo capaz de **estimar el precio por noche de los alojamientos** a partir de sus características estructurales, geográficas y de reputación.

**Contenido:** El proyecto incluye **EDA, preparación de datos, feature engineering, reducción de dimensionalidad y modelado** en un único notebook ejecutable de punta a punta.

---

## 🛠️ Estructura del Repositorio
* **`Tp_Airbnb_Madrid (1).ipynb`**: Notebook único que contiene:
  - **Sección 1:** Análisis exploratorio (EDA), limpieza y preprocesamiento
  - **Sección 2:** Feature engineering, reducción de dimensionalidad
  - **Sección 3:** Modelado, validación cruzada, tuning de hiperparámetros y resultados finales
  
* **`listings.csv`**: Dataset crudo con 25,000 observaciones de Airbnb Madrid (ya incluido en el repositorio)
* **`requirements.txt`**: Archivo de configuración con las librerías y versiones requeridas para garantizar la reproducibilidad del entorno.
* **`README.md`**: Descripción e instrucciones generales del proyecto.

---

## 📊 Dataset: Origen y Acceso
El dataset crudo (`listings.csv`) **está incluido en este repositorio**, descargado desde [Inside AirBnB - Madrid Data](https://insideairbnb.com/get-the-data/).

**Tamaño:** 4.3 MB | **Observaciones:** 25,000 | **Variables:** 18

---

## ⚙️ Instrucciones de Ejecución (Reproducibilidad)

Para clonar este repositorio y ejecutar los modelos en tu entorno local, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Nicolascresp/Airbnb.git
   cd Airbnb
   ```

2. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutar el notebook:**
   ```bash
   jupyter notebook "Tp_Airbnb_Madrid (1).ipynb"
   ```
   - O abre JupyterLab y ejecuta el notebook de punta a punta

---

## 📈 Métodos de Machine Learning Utilizados

- **Baseline:** Regresión Lineal
- **Modelos:** Random Forest, Gradient Boosting, KNN
- **Validación:** Cross-validation (CV)
- **Optimización:** Grid Search para tuning de hiperparámetros
- **Evaluación:** MAE, RMSE, R²

---

## 📝 Reproducibilidad

✅ **El proyecto es completamente reproducible:**
- ✅ Dataset incluido en el repositorio (`listings.csv`)
- ✅ Archivo `requirements.txt` con versiones pinned de todas las dependencias
- ✅ Notebook ejecutado de punta a punta sin dependencias externas
- ✅ Rutas relativas (sin rutas hardcodeadas)
- ✅ Código sin dependencias de archivos generados o variables globales

**Para reproducir:** Solo necesitas clonar, instalar deps y ejecutar el notebook.

---

## 📌 Versión de Entrega
- **Fecha:** Junio 2026
- **Estado:** Entrega completa (EDA + Modelado en un único archivo)
- **Reproducibilidad:** 100% garantizada
