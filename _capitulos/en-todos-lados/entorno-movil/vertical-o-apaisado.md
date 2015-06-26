---
layout: capitulo
title: "2.5.2.	¿Vertical o apaisado?: orientaciones de pantalla"
comments: true
---

Además de tomar en consideración las resoluciones de pantallas, es necesario tener en cuenta que muchos móviles poseeen la capacidad de ser rotados a conformidad del usuario. Al girar el dispositivo, el contenido mostrado en pantalla, y su contenedor, muta para adaptarse a la nueva manera de presentación. Esto es posible gracias al acelerómetro incorporado en el mismo.

Aún cuando esta funcionalidad se encuentra incorporada en un gran porcentaje de modelos, es pertinente recordar que el usuario posee la opción de desactivarla.

A menos que el dispositivo sea una _tablet_ o a lo mejor un lector de libros electrónicos, los cuales suelen ser utilizados tanto horizontal como verticalmente casi por igual, en el resto de los casos el usuario suele utilizar el aparato en orientación vertical mayormente. Este comportamiento puede deberse tanto a la costumbre de los usuarios, a la comodidad a la hora de hacer llamados, como al hecho de que generalmente se publicitan comercialmente en esta posición.

Muchas aplicaciones nativas como web aprovechan esta característica brindada para optimizar el diseño de su información. En la [Figura  5: Orientaciones de pantalla](../../../anexo), se toma como ejemplo una aplicación nativa, el juego _Candy Crush Saga_, dado que presenta distintas estructuras dependiendo de las posición en la que se visualice el dispositivo.

Además de llamársele por la posición a la que apunta la orientación, vertical u horizontal, suelen ser denominadas en retrato, por su término en inglés _portrait_, o paisaje, por _landscape_, respectivamente.

> El acelerómetro integrado en nuestros dispositivos inteligentes se suele utilizar para alinear la pantalla en función de la orientación del dispositivo, es decir, cuando se cambia entre los modos de retrato y paisaje. Esta capacidad proporciona grandes oportunidades para crear mejores experiencias de usuario, ya que ofrece una disposición adicional con un simple giro de un dispositivo, y sin necesidad de pulsar ningún botón (Itzkovitch, 2012).

Al generarse una rotación, ya no se cuenta con la misma resolución. Los valores son iguales, pero invertidos. Es decir, la cantidad de pixeles que antes representaban el alto de la pantalla, ahora son funcionales al ancho. Por esta razón al momento de diseñar, si se desea plantear una interfaz adicional considerando orientaciones, es imprescindible tener en cuenta ambos valores, ya que pueden ser intercambiables con un simple giro.

Itzkovitch (2012) a su vez identifica cuatro patrones de diseño funcionales a la variación en la posición de la pantalla. Estos sirven a la hora de desarrollar una óptima estrategia de experiencia de usuario ya que aportan lineamientos que pueden ser aplicados a cualquier aplicación.

El primero, diseño fluido, es el mayoritario dada la facilidad de empleo. Consiste básica y simplemente en que los elementos de la interfaz se reubiquen y adapten según la posición del dispositivo, como es el caso ilustrado en la [Figura 5: Orientaciones de pantalla](../../../anexo), anteriormente mencionada.

El siguiente patrón es el extendido. Este diseño comparte principios con su antecesor, ya que también se adapta y reubica sus componentes, pero con la particularidad que hace uso y desuso de los mismos al esconderlos, expandirlos y/o modificarlos según sea acorde.

Ya en un plano más complejo se define el diseño complementario, el cual establece que al girar el aparato, la pantalla mute y provea una visualización auxiliar de la misma información. Itzkovitch da como ejemplo una “[…] aplicación financiera móvil que muestre datos en el modo de retrato predeterminado y proporcione un gráfico visual cuando el usuario gira al modo horizontal. Las orientaciones muestran datos similares o complementarios y dependen unos de otros” (2012).

Por último, el patrón de diseño continuo plantea la generación de una pantalla secundaria con una interfaz completamente diferente al girar el dispositivo, que provea de información distinta, pero complementaria a la visualizada en la anterior.

Los últimos dos ejemplos son considerablemente complicados, y no es común encontrarlos en el campo real de aplicación, si bien existen. Sin embargo, los dos primeros sirven y se aplican no solamente en _apps_ sino también en simples sitios y páginas web. Es la conjunción de ambos patrones, además de otros factores, los que delinean el concepto de diseño web responsivo, el cual es abarcado en su totalidad en el próximo capítulo de este Ensayo.
