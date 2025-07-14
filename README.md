# Clasificación KNN en Datos de Recursos Humanos

Este repositorio presenta un proyecto de clasificación supervisada utilizando el algoritmo K-Nearest Neighbors (KNN) sobre un conjunto de datos de recursos humanos. El flujo de trabajo abarca desde la limpieza de datos hasta la evaluación comparativa de diferentes valores de k, aplicando métricas clave para seleccionar el mejor modelo.

## Contenido del análisis

- **Preparación de datos:**
  - Eliminación y codificación de variables categóricas
  - Verificación de valores nulos
  - Estandarización de variables numéricas
  - División del conjunto en entrenamiento y prueba

- **Modelado KNN:**
  - Entrenamiento con distintos valores de k
  - Comparación de precisiones mediante tablas y gráficos

- **Evaluación del desempeño:**
  - Matriz de confusión
  - Reporte de clasificación
  - Curva ROC para visualizar sensibilidad y especificidad

## Herramientas utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  

## Conclusiones

- La variación del parámetro k influye directamente en la precisión del modelo.
- La curva ROC y el reporte de clasificación permiten una evaluación completa.
- El proyecto demuestra cómo KNN puede ser una herramienta efectiva para problemas de clasificación en entornos de recursos humanos.

## Recomendación

Ideal para quienes desean profundizar en algoritmos supervisados, mejorar la estructura de sus notebooks y aplicar técnicas de evaluación de modelos. Este proyecto puede ser extendido incluyendo validación cruzada, selección de características o comparación con otros clasificadores como SVM o Random Forest.
