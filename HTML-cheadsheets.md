### Estructura del documento HTML

1. Un elemento comienza con una etiqueta de apertura de una forma como ésta: <h1>

2. Un elemento termina con una etiqueta de cierre, igual que la de apertura, pero con
una diagonal, de esta forma: </h1>

3. El contenido del elemento siempre se escribirá dentro de las etiquetas de apertura y
cierre, por ejemplo: <h1>Fundamentos de diseño web</h1>

4. Las etiquetas también pueden contener atributos, por ejemplo:
 <a href="http://www.enlace.com" target="_blank">Enlace</a>
a. La etiqueta <a> es la etiqueta de apertura.
b. La etiqueta </a> es la etiqueta de cierre.
c. El texto “Enlace”, contenido entre las etiquetas <a> y </a>, es el contenido.
d. Los atributos son href y target.
e. http://www.enlace.com y _blank son las variables.

5. No todas las etiquetas abren y cierran, algunas etiquetas se conocen como “elementos
vacíos” que solo tienen una etiqueta. Por ejemplo, <br>, la cual produce un salto de
línea.

6. Pueden existir elementos anidados, es decir, etiquetas que se localizan dentro de otras
etiquetas, “heredando” la funcionalidad que le provee la etiqueta “padre” y
adquiriendo una nueva de la etiqueta “hija” o anidada, por ejemplo:
<p>En el párrafo hay palabras en <strong> negritas y en <em> itálica</em></strong>. </p>
Para que cualquier contenido que sea visible en tu página web, debe ir entre la etiqueta de
<body>, que abre, y la etiqueta de </body>, que es la encargada de cerrar el cuerpo de la
página.

```html
<!DOCTYPE html>
<html>
 <head>
 <meta charset="UTF-8">
 <title>Title</title>
 </head>
 <body>
 <!-- content here -->
 </body>
</html>
```

