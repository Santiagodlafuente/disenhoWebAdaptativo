# Etiqueta Input
Sirve para agregar botones de diferentese tipos de datos.

## Atributos 'Type' y sus diferentes valores
Esto sirve para definir un tipo de dato que le solicitemos al usuario. Este cuenta con diferentes valores como:
* text='para que el usuario agregue texto simplemente'.
* date='para que el ususario agregue una fecha'.
* email='para que el usuario agregue un email'.
* color='para que el usuaru=io seleccione un color'.


## Asociar una etiqueta label con un elemento input.
* Para asociar una etiqueta (label) con un input  necesitamos agregar un atributo for con el mismo valor que le asignamos al id del input.
```
<input id="loving" type="checkbox"name="personality">        
<label for="loving">Loving</label>
<input id='lazy' type='checkbox' name='personality'> 
<label for='lazy'>Lazy</label>
```
## Agregar el atributo de seleccion predeterinado.
* Sirve para definir un elemento de seleccion que este elegido como predefinido. Solo con agregar el atributo checked(elegido) dentro del elemento input.
```
<input id='nombre' type='checkbox' name='nombre' value='nombre' checked>
<label for='nombre'>Nombre</label>
```


