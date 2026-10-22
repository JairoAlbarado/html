# HTML Profundizado[cite: 4]

## ¿Qué es el HTML?[cite: 4]

Es un lenguaje de marcado de hipertexto, es el lenguaje estándar para crear páginas web y también describe su estructura[cite: 4]. Consta de una serie de elementos que le indican al navegador cómo mostrar su contenido, por ejemplo: "este es un encabezado", "este es un párrafo", "este es un enlace", etc[cite: 4].

¿Por qué HTML se considera un lenguaje de marcado (*Markup Language*)?[cite: 4]
Un lenguaje de marcado o de marcas se refiere a un sistema de anotación organizado que marca (de ahí proviene su nombre) ciertos elementos de un documento o página web para darle al texto un formato y una estructura específica[cite: 4].

## ¿Qué es un elemento HTML?[cite: 4]

Un elemento HTML es una unidad que forma parte de un documento HTML[cite: 4]. Puede incluir una etiqueta de apertura, contenido y una etiqueta de cierre[cite: 4].

Ejemplo:[cite: 4]
`<h1>` Hola `</h1>`[cite: 4]
* `<h1>`: etiqueta de apertura[cite: 4].
* Hola: contenido del elemento[cite: 4].
* `</h1>`: etiqueta de cierre[cite: 4].

También existen elementos vacíos, que no contienen texto ni otros elementos y no tienen etiqueta de cierre[cite: 4].

Ejemplo:[cite: 4]
* `<br>` representa un salto de línea[cite: 4].
* Otros ejemplos de elementos vacíos son `<img>` y `<meta>`[cite: 4].

## Documento HTML[cite: 4, 5]

* `<!DOCTYPE html>`: declara al documento qué versión de HTML está usando[cite: 4].
* `<html lang="en">`: indica en qué idioma estará el documento[cite: 4].
* `<head>`: es un contenedor para metadatos y configuraciones del documento que el navegador procesa[cite: 4].
* `<meta charset="UTF-8" />`: `charset="UTF-8"` indica al navegador web qué codificación de caracteres debe usar para mostrar el texto de la página[cite: 4].
* `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`: `content="width=device-width"` ajusta el ancho del área visible (*viewport*) para que coincida exactamente con el ancho del dispositivo[cite: 4]. `initial-scale=1.0` define el área del zoom en un 100% cuando el usuario carga la página[cite: 4].
* `<title>freeCodeCamp</title>`: título de la página web[cite: 4].
* `<link rel="stylesheet" href="./styles.css" />`: se utiliza para conectar una hoja CSS externa.
* `</head>`
* `<body>`: es donde se coloca el contenido
* `</body>`
* `</html>`

## ¿Qué es un metadato?[cite: 5]

Los metadatos son información estructurada que describe, explica o proporciona contexto a otros datos[cite: 5].

## Estructura de un HTML[cite: 5]

```html
<header> <nav> </nav> </header>
<main>
  <article></article>
  <section></section>
  <aside></aside>
</main>
<footer></footer>
