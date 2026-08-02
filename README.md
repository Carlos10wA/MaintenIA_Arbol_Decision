# MaintenIA – Predicción de Fallas mediante Árbol de Decisión

## Descripción

MaintenIA es un proyecto de Inteligencia Artificial desarrollado en **Python** utilizando **Google Colab** y la biblioteca **Scikit-learn**.

Su propósito es construir un modelo de **Árbol de Decisión** capaz de predecir fallas en maquinaria industrial a partir de variables operacionales del proceso productivo.

El proyecto sigue un flujo completo de Ciencia de Datos, incluyendo exploración, depuración, transformación de datos, entrenamiento del modelo, evaluación, exportación de resultados y almacenamiento del modelo entrenado.


## Objetivo General

Desarrollar un sistema de mantenimiento predictivo utilizando un algoritmo de Árbol de Decisión para identificar de forma temprana posibles fallas en maquinaria industrial.


## Objetivos Específicos

- Importar y validar el dataset AI4I 2020.
- Explorar la estructura del conjunto de datos.
- Depurar las variables innecesarias.
- Codificar las variables categóricas.
- Construir un modelo de Árbol de Decisión.
- Entrenar el modelo utilizando Scikit-learn.
- Evaluar el desempeño mediante diferentes métricas.
- Exportar el modelo entrenado para futuras predicciones.


## Dataset utilizado

**AI4I 2020 Predictive Maintenance Dataset**

### Variables principales

- Air temperature
- Process temperature
- Rotational speed
- Torque
- Tool wear

### Variable objetivo

- Machine failure


## Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib


## Modelo implementado

Se implementó un algoritmo de **Árbol de Decisión** para la clasificación de fallas en maquinaria industrial.

### Hiperparámetros utilizados

| Parámetro | Valor |
|-----------|------:|
| Criterion | gini |
| Max Depth | 6 |
| Min Samples Split | 20 |
| Min Samples Leaf | 10 |
| Random State | 42 |


## Flujo general del proyecto

1. Carga del dataset.
2. Exploración inicial.
3. Diagnóstico del conjunto de datos.
4. Depuración del dataset.
5. Codificación de variables.
6. Preparación de variables predictoras.
7. División entre entrenamiento y prueba.
8. Construcción del Árbol de Decisión.
9. Entrenamiento del modelo.
10. Evaluación mediante métricas.
11. Exportación del modelo entrenado.
12. Generación de la imagen del árbol.
13. Conclusiones del proyecto.


## Archivos incluidos

| Archivo | Descripción |
|---------|-------------|
| | **MantenimientoIA_Arbol_Decision.ipynb** | Notebook principal del proyecto |
| **ai4i2020.csv** | Dataset original |
| **ai4i2020_depurado.csv** | Dataset depurado |
| **ai4i2020_codificado.csv** | Dataset preparado para el entrenamiento |
| **modelo_maintenia_arbol_decision.joblib** | Modelo entrenado |
| **variables_predictoras_maintenia.joblib** | Variables predictoras utilizadas |
| **metricas_maintenia_arbol_decision.csv** | Métricas de evaluación |
| **arbol_decision_maintenia.png** | Visualización del Árbol de Decisión |


## Ejecución del proyecto

1. Abrir el notebook en Google Colab.
2. Ejecutar todas las celdas en el orden establecido.
3. Cargar el archivo **ai4i2020.csv** cuando el sistema lo solicite.
4. Esperar el entrenamiento del modelo.
5. Revisar las métricas obtenidas.
6. Analizar la imagen del Árbol de Decisión generada automáticamente.


## Resultados obtenidos

El proyecto genera automáticamente los siguientes archivos:

- Dataset depurado.
- Dataset codificado.
- Modelo entrenado.
- Variables predictoras.
- Métricas de evaluación.
- Imagen completa del Árbol de Decisión.

Todos estos archivos quedan disponibles para reutilizar el modelo entrenado o realizar nuevas predicciones.


## Interpretabilidad del modelo

Una de las principales ventajas del algoritmo de Árbol de Decisión es su facilidad de interpretación.

La imagen generada permite visualizar las reglas aprendidas por el modelo, identificar las variables con mayor influencia en la clasificación y comprender el proceso de toma de decisiones utilizado para determinar si una máquina presenta o no una posible falla.

Esta característica facilita el análisis del comportamiento del modelo y aporta mayor transparencia frente a otros algoritmos de Inteligencia Artificial.


## Comparación con otros modelos

Este proyecto hace parte de la iniciativa **MaintenIA**, la cual contempla una segunda implementación utilizando una **Red Neuronal Artificial**.

Posteriormente se realizará una comparación entre ambos enfoques considerando aspectos como:

- Exactitud (Accuracy).
- Precisión (Precision).
- Sensibilidad (Recall).
- F1-Score.
- Tiempo de entrenamiento.
- Interpretabilidad.
- Complejidad computacional.
- Ventajas.
- Limitaciones.


## Autor

**Carlos Alberto Ayala Larrahondo**

Estudiante de Ingeniería de Software.

Proyecto académico desarrollado para la asignatura de Inteligencia Artificial.


## Licencia

Este proyecto fue desarrollado con fines exclusivamente académicos.

El dataset **AI4I 2020 Predictive Maintenance Dataset** pertenece a sus respectivos autores y se utiliza únicamente con fines educativos y de investigación.


## MaintenIA

Sistema inteligente para mantenimiento predictivo industrial mediante técnicas de Inteligencia Artificial.
