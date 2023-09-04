# Funcion Background
Sirve para modificar el color de un elemento seleccionado.

Esta funcion tambien tiene los siguientes atributos:
* ## Atributo color

* ## Atributo linear-gradient
Se llama gradiente, o degradado, a la transición progresiva de un color a otro. La función CSS linear-gradient permite controlar la dirección de la transición a lo largo de una línea, y qué colores participan en el degradado.
```
linear-gradient(gradientDirection, color1, color2, ...);
```
`gradientDirection` es la dirección de la línea a lo largo de la cual tendrá lugar la transición. `color1` y `color2` son argumentos de color, representando los colores usados en la transición. Se pueden pasar a la función en cualquier formato, ya sea el nombre del color, hex, rgb o hsl.

Aplicado en el codigo y queriendo hacer un degradado de 90g y de rojo a verde, quedaria de la siguiente manera:
```
background: linear-gradient(90deg, rgb(255, 0, 0), rgb(0,255,0));
```
La función `linear-gradient` necesita un mínimo de dos colores como argumentos, pero puede aceptar bastantes más. 

Las `paradas de color` permiten afinar el emplazamiento de los colores a lo largo de la línea que sigue el gradiente. Se definen, en la función linear-gradient, mediante unidades de longitud, como px o %, a continuación del color del cual se quiere definir la parada.
```
linear-gradient(90deg, red 90%, black);
```
Nota: Una cosa a tener en cuenta es que la función linear-gradient lo que en realidad crea es un elemento image, y se asocia normalmente con la propiedad background, la cual puede aceptar una imagen como valor.
* ## Propiedad Opacity
`Opacity` describe cuán opaco o no transparente es algo. Por ejemplo, una pared sólida es opaca y no puede pasar la luz. Pero un vaso para beber es mucho más transparente, y puedes ver a través del vaso hacia el otro lado.

Con la propiedad CSS `opacity`, puede controlar cuán opaco o transparente es un elemento. Con el valor 0, o 0%, el elemento será completamente transparente, y en 1.0, o 100%, el elemento será completamente opaco como lo es por defecto.
