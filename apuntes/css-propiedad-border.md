# Propiedad border
Todos los elementos HTML tienen bordes, pero están establecidos a `none` por defecto. Con CSS se tiene control total sobre los bordes de un elemento, pudiendo mostrarlo en todos los lados o simplemente en uno. Para que un borde sea visible, hay que darle grosor (width) y estilo (style).
```
    border-left-width: 10px;
```
Los bordes tienen varios estilos para elegir. Puede ser una línea continua (`solid`) o discontinua (`dashed`), o incluso una línea punteada (`dotted`) si lo prefieres. Lo normal es que sean líneas continuas.
```
    border-left-style: solid;
```
Pero para que tu código sea más legible, es mejor establecer el color del borde explícitamente.Si no se establece ningún color, el negro se utiliza por defecto.
```
    border-left-color: black;
```
La propiedad abreviada border-left permite establecer el grosor, el estilo y el color del borde izquierdo de forma simultánea. La sintaxis sería:
```
border-left: width style color;
```
