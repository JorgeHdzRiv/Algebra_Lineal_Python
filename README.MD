# Introduccion

En este repositorio se daran fundamentos del algebra lineal con python

El Álgebra lineal es una rama de las matemáticas que es sumamente utilizada en el estudio de una gran variedad de ciencias, como ser, ingeniería, finanzas, investigación operativa, entre otras. Es una extensión del álgebra que aprendemos en la escuela secundaria, hacia un mayor número de dimensiones; en lugar de trabajar con incógnitas a nivel de escalares comenzamos a trabajar con matrices y vectores.

# Conceptos

El estudio del Álgebra lineal implica trabajar con varios objetos matemáticos, como ser:

Los Escalares: Un escalar es un solo número, en contraste con la mayoría de los otros objetos estudiados en Álgebra lineal, que son generalmente una colección de múltiples números.

Los Vectores:Un vector es una serie de números. Los números tienen una orden preestablecido, y podemos identificar cada número individual por su índice en ese orden. Podemos pensar en los vectores como la identificación de puntos en el espacio, con cada elemento que da la coordenada a lo largo de un eje diferente. Existen dos tipos de vectores, los vectores de fila y los vectores de columna.


Las Matrices: Una matriz es un arreglo bidimensional de números (llamados entradas de la matriz) ordenados en filas (o renglones) y columnas, donde una fila es cada una de las líneas horizontales de la matriz y una columna es cada una de las líneas verticales. En una matriz cada elemento puede ser identificado utilizando dos índices, uno para la fila y otro para la columna en que se encuentra. 

Los Tensores:En algunos casos necesitaremos una matriz con más de dos ejes. En general, una serie de números dispuestos en una cuadrícula regular con un número variable de ejes es conocido como un tensor.

# Librerias para el algebra lineal y metodos que se usaran

## Numpy

El popular paquete matemático de Python, nos va a permitir crear vectores, matrices y tensores con suma facilidad.

[Documentacion](https://numpy.org/doc/stable/reference/routines.html#)


**array(object[, dtype, copy, order, subok, ...])**

Crear una matriz.

**linalg.solve(a, b)**

Resuelve una ecuación de matriz lineal, o sistema de ecuaciones escalares lineales.

Calcula la solución "exacta", x, de la ecuación de matriz lineal bien determinada, es decir, de rango completo, ax = b.

**numpy.linspace(start, stop, num=50, endpoint=True, retstep=False, dtype=None, axis=0)**

Devuelva números espaciados uniformemente durante un intervalo especificado.

Devuelve muestras espaciadas numéricamente uniformemente, calculadas sobre el intervalo [start, stop].

Opcionalmente, se puede excluir el extremo del intervalo.







## Matplotlib.pyplot

Es una interfaz basada en estados para matplotlib. Proporciona una forma implícita, similar a MATLAB, de trazar. También abre figuras en su pantalla y actúa como el administrador de GUI de figuras.

[Documentacion](https://matplotlib.org/3.5.1/api/_as_gen/matplotlib.pyplot.html#)

**plot(args[, scalex, scaley, data])**

Trazar y versus x como líneas y/o marcadores.

**axis(args[, emit])**

Método de conveniencia para obtener o establecer algunas propiedades del eje.


# Temario

## Sistemas de ecuaciones lineales

### Ecuaciones lineales y representacion geometrica

* [Ecuaciones Lineales](./Notebooks/Ecuaciones_Lineales_Geometria.ipynb)

### Gauss-Jordan

* [Gauss_Jordan](./Notebooks/Gauss_Jordan.ipynb)

## Matrices

### Matriz

* [Que es una matriz](./Notebooks/Matriz.ipynb)








