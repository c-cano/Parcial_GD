Punto 1.
- Variable 1. Gender, Categorica
- Variable 2. Ethnicity. Categorica
- Variable 3. Patental Education, Categorica
- Variable 4 Lunch Categorica
- Variable 5 Preparation, Categorica
Variable 6,7,8. Scores Math, reading and writing continua

Punto 2.
Se evidencia que el dataset, tiene entre un 4-6% de datos nulos, por falta de calidad de datos, la variable que tiene mayor ausencia de información es la variable education de los padres. 

Eliminar los datos con datos faltantes seria una perdida enorme de información, esto se debe a que en el mejor de los casos en donde contemplamos todas las variables perdemos más del 36% de la información y para los datos continuos perdemos más del 16%

Se sugiere para esta situación una imputación de datos, para los datos categoricos su valor mas cercano en el dataset, mientras que para los datos continuos, por el promedio o la mediana. Cabe anotar que no es el mejor método, dado que para un problema de este tipo podría optarse por modelos de imputación mas sofisticados (KNN, Multinomiales, muestreos) pero al ser el tiempo una restricción y se asume que no se puede devolver los datos, el valor más cercano en el data set.

Se omite el proceso de modas, dado que es más probable incurrir en sesgos, producto de sobrecargar una categoria.

Punto 3.

Se revisa tanto, los datos con y sin imputación y se evidencia una leve diferencia en los estadisticos mostrados, las tres materias presentan un comportamiento similar, la media y la varianza es casi igual y tienen una distribución similar en los puntajes de 1 a 100; con respecto a su uniformidad podemos entrar a debates, dado que las cifras del percentil 25, son muy cercanas a la mediana y la media, razón por la cual soprechamos que tiene un sezgo a la derecha, y debe ser leptocurtica, con una gran cantidad de datos entre los puntajes de 50 a 70 puntos. La mejor prueba con respecto a las otras materias es lectura, que tiene unos ligeros puntos sobre las demás materias

Punto 4
Se evidencia que existe una correlación mucho más altas en las pruebas de lectura y escritura, comparada con su relación con matemáticas. Esto puede tener sentido dado que los planes de lectoescrituras de los colegios desarrollan esta habilidad a la par a diferencia de matemáticas

Punto 5
Para el caso de matemáticas el género masculino tuvo los mejores promedio, seguido por muy poco de la población no.binaria. Se evidencia que los percentiles mayores a 75% fueron más altos en los hombre. Si se evidencia un sezago en la población femenina de entre 3-6 puntos, comparados con los demás géneros.

Punto 6.

Se evidencia que está población si tiene una mayor influencia sobre padres con escolaridad mayor al high school, pero no necesariamente un nivel de postgrado aumenta los scores.

Punto 7.

Solo 24, estudiantes de una población de 1000, supera los scores mayores a 90, un total de un 2.4%; de los cuales 13 terminaron el curso de preparación.