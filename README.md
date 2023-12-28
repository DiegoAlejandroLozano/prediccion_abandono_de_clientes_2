# Predicción de abandono de clientes 2

Librerías utilizadas: `Keras`, `Pandas`, `Numpy`  y `Scikit-Learn`

Este proyecto tiene como objetivo predecir si un cliente abandonará su banco, tomando en consideración diversas características como su puntaje de crédito, edad, saldo de la cuenta, número de productos contratados con el banco, entre otros parámetros incluidos en el conjunto de datos Churn_Modelling.csv. La clasificación se lleva a cabo mediante la implementación de una red neuronal en KERAS. Esta red neuronal consta de una capa de entrada con 11 elementos, seguida de dos capas ocultas, cada una compuesta por 6 neuronas, y finalmente, una capa de salida.

Para correr el repositorio de forma local se debe crear un entorno virtual con el siguiente comando:

    Python3 -m venv nombre_entorno_virtual

Se debe activar el entorno virtual e instalar las librerías requeridas a través del archivo requirements.txt

    pip install -r requirements.txt
