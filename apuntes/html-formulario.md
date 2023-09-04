# Formulario
Para crear un formulario existe la siguiente etiqueta
`<form></form>`. Hay un atributo `action` que sirve para que todos los datos que ingrese el usuario vayan a una pagina especifica.
```
<form action='aqui va la direccion url del archivo/pagina'></form>
```
Otro que es muy util es el atributo `method` que especifica como enviar datos del formulario a la direccion url especificada en el atributo action. Los datos del formulario se pueden enviar a través de una solicitud `GET` como parámetros de URL (con method="get") o mediante una solicitud `POST` como datos en el cuerpo de la solicitud (con method="post").
```
<form action='https://google.com' method='post'></form>
```
# Etiquetas dentro del for
* ## Etiqueta `fieldset`
El elemento `fieldset` (grupo de campos) permite organizar en grupos los campos de un formulario. Crea una caja en bloque. `<fieldset></fieldset>`
* ## Etiqueta `label`
El elemento `label` representa una etiqueta para un elemento en una interfaz de usuario. Este puede estar asociado con un control ya sea mediante la utilizacion del atributo for, o ubicando el control dentro del elemento label. Tal control es llamado "el control etiquetado" del elemento label.`<label></label>`
* ## Etiqueta `Input`
El elemento `input` se usa para crear controles interactivos para formularios basados en la web con el fin de recibir datos del usuario. Hay disponible una amplia variedad de tipos de datos de entrada y widgets de control, que dependen del dispositivo y el agente de usuario (user agent (en-US)). El elemento `<input>` es uno de los más potentes y complejos en todo HTML debido a la gran cantidad de combinaciones de tipos y atributos de entrada.

En modo de ejemplo asi iria quedando el codigo de un formulario para agregar un nombre, email y contrasena:
```
<form action='https://google.com' method='post'>
    <fieldset>
        <label>Enter Your First Name: <input></label>
        <label>Enter Your Email: <input></label>
        <label>Create a New Password: <input></label>
    </fieldset>
</form>