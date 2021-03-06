---
layout: subcapitulo
order: "4.5."
title: "Cada cosa en su lugar: sistemas de grillas"
comments: true
---

Desde los inicios del diseño web, se han implementado diversas formas de estructurar y ordenar el contenido en una página. En un pasado, se consideraba una buena práctica crear contenedores visuales utilizando marcos, más comunmente conocidos como _frames_. Éstos dividían la pantalla en cajas rígidas dentro de las cuales se cargaba un contenido específico, independiente del que se mostraba en otro _frame_. Esta técnica marcó una era en la Web, una tendencia que fue chocando contra sus propios límites, ya que era inflexible y tedioso de mantener.

Con el avance del conocimiento, y con la introducción de nuevas y mejores prácticas, se comenzó a armar los _layouts_ y a diseñar en base a sistemas, a veces complejos, de tablas. Muchos sitios solían estar, y aún algunos persisten, configurados en bloques estáticos, que si bien eran un poco más flexibles que cuando se diseñaba con `<frame>`, su mantenimiento seguía siendo arduo. Las tablas, semánticamente, cumplen un objetivo diferente al de servir como soportes de presentación, sino que están pensadas para ser funcionales al manejo de datos y su comparación.

Por esta razón, los diseñadores más puristas fueron migrando a nuevos horizontes en los que se pudiera diseñar con herramientas destinadas para tal fin. Es en este momento donde entró en escena la etiqueta `<div>`. Su función es la de división, de allí su nombre, y su representación visual no es más que un bloque vacío sin estilos. Sus características innatas la convierten en la herramienta perfecta para diseñar estructuras jerárquicas y maleables, y a su vez permiten dar rienda suelta a la imaginación, ya que no presentan límites estéticos, sino que esos son impuestos por la creatividad del diseñador.

No obstante, aquí no comenzó la Web como se la conoce ahora. Por diversos motivos, los diseños seguían siendo inflexibles y hechos a gusto del diseñador, y no con el objetivo de ser utilitarios a la mayor parte de los usuarios. Los `<div>` eran utilizados no como lienzos dúctiles, sino como un medio para posicionar arbitrariamente contenido en la pantalla. Mediante la declaración de la regla de estilo `position: absolute`, se ubicaban los componentes de manera fija, generando un diseño que solamente le era funcional al diseñador y a los usuarios que compartiesen sus mismas características de visualización.

El diseño para la Web, como ella misma, ha ido evolucionando y tomando caminos más universales. Si bien el concepto de grilla reticular proveniente del diseño gráfico y editorial siempre ha sido aplicado, o por lo menos se ha intentado, su implementación mediante el uso de `<div>` ha adquirido popularidad recién en los últimos años.

“Los diseños de grillas pueden agregar ritmo visual para guiar el ojo del usuario, haciendo el diseño limpio, ordenado y proporcionarle consistencia. Permiten estabilidad y estructura en la que se puede agregar fácilmente nuevos elementos y reorganizar los existentes” (Grannell, Sumner y Synodinos, 2012, p. 250).

Básicamente, un sistema de grillas es una cuadrícula compuesta por líneas horizontales y verticales que se intersectan y permiten al diseñador regular la disposición de los componentes en su diseño. Su uso es recomendado ya que, si están bien utilizadas, ayudan a unificar visualmente el mismo. Mediante el uso de columnas de igual tamaño y equidistantes, separadas por _calles_ – en inglés denominadas _gutter_ – los elementos de una página pueden ser colocados de manera que su organización sea precisa y prolija.

Confeccionar una grilla requiere conocer los límites en donde ésta será aplicada. Sin embargo, en la cambiante Web, donde las fronteras son elásticas y prácticamente infinitas, la implementación de un sistema de estas características suele ser una problemática. Existe la posibilidad de ignorar la flexibilidad que éstas deberían tener, y establecer un sistema que ocupe un tamaño fijo, como lo hace el popular sistema 960, el cual establece un tamaño horizontal de esa cantidad de pixeles, y puede ser dividido en 12 o 16 columnas. Pero esto no sería ideal.

Como ya se ha mencionado anteriormente, mediante la utilización correcta de _media queries_, y unidades relativas de medida, es posible crear sistemas propios que respondan a las necesidades específicas de cada diseño, y que a su vez sean adaptables a la mayor cantidad de pantallas como sea posible. En vez de definir valores fijos para el contenedor principal y sus columnas interiores, pueden utilizarse porcentajes, e incluso `em`, para que éstos se amolden a sus contextos.

De cualquier manera, como se puede imaginar, no es recomendable que el sistema de grillas mantenga la misma configuración en todos los dispositivos, esto sería simplemente la misma estructura pero reducida en tamaño. La premisa del diseño web responsivo es que éste responda a las necesidades de cada caso. Esto quiere decir que la organización debe generarse dinámicamente para reestructurarse acorde a la situación. Si bien suena complicado de realizar, es factible su implementación mediante las técnicas anteriormente mencionadas.

Para un proyecto sin gran escala, quizás una mejor opción sería utilizar un sistema que haya sido pre-armado con este fin, en vez de crear uno de cero. Éstos son llamados _frameworks_, y son tratados al final de este capítulo.
