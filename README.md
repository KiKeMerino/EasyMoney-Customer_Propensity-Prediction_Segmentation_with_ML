# EasyMoney: Optimización de Marketing Bancario con IA

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-15B5B0?style=for-the-badge&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Este proyecto es una solución end-to-end de Data Science diseñada para optimizar la rentabilidad de las campañas de marketing de la entidad financiera "easyMoney". Mediante técnicas avanzadas de Machine Learning (clasificación y clustering), el sistema predice la propensión de compra de productos financieros y segmenta a los clientes para personalizar la oferta, logrando un ROI significativamente superior al de las campañas tradicionales.

## 🎯 Objetivos del Proyecto

1. **Predicción de Propensión a Compra:** Identificar qué clientes tienen mayor probabilidad de contratar productos de alto valor (Planes de Pensiones, Depósitos a Largo Plazo).
2. **Segmentación de Clientes:** Agrupar a la base de clientes en perfiles homogéneos para diseñar estrategias de comunicación y venta cruzada (Cross-Selling).
3. **Maximización del ROI:** Demostrar el impacto económico de usar modelos predictivos frente a estrategias de marketing masivas.

## 🛠️ Metodología y Estructura del Código

El proyecto se divide en 4 etapas principales:

### 1. Ingeniería de Datos y Limpieza (1-data_cleaning.ipynb)
Procesamiento de un dataset con más de 5.9 millones de registros.
* Limpieza de nulos en variables clave como canal de entrada y segmento.
* Optimización de tipos de datos para manejo eficiente de memoria.

### 2. Modelado Predictivo - Propensión (2-classification_model.ipynb)
Desarrollo de modelos de clasificación supervisada para predecir la contratación.
* **Algoritmos:** Entrenamiento y evaluación de RandomForest y XGBoost.
* **Métricas:** AUC-ROC de 0.93 para el modelo de Depósitos a Largo Plazo.
* **Insights:** Identificación de variables críticas como la edad y el canal de captación específico.

### 3. Segmentación de Clientes - Clustering (3-clustering.ipynb)
Uso de K-Means para segmentar la cartera basándose en comportamiento transaccional y perfil sociodemográfico.
* Se identificaron 6 clústeres estratégicos (ej. Clientes Leales vs. Inactivos).
* Definición de planes de acción específicos para cada segmento.

### 4. Caso de Uso y ROI (4-use_case.ipynb)
Simulación de una campaña de marketing real comparando IA vs. Tradicional.
* **Resultado:** La campaña dirigida con ML capturó ~27.3M € frente a los ~1.2M € de la campaña tradicional, optimizando el presupuesto de contacto.

## 📊 Resultados Clave

* **AUC-ROC:** 0.93 (Excelente capacidad predictiva).
* **Eficiencia:** ROI más de 20 veces superior al marketing tradicional.
* **Impacto:** Mejora directa en el EBITDA al reducir costes de captación.

## 🚀 Cómo ejecutar este proyecto

1. Clonar el repositorio:
   git clone https://github.com/tu-usuario/nombre-del-repo.git

2. Instalar dependencias:
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn

3. Ejecutar los Notebooks en orden numérico.

## 👤 Autor

Enrique Merino
* Data Scientist | Investigador UGR
* [LinkedIn](https://www.linkedin.com/in/kikemerino/)

---
*Este proyecto forma parte de mi formación en Data Science & AI.*
