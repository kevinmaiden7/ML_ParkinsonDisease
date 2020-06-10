# ML_ParkinsonDisease

Machine Learning Project on UCI Parkinsons Telemonitoring Data Set

## Cómo reproducir los experimentos

El archivo **GridSearch_CrossValidation.ipynb** contiene el código utilizado para realizar la búsqueda de hiperparámetros en malla de los modelos predictivos. En la parte superior se importan las librerías necesarias para las tareas a realizar y se carga la base de datos a utilizar. A continuación se encontrarán bloques de código, uno para cada modelo; estos bloques están compuestos de varias secciones de código: código para ejecutar la búsqueda en malla y código para mostrar los resultados. En la parte inferior de este archivo, se encuentran secciones de código adicionales que se pueden utilizar para probar una combinación específica de hiperparámetros del modelo MLPR y SVR.

El archivo **Feature_Analysis.ipynb** contiene el código utilizado para realizar el análisis de características y la reducción de dimensionalidad. En la parte superior se importan las librerías necesarias para las tareas a realizar y se carga la base de datos a utilizar. A continuación se encontrarán los bloques de código para ejecutar el análisis individual de características, selección de características y extracción de características respectivamente. Se recomienda ejecutar estos bloques de código de manera secuencial, de arriba a abajo.

El archivo **base_code_tests.ipynb** se utilizó para ejecutar pruebas inmediatas sin necesidad de afectar los dos archivos principales.
