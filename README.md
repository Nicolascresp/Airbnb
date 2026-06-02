# 🇪🇸 Analítica de Datos - Predicción de Precios de AirBnB en Madrid

## 👥 Integrantes
* Nicolás Crespo
* Nicolás Villalonga
* Joaquín García

---

## 📌 Descripción del Proyecto
Este proyecto integra un pipeline completo de Ciencia de Datos y Machine Learning Supervisado utilizando el dataset público de **Inside AirBnB para la ciudad de Madrid**. 

El objetivo principal es estructurar un modelo predictivo capaz de **estimar el precio por noche de los alojamientos** a partir de sus características estructurales, geográficas y de reputación, aportando conocimiento accionable para la optimización de decisiones en el sector turístico y de hospitalidad.

---

## 🛠️ Estructura del Repositorio
* **`notebooks/`**: Contiene los cuadernos de desarrollo ejecutados de punta a punta.
  * `Entrega1_EDA_Limpieza.ipynb`: Análisis exploratorio univariado/bivariado, imputación de datos faltantes, tratamiento de outliers mediante el método IQR, y modelado con Baseline (Regresión Lineal), KNN Regressor y Random Forest utilizando validación cruzada y optimización de hiperparámetros.
  * `Entrega2_Modelado_Conclusiones.ipynb`: Resultados finales y conclusiones del modelado.
* **`requierments.txt`**: Archivo de configuración con las librerías y versiones requeridas para garantizar la reproducibilidad del entorno.
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
   git clone [https://github.com/](https://github.com/)[Tu-Usuario-De-GitHub]/[Nombre-Del-Repositorio].git
   cd [Nombre-Del-Repositorio]