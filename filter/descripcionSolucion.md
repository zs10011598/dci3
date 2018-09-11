# Solución del reto filtro

### Equipo: *Compu mundo hyper mega red*
### Integrantes: 
1. Santiago de Jesus Gonzalez Medellin
2. Noé Hoyos Quiroz
3. Pedro Romero Martinez

### Repositorio de soluciones:
[Aquí](https://github.com/zs10011598/dci3.git)


## Descripción de datos
 (Noé)

## Justificación de modelos
 
Nosotros decidimos atacar el problema utilizando modelos de *machine learning*, despues de explorar los datos y teniendo en cuenta que la naturaleza de las salidas es discreta, optamos por utilizar aprendizaje supervisado, en particular modelos de clasificacion.

## Exploración de modelos

Intentamos el problema de clasificación con el lenguaje de programación `python 3.6` utilizando las siguientes librerias:

1. `pandas`: Para lectura y preprocesamiento de los datos de entrenamiento y de prueba.
2. `numpy`: Para preprocesamiento de los datos de entrenamiento y de prueba.
3. `scikitlearn`: Obtener instancias de los modelos, entrenarlos y clasificar datos de prueba y validacion.

Ademas utilizamos `jupyter notebook` para poner el codigo de cada uno de los modelos en notebooks.

Los modelos de clasificacion que utilizamos fueron *decision trees* y *multi layer perceptron network*, ambos modelos estan incluidos en `scikitlearn` con las funciones `DecisionTreeClassifier()` y `MLPNC()` respectivamente.

El primero intento fue el modelo de *decision trees*, el codigo esta en './filter/pedro_solutions/filterSolTree.ipynb' en el repositorio. Este modelo fue entrenado con los datos de entrenamiento proporcionados. Antes de entrenar el modelo se calculo la correlacion de Pearson entre las columnas de los datos, se observaron altas correlaciones y se eliminaron algunas columnas, de esta manera se obtuvo una precision aproximadamente del 83% sobre los datos de prueba y despues utilizando todas las columnas se obtuvo una precision aproximadamente del 85% sobre los datos de prueba.

Finalmente el otro modelo utilizado fue *multi layer perceptron network*, que se explica en la siguiente seccion, con el que se obtuvo una precision de aproximadamente el 87%, esto se explica mas a detalle a continuacion.

## Modelo elegido
 (Santi)

## Conclusiones
 (Santi)

## Referencias
 (Noé)
