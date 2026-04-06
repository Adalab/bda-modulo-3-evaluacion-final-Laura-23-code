Informe de Análisis: Comportamiento de los clientes dentro de un programa de fidelidad de una aerolinea


Datasets: Customer flight analysis y customer loyalty history


Fase 1: Exploracion y limpieza.

Comienzo haciendo una exploración inicial de cada dataset identificando posibles problemas como valores nulos, valores duplicados y outliers.
Tras unir los datasets, se realizaron las siguientes acciones:
Detecto que tengo valores nulos en el salario y lo comparo con la educación ya que entiendo que tienen relacion. A si mismo me doy cuenta que en el salario tengo valores negativos y al hacer esa comparación con Educacion me doy cuenta que ha podido ser un error por lo cual voy a pasarlos a valores positivos
Estos fueron imputados con la mediana para no sesgar los análisis económicos.
Compruebo que tanto la columna cancellation year y cancellation month tienen exactamente los mismos nulos , procedo a duplicar las columnas y luego las elimino ya que para este ejercicio no son redundantes.
Compruebo que ya no queda ningun valor nulo.
Continuo con los valores duplicado y decido eliminarlos pero dejando el primer valor de cada fila.

 Fase 2 Analisis estadisticos
 
Segun puedo comprobar en la estadísta descriptiva de Flights Booked El promedio es de 4.13, sin embargo la mediana es solo 1, lo que me da a entender que vuelan muy poco
En el salario: El sueldo típico ronda los 73479 y esta muy  cerca de la media. Mas o menos tienen el mismo poder adquisitivo quitando algun pico en el 75% y max
CLV:  me hace ver a primera vista que hay mas clientes que aportan valor a la empresa
 
compruebo los valores atipicos comparando el maximo con el 75% hay clientes con ingresos que se salen de la normalidad, lo mismo podemos decir del CLV. Se puede comprobar que los vuelos que mas se realizan son de mayor distancia y por norma general los viajeros reservan muy pocos vuelos pero hay una pequeña cantidad de clientes que vuela mucho por ello sube el 75% 
 
hago un analasis de correlacion y puedo ver que hay una cierta relacion entre los vuelos, la distancia y los puntos acumulados


Fase 3:  Visualizacion.

He trabajado con graficas como scatterplot, countplot, blorplot para contestar una serie preguntas y llegar a una conclusion. 
las personas que más vuelan tienen mas fidelidad con la aerolinea. Estos clientes suelen ser de ciudades grandes con niveles de estudios altos ( aunque hay de todo ) y da igual si son hombres o mujeres, si que es verdad que hay mas gente casada.

