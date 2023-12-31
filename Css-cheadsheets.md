# __MI HOJA DE TRUCOS DE CSS__


Conceptos básicos de CSS:

Las siglas CSS representan el término Cascading Style Sheets, cuya traducción es Hoja de
Estilos en Cascada. Atendiendo a la traducción de su nombre, se puede decir que esa hoja
de estilos describe cómo se mostrarán los elementos del HTML (MDN Web Docs, 2022. -b),
respetando cada una de las reglas, línea por línea (cascada).
Dentro del CSS se definen los estilos y el diseño, así como la disposición y variaciones de
tamaño y comportamiento de los elementos.

## Sintaxis:

__h1__

Selector


__{color: blue; Font-size: 14px;}__

Declaración

__color:__ 

Propiedad

__blue;__

Valor

__Font-size:__

Propiedad

__14px;__

Valor

• El selector hace referencia a la etiqueta HTML a la que se le quiere aplicar el
formato.

• El bloque de declaración contiene una o más declaraciones contenidas en
llaves, y separadas (preferentemente línea a línea) por punto y coma.

• Cada declaración con tiene un nombre de la propiedad CSS y un valor. Estos se
separan por dos puntos.


## Maquetación:


Maquetar en CSS tiene como objetivo brindarle al usuario una apariencia mejorada, única
y atractiva de la página que se crea, donde es fácil distinguir cada elemento, para resaltar
los detalles importantes de cada uno.

Desde la perspectiva de un diseñador, el estilo CSS funciona para separar el contenido de
la presentación o el diseño en el que debe mostrarse. Debemos recordar que, si separamos
estas dos cosas, será más fácil guardar páginas y administrar información. Gracias a esto,
también podemos obtener páginas limpias y claras, según el código.


## Fuentes y texto:


Las fuentes constituyen uno de los elementos más importantes en una página web, ya que
representa los recursos que el usuario tendrá a su disposición en forma de información
textual, esencial para la transmisión de ideas a los usuarios. Las fuentes comprenden:
títulos, párrafos, pies de página, contenido textual de tablas e información en general,
tomando en cuenta el tipo de letra, su color, tamaño, sombra y cualquier característica
ligada a los textos. A continuación, exploraremos propiedades ligadas al tratamiento de los
textos y fuentes:


## Propiedades del texto:


__text-indent__ 

Desplazamiento de la primera línea del texto. 

longitud | porcentaje



__text-align__

Alineación del texto.

left | right | center | justify


__text-decoration__

Efectos de subrayado y tachado. 

none | underline | overline | line-through | * 


__letter-spacing__ 

Espacio entre caracteres.

normal | longitud 


__word-spacing__ 

Espacio entre palabras.

normal | longitud


__text-transform__

Convertir a mayúsculas /minúsculas.

capitalize | uppercase | lowercase | none 


__line-height__ 

Tamaño del espacio entre líneas. 

longitud | porcentaje


__vertical-align__

Alineación vertical.

top | middle | bottom baseline | sub | super | valor


__font-family__

Familias de fuentes. 

nombre-familia|nombre-familia-genérica| * 


__font-style__ 

Estilo de la fuente. 

normal | italic | oblique


__font-variant__ 

Convierte a mayúsculas manteniendo un tamaño inferior.

normal | small-caps


__font-weight__

Anchura de los caracteres. Normal = 400, Negrita = 700.

normal | bold | bolder | lighter | 100 | 200 | 300 | 400 | 500 | 600 |700 | 800 | 900


__font-size__

Tamaño de la fuente.

xx-small | x-small | small | medium | large | x-large | xx-large | larger | smaller | longitud | porcentaje



## Color y fondos:


Los colores en CSS se pueden indicar de cinco formas distintas:
• Por palabras clave.
• Por colores del sistema.
• Por RGB.
• Por Hexadecimal.
• Por RGB numérico y RBG porcentual.

A continuación, se presentan los colores básicos:

