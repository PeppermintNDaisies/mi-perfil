# Mi Perfil
Ejercicio de HTML

En este proyecto van a encontrar 2⃣ archivos:
- index.html
- perfil.html

En el primero encontrarán el contenido de la primera página, la de inicio, y en el segundo encontrarán el contenido de la página de "Mi Perfil". Para hacer este ejercicio tienen dos opciones: descargarlo y modificarlo, o seguir los pasos que se encuentran en esta guía para hacerlo de cero. 

# Descargar el Proyecto

En la parte de arriba de este documento haz click en el botón **Clone or Download** y luego en el botón **Download ZIP**

![](https://cdn.sparkfun.com/assets/learn_tutorials/1/1/DownloadZip2.jpg)


# Hacerlo de Cero

### Crear un Archivo index.html

Dentro del *tag* `<body> </body>` insertar el siguiente fragmento de código

```<h1>Hola todos</h1>

    <a href="perfil.html" target="_blank">Mi perfil nueva pestaña</a>
    <br>
    <a href="perfil.html">Mi perfil misma pestaña</a>
 ```
- El *tag* `<h1>` hace referencia a un *elemento* de tipo título.
- El *tag* `<br>` se usa para generar espacios entre líneas.
- El *tag* `<a>` hace referencia a un *elemento* de tipo vínculo o link. 
    - Dentro de este tag, el atributo `target="_blank"` significa que el vínculo va a abrir en una pestaña nueva
    - Dentro de este tag, el atributo `href="perfil.html"` significa que el vínculo apunta a este archivo
- El *tag* `<a>` hace referencia a un *elemento* de tipo vínculo o link.

### Crear un Archivo perfil.html

Dentro del *tag* `<body> </body>` insertar el siguiente fragmento de código

```<h1><a href="index.html">Inicio</a> - Mi perfil</h1>

    <h2>Foto</h2>
    <a href="https://www.eltiempo.com" target="_blank">
        <img src="https://www.ecestaticos.com/imagestatic/clipping/dfd/996/dfd996d0c22dd7e69412274972f5598d/por-que-nos-parece-que-los-perros-sonrien-una-historia-de-30-000-anos.jpg?mtime=1558346796" alt="Foto de perfil" width="300">
    </a>

    <marquee behavior="" direction="right">Diegooooo</marquee>

    <p>
        Esto es un texto: <b>Negrita</b> <strong>otro tipo de negrita</strong>
        <i>Italica</i> <u>subrayada</u> <strike>rayado</strike>
    </p>

    <h2>Datos personales</h2>

    <p>Cel: 3504897911</p>
    <p>Correo: diegorbaquero@gmail.com</p>
    <p><a href="https://github.com/DiegoRBaquero">GitHub</a></p>
```
- El *tag* `<h2>` hace referencia a un *elemento* de tipo título.
- El *tag* `<img>` hace referencia a un *elemento* de tipo imagen.
    - Dentro de este tag, el atributo `scr=" "` indica el lugar en el que se encuentra ubicada la imagen (archivo en su computador o un link a una imágen)
- El *tag* `<p>` hace referencia a un *elemento* de tipo párrafo.
- El *tag* `<marquee>` hace referencia a un *elemento* que se mueve.
