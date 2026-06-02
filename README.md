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
  
* **`requirements.txt`**: Archivo de configuración con las librerías y versiones requeridas para garantizar la reproducibilidad del entorno.
* **`README.md`**: Descripción e instrucciones generales del proyecto.

---

## 📊 Dataset: Origen y Acceso
De acuerdo con las directrices de la cátedra para el manejo de archivos pesados, el dataset crudo (`listings.csv`) **no se encuentra subido a este repositorio**. 

* **Fuente oficial de los datos:** Puedes acceder y descargar el archivo directamente desde [Inside AirBnB - Madrid Data](https://insideairbnb.com/get-the-data/).

---

## ⚙️ Instrucciones de Ejecución (Reproducibilidad)

Para clonar este repositorio y ejecutar los modelos en tu entorno local, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Nicolascresp/Airbnb.git
   cd Airbnb
   ```

2. **Descargar el dataset:**
   - Descarga `listings.csv` desde [Inside AirBnB - Madrid](https://insideairbnb.com/get-the-data/)
   - Coloca el archivo en la raíz del repositorio

3. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ejecutar el notebook:**
   - Abre Jupyter Notebook o JupyterLab
   - Ejecuta `Tp_Airbnb_Madrid (1).ipynb` de punta a punta

---

## 📈 Métodos de Machine Learning Utilizados

- **Baseline:** Regresión Lineal
- **Modelos:** Random Forest, Gradient Boosting, KNN
- **Validación:** Cross-validation (CV)
- **Optimización:** Grid Search para tuning de hiperparámetros
- **Evaluación:** MAE, RMSE, R²

---

## 📝 Notas Importantes

- El notebook está ejecutado completamente y contiene todas las salidas (outputs)
- El dataset (`listings.csv`) debe descargarse por separado
- La reproducibilidad está garantizada mediante `requirements.txt` y el código sin dependencias externas
- Todos los integrantes del grupo comprenden cada sección del código y pueden defender el trabajo

---

## 📌 Versión de Entrega
- **Fecha:** Junio 2026
- **Estado:** Entrega completa (EDA + Modelado en un único archivo)
