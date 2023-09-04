# PRopiedad box-shadow
La propiedad box-shadow permite aplicar una o más sombras alrededor de un elemento. Esta sería la sintaxis básica:
```
    box-shadow: offsetX offsetY color;
```
Así es como funcionan los valores offsetX y offsetY: tanto `offsetX` como `offsetY` aceptan valores numéricos en px y otras unidades CSS, un valor offsetX positivo desplaza la sombra hacia la derecha y un valor negativo hacia la izquierda.
Un valor positivo de offsetY desplaza la sombra hacia abajo y un valor negativo hacia arriba.

Si quieres un valor de cero (0) para offsetX y offsetY, no necesitas añadir una unidad. Todos los navegadores entienden que cero significa que no hay cambios.

La altura y anchura de la sombra viene determinada por la altura y anchura del elemento al que se aplica. También puedes usar un valor opcional de `spreadRadius` para extender el alcance de la sombra. Más adelante hablaremos de ello.
```
    box-shadow: 5px 5px red;
```
los límites de la sombra son muy bruscos. En la propiedad box-shadow, se encuentra el valor opcional `blurRadius`:
```
    box-shadow: offsetX offsetY blurRadius color;
```
Si no se indica un valor para blurRadius, será 0 por defecto, produciendo sombras con los límites bruscos. Cuanto mayor sea el valor de blurRadius, mayor será el efecto de difuminado de la sombra.
