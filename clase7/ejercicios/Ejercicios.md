# Ejercicios para practicar

1. Use el dataset [Iris Species](https://archive.ics.uci.edu/dataset/53/iris). El cual consiste en 50 muestras de flores de tres especies distintas (Iris-setosa, Iris-versicolor y Iris-virginica) con diferentes características (Largo del sépalo, ancho del sépalo, largo del pétalo y ancho del pétalo). En este caso, sabemos a que clase pertenece cada planta, pero podemos con ello evaluar métodos de agrupación.
   1. Implemente 1 modelo usando el algortimo de K-means.
      1. Con el método del codo, determine el numero de clusters. Cuanto clusters se eligió, es igual a la cantidad de especies de planta? Hay una correlación (por ejemplo, supongamos que quedan 4 clusters, en los cuales 2 corresponden perfectamente a una tipo de planta y las otras dos a la otras dos categorias respectivamente)? 
      2. Separe un 20% de los datos del dataset y guardelos.  
      3. Arme el modelo con el número optimo de clúster usando el 80% de los datos restantes. Con los cluster obtenidos, determine a que clase de planta pertence mediante algun metodo de mayoria. 
      4. Clasifique al 20% de los datos, usando el modelo de agrupamiento y el metodo de mayoria elegida. Que resultado obtuvo? (Elija la metrica de evaluación que mejor considere). Que tan correcto fue armando agrupamientos de datos con respecto a la clase que dan origen a los datos?
      5. Compare el procedimiento que realizó con KNN. Que tán similar es al clasificador a nivel de procedimiento?
   2. Implemente 4 modelos usando el algoritmo de Hierarchical Clustering usando los enlaces del tipo: Single, Complete, Average y Ward. Para cada uno de ellos realice:
      1. Con el método del codo, determine el numero de clusters. Cuanto clusters se eligió, es igual a la cantidad de especies de planta? Hay una correlación (por ejemplo, supongamos que quedan 4 clusters, en los cuales 2 corresponden perfectamente a una tipo de planta y las otras dos a la otras dos categorias respectivamente)?  
      2. Separe un 20% de los datos del dataset y guardelos.  
      3. Arme el modelo con el número optimo de clúster usando el 80% de los datos restantes. Con los cluster obtenidos, determine a que clase de planta pertence mediante algun metodo de mayoria. 
      4. Clasifique al 20% de los datos, usando el modelo de agrupamiento y el metodo de mayoria elegida. Que resultado obtuvo? (Elija la metrica de evaluación que mejor considere). Que tan correcto fue armando agrupamientos de datos con respecto a la clase que dan origen a los datos? Cuál tipo de enlace genero el mejor resultado?
      5. Compare con el resultado de K-means y de KNN. Cómo fue el rendimiento de este modelo? 
