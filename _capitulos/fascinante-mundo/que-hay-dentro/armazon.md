---
layout: subcapitulo
order: "1.1.1."
title: "El armazón: HTML"
comments: true
---

_HyperText Markup Language_, o su abreviación, HTML, es el lenguaje que estructura el contenido de cualquier página web y le da formato semántico y en menor medida, visual, al contenido. “HTML es el lenguaje de publicación de la World Wide Web.” (_World Wide Web Consortium_, 2013b).

La última versión estandarizada por la W3C es HTML 4.01, la cual fue lanzada en diciembre de 2004. Aunque aún su especificación no ha sido completada, HTML5 es la versión en la que los desarrolladores trabajan actualmente, ya que todos los navegadores modernos soportan la mayoría de sus módulos.

HTML es un lenguaje que se conoce como de marcado, ya que envuelve el contenido en marcas, o etiquetas, las cuales indican al navegador la manera en que éste se debe _renderear_ en pantalla.

Se reconocen las etiquetas en un documento HTML, ya que son delimitadas por el signo menor que y mayor que (`<>`), y son predefinidas, es decir, son establecidas según la estandarización vigente. Las etiquetas encierran un contenido, por lo tanto se cierran al final del mismo. Una etiqueta con su contenido dentro genera lo que se conoce como elemento. La diferencia entre la etiqueta de apertura con la de cierre, es que esta última agrega una barra diagonal luego del signo menor que.

El siguiente ejemplo ilustra un texto con formato de negrita: `<strong>Texto a resaltar</strong>`. Como se puede observar, la frase es el contenido y se encuentra encapsulada entre una etiqueta de apertura y otra de clausura, las cuales se evidencian por los signos que las separan y el nombre de la misma que es auto-referencial, por su nombre en inglés. Hay, sin embargo, etiquetas que no guardan contenido y se cierran en si mismas, como la etiqueta de imagen o de salto de línea: `<br/>`. Se conocen como elementos vacíos.

Las etiquetas pueden aceptar atributos, los cuales también son predefinidos por la estandarización vigente. Éstos son siempre declarados dentro de la etiqueta de apertura. Los atributos son declarados en pares de manera que al nombre de atributo le corresponde un valor, el cual puede ser arbitrario o pre-establecido.

El siguiente es un ejemplo de como se establecería un hipervínculo: `<a href="http://www.google.com" target="_blank">Google</a>`. En el ejemplo, dentro de la etiqueta `<a>` se pueden distinguir dos atributos diferentes: el atributo _href_ establece el destino del hipervínculo – valor arbitrario – y el atributo _target_, el cual indica de qué manera debe abrirse ese enlace: dentro del mismo marco, en la misma ventana o en una nueva. Éste ejemplo tiene como valor `_blank`, que abre el vínculo en una ventana independiente del navegador.

Las etiquetas pueden ser anidadas, es decir, una etiqueta puede contener en su contenido otras etiquetas adentro suyo y así sucesivamente. En términos generales, una página web clásica contiene por lo menos tres etiquetas diferentes, que son los cimientos de la misma, y sólo pueden ser utilizadas una vez por documento. La etiqueta <html> envuelve todas las demás y no puede estar dentro de ninguna otra etiqueta, por eso suele ser la primera y última etiqueta en un documento. Se considera que suele ser la primera ya que en muchos de los casos antes de la apertura de `<html>` se coloca una declaración que define el tipo de documento, el _doctype_.

En el mismo nivel, dentro de `<html>` hay dos etiquetas que separan al documento en dos bloques: `<head>` y `<body>`. `<head>` contiene una serie de etiquetas específicas que definen información global del documento. Dentro de este bloque se coloca la etiqueta de título, de llamada a hojas de estilos CSS, de llamada a _scripts_ de _Javascript_, y etiquetas que serán utilizadas por los motores de búsquedas: palabras relacionadas, autores, contenido, entre otras. La etiqueta `<body>` contiene lo que el navegador interpretará como visible en pantalla. Comienza al cierre de la etiqueta `<head>` y cierra justo antes del cierre de `<html>`. Aquí pueden utilizarse todas las etiquetas, salvo las que pertenecen dentro del `<head>`, y por supuesto `<html>`, `<head>` y `<body>`, que no corresponden y no pueden volver a ser utilizadas. Entonces, una estructura clásica, utilizando las etiquetas que ya han sido presentadas y algunas nuevas para ilustrar el ejemplo puede visualizarse en la [Figura 1: Anatomía de una página web](../../anexo/).
