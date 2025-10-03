📖 Descripción del Proyecto

Este proyecto tiene como objetivo predecir la evasión de clientes del Beta Bank utilizando técnicas de Machine Learning. Basándose en datos de comportamiento de los clientes, se busca identificar a aquellos con mayor riesgo de churn y proporcionar insights estratégicos para retención.

## 🎯 Objetivos

- Construir modelos predictivos de churn de alto rendimiento  
- Comparar diferentes algoritmos de clasificación  
- Analizar el impacto de diversas características en el riesgo de churn  
- Evaluar métricas de desempeño, priorizando F1-score y AUC-ROC  

## 🗂️ Dataset

El dataset contiene información sobre los clientes de Beta Bank, incluyendo:

- Datos demográficos (edad, género, ubicación)  
- Historial de transacciones y actividad financiera  
- Interacciones con productos y servicios del banco  
- Estado de churn (cliente activo o evadido)  

*Nota: Todos los datos utilizados en este proyecto son ficticios o anonimizados para fines de estudio.*

## ⚙️ Metodología

**Análisis Exploratorio de Datos (EDA)**

- Visualización de distribuciones y correlaciones  
- Identificación de valores faltantes y outliers  

**Preprocesamiento**

- Tratamiento de valores faltantes  
- Codificación de variables categóricas  
- Normalización y estandarización (StandardScaler)  

**Modelado**

- Regresión Logística  
- Árbol de Decisión  
- Random Forest  
- Gradient Boosting (LightGBM)  

**Tratamiento de Datos Desbalanceados**

- Oversampling (SMOTE)  
- Undersampling  

**Evaluación de Modelos**

- F1-score, AUC-ROC  
- Matriz de confusión  
- Comparación de métricas entre modelos  

## 📊 Resultados

- Modelo con mejor desempeño: LightGBM  
- Features más relevantes: feature1, feature2, feature3  
- Se generaron insights estratégicos para acciones de retención de clientes  

## 💡 Conclusión

El proyecto demuestra cómo las técnicas de Machine Learning pueden ayudar a los bancos a identificar clientes en riesgo de churn e implementar estrategias de retención más efectivas.
