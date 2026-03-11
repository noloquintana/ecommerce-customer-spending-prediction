# Español

# 📊 Predicción del Gasto Anual de Clientes de Ecommerce

## 📌 Descripción del Proyecto

Este proyecto aplica **técnicas de aprendizaje automático supervisado** para predecir el **gasto anual de clientes de una plataforma de comercio electrónico** a partir de su comportamiento dentro del sitio y la aplicación.

El objetivo es analizar los datos de interacción de los clientes y construir modelos predictivos capaces de estimar cuánto gastará un cliente durante un año.

El proyecto sigue un **pipeline completo de Machine Learning**, que incluye exploración de datos, entrenamiento de modelos, evaluación y comparación entre distintos algoritmos.

---

## 📂 Dataset

El conjunto de datos utilizado corresponde al dataset **Ecommerce Customers**, que contiene información sobre el comportamiento de clientes en una tienda online.

Las principales variables del dataset son:

- **Avg. Session Length** – Duración promedio de las sesiones del cliente
- **Time on App** – Tiempo que el cliente pasa en la aplicación móvil
- **Time on Website** – Tiempo que el cliente pasa en el sitio web
- **Length of Membership** – Tiempo que el cliente lleva siendo miembro
- **Yearly Amount Spent** – Gasto anual del cliente (variable objetivo)

La variable **Yearly Amount Spent** es un valor numérico continuo, por lo que el problema se aborda como un **problema de regresión**.

---

## ⚙️ Pipeline de Machine Learning

El proyecto implementa un flujo completo de aprendizaje supervisado:

1. Carga del dataset  
2. Exploración inicial de los datos (EDA)  
3. Selección de variables  
4. División de los datos en entrenamiento y prueba  
5. Entrenamiento de modelos  
6. Generación de predicciones  
7. Evaluación del desempeño  
8. Comparación entre modelos  

---

## 🤖 Modelos Implementados

Durante el proyecto se entrenaron y evaluaron distintos modelos de Machine Learning:

- Regresión Lineal
- Regresión Polinomial
- Ridge Regression
- Lasso Regression
- Gradient Boosting Regressor
- K-Nearest Neighbors (utilizado como comparación conceptual de clasificación)

---

## 📏 Métricas de Evaluación

Los modelos fueron evaluados utilizando métricas estándar para problemas de regresión:

- **MAE (Mean Absolute Error)** – Error absoluto medio
- **MSE (Mean Squared Error)** – Error cuadrático medio
- **RMSE (Root Mean Squared Error)** – Raíz del error cuadrático medio
- **R² (Coeficiente de determinación)**

Estas métricas permiten comparar la precisión de los distintos modelos entrenados.

---

## 📊 Resultados

La comparación de modelos muestra que **los modelos lineales presentan el mejor desempeño para este dataset**.

Los modelos regularizados, como **Ridge Regression**, obtuvieron el menor error de predicción, lo que indica que las relaciones entre las variables y el gasto anual de los clientes son principalmente **lineales**.

Modelos más complejos, como **Gradient Boosting**, no lograron mejorar el desempeño, probablemente debido al tamaño relativamente pequeño del dataset y a la estructura simple de las relaciones entre variables.

---

## 💡 Insights

El análisis de los coeficientes del modelo sugiere que:

**Length of Membership** es la variable con mayor influencia sobre el gasto anual de los clientes.

Esto indica que **la fidelización de clientes y la duración de la membresía podrían tener un impacto significativo en los ingresos del negocio**.

---

## 🛠 Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Estructura del Repositorio

```
ecommerce-customer-spending-prediction
│
├── proyecto_prediccion_gasto_clientes_ecommerce.ipynb
├── Ecommerce Customers.csv
└── README.md
```

---

## 🎓 Contexto Académico

Este proyecto fue desarrollado como parte del curso:

**Fundamentos de Ciencia de Datos**

El objetivo fue demostrar la correcta implementación de un **pipeline de Machine Learning supervisado**, la evaluación de distintos modelos y la justificación técnica de las decisiones tomadas durante el desarrollo del proyecto.

---

## 👤 Autor

**Manuel Quintana**  
Ingeniero Civil Industrial  
Estudiante de Ciencia de Datos

# English

# 📊 Ecommerce Customer Spending Prediction

## 📌 Project Overview

This project applies **supervised machine learning techniques** to predict the **annual spending of e-commerce customers** based on their behavior on the platform.

The goal is to analyze customer interaction data and build predictive models capable of estimating how much a customer is likely to spend per year.

The project follows a complete **Machine Learning pipeline**, including data exploration, preprocessing, model training, evaluation, and comparison of different algorithms.

---

## 📂 Dataset

The dataset used in this project is **Ecommerce Customers**, which contains behavioral data about customers of an online store.

Main variables include:

- **Avg. Session Length** – Average duration of customer sessions
- **Time on App** – Time spent using the mobile application
- **Time on Website** – Time spent browsing the website
- **Length of Membership** – How long the customer has been a member
- **Yearly Amount Spent** – Annual spending by the customer (target variable)

The target variable **Yearly Amount Spent** is continuous, making this a **regression problem**.

---

## ⚙️ Machine Learning Pipeline

The project implements a complete supervised ML workflow:

1. Data loading  
2. Exploratory Data Analysis (EDA)  
3. Feature selection  
4. Train/Test split  
5. Model training  
6. Prediction  
7. Model evaluation  
8. Model comparison  

---

## 🤖 Models Implemented

Several models were trained and evaluated:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Gradient Boosting Regressor
- K-Nearest Neighbors (for classification comparison)

---

## 📏 Evaluation Metrics

The models were evaluated using standard regression metrics:

- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **R² (Coefficient of Determination)**

These metrics allow comparing the prediction accuracy of each model.

---

## 📊 Results

A comparison of model performance shows that **linear models performed best for this dataset**.

Regularized models such as **Ridge Regression** achieved the lowest prediction error, suggesting that the relationship between the variables and customer spending is largely linear.

More complex models such as **Gradient Boosting** did not improve performance, likely due to the relatively small dataset and the strong linear relationships present in the data.

---

## 💡 Insights

Analysis of the regression coefficients suggests that:

**Length of Membership** has the strongest influence on yearly spending.

This insight suggests that **customer retention and long-term membership may significantly impact revenue** for the business.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure

```
ecommerce-customer-spending-prediction
│
├── proyecto_prediccion_gasto_clientes_ecommerce.ipynb
├── Ecommerce Customers.csv
└── README.md
```

---

## 🎓 Academic Context

This project was developed as part of the course:

**Fundamentos de Ciencia de Datos**

The objective was to demonstrate the correct implementation of a **supervised machine learning pipeline**, model evaluation, and technical reasoning behind algorithm selection and optimization.

---

## 👤 Author

**Manuel Quintana**  
Industrial Civil Engineer  
Data Science Student
