# Propiedad de margen (margin)
Esta propiedad 'margin' sirve para agregar, como la palabra lo dice, un espacio a un elemento seleccionado. Esta cuenta con diferentes tipos de valores, para una mejor ejemplificacion, imaginemos que tenemos 2 cajas pero queremos separarlas entre si, este espacio se denomina un margen. 

Entonces si ponemos la caja A y a lado derecho la caja B, tendremos que usar 'margin-right', en espanol: margen derecho, y seguido agregaremos dos puntos y le agregamos una unidad de medida.
h1{margin-right: 50px;}. 

Ahora, si de la misma forma invertimos de lado la posicion de las cajas, quedaria del Lado Izquierdo, tendremos que usar 'margin-left' y su unidad de medida.
h1{margin-left: 50px;}

En cambio si ahora la caja B estuviera en la parte de arriba, tendremos que usar 'margin-top'.
h1{margin-top: 50px;}

Y si ahora estaria abajo, tendremos que usar la propiedad 'margin-buttom'.
h1{margin-buttom: 50px;}

Tambien hay una forma si queremos simplificar un poco mas el codigo, solo usando la propiedad margin y su valor:
* margin: auto - Para centrar el elemento.
* margin: 20px 50px; - De esta forma estaremos dando un margen de 20px hacia arriba y abajo, y de 50px hacia el lado derecho y izquierdo.
