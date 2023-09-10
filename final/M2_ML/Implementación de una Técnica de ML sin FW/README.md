# Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework
Dentro de este apartado puede encontrar encontrarán el primer entregable de mi portafolio de implementación, que básicamente consiste en la implementación de un algoritmo básico de Machine Learning, en mi caso utilicé una regresión polinomial. Cuenta con los siguientes archivos:
* **<a href="https://github.com/4lb3rt0r/TC3006_Portafolio_Implementacion/blob/main/final/M2_ML/Implementación de una Técnica de ML con FW/Marvel_Movies.csv">**Marvel_Movies.csv:**</a>** Datos de Películas de Marvel que han salido a lo largo de los años.
* **<a href="https://github.com/4lb3rt0r/TC3006_Portafolio_Implementacion/blob/main/final/M2_ML/Implementaci%C3%B3n%20de%20una%20T%C3%A9cnica%20de%20ML%20sin%20FW/M2_Implementaci%C3%B3n_de_una_t%C3%A9cnica_de_aprendizaje_m%C3%A1quina.ipynb">M2_Implementación_de_una_técnica_de_aprendizaje_máquina.ipynb:**</a> Jupyter Notebook que contiene el código y analisis realizado para la implementación del código de Mahcine Learning que realizará predicciones en base a datos de películas de Marvel. A continuación se presenta un indice de los contenidos de dicho archivo

1. Encabezado

    1.1 **Instrucciones e Información acerca del entregable:**

    Explicación breve sobre las instrucciones a seguir y un poco de contexto acerca de los datos utilizados para este trabajo.

2. Implementación de un Algoritmo de Machine Learning utilizando regresión polinomial:<br/>
   
   Código de Python empleado para la implementación del algoritmo de ML, utilizando el método de regresión polinomial y la base de datos obtenida de <a href="https://www.kaggle.com/datasets/joebeachcapital/marvel-movies">Kaggle</a> con información sobre películas de Marvel.

4. Graficas y Tabla Comparativa:<br/>
   
   Graficación y tabulación de información utilizada durante el análisis posterior a la predicción con el fin de visualizar el flujo de los datos y su comportamiento con respecto a los valores reales.

## Cambios realizados con respecto a la entrega anterior
Se realizaron varias observaciones por parte del docente con respecto a la primera versión de este entregable, por lo cual, se realizaron varias modicaciones con el fin de cumplir con los criterios de la rúbrica que no se lograron alcanzar previamente. Es por ello que, a continuación se presentan las modificaciones realizadas al trabajo basados en la retroalimentación proporcionada por criterio faltante:

* **El readme contiene una sección de cambios implementados, donde se mencione el cambio indicado por el docente y lo que se hizo para resolverlo (solo aplica para entrega final)**
   * Esta marca se resuelve justamente añadiendo esta misma sección a este mismo archivo README correspondiente a la entrega.

* **El reporte incluye una descripción de las métricas de desempeño para el subconjunto de entrenamiento**
   * Se dedicó una pequeña sección para describir brevemente qué tipo de métrica se utiliza para evaluar el modelo durante el entrenamiento y el por qué de esta decisión.

* **El reporte incluye una descripción de las métricas de desempeño para el subconjunto de prueba**
   * Se dedicó una pequeña sección para describir brevemente qué tipo de métrica se utiliza para evaluar el modelo durante las pruebas.

* **El reporte incluye una comparación entre las predicciones generadas y los valores que debieron obtenerse**
   * A pesar de que la versión anterior del reporte ya incluía una sección donde se comparaban los datos estimados con los datos reales, se hicieron algunas modificaciones, como por ejemplo, reducir el tamaño de la tabla comparativa de datos que ahora incluye las 4 variables de entrada, la variable independiente y la variable estimada, pero solo se incluyeron los valores del subset de validación para proyectar de mejor manera las diferencias entre valores reales y estimados.

* **El modelo implementado es genérico y permite variar sus hiper-parámetros y datos (e.g., número de iteraciones, learning rate, etc.)**
   * El modelo es completamente modificable y es posible modificar cualquiera de sus hiperarámtros (learningRate, theta, número n de iteraciones, entre otros). El comentario que se dejó al respecto a este criterio fue que los valores de las variables de entrada debían de ser independientes la una de la otra y no potencias de la misma variable, que como se había trabajado en la versión anterior. Ahora, se tienen 4 variables independientes ("opening weekend", "budget", "% gross from opening weekend" y "audience % score") que se implementan dentro del modelo para predecir el valor de salida (second weekend).

* **El modelo está implementado correctamente**
   * El modelo se ha mejorado, como se indica en el punto anterior, de forma que su implementación ahora es correcta y como el docente esperaba que se realizara desde el principio (revisar criterio anterior para más detalles). 