---
layout: capitulo
title: "4.1.	Condicionar las reglas: media queries"
comments: true
---

La característica más destacable del diseño web responsivo es su adaptabilidad a los límites y espacios que el dispositivo de visualización le imponga. Básicamente, al diseñar siguiendo esta pauta, se le puede indicar al navegador que establezca nuevas reglas de estilo dependiendo el tamaño del contenedor, entre otras variables. Es decir, es posible reubicar, reorganizar y hasta volver a diseñar elementos de una página web para cada situación mediante una serie de comandos.

Anteriormente se explicó que en cualquier diseño web deberían haber tres niveles separados de armado que hacen al funcionamiento integral del mismo: estructura, presentación y comportamiento. La estructura es su esqueleto, en donde a su vez se plasma el contenido embebido en etiquetas HTML. Esto le indica al navegador cómo debe mostrar los distintos elementos. Donde realmente se evidencia el diseño es en la capa de presentación. Ésta se caracteriza por dictar una serie de órdenes sobre cómo interpretar cada elemento gráficamente. Es aquí donde se definen los colores, tamaños, ubicaciones y variables estilísticas de todos los componentes visuales de una página. Para estas declaraciones se utiliza el lenguaje CSS, y es en este nivel donde las mismas reglas de estilo pueden ser replanteadas dinámicamente. El comportamiento puede servir como complemento para optimizar la experiencia en variados entornos, pero en términos generales, no debería ser en este nivel donde se marquen pautas de visualización al navegador.

Ya que al diseñar responsivamente se está sirviendo únicamente un mismo archivo HTML, es necesario hacer la separación de _layouts_ mediante una indicación al navegador para que levante una u otra hoja de estilo, o si se unifica todo en una sola señalarle qué declaraciones en ella específicamente deben ser interpretadas en cada situación. Para lo primero, se utiliza el atributo _media_ en la llamada a cada documento CSS. En el segundo caso se hace mediante un bloque `@media` en la hoja de estilos.

Desde la versión 2 de CSS, `media` puede recibir valores para distintos tipos de casos: `screen` para la visualización en pantalla, `print` para impresión, entre otros no tan utilizados como `tv` o `handheld`. Por defecto se aplica `all`, que unifica todo el espectro. Es decir, si se declara que `media` es igual a `screen`, todas las instrucciones CSS allí definidas serán únicamente aplicables cuando se muestre ese sitio en una pantalla. Caso contrario, si equivale a `print`, esos estilos serán aplicados al momento de impresión de la página. Esto es útil ya que el soporte es diferente, por lo tanto es necesario adaptar la presentación del contenido para que sea óptimo en la mayoría de las situaciones. Exactamente lo mismo ocurre cuando se diseña para dispositivos móviles, ya que surge la necesidad de dar prioridad a la presentación del contenido en las mejores condiciones. Sin embargo, con definir meramente este valor no es posible separar estilos para diferentes pantallas, ya que `screen` apunta a todas ellas por igual.

Desde la introducción de CSS3, algunos de sus módulos ya han sido estandarizados por la W3C, como es el caso de las _media queries_. “Las media queries permiten definir los estilos que deben aplicarse en determinadas circunstancias dependiendo los valores de características como resolución, profundidad de color, la altura y el ancho” (Kadlec, 2012, p. 54) del área visible del dispositivo. Éstas son condiciones que se adicionan al atributo `media` y permiten limitar el entorno al que se aplica un conjunto de declaraciones de estilo. Estas variables permiten, entre otras cosas, indicar puntos de quiebre en una estructura, conocidos técnicamente como _breakpoints_, sobre los cuales se harán las distinciones. Los valores que toman son generalmente dictados por convención, y responden a números derivados de resoluciones estándares de diversos dispositivos. En el segundo capítulo, al hablar de resoluciones y orientaciones de pantalla, se presentaron algunos números de referencia. Estos _breakpoints_ dividen el flujo del contenido y la estructura, presentando así diferentes _layouts_ según sus valores. Generalmente, se utilizan únicamente segmentaciones basadas en el ancho de la ventana gráfica con las declaraciones `max-width` y `min-width`, es decir, el ancho máximo y mínimo que ésta debe tener para que las consiguientes reglas de estilo le sean aplicadas. A su vez, se pueden crear condiciones complejas al juntar varios atributos mediante operadores como `and`, `or`, y `not`, los cuales enriquecen los límites impuestos en la _media query_.

Las dos maneras de incluirlas, tanto desde la etiqueta `<link>` en el HTML como desde un bloque `@media` en el CSS, son ilustradas en la [Figura 6: Declaraciones de _media queries_](../../anexo).