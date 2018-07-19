# Guía rápida de Evaluación de Accesibilidad Web

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


  - [Introducción](#introducci%C3%B3n)
  - [Estructura de la guía](#estructura-de-la-gu%C3%ADa)
  - [Herramientas utilizadas para las verificaciones](#herramientas-utilizadas-para-las-verificaciones)
  - [Aspectos generales de accesibilidad web](#aspectos-generales-de-accesibilidad-web)
    - [Título de la página](#t%C3%ADtulo-de-la-p%C3%A1gina)
    - [Texto alternativo para imágenes](#texto-alternativo-para-im%C3%A1genes)
    - [Contenido con movimiento, destellos o parpadeo](#contenido-con-movimiento-destellos-o-parpadeo)
    - [Alternativas multimedia (audio o video)](#alternativas-multimedia-audio-o-video)
    - [Estructura básica de la página web](#estructura-b%C3%A1sica-de-la-p%C3%A1gina-web)
  - [Aspectos de accesibilidad web referentes al texto](#aspectos-de-accesibilidad-web-referentes-al-texto)
    - [Uso de encabezados](#uso-de-encabezados)
    - [Contraste del texto](#contraste-del-texto)
    - [Cambio de tamaño del texto](#cambio-de-tama%C3%B1o-del-texto)
  - [Aspectos de accesibilidad web referentes a la interacción](#aspectos-de-accesibilidad-web-referentes-a-la-interacci%C3%B3n)
    - [Acceso por teclado y foco](#acceso-por-teclado-y-foco)
    - [Formularios, etiquetas y errores](#formularios-etiquetas-y-errores)
  - [Referencias](#referencias)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introducción

Esta guía se orienta a detectar y solucionar los problemas más comunes de accesibilidad web. La eliminación de estas barreras no significa de ningún modo cumplir en su totalidad con las "[Pautas de Accesibilidad de Contenido Web 2.0](http://www.codexexempla.org/traducciones/pautas-accesibilidad-contenido-web-2.0.htm)" (WCAG 2.0), lo cual requerirá una evaluación de accesibilidad completa que verifique cada uno de los criterios de conformidad.
De forma similiar sucede con la [Ley N° 26.653 de “Accesibilidad de la Información en las Páginas Web”](http://servicios.infoleg.gob.ar/infolegInternet/anexos/175000-179999/175694/norma.htm) y la [Disposición ONTI N° 2/2014](http://servicios.infoleg.gob.ar/infolegInternet/anexos/230000-234999/233667/norma.htm), la presente Guía facilita el cumplimiento de ambas pero no lo asegura, para ello deberá referirse especificamente a las normas citadas.

La Guía está dirigida a personas con cierto conocimiento técnico aunque no necesariamente desarrolladores o expertos en accesibilidad web. El documento ha sido inspirado en la publicación de la [W3C](https://www.w3c.es/Consorcio/): "[Chequeos básicos - Una primera revisión de accesibilidad web](https://www.w3.org/WAI/eval/preliminary)" ("Easy Checks - A First Review of Web Accessibility", en inglés); a partir de este recurso se ha adaptado el texto e incluido herramientas de evaluación diferentes de las propuestas en la publicación original.

Este es un documento propuesto por la Oficina Nacional de Tecnologias de Información de Argentina, sujeto a discusión, colaborativo y en progreso. Es por ello, que alentamos a organizaciones y ciudadanos a hacernos sugerencias o comentarios que nos ayuden a mejorarlo. Trabajamos fuertemente para incluir referencias en castellano pero esto no ha sido posible en todos los casos, si encontró alguna que hayamos puesto en otro idioma y podamos reemplazarla nos encantaría conocerla.

## Estructura de la guía

Para cada uno de los aspectos considerados en la guía se comentará brevemente:

* una recomendación general referenciada en las WCAG 2.0.

* qué y cómo verificar el cumplimiento de esa recomendación con el uso de las herramientas "Wave Evaluation Tool" y “Web Developer Toolbar”.

* ejemplo del código html respecto a la recomendación (sólo para algunas recomendaciones).

## Herramientas utilizadas para las verificaciones

La lista de herramientas utilizadas en las verificaciones es la de la tabla a continuación. Es importante aclarar que si bien hemos seleccionado estas herramientas en particular, no las recomendamos especialmente por sobre otras ni garantizamos su buen funcionamiento. La W3C permite consultar un extenso "[listado de herramientas de evaluación de accesibilidad web](https://www.w3.org/WAI/ER/tools/)" (en inglés) donde pueden encontrarse estas y muchas otras.


<table>
  <tr>
    <th>Herramienta de evaluación</th>
    <th>Extensión para Mozilla Firefox</th>
    <th>Extensión para Google Chrome</th>
    <th>Extensión para MS Internet Explorer</th>
    <th>Repositorio de código abierto</th>
  </tr>
  <tr>
    <td><a href="http://wave.webaim.org/extension/" title="Wave Evaluation Tool - Sitio del proyecto">Wave Evaluation Tool - Sitio del proyecto</a>
</td>
    <td><a href="https://addons.mozilla.org/en-US/firefox/addon/wave-accessibility-tool/" title="WAVE Evaluation Tool - Extensión para Mozilla Firefox" >WAVE Evaluation Tool - Extensión para Mozilla Firefox</a></td>
    <td> <a href="https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh" title="WAVE Evaluation Tool - Extensión para Google Chrome" >WAVE Evaluation Tool - Extensión para Google Chrome</a></td>
    <td>Sin datos disponibles</td>
    <td>Sin datos disponibles</td>
  </tr>
  <tr>
    <td><a href="https://chrispederick.com/work/web-developer/" title="Web Developer Toolbar - Sitio del proyecto" >Web Developer Toolbar - Sitio del proyecto</a></td>
    <td><a href="https://addons.mozilla.org/es/firefox/addon/web-developer/" title="Web Developer Toolbar - Extensión para Mozilla Firefox" >Web Developer Toolbar - Extensión para Mozilla Firefox</a></td>
    <td><a href="https://chrome.google.com/webstore/detail/web-developer/bfbameneiokkgbdmiekhjnmfkcnldhhm" title="Web Developer Toolbar - Extensión para Google Chrome">Web Developer Toolbar - Extensión para Google Chrome</a></td>
    <td>Sin datos disponibles</td>
    <td><a href="https://github.com/chrispederick/web-developer/" title="Web Developer Toolbar - Repositorio de código abierto" >Web Developer Toolbar - Repositorio de código abierto</a></td>
  </tr>
  <tr>
    <td><a href="https://developer.paciellogroup.com/resources/wat" title="Web Accessibility Toolbar - Sitio del proyecto">Web Accessibility Toolbar - Sitio del proyecto</a></td>
    <td>Sin datos disponibles</td>
    <td>Sin datos disponibles</td>
    <td><a href="https://developer.paciellogroup.com/resources/wat/" title="Web Accessibility Toolbar - Extensión para MS Internet Explorer">Web Accessibility Toolbar - Extensión para MS Internet Explorer</a></td>
    <td> <a href="https://github.com/ThePacielloGroup/WebAccessibilityToolbar/releases/tag/2015-05-20" title="Web Accessibility Toolbar - Repositorio de código abierto">Web Accessibility Toolbar - Repositorio de código abierto</a>
</td>
  </tr>
</table>



Para la mayoría de las verificaciones se han utilizado las herramientas "Wave Evaluation Tool" y “Web Developer Toolbar” por estar ambas disponibles para los navegadores Mozilla Firefox y Google Chrome. La herramienta “Wave Evaluation Tool” realiza un chequeo completo de la página web en base a las pautas de accesibilidad. La “Web Developer Toolbar” está orientada al desarrollo web en general y no específicamente a la accesibilidad, por lo que permite realizar diferentes operaciones con imágenes, CSS, etc.

Previamente a las verificaciones deberá agregar las barras a su navegador como "extensiones". Una ventaja destacable de utilizar barras integradas al navegador, a diferencia de las herramientas de evaluación en línea, es que no es necesario que la página web evaluada esté publicada, pudiéndose incluso evaluar secciones del sitio web que requieren logueo. 

Las herramientas comentadas en esta guía están disponibles sólo en idioma inglés, pero son de fácil operación y detallamos los pasos para su uso. Si el lector lo prefiere puede utilizar servicios en línea en castellano para evaluar la accesibilidad de una página web, por ejemplo:

* [Evaluador Examinator](http://examinator.ws/) - Autor: Carlos Benavidez.

* [Evaluador TAW](http://www.tawdis.net/) - Autor: Fundación CTIC.

Estos dos servicios en línea permiten diagnosticar de manera rápida y sencilla los principales errores de accesibilidad que pudiera presentar la página evaluada. Sin embargo, muchas de las pautas requieren complementar esta evaluación "automática" con una evaluación "manual". Para más información sobre esta distinción consulte el apartado [¿Cómo evaluar la accesibilidad web de una página web?]( https://github.com/argob/accesibilidad-web/blob/master/docs/recomendaciones_pautas_accesibilidad_web.md#c%C3%B3mo-evaluar-la-accesibilidad-web-de-una-p%C3%A1gina-web) del documento "Recomendaciones básicas para cumplimiento de las Pautas de Accesibilidad Web" de la ONTI.

A continuación presentamos cómo verificar los aspectos más importantes de accesibilidad web, agrupados en las siguientes dimensiones:

* Aspectos generales de accesibilidad web.

* Aspectos de accesibilidad web referentes al texto.

* Aspectos de accesibilidad web referentes a la interacción

Como comentario final de este apartado, y si bien no se trata especificamente de herramientas de evaluación de accesibilidad web, recomendamos validar el código html/ xhtml y css de las páginas mediante los validadores específicos disponibles en el sitio de la W3C:

* [Validador de html/ xhtml](https://validator.w3.org)

* [Validador de CSS](http://jigsaw.w3.org/css-validator/)


## Aspectos generales de accesibilidad web

### Título de la página

#### Recomendación

La página web debe tener un título que describa su temática o propósito.

(Ref.: WCAG 2.0; [criterio de conformidad 2.4.2](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-title.html), Nivel A)

#### ¿Qué y cómo verificar?

Verificar que el título de la página exista y sea realmente descriptivo del contenido.

Para verificar, leer el título de la página en la ventana o en la pestaña del navegador.

Alternativamente, para verificar puede utilizarse la "Web Developer toolbar":

1. Abrir la página web a chequear.

2. En la barra, seleccionar "Tools", luego "View Source". Se abre una ventana.

3. Verificar.

#### Código html de ejemplo

```
<head>     
      <title>The World Wide Web Consortium</title>     
   </head>  
```

### Texto alternativo para imágenes

#### Recomendación

Las alternativas textuales para las imágenes están orientadas a aquellos usuarios que no pueden verlas. Cada imagen debe tener el atributo "alt" y este debe ser apropiado según el contexto en el que se use. Por ejemplo:

* como equivalente funcional. La imagen de una lupa que con un click realiza una búsqueda debería tener su atributo definido `alt="buscar"` y no `alt="lupa"`.

* como descripción del texto. El logo de la W3C podría ser `alt="W3C logo”`.

* entre otros casos.

(Ref.: WCAG 2.0; [criterio de conformidad 1.1.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv-all.html), Nivel A)

#### ¿Qué y cómo verificar?

Verificar que el atributo ´"alt"´ exista y que su contenido sea apropiado. 

Para verificar usando la "WAVE web accessibility toolbar":

1. Abrir la página web a chequear.

2. Clickear el botón "WAVE".

3. Para ver cuales son los `"alt"` que faltan, busque el título "Errors” y los íconos rojos con las leyendas: “Missing alt text" y “Linked image missing alternative text”.

4. Para chequear que el texto `"alt"` sea correcto, busque el título “Features” y los íconos verdes con las leyendas: “Alternative text” y “Linked image with alternative text”.

5. Verificar.

#### Código html de ejemplo

```
<img src="newsletter.gif" alt="Suscribite a las noticias!" />
```

### Contenido con movimiento, destellos o parpadeo

#### Recomendación

El contenido con movimiento, destellos o parpadeo puede afectar a distintos tipos de usuarios especialmente a aquellos con problemas visuales o de atención. Este tipo de contenido incluye carousels, sliders, contenido actualizable automaticamente, etc.

(Ref.: WCAG 2.0; [criterio de conformidad 2.2.2](https://www.w3.org/TR/UNDERSTANDING-WCAG20/time-limits-pause.html);  [criterio de conformidad 2.3.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/seizure-does-not-violate.html); Nivel A)

#### ¿Qué y cómo verificar?

Verificar:

* que el contenido con movimiento o parpadeante dure más de cinco segundos y pueda ser pausado, detenido u ocultado.

* si existe contenido que se actualiza automáticamente, que este contenido pueda ser pausado, detenido u ocultado.

* que no exista contenido que destelle o parpadee más de tres veces por segundo.

Podrán realizarse esas verificaciones mediante la observación de la página web en el navegador.

### Alternativas multimedia (audio o video)

#### Recomendación

Para la información audible debe proveerse un formato alternativo tal cómo una transcripción. Los videos deben tener subtítulos, transcripciones y opcionalmente audiodescripciones.

(Ref.: WCAG 2.0; [criterio de conformidad 1.2.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-av-only-alt.html), [criterio de conformidad 1.2.2](https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-captions.html), [criterio de conformidad 1.2.3](https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-audio-desc.html); Nivel A)

#### ¿Qué y cómo verificar?

Verificar que:

* las transcripciones incluyan toda la información audible.

* los subtítulos existan, sean precisos y estén sincronizados.

* las audiodescripciones incluyan toda la información visible importante.

Podrán realizarse estas verificaciones directamente en la página web presentada en el navegador.

### Estructura básica de la página web

#### Recomendación

La estructura del sitio debe simplificar el acceso al contenido para el usuario que no pueden acceder al mismo de manera visual. Por ello, se analizará el sitio desactivando imágenes y estilos, acercándonos a la funcionalidad de un lector de pantalla o un display Braille. Esta característica no responde a un único criterio de conformidad, es más amplia.

(Ref.: WCAG 2.0; [criterio de conformidad 1.3.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-programmatic.html), Nivel A; [criterio de conformidad 1.3.2](https://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-sequence.html); [criterio de conformidad 2.4.6](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-descriptive.html), Nivel AA)

#### ¿Qué y cómo verificar?

Verificar que la página web mantenga una estructura fácilmente comprensible.

Para verificar usando la "Web Developer toolbar":

1. Abrir la página web a chequear.

2. En la barra, seleccionar "Images", luego "Disable Images", luego "Disable All Images".

3. En la barra, seleccionar "CSS", luego "Disable Styles", luego "Disable All Styles". 

4. En la barra, seleccionar "Miscellaneous", luego "Linearize Page".

5. Verificar explorando el contenido de la página chequeando que el orden en el cual este se presenta tenga sentido. Por ejemplo: que los encabezados se correspondan con el contenido que presentan, que la sección "footer" se presente debajo de todo el contenido, que las opciones de navegación contribuyan a la accesibilidad del sitio, etc.

## Aspectos de accesibilidad web referentes al texto

### Uso de encabezados

#### Recomendación

Utilizar encabezados, es decir etiquetas del tipo `"<h1>"`, `“<h2>”`, etc., conservando para ellos una jerarquía lógica. Los lectores de pantalla por ejemplo, permiten navegar encabezados facilitando el acceso la página web. Una representación sería:

```
* Nivel de encabezado 1 <h1>

    * Nivel de encabezado 2 <h2>

        * Nivel de encabezado 3 <h3>

        * Nivel de encabezado 3 <h3>

* Nivel de encabezado 2 <h2>
```


#### ¿Qué y cómo verificar?

Verificar en la página web:

* la existencia de al menos un encabezado `"<h1>"`.

* que la jerarquía de encabezados sea lógica y que no se salten niveles.

* que el texto que parezca un encabezado en la página original, así lo sea también en el código.

* que el orden de los encabezados de la página "en formato lineal" coincida con la página original.

Para verificar usando la "Web Developer toolbar":

1. Abrir la página web a chequear.

2. En la barra, seleccionar "Images", luego "Disable Images", luego "Disable All Images".

3. En la barra, seleccionar "CSS", luego "Disable Styles", luego "Disable All Styles". 

4. En la barra, seleccionar "Miscellaneous", luego "Linearize Page".

5. En la barra, seleccionar "Outline", luego "Show Element Tags Names When Outlining"

6. En la barra, seleccionar "Outline", then "Outline Headings".

7. Verificar.

Para verificar, usando alternativamente la "WAVE web accessibility toolbar":

1. Abrir la página web a chequear.

2. Clickear el botón "WAVE"

3. Localizar los encabezados bajo la opción "Structural Elements".

4. Verificar.

#### Código html de ejemplo

```
<body>
<h1>Herramientas de evaluación de Accesibilidad Web</h1>
<p>Las herramientas son...</p>
<h2>Herramientas de evaluación de accesibilidad web para el navegador XYZ</h2>
<p>Para el navegador XYZ....</p>
<h3>Web Tool version 8</h3>
<h3>Accessibility Toolkit</h3>
<h2>Herramientas de evaluación de accesibilidad web para otros navegadores</h2>
<p>En este caso...</p>
</body>
```

### Contraste del texto

#### Recomendación

El contraste entre el texto y el fondo debe ser de al menos 4.5:1 para texto con tamaño menor a 18 puntos o menor a 14 puntos si el texto está en negrita.

(Ref.: WCAG 2.0; [criterio de conformidad 1.4.3](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html), Nivel AA)

#### ¿Qué y cómo verificar?

Verificar que el contraste entre el texto y el fondo sea de al menos 4.5:1 para texto con tamaño menor a 18 puntos o menor a 14 puntos si el texto está en negrita.

Para verificar, puede usarse la "WAVE web accessibility toolbar":

1. Abrir la página web a chequear.

2. Clickear el botón "WAVE"

3. Localizar la pestaña "Contrast", y luego “Contrast Errors”.

4. Navegar a través de cada uno de los errores detectados. En la parte inferior de la barra de "WAVE" podrá verse cual es el color del texto, del fondo, el ratio de contraste detectado y testear con otros colores que permitan obtener un ratio adecuado.

5. Verificar.

Un procedimiento similar al anterior puede realizarse utilizando la "Web Accessibility Toolbar" para Internet Explorer. 

Para verificar, puede usarse alternativamente una extensión para Mozilla Firefox denominada "[Juicy Studio Accessibility Toolbar](https://addons.mozilla.org/en-US/firefox/addon/juicy-studio-accessibility-too/)":

1. Abrir la página web a chequear.

2. En la barra, seleccionar "Colour Contrast Analyser", luego "Luminosity Contrast Ratio". Se abrirá una nueva pestaña.

3. En la última columna, bajo el rótulo "Luminosity Contrast Ratio" podrán verse los chequeos exitosos y con fallas.

4. Verificar.

### Cambio de tamaño del texto

#### Recomendación

El texto debe estar especificado utilizando unidades `em` y no `px`, debe poder aumentarse el tamaño del texto hasta un 200 por ciento mediante el uso de las opciones propias del navegador sin que la página pierda contenido o funcionalidad (por ejemplo: sin que un texto se superponga con otro, desaparezca, etc.).

(Ref.: WCAG 2.0; [criterio de conformidad 1.4.4](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-scale.html), Nivel AA)

#### ¿Qué y cómo verificar?

Verificar que el texto aumente sin perder la página contenido o funcionalidad. Con el tamaño del texto aumentado 200 por ciento verificar que: 

* todo el texto, y no sólo alguna parte, se agrande. 

* parte del texto no desaparezca ni aparezca cortado.

* el texto no se superponga con imágenes ni con otro contenido.

* los botones, campos de formularios u otro tipo de contenido permanezcan visibles y usables.

* no se requiera desplazamiento (scrolling) horizontal.

Para verificar usando Mozilla Firefox:

1. Seleccionar "Ver", luego “Zoom”, luego “Solamente zoom en el texto”.

2. Seleccionar "Ver", luego “Zoom”, luego “Aumentar”.

3. Verificar.

Para verificar usando Google Chrome:

1. Descargar una extensión que permita sólo zoom de texto (ejemplo: [Zoom Text Only](https://chrome.google.com/webstore/detail/zoom-text-only/jamhfhbppcmkgghlkeieococonlbppjg); proponemos descargar una extensión ya no hemos identificado en Google Chrome la opción para sólo ampliar texto, es decir sin incluir otros objetos.).

2. Presione la tecla "Alt" junto con la tecla “+” para aumentar el tamaño del texto.

3. Verificar.

## Aspectos de accesibilidad web referentes a la interacción

### Acceso por teclado y foco

#### Recomendación

Debe ser posible navegar mediante el teclado, sin necesidad de utilizar un mouse o un touchpad. En este caso el foco debe ser visible y seguir un orden lógico a través de los distintos elementos de la página web. Que sea visible significa que el foco se indique mediante bordes, subrayados o resaltados cuando se navega utilizando la tabulación (tecla "Tab") del teclado.

(Ref.: WCAG 2.0; [pauta 2.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation.html); [criterio de conformidad 2.4.3](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-focus-order.html), Nivel A; [criterio de conformidad 2.4.7](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-focus-visible.html), Nivel AA)

#### ¿Qué y cómo verificar?

Verificar que:

* toda la funcionalidad de página esté disponible navegando sólo con el teclado.

* todos los elementos (enlaces, campos de formularios, botones, controles de reproductores de videos, etc.) sean accesibles mediante la tecla "Tab".

* los elementos de las listas desplegables sean navegables mediante las teclas  "arriba", “abajo”, “izquierda” y “derecha” 

* el foco nunca queda en un elemento sin que la tecla "Tab" permite avanzar al próximo elemento o retroceder al anterior (evitar el denominado "keyboard trap").

* el orden de tabulación sea el mismo que el orden lógico de lectura (izquierda-derecha, arriba-abajo).

* el foco sea claramente visible mediante bordes, subrayado o resaltado.

* las imágenes que sean enlaces, tengan un foco visual y sean activables presionando la tecla "Enter".

Con la página cargada en el navegador y mediante el teclado:

1. Presionar "Tab" para avanzar a través de los elementos de la página, y “Shift” + “Tab” para moverse hacia atrás.

2. Usar las teclas "arriba", “abajo”, “izquierda” y “derecha” para moverse dentro de elementos como listas desplegables o barras de menú.

3. Presionar "Enter" o la “Barra espaciadora” para seleccionar algún elemento en el cual se haya hecho foco.

4. Verificar.

### Formularios, etiquetas y errores

#### Recomendación

Los formularios deben tener etiquetas definidas, ser accesibles mediante el teclado, proveer instrucciones claras y manejar los errores de una manera efectiva.

Los formularios son elementos muy comunes en la interacción del usuario con la página. Estos pueden ser simples, como un formulario con un campo de texto para búsqueda, o muy complejos como un formulario de registración que incluya listas de selección, casillas de verificación, etc.

(Ref.: WCAG 2.0; [criterio de conformidad 3.3.2](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-cues.html), Nivel A; [criterio de conformidad 1.3.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-programmatic.html), Nivel A;  [criterio de conformidad 3.3.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-identified.html), Nivel AA; [criterio de conformidad 3.3.3](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-suggestions.html), Nivel AA;  [criterio de conformidad 3.3.4](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-reversible.html), Nivel AA;)

#### ¿Qué y cómo verificar?

**Verificar el acceso por teclado y foco.** Para el formulario bajo análisis verificar que todas las comprobaciones tratadas en el apartado "Acceso por teclado y foco" se cumplan.

**Verificar etiquetas.** Para el formulario bajo análisis verificar que cada elemento tenga una etiqueta asociada utilizando `"<label>"` , `“for”` e `“id”`. Ejemplo:

```
<label for="nombre">Nombre: </label>
<input type="text" name="nombre" id="nombre" />
```

**Verificar el tratamiento de campos obligatorios y otras instrucciones.** Para el formulario bajo análisis verificar que:

* los campos obligatorios estén claramente indicados. Por ejemplo: no es correcto que estén indicados utilizando solamente color rojo. Un indicador claro puede ser un "*", indicando que los “campos marcados con * son obligatorios”.

* las instrucciones para completar el formulario sean provistas en la parte superior del mismo y no al final. Esto incluye el formato de los datos que se espera que el usuario introduzca. Ejemplo: "Fecha de nacimiento (DD/MM/AAAA)".

**Verificar la gestión de errores.** Para el formulario bajo análisis verificar dejando campos en blanco para información obligatoria, datos en formatos no correctos, etc., con el objetivo de provocar errores y poder comprobar que:

* los mensajes de error sean claros y guíen al usuario para entenderlos y solucionarlos.

* los mensajes de error sean fácilmente localizables. Es mejor que los errores del formulario aparezcan en la parte superior, antes y no al final del mismo.

* los campos sin error conserven los datos que el usuario ingresó correctamente, de modo que no tenga que completarlos nuevamente.

Para las verificaciones relacionadas a etiquetas, puede utilizarse la "WAVE web accessibility toolbar":

1. Abrir la página web a chequear.

2. Clickear el botón "WAVE"

3. Localizar la pestaña "Errors", y luego “Missing form labels”. Si es que faltan etiquetas allí serán reportadas.

4. Verificar.


Para las verificaciones relacionadas a etiquetas, se recomienda complementar lo anterior utilizando la "Web Developer toolbar":

1. Abrir la página web a chequear.

2. Seleccionar "Forms", luego “View Forms Information”. Se abrirá una nueva pestaña con información del formulario, presentando: nombre de las etiquetas existentes, entre otra información relevante.

3. Verificar.

## Referencias

"[Chequeos básicos - Una primera revisión de accesibilidad web](https://www.w3.org/WAI/eval/preliminary)" ("Easy Checks - A First Review of Web Accessibility", en inglés), W3C.

"[Recomendaciones básicas para cumplimiento de las Pautas de Accesibilidad Web
](https://github.com/argob/accesibilidad-web/blob/master/docs/recomendaciones_pautas_accesibilidad_web.md)", Oficina Nacional de Tecnologías de Información.
