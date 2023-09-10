# Momento de Retroalimentación: Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución
Dentro de este apartado puede encontrar encontrarán el segundo entregable de mi portafolio de implementación respecto al módulo de Machine Learning, que básicamente consiste en la implementación de un algoritmo un poco más elaborado de ML; para este segundo entregable utilicé redes neuronales apoyado de librerías como TensorFlow, Keras y ScikitLearn. Básicamente, las redes neuronales son un tipo de modelo de ML que puede ser utilizado para regresion o bien clasificación, aunque puede tener otros usos. En mi caso, lo utilicé para predecir los mismos datos que usé para la entrega anterior (sin uso de framework), variando un poco la cantidad de neuronas, capas, batch_size, iteraciones y funciones de activación. Esta entrega se conforma de los siguientes archivos:
* <a href="https://github.com/4lb3rt0r/TC3006_Portafolio_Implementacion/blob/main/retro/M2_ML/Implementación de una Técnica de ML con FW/Marvel_Movies.csv">**Marvel_Movies.csv:**</a> Datos de Películas de Marvel que han salido a lo largo de los años. Este dataset lo puedes encontrar dentro del siguiente <a href="https://www.kaggle.com/datasets/joebeachcapital/marvel-movies">enlace</a> y contiene las siguientes columnas:
    1. **film:** Nombre de la película.
    2. **category:** Ctegoría de la película. En concreto se refiere a si la película pertenece a un subconjunto de películas, como una trilogía o una saga (Avengers, Captain America, IronMan, Thor, etc.).
    3. **worldwide gross (m):** Recaudación mundial bruta de la película en millones de dólares.
    4. **% budget recovered:** Porcentaje de presupuesto recuperado de la película.
    5. **critics % score:** Porcentaje del puntaje de la película según los críticos.
    6. **audience % score:** Porcentaje del puntaje de la película según la audicencia.
    7. **audience vs critics % deviance:** Porcentaje que representa la diferencia entre los porcentajes de la opinión de la crítica y la audiencia.
    8. **budget:** Presupuesto de la película en millones de dólares.
    9. **domestic gross (m):** Recaudación total recibida por todos los sectores de la economía estadounidense generada por la película.
    10. **international gross (m):** Recaudación total recibida por todos los sectores de la economía internacional generada por la película.
    11. **opening weekend (m)**: Recaudación de la película durante el primer fin de semana de estreno en millones de dólares.
    12. **second weekend (m):** Recaudación de la película durante el segundo fin de semana en millones de dólares.
    13. **1st vs 2nd weekend drop off:** Porcentaje de caída en la recaudación entre el primer y segundo fin de semana.
    14. **% gross from opening weekend:** Porcentaje de la recaudación total de la película que proviene del primer fin de semana de estreno.
    15. **% gross from domestic:** Porcentaje de la recaudación total de la película que proviene del mercado doméstico.
    16. **% gross from international:** Porcentaje de la recaudación total de la película que proviene del mercado internacional.
    17. **% budget opening weekend:** Porcentaje del presupuesto de la película gastado en el primer fin de semana de estreno.
    18. **year:** Año de lanzamiento de la película.
    19. **source:** Fuente de los datos o información sobre la película. 
* <a href="https://github.com/4lb3rt0r/TC3006_Portafolio_Implementacion/blob/main/retro/M2_ML/Implementación de una Técnica de ML con FW/M2_Uso_de_framework_o_biblioteca_de_aprendizaje_máquina.ipynb">**M2. Uso de framework o biblioteca de aprendizaje máquina.ipynb:**</a> Jupyter Notebook que contiene el código y analisis realizado para la implementación del código de Machine Learning que realizará predicciones en base a datos de películas de Marvel haciendo uso de redes neuronales. A continuación se presenta un indice de los contenidos de dicho archivo:

1. Encabezado

    1.1 **Instrucciones e Información acerca del entregable:**

    Explicación breve sobre las instrucciones a seguir y un poco de contexto acerca de los datos utilizados para este trabajo y el modelo a implementar.

2. Implementación de un Algoritmo de Machine Learning utilizando redes neuronales:<br/>
   
   Código de Python empleado para la implementación del algoritmo de ML, utilizando redes neuronales y la base de datos obtenida de <a href="https://www.kaggle.com/datasets/joebeachcapital/marvel-movies">Kaggle</a> con información sobre películas de Marvel, incluye pequeñas descripciones de los pasos que se siguieron desde la construcción del modelo, su entrenamiento hasta su implementación.

4. Gráfica:<br/>
   
   Graficación y tabulación de información utilizada durante el análisis posterior a la predicción con el fin de visualizar el flujo de los datos.
