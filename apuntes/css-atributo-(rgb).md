# Funcion Rgb
En CSS, un color se puede especificar como un valor RGB, utilizando esta fórmula:

rgb (rojo , verde, azul)

Cada parámetro (rojo, verde y azul) define la intensidad del color entre 0 y 255.
## Crear colores Primarios
* Color Rojo rgb(255, 0, 0) - Para establecer el color rojo solo basta con darle el maximo valor a la seccion que vale por rojo, es decir a la primera seccion le damos el valor de 255 y a los demas de cero.
* Color Verde rgb(0, 255, 0) - Para establecer el color verde de la misma forma, establecemos el maximo valor a la seccion de verde y los demas dejamos en cero.
* Color Azul rgb(0, 0, 255) - Para establecer el color verde, lo mismo, damos el mmaximo valor y los demas en cero.
* Color Negro rgb(0, 0, 0) - Configure todos los parámetros en 0.
* Color Blanco rgb(255, 255, 255) - Configure todos los parámetros en 255.
## Colores Secundarios
* Color Amarillo rbg(255, 255, 0)
* Color Cian rgb(0, 255, 255)
* Color Magenta rgb(255, 0, 255)
## Colores Terciarios
* Color Gris rgb(200, 200, 200)
* Color Naranja rgb(255, 127, 0)
* Color Verde Claro rbg(0, 255, 127)
* Color Violeta rgb(127, 0, 255)
## Otros 
* Color Verde Oscuro rgb(127, 255, 0)
* Color Azure rgb(0, 127, 255)
* Color Rosa rgb(255, 0, 127)

# Otras Funciones
## Funcion hexadecimal
Seguramente estés familiarizado con valores en base 10, o decimales, los cuales van de 0 a 9. Hexadecimales, o valores en base 16, van de 0 a 9 y a continuación de A a F:

0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

Para los colores en hexadecimal, 00 es 0% de ese color, y FF es 100%. De tal manera que #00FF00 se traduce en 0% rojo, 100% verde y 0% azul, siendo equivalente a rgb(0, 255, 0).

## Funcion Hsl
Otra forma de representar colores es el modelo HSL, siglas de hue, saturation y lightness (matiz, saturación y luminosidad).

La función CSS hsl acepta 3 valores: un número de 0 a 360 para el tono, un porcentaje de 0 a 100 para la saturación y un porcentaje de 0 a 100 para la luminosidad.

1-Sobre un círculo cromático, el matiz (hue) rojo está en 0 grados, el verde en 120 y el azul en 240.

2-La saturación es la intensidad de un color desde 0%, o gris, hasta 100% para el color puro. Debe añadir el signo de porcentaje % a los valores de saturación y luminosidad.

3-La luminosidad (lightness) es lo brillante que parece un color, desde 0% o completamente negro, hasta 100%, completamente blanco, siendo neutro el 50%.
* Color Azul hsl(240, 100%, 50%)
* Color Rojo hsl(240, 0%, 0%)

# Funcion rgba
Los valores de color RGBA son una extensión de los valores de color RGB con un canal alfa, que especifica la opacidad de un color.

Un valor de color RGBA se especifica con:
rgba ( rojo, verde , azul, alfa )

El parámetro alfa es un número entre 0.0 (totalmente transparente) y 1.0 (nada transparente)