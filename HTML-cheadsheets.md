# **MI HOJA DE TRUCOS DE HTML**
-----------------------------
## __Estructura de un documento de HTML__

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

El portal para developers de Mozilla define a HTML (Hypertext Markup Language) como el
componente principal de Internet. Es el que describe el significado y la estructura del
contenido de los documentos web. Además de HTML, a menudo suelen utilizarse otras
tecnologías para definir la apariencia de una página web (con CSS), la funcionalidad o
comportamiento (con JavaScript), (MDN Web Docs, 2022 -a).

Hay que hacer énfasis en que HTML no es un lenguaje de programación, sino un lenguaje
de marcado que le proporciona a los navegadores web reglas sobre cómo estructurar las
páginas. Entonces, HTML consiste en una serie de elementos que se utilizan para
encerrar, delimitar, marcar o etiquetar diferentes partes que conforman un contenido para
hacer que obtengan una estructura, misma que será posteriormente formateada con
otro lenguaje de etiquetado (CSS).

Un elemento HTML responde a la siguiente sintaxis, haciendo uso de los símbolos “<” y “>”
(menor que y mayor que):

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

Etiquetas:

Las etiquetas dentro de HTML son bloques de código con apertura y cierre que indican al
navegador cómo interpretar el contenido que contienen las etiquetas (Sánchez, 2020).
Conocer las etiquetas HTML para su posterior uso es tema de interés para todo
desarrollador web, a continuación, el listado con las etiquetas agrupadas por categorías:

Etiquetas iniciales o de raíz:

<!DOCTYPE html>
Le indica al navegador el estándar en el que está basado, es
decir, en HTML5.

<html> </html>
Raíz del documento. Todos los elementos tendrán que ir
dentro de esta etiqueta.

Etiquetas para metadatos:

<head> </head>
Representa un conjunto de metadatos sobre un documento,
incluidos enlaces o descripciones de texto y hojas de estilo.

<title> </title>
Es donde se define el título del documento.

<link>
Sirve para enlazar recursos externos, como hojas de estilos
CSS.

<meta>
Es donde se definen los metadatos (autor, descripción,
palabras clave).

<style> </style>
Es donde se incorporan las reglas de CSS.

Etiquetas de secciones:

<body> </body>
Etiqueta que contiene todo el contenido que debe
mostrarse en la web.

<nav> </nav>
Contiene la sección destinada a la navegación.

<main> </main>
Contiene la sección destinada a la sección principal.

<section> </section>
Contiene la sección destinada a alguna parte del
documento.

<article> </article>
Contiene la sección destinada a espacios catalogados, como
artículos o mini secciones.

<aside> </aside>
Contiene la sección destinada a contenido adicional,
generalmente una parte lateral.

<h1>,<h2>,<h3>,<h4>,<h5>,<h6>
Contienen los textos que están destinados a ser títulos.

<header> </header>
Contiene la sección destinada a la cabecera de la página.

<footer> </footer>
Contiene la sección destinada al pie de página.


Etiquetas para agrupación de contenidos:

<p> </p>
Para escribir párrafos de texto.

<hr>
Se utiliza como línea divisoria.

<pre> </pre>
Para texto manteniendo el preformato.

<blockquote> </blockquote>
Texto indicativo para citar una fuente.

<ol> </ol>
Etiqueta para la creación de listas ordenadas.

<li> </li>
Etiqueta para la creación de listas desordenadas.

<li> </li>
Etiqueta que contiene elementos de listas (ordenadas o
desordenadas). Generalmente los elementos li se
encuentran anidados en los elementos ol o ul.

<dl> </dl>
Etiqueta para la creación de listas de definiciones.

<dt> </dt>
Especifica un término, descripción o definición. Se utiliza
dentro del elemento dl.

<dd> </dd>
Provee detalles sobre la definición de un término que
procede de dt.

<figure> </figure>
Representa contenido independiente.

<figcaption> </figcaption>
Define la leyenda de una figura.

<div> </div>
Etiqueta para originar un contenedor genérico.


Etiquetas semánticas para texto:


<a> </a>
Etiqueta para hiperenlaces.

<strong> </strong>, <b> </b>
Formato en bold.

<em> </em>, <i> </i>
Formato en itálica.

<u> </u>
Formato en subrayado.

<small> </small>
Formato de comentario tipo nota.

<cite> </cite>
Formato para marcar una referencia o fuente.

<sub> </sub> y <sup> </sup>
Para marcar subíndices y superíndices.

<mark> </mark>
Formato de resaltado de texto.

<span> </span>
Contenedor de texto sin un significado en específico.

<br>
Salto de línea.



Etiquetas de incrustado de contenido:


<img>
Etiqueta para insertar imágenes.

<iframe> </iframe>
Etiqueta que “anida” otro documento HTML.

<embed>
Integración de contenido o aplicación externo.


<object> </object>
Se utiliza para llamar a un recurso externo.

<video> </video>
Etiqueta para insertar archivos de video.

<audio> </audio>
Etiqueta para insertar archivos de audio.

<source>
Etiqueta para insertar recursos multimedia alternativos.

<svg> </svg>
Etiqueta para insertar imagen vectorizada.


Etiquetas para manejo de tablas:


<img>
Apertura y cierre de una tabla. Todas las etiquetas de
manejo de tablas deben ir dentro de esta etiqueta.

<iframe> </iframe>
Indica el título de una tabla.

<embed>
Agrupación de columnas de una tabla.

<object> </object>
Cuerpo de una tabla

<audio> </audio>
Cabecera de la tabla que describe los títulos de las
columnas.

<source>
Última fila de una tabla, generalmente el pie.
Para indicar las filas (table row).

<svg> </svg>
Para indicar las filas (table row).

<td> </td>
Para definir una celda de una tabla.

<th> </th>
Para definir el encabezado de una celda.


Formularios:

La parte interactiva de HTML son los formularios, espacios en donde el usuario suele
introducir valores numéricos, textuales, de fechas, rangos u opciones como activar,
desactivar, verdadero, falso, etc. (MDN Web Docs, 2022, -a).


Etiquetas para la creación de formularios:


<form> </form>
Etiqueta de apertura y cierra que engloba un formulario.
Todas las etiquetas sobre formularios deben de ir dentro
de ésta.


<fieldset> </fieldset>
Permite organizar grupos de campos.


<legend> </legend>
Ligada al fieldset indica el título del fieldset.


<label> </label>
Leyenda, nombre o título de un control de formulario.


input>
Campo de introducción de datos para el usuario. Se le da
diferente finalidad haciendo uso de sus atributos.


<button> </button>
Botón dentro del formulario.


<select> </select> I
Input para la selección entre un conjunto de opciones.


<option> </option>
Está ligada a select, que permite añadir opciones.


<textarea> </textarea> 
Campo de introducción de texto.










