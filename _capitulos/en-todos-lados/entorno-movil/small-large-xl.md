---
layout: capitulo
title: "2.5.1.	Small, large y XL: resoluciones"
comments: true
---

Tal como las pantallas de las computadoras de escritorio y las de _laptops_ presentan una serie de resoluciones casi estándares, los dispositivos móviles también cuentan con un sistema de medidas de resoluciones, que si bien son muy variadas, pueden agruparse y/o simplificarse en una serie valores comunes.

Cuando se genera un diseño para un sitio _desktop_, es decir, pensado para su visualización en monitores fijos, se toma como base un ancho seguro mínimo de aproximadamente 960 pixeles, ya que, en promedio, las resoluciones más utilizadas van desde 1024x768 a 1280x800 pixeles – estos valores deben leerse como ancho por alto –. A éstos deben descontársele horizontalmente algunos pixeles que son ocupados por elementos de la interfaz gráfica de los navegadores, como por ejemplo la barra de _scroll_, los cuales quitan espacio en el área real de _renderización_ de la página web. Es así como se obtiene este número, que es considerado por algunos estudiosos de la materia como una proporción _mágica_, para exhibir correctamente el contenido deseado en pantalla. A medida que la tecnología avanza, los monitores crecen y/o presentan mayor densidad de pixeles por pulgadas (abreviado PPP, o PPI por sus siglas en inglés, _pixels per inch_) como las pantallas retina comercializadas por _Apple_ en los nuevos modelos de sus _MacBooks_, y algunos de sus dispositivos móviles. Es por esto que las resoluciones en _desktops_ aumentan y un diseño basado en el ancho de 960 pixeles resulta insuficiente. Actualmente, muchos sistemas de grillas y _frameworks_, los cuales son desarrollados en el cuarto capítulo, establecen su ancho base en números mayores, como 1170 pixeles.

Como tantas otras variables, al momento de trasladarse al paradigma de visualización en dispositivos móviles, estos cálculos y aproximaciones pierden su validez. Físicamente, una de las características principales de estas terminales es su tamaño. Suelen ser por lo menos 1/5, en el caso de _smartphones_, o ½ en el caso de las _tablets_, aproximadamente, del tamaño de los monitores convencionales por lo cual su resolución en pantalla también debe ser menor.

Al haber en existencia en el mercado centenares de modelos, cada uno con sus medidas específicas y resoluciones variadas – ya que el hecho que dos dispositivos que cuenten con la misma mesura física no garantiza que ambos porten la misma resolución –, es meramente imposible tratar de cubrir todas las variables y combinaciones posibles para satisfacer a todos los usuarios por igual.

Es por esta razón que han sido trazadas, por convención, una serie de medidas para definir patrones de estandarización al momento de diseñar, y posteriormente desarrollar una interfaz web para móviles. Es del interés de un diseñador, primordialmente, conocer el ancho ya que, en la mayoría de los casos, se construyen sitios verticales con un ancho fijo y un alto variable que depende del contenido de cada página. Algunos de estos valores, tomando como base los mencionados por Firtman (2013) en _Programming the mobile web_ son, en orden ascendente, 320px para celulares más antiguos con resoluciones reducidas, 480px también para celulares y algunos _smartphones_, 768px para _smartphones_, y 1024px y 1280px para _tablets_, por mencionar los más utilizados (2013).

Es fundamental que el lector comprenda y memorice estos datos ya que sientan las bases sobre las cuales deberá trabajar al momento de definir la estructura de su diseño para dispositivos móviles.

Los valores presentados son puestos en práctica cuando se desarrolle el tema de _media queries_ y su aplicación en el diseño web adaptable, en el cuarto capítulo de este Ensayo.
