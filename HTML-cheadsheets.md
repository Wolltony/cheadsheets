### Estructura del documento HTML

1. Un elemento comienza con una etiqueta de apertura de una forma como ésta: <h1>

2. Un elemento termina con una etiqueta de cierre, igual que la de apertura, pero con
una diagonal, de esta forma: </h1>

3. El contenido del elemento siempre se escribirá dentro de las etiquetas de apertura y
cierre, por ejemplo: <h1> Fundamentos de diseño web </h1>

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

Etiquetas

Las etiquetas dentro de HTML son bloques de código con apertura y cierre que indican al
navegador cómo interpretar el contenido que contienen las etiquetas (Sánchez, 2020).
Conocer las etiquetas HTML para su posterior uso es tema de interés para todo
desarrollador web, a continuación, el listado con las etiquetas agrupadas por categorías:

Etiquetas iniciales o de raíz
<!DOCTYPE html> Le indica al navegador el estándar en el que está basado, es
decir, en HTML5.
Raíz del documento. Todos los elementos tendrán que ir
dentro de esta etiqueta.
Etiqueta Función
<html> </html>
Etiquetas para metadatos
<head> </head> Representa un conjunto de metadatos sobre un documento,
incluidos enlaces o descripciones de texto y hojas de estilo.
Es donde se define el título del documento.
Sirve para enlazar recursos externos, como hojas de estilos
CSS.
Es donde se definen los metadatos (autor, descripción,
palabras clave).
Es donde se incorporan las reglas de CSS.
Etiqueta Función
<title> </title>
<link>
<meta>
<style> </style>
Etiquetas de secciones
<body> </body> Etiqueta que contiene todo el contenido que debe
mostrarse en la web.
Contiene la sección destinada a la navegación.
Contiene la sección destinada a la sección principal.
Contiene la sección destinada a alguna parte del
documento.
Contiene la sección destinada a espacios catalogados, como
artículos o mini secciones.
Etiqueta Función
<nav> </nav>
<main> </main>
<section> </section>
<article> </article>
05
Explicación Fundamentos de desarrollo web
<aside> </aside> Contiene la sección destinada a contenido adicional,
generalmente una parte lateral.
Contienen los textos que están destinados a ser títulos.
Contiene la sección destinada a la cabecera de la página.
Contiene la sección destinada al pie de página.
<h1>,<h2>,<h3>,<h4>,<h5>,<h6>
<header> </header>
<footer> </footer>
Etiquetas para agrupación de contenidos
<p> </p> Para escribir párrafos de texto.
Se utiliza como línea divisoria.
Para texto manteniendo el preformato.
Texto indicativo para citar una fuente.
Etiqueta para la creación de listas ordenadas.
Etiqueta para la creación de listas desordenadas.
Etiqueta que contiene elementos de listas (ordenadas o
desordenadas). Generalmente los elementos li se
encuentran anidados en los elementos ol o ul.
Etiqueta para la creación de listas de definiciones.
Especifica un término, descripción o definición. Se utiliza
dentro del elemento dl.
Provee detalles sobre la definición de un término que
procede de dt.
Representa contenido independiente.
Define la leyenda de una figura.
Etiqueta para originar un contenedor genérico.
Etiqueta Función
<hr>
<pre> </pre>
<blockquote> </blockquote>
<ol> </ol>
<li> </li>
<li> </li>
<dl> </dl>
<dt> </dt>
<dd> </dd>
<figure> </figure>
<figcaption> </figcaption>
<div> </div>
Etiquetas semánticas para texto
<a> </a> Etiqueta para hiperenlaces.
Formato en bold.
Formato en itálica.
Etiqueta Función
<strong> </strong>, <b> </b>
<em> </em>, <i> </i>
06
<u> </u> Formato en subrayado.
Formato de comentario tipo nota.
Formato para marcar una referencia o fuente.
Para marcar subíndices y superíndices.
Formato de resaltado de texto.
Contenedor de texto sin un significado en específico.
Salto de línea.
<small> </small>
<cite> </cite>
<sub> </sub> y <sup> </sup>
<mark> </mark>
<span> </span>
<br>
Explicación Fundamentos de desarrollo web
Etiquetas de incrustado de contenido
<img> Etiqueta para insertar imágenes.
Etiqueta que “anida” otro documento HTML.
Integración de contenido o aplicación externo.
Se utiliza para llamar a un recurso externo.
Etiqueta para insertar archivos de video.
Etiqueta para insertar archivos de audio.
Etiqueta para insertar recursos multimedia alternativos.
Etiqueta para insertar imagen vectorizada.
Etiqueta Función
<iframe> </iframe>
<embed>
<object> </object>
<video> </video>
<audio> </audio>
<source>
<svg> </svg>
Etiquetas para manejo de tablas
<img> Apertura y cierre de una tabla. Todas las etiquetas de
manejo de tablas deben ir dentro de esta etiqueta.
Indica el título de una tabla.
Agrupación de columnas de una tabla.
Cuerpo de una tabla
Cabecera de la tabla que describe los títulos de las
columnas.
Última fila de una tabla, generalmente el pie.
Para indicar las filas (table row).
Etiqueta Función
<iframe> </iframe>
<embed>
<object> </object>
<audio> </audio>
<source>
<svg> </svg>
07
Fundamentos de desarrollo web Explicación
La parte interactiva de HTML son los formularios, espacios en donde el usuario suele
introducir valores numéricos, textuales, de fechas, rangos u opciones como activar,
desactivar, verdadero, falso, etc. (MDN Web Docs, 2022, -a).
Formularios
Las siglas CSS representan el término Cascading Style Sheets, cuya traducción es Hoja de
Estilos en Cascada. Atendiendo a la traducción de su nombre, se puede decir que esa hoja
de estilos describe cómo se mostrarán los elementos del HTML (MDN Web Docs, 2022. -b),
respetando cada una de las reglas, línea por línea (cascada).
Dentro del CSS se definen los estilos y el diseño, así como la disposición y variaciones de
tamaño y comportamiento de los elementos.
Conceptos básicos de CSS
<td> </td> Para definir una celda de una tabla.
<th> </th> Para definir el encabezado de una celda.
Etiquetas para la creación de formularios
<form> </form>
Etiqueta de apertura y cierra que engloba un formulario.
Todas las etiquetas sobre formularios deben de ir dentro
de ésta.
Permite organizar grupos de campos.
Ligada al fieldset indica el título del fieldset.
Leyenda, nombre o título de un control de formulario.
Campo de introducción de datos para el usuario. Se le da
diferente finalidad haciendo uso de sus atributos.
Botón dentro del formulario.
Input para la selección entre un conjunto de opciones.
Está ligada a select, que permite añadir opciones.
Campo de introducción de texto.
Etiqueta Función
<fieldset> </fieldset>
<legend> </legend>
<label> </label>
input>
<button> </button>
<select> </select> I
<option> </option>
<textarea> </textarea> 
