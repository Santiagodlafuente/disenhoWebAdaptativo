# Atributo para seleccionar una etiqueta de html en css

## Vincular un archivo de css con html
Primero debemos crear un archivo nuevo con el nombre que quieramos pero debemos agregarle (.css), siempre que se trate de un archivo de estilo llevara ese nombre. Luego en el head debemos crear una etiqueta (link) con un atributo 'rel=' y el valor 'stylesheet' y el atributo 'href='.
```
<head>
    <link rel='stylesheet' href=''>
</head>
```
Y aqui sera donde agregaremos la ubicacion de nuestro archivo de estilo.
```
    <link rel='stylesheet' href='pc/style.css'>
```

## Agregar estilo a un elemento
Para esto debemos ir a nuestra hoja de css, agregar el nombre de la etiqueta y seguido, un par de llaves donde dentro agregaremos un atributo con un valor determinado.
```
elemento{
    atributo: valor;
}
```

# Forma de seleccionar una Etiqueta
## De tipo
Solo basta con agregar el nombre de la etiqueta. 
```
h1{
    text-align: center;
}
```
Tambien se puede seleccionar varias etiquetas solo hay que separarlas con una coma.
```
h1, h2, p{
    text-align: center;
}
```
## Con una Clase
Para agregar una clase devemos ir a nuestra hoja de html y dentro de una etiqueta, donde abre, y  agregarle el atributo 'class=''' y un nombre que quieramos.
```
<h1 class='titulo'>titulo</h1>
```
Para escribir varios nombres una buena practica es separarlo por un guion (-) o la primero palabra escribirla en miniscula y la segunda palabra que no tenga espacio y que la empieze con mayuscula.
```
1era: <h1 class='titulo-principal'>Titulo</h1>
2da: <h1 class='tituloPrincipal'>Titulo</h1>
```
## Con un id
Esta tipo de selector se debe usar para una unica etiqueta, la cual debe llevar un unico nombre en todo nuestro archivo.
Esta se usa de la misma forma el selector clase.
```
<h1 id='titulo'>Titulo</h1>
```
Tambien alclarar que se puede agregar un selector id y uno de clase al mismo elemento.