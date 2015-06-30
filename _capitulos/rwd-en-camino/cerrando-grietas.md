---
layout: capitulo
title: "4.6.	Cerrando grietas con polyfills"
comments: true
---

Desde que HTML5 y CSS3 fueron introducidos a la escena del desarrollo web, hace ya algunos años, muchos adelantados han ido incluyendo en sus proyectos elementos propios de estas nuevas tecnologías de manera indiscriminada. Si bien las últimas versiones de los navegadores más populares soportan casi todas las novedades – más información al respecto se detalla en el [apartado 2.5.3](../../en-todos-lados/entorno-movil/navegador-reglas) – aún hay usuarios que no han migrado a ellos, por variadas razones.

La mayor parte de los problemas de compatibilidad son ocasionados por versiones antiguas de _Internet Explorer_ que no son capaces de interpretar nuevos elementos en HTML5, como por ejemplo `<video>`, `<audio>`, `<section>`, entre otros. Al no reconocerlos, meramente los ignora, es decir, no permite que se le puedan agregar estilos, y mucho menos funcionalidad. A su vez, navegadores desactualizados en teléfonos móviles de gama baja, o simplemente viejos, sufren la misma problemática.

Si bien los desarrolladores deberían diseñar en función de todos sus usuarios, posean la última tecnología o no, estas nuevas características son provechosas para el buen funcionamiento de los sistemas, y verse limitado en el desarrollo por navegadores desactualizados es desalentador.

Ya Jakob Nielsen había establecido una regla sobre estas cuestiones en su libro _Designing web usability_, en la que recomienda evitar utilizar cualquier tecnología web innovadora hasta que hayan pasado, por lo menos, uno o dos años luego de su lanzamiento oficial y estable (1999), para así evitar que un gran porcentaje de los usuarios se vean impedidos de experimentarla. Si bien es un plazo prudente, es importante resaltar que la especificación de HTML5 aún no es estándar, a pesar de que tiene un buen soporte en los navegadores modernos.

Para suplir la falta en dichos casos, que suelen ser específicos, existe una serie de soluciones que apunta a unificar la experiencia de la mayoría de los usuarios. Los _polyfills_ son pequeñas librerías desarrolladas en _Javascript_ que hacen creer  al navegador que los elementos nuevos en verdad existen, para que los consideren como tal.

> El término polyfill fue originado […] como una alusión a llenar las grietas en los navegadores antiguos con Polyfilla (conocido como masilla de pegar en los EE.UU.). Por lo tanto, un polyfill es un suplemento de JavaScript que replica de manera efectiva nuevas características en los navegadores más antiguos. (Frain, 2012, p. 98)

Estos _scripts_ garantizan que la experiencia sea por lo menos un poco más democrática para todos los navegantes, sin importar su entorno. A su vez, han sido desarrollados _polyfills_ que se aseguran que los usuarios móviles, y no solamente los de escritorio con versiones viejas de _Internet Explorer_ puedan disfrutar estos avances tecnológicos por igual.

Probablemente el _polyfill_ más conocido y utilizado es _Modernizr_, una completa librería que detecta carencias en el navegador de acceso y, además de permitir el uso de elementos de HTML5, habilita la posibilidad de incluir condicionalmente nuevos _polyfills_ específicos para casos más puntuales.

Si bien estas soluciones son útiles y efectivas, no dejan de generar una petición al servidor en cada carga. Esto puede conllevar a problemas de rendimiento en dispositivos móviles. “Los polyfills no siempre son una buena idea para los navegadores móviles […] debido a la sobrecarga de rendimiento que añaden a las (por lo general más antiguas y menos capaces) plataformas móviles” (Firtman, 2013). Por esta razón, sería prudente hacer una evaluación previa sobre el público al que apunta el proyecto web en cuestión para identificar si la utilización de una librería de este tipo se ve justificada, considerando todos los factores.
