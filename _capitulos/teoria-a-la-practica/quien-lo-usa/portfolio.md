---
layout: subcapitulo
order: "5.1.2."
title: "Pensando un portfolio: rediseño del sitio web personal de la autora"
comments: true
---

Como se ha mencionado anteriormente, la autora de este Proyecto se desempeña de forma profesional actualmente como maquetadora, por lo cual su entorno de trabajo permanente es la creación y diseño de interfaces efectivas y usables para la Web actual. Esto quiere decir que procura que sus proyectos cumplan con los máximos estándares de calidad para que los usuarios de los mismos puedan disfrutar de la mejor experiencia que se les pueda ofrecer. Esta línea de pensamiento ha sido plasmada a lo largo del presente Ensayo, y es a su vez implementada en sus creaciones.

Durante el transcurso del mes de marzo de 2014, se realizó el rediseño y posterior actualización de contenidos del [sitio web personal de la autora](http://www.amireynoso.com.ar). Esta clase de sitio suele ser conocido en el ámbito del diseño como portfolio, ya que es una exhibición de los trabajos más destacados realizados por el o los diseñadores.

El principal objetivo para plasmar en esta transición era la correcta aplicación de los conceptos de diseño web responsivo, ya que se consideraba importante destacar la creatividad impuesta en la utilización de esta técnica, teniendo en cuenta que es una cualidad muy valorada por reclutadores laborales a la hora de seleccionar candidatos para puestos en el área.

Desde el punto de vista estético, se buscó mantener una coherencia visual desde la utilización de una paleta de colores limitada pero dinámica. A su vez, se realizó la elección de una familia tipográfica que fuese maleable para ser utilizada tanto para grandes cantidades de texto como para titulares, y que a su vez escalase bien en tamaños reducidos sin perder legibilidad.

Partiendo desde una concepción minimalista del diseño, en donde el contenido debe destacarse por sí mismo, se comenzó a desarrollar el sitio en términos técnicos. Para esto se utilizó como base estructural el _framework_ _Bootstrap_, anteriormente mencionado, dado que ofrece numerosos recursos pre-armados para ahorrar pasos en el flujo de trabajo. Empero, tal como se recomendó también, estas bases fueron manipuladas para adecuarse al partido gráfico propio del diseño propuesto.

Es posible apreciar que se ha sacado provecho del sistema de grillas, sobre el cual se construyen los cimientos de la estructura. Los elementos se encuentran en ella establecidos, y la misma, al ser flexible, permite que éstos se reacomoden dinámicamente.

La página principal cuenta con dos aspectos que ya han sido planteados. Por un lado, los ítems del portfolio que se muestran por debajo de la introducción tienen una cuadrícula propia, que sigue sus propias reglas de adaptación a diferentes pantallas. Es decir, no escala igual que el resto de las columnas, sino que fueron diseñadas especialmente para que su contenido, el elemento de mayor relevancia para el diseñador, se muestre siempre de la mejor manera posible. Por otro lado, es de suma importancia resaltar que las imágenes de estos items son a su vez elásticas, flexibles y que se adaptan a su contenedor, es decir, la columna que las contiene. Sin embargo, no se tiene extremada consideración por el peso de las mismas, lo cual puede llegar a ocasionar demoras en su carga en dispositivos con conexión limitada.

Se puede observar que si bien se ha intentado que el diseño funcione de la mejor manera posible para todos los dispositivos, hay una falla de planificación a la hora de mostrar el contenido extendido de cada item del portfolio. Esta información se muestra en forma de ventana modal, una clase de _pop-up_ que se posiciona por delante del contenido y que se carga de manera dinámica. Aquí se presenta una galería de imágenes, y en los casos que corresponde, un video, además de texto en dos columnas. En condiciones de visualización amplias, es decir, en computadoras de escritorio y hasta en _tablets_, este contenido se ve correctamente ya que tiene espacio disponible para acomodarse cómodamente. No obstante, en parámetros de visualización más reducidos, éste comienza a _enlatarse_, es decir, reducirse al punto de mostrarse comprimido, de manera que no permite una lectura fluida. Además, tanto las imágenes como los videos reducen su ancho al del dispositivo, por lo cual se muestran en tamaños minúsculos.

Si bien el sitio no cuenta con una cantidad extensiva de páginas interiores, cada una de ellas ha sido trabajada con especial cuidado para que cumplan su objetivo bajo distintos parámetros de visualización.

La navegación adopta un formato diferente en dispositivos pequeños, el cual facilita al usuario _clickear_ sobre sus enlaces. Para mantener la consistencia, se siguió la misma lógica para mostrar las categorías del portfolio en la página principal, como los enlaces a las secciones del _curriculum vitae_. Otro componente en esta página que toma una morfología diferente a la planteada originalmente es la línea de tiempo. Sus datos se reacomodan y se suprimen elementos gráficos meramente decorativos para optimizar la lectura de la información.

En el desarrollo de este proyecto personal se obvió un aspecto que ha sido tratado en este Ensayo y cuya utilización le hubiese dado un nivel invaluable de funcionalidad y usabilidad en móviles: los gestos táctiles. Siguiendo el ejemplo que se desarrolló en la explicación de los mismos, el del carrusel de imágenes, dicha implementación podría haber sido aplicada para navegar entre las diferentes ventanas modales de los items del portfolio. Éstas tienen ya un botón que permiten ir hacia adelante y hacia atrás, pero se ha observado en pruebas reales de usuarios sobre este mismo diseño que ellos entienden que esa funcionalidad le es innata. Se sugiere entonces una futura actualización del mismo para incluir esta capacidad.

En términos generales, entonces, este sitio aplica correctamente las técnicas de diseño web adaptable, ya que la experiencia de usuarios en la mayoría de los casos se encuentra optimizada.

Para la comparación de visualizaciones en diferentes dispositivos, se han utilizado exactamente los mismos aparatos mencionados anteriormente para las pruebas de análisis en los sitios más visitados de Argentina.
