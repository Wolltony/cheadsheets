# __MI HOJA DE TRUCOS DE CSS__


Conceptos básicos de CSS:

Las siglas CSS representan el término Cascading Style Sheets, cuya traducción es Hoja de
Estilos en Cascada. Atendiendo a la traducción de su nombre, se puede decir que esa hoja
de estilos describe cómo se mostrarán los elementos del HTML (MDN Web Docs, 2022. -b),
respetando cada una de las reglas, línea por línea (cascada).
Dentro del CSS se definen los estilos y el diseño, así como la disposición y variaciones de
tamaño y comportamiento de los elementos.

Sintaxis:

h1

Selector


{color: blue; Font-size: 14px;}

Declaración

color: 

Propiedad

blue;

Valor

Font-size:

Propiedad

14px;

Valor

• El selector hace referencia a la etiqueta HTML a la que se le quiere aplicar el
formato.

• El bloque de declaración contiene una o más declaraciones contenidas en
llaves, y separadas (preferentemente línea a línea) por punto y coma.

• Cada declaración con tiene un nombre de la propiedad CSS y un valor. Estos se
separan por dos puntos.


Maquetación:


Maquetar en CSS tiene como objetivo brindarle al usuario una apariencia mejorada, única
y atractiva de la página que se crea, donde es fácil distinguir cada elemento, para resaltar
los detalles importantes de cada uno.

Desde la perspectiva de un diseñador, el estilo CSS funciona para separar el contenido de
la presentación o el diseño en el que debe mostrarse. Debemos recordar que, si separamos
estas dos cosas, será más fácil guardar páginas y administrar información. Gracias a esto,
también podemos obtener páginas limpias y claras, según el código.


Fuentes y texto:


Las fuentes constituyen uno de los elementos más importantes en una página web, ya que
representa los recursos que el usuario tendrá a su disposición en forma de información
textual, esencial para la transmisión de ideas a los usuarios. Las fuentes comprenden:
títulos, párrafos, pies de página, contenido textual de tablas e información en general,
tomando en cuenta el tipo de letra, su color, tamaño, sombra y cualquier característica
ligada a los textos. A continuación, exploraremos propiedades ligadas al tratamiento de los
textos y fuentes:


Propiedades del texto:


text-indent 
Desplazamiento de la primera línea del texto. 
longitud | porcentaje



text-align
Alineación del texto.
left | right | center | justify


text-decoration
Efectos de subrayado y tachado. 
none | underline | overline | line-through | * 


letter-spacing 
Espacio entre caracteres.
normal | longitud 


word-spacing 
Espacio entre palabras.
normal | longitud


text-transform
Convertir a mayúsculas /minúsculas.
capitalize | uppercase |
lowercase | none 


line-height 
Tamaño del espacio entre líneas. 
longitud | porcentaje


vertical-align
Alineación vertical.
top | middle | bottom baseline | sub | super | valor


font-family
Familias de fuentes. 
nombre-familia|nombre-familia-genérica| * 


font-style 
Estilo de la fuente. 
normal | italic | oblique


font-variant 
Convierte a mayúsculas manteniendo un tamaño inferior.
normal | small-caps


font-weight
Anchura de los caracteres. Normal = 400, Negrita = 700.
normal | bold | bolder | lighter | 100 | 200 | 300 | 400 | 500 | 600 |700 | 800 | 900


font-size
Tamaño de la fuente.
xx-small | x-small | small | medium | large | x-large | xx-large | larger | smaller | longitud | porcentaje


Color y fondos:



