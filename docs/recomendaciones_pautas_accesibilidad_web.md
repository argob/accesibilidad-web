# Recomendaciones básicas para el cumplimiento de las Pautas de Accesibilidad Web

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Introducción](#introducci%C3%B3n)
  - [Objetivo](#objetivo)
  - [Estructura del documento](#estructura-del-documento)
  - [Consideraciones previas](#consideraciones-previas)
- [¿Qué es "accesibilidad web"?](#qué-es-accesibilidad-web)
- [¿Qué pautas de accesibilidad web existen a nivel internacional y en Argentina?](#qué-pautas-de-accesibilidad-web-existen-a-nivel-internacional-y-en-argentina)
  - [Las pautas de accesibilidad web a nivel internacional](#las-pautas-de-accesibilidad-web-a-nivel-internacional)
  - [Las pautas de accesibilidad web en la Argentina](#las-pautas-de-accesibilidad-web-en-la-argentina)
- [¿Qué, cómo y con qué metodología evaluar el nivel de accesibilidad web?](#qué-cómo-y-con-qué-metodología-evaluar-el-nivel-de-accesibilidad-web)
  - [¿Qué evaluar? Páginas web, sitios web y procesos completos](#qué-evaluar-páginas-web-sitios-web-y-procesos-completos)
  - [¿Cómo evaluar la accesibilidad web de una página web?](#cómo-evaluar-la-accesibilidad-web-de-una-página-web)
    - [Evaluación con herramientas automáticas](#evaluaci%C3%B3n-con-herramientas-autom%C3%A1ticas)
    - [Evaluación "manual" de los criterios de conformidad](#evaluaci%C3%B3n-manual-de-los-criterios-de-conformidad)
    - [Complementado la evaluación: test de usuarios](#complementado-la-evaluaci%C3%B3n-test-de-usuarios)
  - [¿Qué metodología utilizar para evaluar la accesibilidad de un sitio web?](#qué-metodología-utilizar-para-evaluar-la-accesibilidad-de-un-sitio-web)
- [¿Qué herramientas existen para evaluar el nivel de accesibilidad de un sitio web?](#qué-herramientas-existen-para-evaluar-el-nivel-de-accesibilidad-de-un-sitio-web)
  - [Herramientas de evaluación en línea](#herramientas-de-evaluaci%C3%B3n-en-l%C3%ADnea)
  - [Barras de herramientas para navegadores](#barras-de-herramientas-para-navegadores)
  - [Otras herramientas importantes](#otras-herramientas-importantes)
- [¿Cómo diseñar, desarrollar o mantener un sitio web accesible?](#cómo-diseñar-desarrollar-o-mantener-un-sitio-web-accesible)
  - [Recomendaciones a nivel organización o proyecto](#recomendaciones-a-nivel-organizaci%C3%B3n-o-proyecto)
  - [Recomendaciones técnicas](#recomendaciones-t%C3%A9cnicas)
  - [Otras recomendaciones y recursos](#otras-recomendaciones-y-recursos)
    - [Documentos digitales accesibles](#documentos-digitales-accesibles)
    - [Poncho - Framework de desarrollo](#poncho---framework-de-desarrollo)
    - [Curso "Accesibilidad Web - Pautas 2.0" (ONTI)](#curso-accesibilidad-web---pautas-20-onti)
- [Anexo I - Normativa relacionada](#anexo-i---normativa-relacionada)
- [Anexo II - Software de apoyo](#anexo-ii---software-de-apoyo)
    - [Productos de apoyo motriz](#productos-de-apoyo-motriz)
    - [Productos de apoyo visual](#productos-de-apoyo-visual)
    - [Programas de aplicación para Comunicación Alternativa / Aumentativa](#programas-de-aplicaci%C3%B3n-para-comunicaci%C3%B3n-alternativa--aumentativa)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introducción

### Objetivo

El objetivo del documento es presentar recomendaciones y sugerir recursos orientados al cumplimiento de las “Pautas de Accesibilidad de Contenido Web 2.0 (WCAG 2.0)” desarrolladas por la W3C.

Este es un documento propuesto por la Oficina Nacional de Tecnologías de Información de Argentina, sujeto a discusión, colaborativo y en progreso. Es por ello, que alentamos a organizaciones y ciudadanos a hacernos sugerencias o comentarios que nos ayuden a mejorarlo. Trabajamos fuertemente para incluir referencias en castellano pero esto no ha sido posible en todos los casos, si encontraste alguna que hayamos puesto en otro idioma y podamos reemplazarla nos encantaría conocerla.

### Estructura del documento

El documento tiene la estructura detallada a continuación y se espera que cada una de las secciones oriente en la respuesta a los siguientes interrogantes:

* ¿Qué es "accesibilidad web"?

* ¿Qué pautas de accesibilidad web existen a nivel internacional y en Argentina?

* ¿Qué, cómo y con qué metodología evaluar el nivel de accesibilidad web?

* ¿Qué herramientas existen para evaluar el nivel de accesibilidad de un sitio web?

* ¿Cómo diseñar, desarrollar y mantener un sitio web accesible?

### Consideraciones previas

Gran parte de las recomendaciones y recursos de la presente Guía se referencian en la "[Iniciativa por la accesibilidad web](https://www.w3.org/WAI/)" (Web Accessibility Initiative, en inglés) que la W3C desarrolla en el marco de sus misiones.

La [W3C]( http://www.w3c.es/) ([World Wide Web Consortium](https://www.w3.org/), en inglés) es una comunidad internacional donde diversas organizaciones y personas trabajan conjuntamente para desarrollar estándares web.

## ¿Qué es "accesibilidad web"?

La "accesibilidad web" es la posibilidad de que la información de la web pueda ser comprendida y consultada por personas con discapacidad, con el objeto de garantizarles la igualdad real de oportunidades y trato, evitando así todo tipo de discriminación.

Para que el acceso a la información sea posible existen determinadas normas y requisitos que las páginas web deben cumplir, tal como indica la "[Ley de Accesibilidad de la Información en las Páginas Web" (Ley N° 26.653)](http://servicios.infoleg.gob.ar/infolegInternet/anexos/175000-179999/175694/norma.htm) y la normativa que de ella se deriva. En el ámbito de la accesibilidad web estas normas y requisitos se denominan “pautas” y están orientadas a la eliminación o reducción de las barreras que dificultan el acceso.

El cumplimiento de las pautas contribuye a que el contenido sea más accesible para todas las personas, con o sin discapacidad, incluyendo por supuesto a personas que para acceder a la web utilizan diversos productos de apoyo (visuales, auditivos, motrices u otros) 

## ¿Qué pautas de accesibilidad web existen a nivel internacional y en Argentina?

### Las pautas de accesibilidad web a nivel internacional

Las pautas de accesibilidad web internacionalmente adoptadas son las definidas por la W3C y se denominan en castellano: "[Pautas de Accesibilidad de Contenido Web 2.0](http://www.codexexempla.org/traducciones/pautas-accesibilidad-contenido-web-2.0.htm)", WCAG 2.0 por sus siglas en inglés. 

La versión original y normativa en inglés se denomina, "[Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)". Las WCAG 2.0 se han convertido además en el [estándar internacional ISO/IEC 40500:2012](https://www.iso.org/standard/58625.html).

El contenido de las WCAG 2.0 se estructura a partir de cuatro conceptos importantes: principios, pautas, criterios de conformidad y técnicas suficientes y recomendables.

* Principios: son cuatro principios que proporcionan los fundamentos de la accesibilidad web, a saber: perceptible, operable, comprensible y robusto.

* Pautas: para cada uno de los cuatro principios se han definido pautas. En total son doce pautas que poseen un nivel de abstracción menor que los principios, aunque no son totalmente verificables como sí lo son los criterios de conformidad.

* Criterios de conformidad: para cada pauta se proporcionan criterios de conformidad verificables que permiten emplear las WCAG 2.0 en la práctica. Con el fin de cubrir las diferentes necesidades de las personas que navegan la web se han defindo tres niveles de conformidad; de menor a mayor exigencia estos niveles son:

    * A, deben cumplirse 25 criterios de conformidad.

    * AA, se agregan 13 criterios de conformidad a los 25 del nivel A; total 38 criterios.

    * AAA, se agregan 23 criterios de conformidad a los 38 de los demás niveles; total 61 criterios.

"Verificable" significa en este contexto que cada criterio puede ser evaluado de forma directa, pudiendo ser los resultados de cada verificación los siguientes: “cumple”, “no cumple”, “no aplica”.

* Técnicas suficientes y recomendables: las técnicas son informativas y se agrupan en dos categorías, aquellas que son suficientes para satisfacer los criterios de conformidad y aquellas que son recomendables. Es decir, estas técnicas orientan acerca de cómo cumplir con las pautas.

### Las pautas de accesibilidad web en la Argentina

La normativa técnica que adopta las WCAG 2.0 de la W3C en Argentina es la [Disposición ONTI N° 2/201](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=233667)[4](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=233667), siendo "A" el nivel de conformidad requerido.

Además de adoptar las pautas, la Disposición ONTI:

* aprueba los "Niveles Mínimos de Conformidad". Los mismos asignan a cada criterio de conformidad un puntaje con el objetivo de poder cuantificar el nivel de cumplimiento. Al asignar un puntaje de “4” a cada uno de los 25 criterios de conformidad para el nivel “A”, el resultado de la evaluación de una página web puede variar entre 0 y 100 puntos.

* establece un nivel mínimo de conformidad a ser cumplimentado por las páginas web de las organizaciones alcanzadas por la norma. El puntaje se calcula en base a los criterios del punto anterior. Durante el primer período evaluatorio el puntaje mínimo es de CINCUENTA (50) puntos y en el segundo período el umbral de aprobación es OCHENTA (80), acorde lo establecido según los "Niveles Mínimos de Conformidad". Los períodos evaluatorios son los que determina la Autoridad de Aplicación de la Ley.

Es importante aclarar que si bien este documento de recomendaciones facilita el cumplimiento de la Ley N° 26.653 de “Accesibilidad de la Información en las Páginas Web” y de la Disposición ONTI N° 2/2014 no las reemplaza de ningún modo. Es decir, el seguimiento de las recomendaciones facilita el cumplimiento pero no lo asegura, para ello deberás referirse específicamente a las normas citadas.

## ¿Qué, cómo y con qué metodología evaluar el nivel de accesibilidad web?

En esta sección se desarrollan tres interrogantes y tres respuestas en torno a una evaluación de accesibilidad web. Los interrogantes y las respectivas respuestas se mencionan sintéticamente a continuación:

* **¿Qué evaluar?** De manera esquemática podemos sostener que puede evaluarse la accesibilidad web de tres elementos: una página web, un sitio web o un proceso completo. 

* **¿Cómo evaluar la accesibilidad de una página web?**  Verificando la página web (o las páginas web en el caso de un sitio o un proceso completo) en base a cada uno de los criterios de conformidad de las WCAG 2.0. 

* **¿Qué metodología utilizar para evaluar la accesibilidad de un sitio web?** Recomendamos utilizar la metodología WCAG-EM 1.0 de la W3C.

A continuación se desarrollarán más detalladamente cada uno de los interrogantes planteados y las respuestas a los mismos.

### ¿Qué evaluar? Páginas web, sitios web y procesos completos 

Las pautas WCAG 2.0 están orientadas en la evaluación de una (1) "página web". En situaciones reales, seguramente nos interesará evaluar un sitio web o un proceso completo, ambos casos involucran la evaluación de más de una página. Por lo anterior, es importante considerar las siguientes definiciones, que aunque no sean normativas es decir totalmente acordes a las pautas, permiten entender mejor qué elementos son susceptibles de evaluación.

**Página web:** es definida por la W3C como “un recurso no incrustado obtenido de un único URI empleando el protocolo HTTP además de otros recursos que se empleen en la representación o que hayan sido ideados para la representación junto a aquel por parte de un agente de usuario”. Para una definición precisa, normativa y con ejemplos puede [consultar en el sitio de la W3C el recurso “Entendiendo el concepto de “página web”](https://www.w3.org/TR/UNDERSTANDING-WCAG20/conformance.html#uc-web-page-head)” (en inglés).

**Sitio web:** podemos definirlo como una colección coherente de una o más páginas web relacionadas que juntas proveen un uso o funcionalidad común.

**Proceso completo:** se define como una secuencia de pasos que se necesitan para completar una actividad e involucra varias páginas web. Para evaluar un proceso completo, cada una de las páginas del proceso deben ser conformes al nivel especificado. Por ejemplo: si un proceso de registro involucra el acceso a tres páginas web y se está evaluando la accesibilidad web según el nivel de conformidad "AA", cada una de las tres páginas deberán conformar como mínimo con el nivel definido; si una de las páginas verifica sólo con el nivel de conformidad “A”, ese será el nivel del proceso completo. 

En conclusión, la evaluación de sitios o procesos completos siempre incluirá la evaluación de una o varias páginas web, y para cada una de ellas deberá evaluarse individualmente el nivel de conformidad.

### ¿Cómo evaluar la accesibilidad web de una página web?

Idealmente una evaluación integral de accesibilidad web debe realizarse mediante la verificación de cada criterio de conformidad, pudiendo por supuesto utilizarse para ello herramientas automáticas de soporte a la tarea.

Para cada criterio de conformidad deberá indicarse el resultado de la verificación mediante las categorías: “cumple”, “no aplica” o “no cumple”; pudiéndose alternativamente agrupar las dos primeras categorías, ya que lo que más interesa es saber si se respeta o no el criterio.

#### Evaluación con herramientas automáticas

La evaluación con herramientas automáticas es la realizada mediante una aplicación informática que analiza el código de una página web devolviendo como resultado un reporte, es decir, una serie de anotaciones con los criterios verificados exitosamente y con las fallas o problemas encontrados. Las herramientas automáticas pueden categorizarse básicamente en dos tipos: herramientas de evaluación en línea y barras de herramientas para navegadores ("extensiones").

Aunque este tipo de evaluación automática se basa en herramientas muy útiles por su velocidad y simpleza, muchos aspectos de accesibilidad sólo pueden verificarse mediante una revisión manual complementaria. Por lo tanto, las herramientas automáticas pueden utilizarse como un excelente primer paso para resolver los principales problemas de accesibilidad pero no proveen una solución completa.

Un ejemplo que demuestra la necesidad de tener en cuenta la revisión manual es la descripción del contenido de las imágenes mediante un texto alternativo. Una herramienta automática puede verificar si las imágenes contenidas en una página web tienen o no una descripción alternativa (a partir de chequear la existencia del atributo "alt" dentro de la etiqueta “img”), pero es incapaz de verificar si el texto representa una descripción real de la imagen. Si la descripción alternativa no existe o no es adecuada, una persona que utiliza un lector de pantalla no podrá conocer el contenido de la imagen.

#### Evaluación manual de los criterios de conformidad

La evaluación mediante la verificación manual de cada uno de los criterios de conformidad web es una complementación necesaria a la evaluación con herramientas automáticas. Utilizamos el término "manual" para referirnos a todos aquellos procedimientos que exceden "presionar un botón" para evaluar la accesibilidad de una página.
La verificación manual implica la participación de un analista familiarizado con las WCAG 2.0. Este analista verificará cada criterio de conformidad pudiendo utilizar herramientas automáticas en línea y "extensiones" integradas al navegador, complementando su evaluación mediante la navegación de la página utilizando:

* sólo el teclado.

* diversos dispositivos -escritorio, tablets, móviles- o una herramienta para emularlos.

* diversos navegadores (por ejemplo: Firefox, Chrome, Explorer, Safari, entre otros).

Es importante destacar que cada criterio de conformidad cubre diferentes aspectos y técnicas, por lo que no es posible establecer un solo test que mida todos los aspectos relevantes de cada criterio de conformidad. Por ejemplo, el criterio 1.1.1 "Proveer alternativas textuales para contenido no textual" tiene asociadas diversas técnicas que pueden ser relevantes o no en diferentes situaciones. Las herramientas automáticas sólo chequean una parte del criterio de conformidad, por eso es necesaria la evaluación manual.

#### Complementado la evaluación: test de usuarios

Si bien los test de usuarios no forman parte necesaria de una evaluación de accesibilidad web en sentido estricto, son muy recomendables. Estos test preferentemente deben ser realizados invitando a personas con y sin discapacidad; y claro está, incluyendo a personas con discapacidad que utilizan distintos tipos de apoyos (visuales, motrices, etc.) para navegar la web, lectores de pantalla por ejemplo.

Para obtener una orientación general acerca de cómo realizar tests de usuarios recomendamos consultar la página "[Cómo las personas con discapacidad usan la Web](https://www.w3.org/WAI/intro/people-use-web/Overview.html)" (en inglés). Allí pueden encontrarse  historias de usuarios, las barreras que las personas con discapacidad encuentran y el tipo de apoyo que utilizan para reducir o eliminar dichos obstáculos. Para una orientación más procedimental y práctica, recomendamos analizar “[Accesibilidad en el diseño centrado en el usuario. Test de usabilidad](http://www.uiaccess.com/accessucd/ut_checklist.html)”  (en inglés). Este recurso identifica las etapas y tareas necesarias en un testeo de usabilidad orientado a la accesibilidad.

### ¿Qué metodología utilizar para evaluar la accesibilidad de un sitio web?

Como ya hemos mencionado previamente, una evaluación de accesibilidad web integral incluye la verificación de cada uno de los criterios de conformidad. La conformidad de la página con cada criterio se podrá indicar mediante las categorías: "cumple", “no aplica” o “no cumple”; pudiéndose alternativamente agrupar las dos primeras categorías, ya que lo que más interesa es saber si se respetan o no los criterios.

En este apartado nos referimos a sitios y ya no únicamente a páginas web. En esa dirección, sostenemos que lo ideal es evaluar cada una de las páginas web de un sitio. Habrá casos en los que esto podrá hacerse, pero si las páginas web de un sitio son miles, una buena estrategia será seleccionar una muestra de ellas que permita tener una buena aproximación al nivel de accesibilidad del sitio completo. Para esta tarea, recomendamos la "[Metodología de Evaluación de Conformidad de Accesibilidad de Sitios Web de la W3C](https://www.w3.org/TR/WCAG-EM/)", WCAG-EM por sus siglas en inglés.

La metodología involucra los siguientes cinco pasos:

1. Definir el alcance de la evaluación.

2. Explorar el sitio a evaluar. 

3. Seleccionar una muestra representativa.

4. Auditar la muestra seleccionada.

5. Reportar los resultados de la evaluación.

En mérito a la brevedad remitimos al lector al sitio web precitado en el que la W3C detalla la metodología. Como recurso complementario, recomendamos el uso del "[Generador de reportes de evaluación de accesibilidad de sitios web](https://www.w3.org/WAI/eval/report-tool/#/)" (en inglés). Es una herramienta desarrollada por la W3C que facilita la aplicación de la WCAG-EM. Cabe destacar que la herramienta no realiza ningún tipo de evaluación de accesibilidad de manera automática, sino que permite seguir los pasos de la metodología de una manera más sencilla: desde el ingreso de las URL, pasando por la verificación de cada uno de los criterios hasta finalizar en la generación del reporte.

Recomendamos al lector que quiera obtener una visión completa sobre la evaluación de accesibilidad web -tipos, metodologías, herramientas, etc.-, consultar el sitio  "[Recursos de Evaluación de Accesibilidad de la W3C](https://www.w3.org/WAI/eval/Overview)" (en inglés).

## ¿Qué herramientas existen para evaluar el nivel de accesibilidad de un sitio web?

Podemos mencionar fundamentalmente tres tipos de herramientas relacionadas con las evaluaciones de accesibilidad web:

* herramientas de evaluación en línea.

* barras de herramientas para navegadores ("extensiones").

* productos de apoyo (software y/o hardware) para tests de usuario.

Se presentarán aquí algunas herramientas seleccionadas a partir de un "[listado de herramientas de evaluación de accesibilidad web](https://www.w3.org/WAI/ER/tools/)" (en inglés) realizado por la W3C. Ni la ONTI ni la W3C homologan o promueven alguna de estas herramientas por sobre otras, tampoco se garantiza su buen funcionamiento, sino que se ofrece al lector una selección a modo orientativo.

En el “Anexo II - Software de apoyo” detallamos algunos productos de apoyo útiles para realizar test de usuario, entre los que se destacan los lectores de pantalla.


### Herramientas de evaluación en línea

Podemos mencionar los siguientes servicios en línea en castellano para evaluar la accesibilidad de una página web:

* [Evaluador Examinator](http://examinator.ws/) - Autor: Carlos Benavidez.

* [Evaluador TAW](http://www.tawdis.net/) - Autor: Fundación CTIC.

Otros servicios en línea, estos en inglés, son:

* [Evaluador Wave](http://wave.webaim.org/) - Autor: WebAIM.

* [Evaluador Tenon](https://tenon.io/index.php) - Autor: Tenon LLC.

### Barras de herramientas para navegadores

Una ventaja destacable de utilizar barras integradas al navegador, a diferencia de herramientas de evaluación de accesibilidad web en línea, es que no necesariamente la página web a evaluar debe estar publicada, pudiéndose incluso verificar secciones del sitio que requieren logueo para ser accedidas. 

Las herramientas comentadas en este apartado están disponibles sólo en idioma inglés pero son de fácil operación y detallamos los pasos para su uso en la "[Guía rápida de Evaluación de Accesibilidad Web](https://github.com/argob/accesibilidad-web/blob/master/docs/guia_rapida_evaluacion_accesibilidad_web.md)" elaborada por la ONTI. En la guía mencionada, se han seleccionado y utilizado fundamentalmente las herramientas “Wave Evaluation Tool” y “Web Developer Toolbar”, por estar ambas disponibles para los navegadores Mozilla Firefox y Google Chrome.

La herramienta "Wave Evaluation Tool" realiza, con sólo presionar un botón, un chequeo completo de la página web en base a las WCAG 2.0. La “Web Developer Toolbar” está orientada al desarrollo web y no específicamente a la accesibilidad, por lo que permite realizar diferentes operaciones (con imágenes, CSS, etc.).

Previamente a realizar a las verificaciones deberá agregar las herramientas a su navegador como "extensiones". 

A continuación listamos una selección de las mismas herramientas utilizadas en la mencionada "Guía rápida de Evaluación de Accesibilidad Web":

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

### Otras herramientas importantes

Si bien no se trata especificamente de herramientas de evaluación de accesibilidad web recomendamos validar el código html/ xhtml y css de las páginas mediante los validadores específicos disponibles en el sitio de la W3C:

* [Validador de html/ xhtml](https://validator.w3.org).

* [Validador de CSS](http://jigsaw.w3.org/css-validator/).


## ¿Cómo diseñar, desarrollar o mantener un sitio web accesible?

Como buena práctica, la accesibilidad web debe ser incluida "desde el comienzo", es decir, desde la planificación y antes del desarrollo del sitio; evitando así la implementación de un sitio no accesible que luego de una evaluación de accesibilidad con resultados negativos deba ser modificado y/o rediseñado para ser válido de acuerdo a las pautas.

### Recomendaciones a nivel organización o proyecto

La recomendación "[Planificando y gestionando la accesibilidad web](https://www.w3.org/WAI/impl/Overview)" (en inglés) de la W3C, identifica las actividades necesarias para integrar la accesibilidad a lo largo del proceso de desarrollo web. Estas actividades pueden aplicarse a nivel proyecto o a nivel organizacional, no necesariamente deben ejecutarse en orden secuencial e idealmente deben ser repetidas en el tiempo para mejorar de manera continua las capacidades de su equipo relacionadas a accesibilidad web.

Un buen recurso para entender, y en consecuencia asignar, los roles correspondientes dentro de un equipo que implemente sitios web accesibles son las "[Pautas de Accesibilidad al Contenido Web 2.0 por responsabilidad](http://code.viget.com/interactive-wcag/#responsibility=&level=aaa)" (en inglés). Este no es un recurso oficial de la W3C pero copia textualmente las pautas asociándole a cada criterio de conformidad las responsabilidades más fuertemente vinculadas a su cumplimiento. Cada criterio de conformidad de las WCAG 2.0 se asocia con una, algunas o todas estas responsabilidades dentro de un equipo de trabajo:

* Contenido.

* Diseño.

* Desarrollo en general.

* Desarrollo Front End.

* Experiencia de usuario (UX).

Por ejemplo, que el sitio sea accesible por teclado (pauta 2.1 de las WCAG 2.0) es principalmente una responsabilidad del desarrollo front end; que el uso del color y el contraste sea el adecuado (criterios 1.4.1 y 1.4.3 de las WCAG 2.0) es principalmente una responsabilidad de diseño; que el sitio sea adaptable (pauta 1.3 de las WCAG 2.0) involucra responsabilidades de diseño, desarrollo front end y experiencia de usuario.

### Recomendaciones técnicas

Presentamos en esta sección tres conjuntos de recursos de la W3C para diseñar, desarrollar y mantener desde el aspecto técnico sitios web accesibles. Si bien estos recursos comparten el objetivo mencionado, los abordajes y el modo de presentación de cada uno de ellos es diferente; en este sentido, podemos decir entonces que estos recursos son alternativos y complementarios, dejamos a criterio del lector seleccionar el que sea más adecuado a sus necesidades.

En primer lugar, pueden mencionarse las "[técnicas de la W3C para cumplir con las WCAG 2.0](https://www.w3.org/WAI/WCAG20/quickref/?currentsidebar=%23col_customize&levels=aaa&techniques=advisory)". Se trata de una página web dinámica que permite filtrar las pautas, criterios de conformidad y las recomendaciones aplicando algunos de los siguientes filtros:

* etiquetas a modo de palabras clave: botones, captcha, formularios, entre muchos otros.

* roles en el equipo de trabajo que implementa el sitio web (de manera similar al recurso comentado en el apartado anterior).

* nivel de conformidad requerido: A, AA, AAA.

* tecnología utilizada: HTML, CSS, ARIA, PDF, etc.

Esta forma de presentar la información simplifica en gran medida el proceso de búsqueda de soluciones a errores de accesibilidad puntuales.

En segundo lugar, mencionamos los "[tutoriales de accesibilidad web de la W3C](https://www.w3.org/WAI/tutorials/)". Estos cubren tópicos referidos a los siguientes elementos de una página web:

* estructura.

* menús.

* imágenes.

* tablas.

* formularios.

* carousels, sliders o slideshows.

Por último, las "[Técnicas para WCAG 2.0. Técnicas y fallas](https://www.w3.org/TR/WCAG-TECHS/Overview.html)". En ese sitio se listan algunas técnicas y fallas comunes agrupadas en las siguientes categorías:

* generales.

* HTML y XHTML.

* CSS.

* lenguaje/scripts del lado del cliente.

* lenguaje/scripts del lado del servidor.

* texto plano.

* PDF.

* WAI-ARIA.

* fallas más comunes.

### Otras recomendaciones y recursos

En esta sección se listan algunas recomendaciones y recursos adicionales vinculados a la accesibilidad web.

#### Documentos digitales accesibles

Para hacer accesibles los documentos digitales de texto en formatos docx, odt y pdf sugerimos consultar las "[Recomendaciones para la redacción de documentos digitales de texto accesibles](https://github.com/argob/accesibilidad-web/blob/master/docs/recomendaciones_textos_accesibles.md)" de la ONTI, recurso basado en las pautas WCAG 2.0.

#### Poncho - Framework de desarrollo 

Para el desarrollo de sitios web recomendamos [Poncho ](https://github.com/argob/poncho), un framework front-end html y css basado en [Bootstrap](http://getbootstrap.com/). Es utilizado para la creación de sitios pertenecientes a la Administración Pública Nacional de la República Argentina. De forma constante el equipo responsable de su desarrollo le incorpora mejoras en términos de accesibilidad web.

#### Curso "Accesibilidad Web - Pautas 2.0" (ONTI)

Para capacitar a su equipo en lo referente a accesibilidad web recomendamos este curso dictado por la ONTI, [más información sobre el curso "Accesibilidad Web - Pautas 2.0"](http://capacitacion.inap.gob.ar/). Es un curso orientado fundamentalmente a sensibilizar sobre la temática, abordando de manera básica aspectos técnicos referentes a la adecuación de los sitios web para que sean accesibles. 

## Anexo I - Normativa relacionada

* Ley N° 26.653 (2010), "[Ley Accesibilidad de la Información en las Páginas Web](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=175694)".

* Ley 26.378 (2008), Aprueba la "[Convención sobre los Derechos de las Personas con Discapacidad y su protocolo facultativo](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=141317)", aprobados mediante resolución de la Asamblea General de las Naciones Unidas del 13 de diciembre de 2006.

* Decreto N° 355/2013, "[Aprueba la reglamentación de la Ley Nº 26.653](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=210143)".

* Disposición ONTI N° 2/2014, “[Aprueba las Normas de Accesibilidad Web 2.0](http://servicios.infoleg.gob.ar/infolegInternet/anexos/230000-234999/233667/norma.htm)”.

## Anexo II - Software de apoyo

El "[Manual de Buenas Prácticas en Discapacidad](https://www.argentina.gob.ar/sites/default/files/manual_de_buenas_practicas_en_discapacidad_0.pdf)" elaborado por el Ministerio de Modernización de la Nación sugiere diferentes software según los diversos tipos de apoyo que brindan a los usuarios. Los mencionaremos a continuación ya que muchos pueden ser utilizados para realizar test de usuarios o pruebas de accesibilidad web.

### Productos de apoyo motriz

[Rata Plaphoon](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf)**.** Programa que emula el funcionamiento del mouse mediante un switch o pulsador. Es necesario que la persona tenga como mínimo un movimiento controlable voluntariamente. El programa permite controlar los movimientos (izquierda, derecha, arriba y abajo) y las funciones de los botones del mouse (izquierdo, derecho, doble clic y arrastre). 

[VirtualKeyboard](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf)**.** Teclado virtual en pantalla que incorpora un sistema de predicción para facilitar la escritura diseñado específicamente para personas con problemas de movilidad. 

[Headmouse](http://modalidadespecial.educ.ar/datos/tecnologi a-adaptativa.html#sthash.MMOy6e7X.dpuf)**.** Mouse virtual diseñado específicamente para personas con problemas de movilidad. Sólo requiere una webcam USB. 

[Mouse Joystick](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf)**.** Programa que permite controlar el mouse mediante un joystick convencional. 

### Productos de apoyo visual

[NVDA](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf)**.** Lector de pantalla gratuito y de código abierto para Windows (XP y superior, VISTA y Windows 7). Se puede ejecutar directamente desde una memoria USB sin tener que instalar loy está disponible en 11 idiomas, entre los que se encuentra el español. La mayoría de los comandos de NVDA consisten en pulsar la tecla "modificador de NVDA" junto con una o más teclas. 

[Orca](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Software libre de código abierto que posee un lector de pantalla y un magnificador. Proporciona acceso a aplicaciones y herramientas del entorno Linux. 

[Jaws](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Potente lector de pantalla que permite a las personas ciegas acceder a los contenidos de la salida visual de una computadora personal mediante voz. 

[Pequén Lee todo](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Software libre y gratuito diseñado para favorecer el acceso a las TIC de personas ciegas y con baja visión. Generalmente se lo utiliza como software de entrenamiento, como paso previo al trabajo con otros lectores de pantalla. 

**Conversores Texto a Audio:**

[Ballabolka](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Programa portable que permite transferir documentos de texto a formatos de audio (mp3 o wav) para que personas ciegas o con baja visión puedan acceder a documentos. 

[Dspeech](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Programa gratuito que convierte archivos txt, doc o pdf a formato de audio (wav o mp3). Permite crear audiolibros e incorpora la opción de seguimiento de texto. 

### Programas de aplicación para Comunicación Alternativa / Aumentativa

[Plaphoons](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Comunicador dinámico. Programa para ser utilizado como comunicador y editor de plafones de comunicación.

[Clic y JClic](http://modalidadespecial.educ.ar/datos/tecnologia-adaptativa.html#sthash.MMOy6e7X.dpuf). Formado por un conjunto de aplicaciones de software libre que permiten crear diversos tipos de actividades educativas multimedia. Poseen opciones de accesibilidad que permiten la ejecución de actividades haciendo un clic en el mouse o un pulsador. 