__black__

HEX

#000000

RGB

0,0,0


__white__

#ffffff

255,255,255


__red__

#ff0000

255,0,0


__blue__

#0000ff

0,0,255


__yellow__

#ffff00

255,255,0


__gray__


#808080

128,128,128



__green__


#008000


0,128,0 



## Propiedades de color y fondo


__color__

Color del texto 

RGB | HSL | HEX | nombre del color | RGBA | HSLA

__background-color__

Color de fondo 

RGB | HSL | HEX | nombre del color | RGBA | HSLA



__background-image__

Imagen de fondo 

url(…)| none


__background-repeat__

Repetición de la imagen de fondo.

repeat | repeat-x | repeat-y | no-repeat 


__background-attachment__

Posición de la imagen de fondo. 

scroll | fixed 


__background-position__ 

Posición de la imagen de fondo. 

percentage | length | left | center | right


__background-size__


Tamaño de la imagen de fondo.

 valor

 
__Opacity__

Transparencia de un elemento.

t [ 0 – 1 ] (0 ° totalmente transparente) 



## Listas


Las listas en HTML son aquellos elementos textuales que nos permiten crear conjuntos de
elementos en forma de lista, pueden encontrarse como listas ordenadas, listas
desordenadas, o listas de definiciones (ManualWeb, s.f.). A continuación, sus propiedades:


__list-style-type__ 

Estilo aplicable a los marcadores visuales de las listas.


disc | circle | square | decimal | decimal-leading-zero | lower-roman | upper-roman | lower-greek | lower-latin |
upper-latin | armenian | georgian | lower-alpha | upper-alpha | none



__list-style-image__

Imagen aplicable a los elementos de las listas.

url(«…») | none



__list-style-position__

Posición dentro de la lista de los elementos marcadores de las listas.

inside | outside



__list-style__

Permite establecer el estilo de la lista, la imagen y/o la posición.

list-style-type | list-style-position | list-style-image 



## Bordes

Los bordes son propiedades que se sirven para establecer a los elementos un ancho, estilo
y color.

Las propiedades de los bordes se establecen en los cuatro lados del contendedor y adicional al borde,
existen secciones internas (padding) y externas (margin), que es el espacio entre el borde y el contenedor 
(para el padding) y de otros elementos y el borde (margin). Sus propiedades son las siguientes:

__Propiedades de los borders:__


__padding-top
padding-right
padding-bottom
padding-left__

Tamaño del relleno superior, derecho, inferior e izquierdo. 

longitud | porcentaje 



__padding__

Tamaño del relleno. 

longitud | porcentaje {1,4}



__margin-top
margin-right
margin-bottom
margin-left__

Tamaño del margen superior, derecho, inferior e izquierdo. 

longitud | porcentaje | auto



__margin__ 

Ancho de los márgenes. 

longitud | porcentaje | auto {1,4}



__border-top-width
border-right-width
border-bottom-width
border-left-width__

Anchura del borde superior, derecho, inferior o izquierdo. 

thin | medium | thick | longitud



__border-width__

Anchura del borde (reducida). 

thin | medium | thick | longitud {1,4}



__border-top-color
border-right-color
border-bottom-color
border-left-color__

Color del borde superior, derecho, inferior e izquierdo. 

color | transparent



__border-color__

Color del borde (reducida).

color | transparent {1,4}



__border-top-style
border-right-style
border-bottom-style
border-left-style__

Estilo del borde superior, derecho, inferior e izquierdo.

none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset



__border-style__

Estilo del borde (reducida).

none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset {1,4}



__border-top
border-right
border-bottom
border-left__

Ancho, estilo y color para el borde superior, derecho, inferior e izquierdo.

border-top-width | border-top-style | border-top-color



__border__

Ancho, estilo y color para los bordes (reducida).

border-width | border-style | border-color 



__border-radius__ 

Curvatura del borde. 

longitud | porcentaje {1,4}




