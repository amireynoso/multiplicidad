---
layout: capitulo
title: "1.1.3.	La magia: Javascript"
comments: true
---

Ya se ha hablado de dos de los tres pilares que sostienen el armado de una página web: la estructura y la presentación. El comportamiento, el último de ellos, puede ser pensado como una capa de interactividad. Para poder romper con las bases estáticas de la página, es necesario introducir un lenguaje de programación llamado _Javascript_, también conocido como _ECMAscript_, o su abreviación JS.

_Javascript_ es un lenguaje de programación que funciona del lado del cliente. La diferencia entre que un lenguaje corra del lado del cliente, o del lado del servidor es que en el último caso, la petición realizada por el usuario es enviada al servidor para su análisis, y su respuesta es devuelta. Esto generalmente requiere una recarga en la página. Por el contrario, un lenguaje que corre del lado del cliente trabaja desde la máquina y navegador del usuario, llamado el cliente, sin la necesidad de pasar por un servidor, tomando los recursos de ésta para procesar la información. En el próximo apartado se tratan lenguajes de programación que interactúan con el servidor.

Por lo tanto, “Javascript depende de las capacidades y configuraciones del navegador Web” (Niederst Robbins, 2012, p. 459). Es un lenguaje que no necesita más que el _browser_ para ser interpretado. Como depende del navegador, quien diseñe una página web debe tener en cuenta que el usuario puede desactivar _Javascript_, y por ende, perder las funcionalidades que mediante este lenguaje se inyecten en la página.

De la misma manera que con las hojas de estilo, el diseñador web puede incluir código de _Javascript_ de dos maneras diferentes, y simultáneas: haciendo una llamada a un archivo externo, que debe tener extensión de archivo `.js` mediante la etiqueta `<link>`, o dentro del documento, entre etiquetas `<script>`.

Al ser un agregado de interacción, generalmente estas funcionalidades se ejecutan mediante eventos y a demanda. Éstos son llamados que se activan al momento que el usuario realiza una acción con los elementos de la página, como puede ser por ejemplo un botón. Con _Javascript_, es posible asignarle a diferentes elementos una función específica que corra cuando un determinado evento ocurra.

El lector puede reconocer el uso de _Javascript_ en diferentes sitios web dada la interactividad que esta herramienta le proporciona. Un ejemplo frecuente de su uso es la validación de formularios. En la Figura 3 se ilustra el caso cuando un usuario completa uno, e ingresa una dirección de correo electrónico que no es correcta en su sintáxis – por lo tanto no es válida como tal – e inmediatamente
la página devuelve un mensaje de error.

Existe también el caso de un paso más avanzado en validación de formularios, como puede suceder en grandes sitios comerciales que requieran registración por parte del usuario. Es usual que al introducir un nombre de usuario que ya ha sido registrado la página devuelva inmediatamente, sin ningún tipo de participación del usuario, o sin recarga de la misma, un mensaje que indique el error. Para este caso se utiliza una tecnología llamada _Ajax_ que corre en _Javascript_ y hace pedidos asincrónicos a un servidor. _Ajax_ es una tecnología intermediaria entre lenguajes del lado del cliente y los del lado del servidor.

Dentro del amplio espectro de soluciones que brinda _Javascript_, es posible beneficiarse del uso de librerías. Las librerías son paquetes de funcionalidades modulares enfocadas en que al programador o desarrollador web se le facilite su trabajo, ya que provee de funciones predefinidas listas para utilizar. La mayormente utilizada en la industria es _jQuery_, ya que posee una sintáxis de sencillo aprendizaje y puede ser extendida con _plug-ins_. _JQuery_ “hace que cosas como el recorrido de un HTML y su manipulación, control de eventos, animación y Ajax sean mucho más simple con una API fácil de usar que funciona a través de una multitud de navegadores” (JQuery, 2013). Esta librería también cuenta con una versión para desarrollar sitios web para plataformas móviles, _jQuery Mobile_, la cual es retomada en el cuarto capítulo.
