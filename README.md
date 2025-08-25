# Selección de características 

Este trabajo tiene como objetivo aplicar técnicas de selección de características en un conjunto de datos real. El dataset utilizado corresponde a muestras de vino tinto con variables físico-químicas y una variable de calidad evaluada sensorialmente.

Objetivos:

1. Cargar y explorar los datos, verificando dimensiones y estructura.

2. Dividir el dataset en un conjuntos de entrenamiento 80% y prueba 20% para evaluar generalización

3. Implementar forward selection con regresión lineal y validación cruzada 10 fold, probando diferentes valores de k

4. Entrenar un modelo con el subconjunto sleccionado y calcular el R² de prueba

5. Aplicar backward selection sobre el conjunto elegido en forward, evaluando distintos valores de k

6. Comparar el desempeño de ambos modelos en el conjunto de prueba y ver cual resulta mejor opción.

Herramientas utilizadas:

• scikit-learn:

• train_test_split para la participación de datos

• LinearRegression para regresión lineal múltiple

• SequentialFeatureSelector para selección forward/backward

• KFold y cross_val_score para validación cruzada

• r2_score para ver desempeño en prueba

El trabajo muestra cómo la selección de caracteristicas ayuda a balancear el desempeño predictivo con la simplicidad del modelo. Forward alcanzo un R² de prueba un poco mayor, backward logra casi el mismo rendimiento con menos variables, lo cual puede ser buenos en terminos de eficiencia.


La actividad va de 3 documentos:

[reporte ipynb](A1.4_652911.ipynb)

[reporte html](A1.4_652911.html)

[reporte Vino_Tinto.cvs](Vino_Tinto.cvs)
