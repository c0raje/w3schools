# Introducción

HTML es el lenguaje de marcado estándar para crear páginas web. 

## ¿Qué es HTML?

- HTML significa lenguaje de marcado de hipertexto.
- HTML es el lenguaje de marcado estándar para crear páginas web.
- HTML describe la estructura de una página web.
- HTML consta de una serie de elementos.
- Los elementos HTML le dicen al navegador cómo mostrar el contenido.
- Los elementos HTML etiquetan fragmentos de contenido como "este es un encabezado", "este es un párrafo". "este es un enlace", etc.

## Un documento HTML sencillo

### Ejemplo:

```hmtl
<!DOCTYPE html>
<html>
<head>
<title>Titulo de pagina</title>
</head>
<body>
<h1>Mi primer encabezado</h1>
<p>Mi primer parrafo.</p>
</body>
</hmtl>
```

#### Ejemplo explicado
- EL `<!DOCTYPE html>` la declaración define que este documento es un documento HTML5.
- El elemento `<html>` es el elemento de una raíz de una página HTMl.
- El elemento `<head>` contiene metainformación sobre la página HTML.
- El elemento `<title>` especifica un título para el página HTML (que se muestra en la barra de título del navegador o en la pestaña de la página).
- El elemento `<body>` define el cuerpo del documento y es un contenedor para todos los contenidos visibles, como encabezados, párrafos, imágenes, hipervínculos, tablas, listas, etc.
- El elemento `<h1>` define un encabezado grande.
- El elemento `<p>` define un párrafo.


## ¿Qué es un elemento HTML?

Un elemento HTML se define mediante una etiqueta de inicio, algo de contenido y una etiqueta de cierre:

`<nombre de etiqueta>El contenido va aquí...</nombre de etiqueta>`

El elemento HTML es todo, desde la etiqueta inicial hasta la etiqueta final:

`<h1>Mi primer título</h1>`

`<p>Mi primer párrafo</p>`

| Etiqueta de inicio | Contenido del elemento | Etiqueta de cierre |
|------|------|------|
| **`<h1>`** | **Mi primer encabezado** | **`</h1>`** |
| **`<p>`** | **Mi primer parrafo** | **`</p>`** |
| **`<br>`** | **none** | **`none`** |

> **Nota:** Algunos elementos HTML no tienen contenido (como el **`<br>`** elemento). Estos elementos se llaman elementos vacíos. ¡Los elementos vacíos no tienen etiqueta final!

## Estructura de la página HTML

A continuación se muestra una visualización de la estructura de una página HTML:

> `<html>`
>> `<head>`
>>
>>> `<title>Título de la página</title>`
>>
>> `</head>`
>>
>> `<body>`
>>
>>>>  `<h1>Este es un título</h1>`
>>>>
>>>>  `<p>Este es un párrafo.</p>`
>>>>
>>>>  `<p>Este es otro párrafo.</p>`
>>
>> `</body>`
>
> `</html>`

> **Nota:** El contenido dentro de la sección **`<body>`** se mostrará en un navegador. El contenido dentro del elemento **`<title>`** será se muestra en la barra de título del navegador o en la pestaña de la página.

## Historia HTMl

Desde los primeros días de la World Wide Web, ha habido muchas versiones HTML:

| Año | Versión |
|------|------|
| **1989** | **Tim Berners-Lee invented www**|
| **1991** | **Tim Berners-Lee invented HTML**|
| **1993** | **Dave Raggett drafted HTML+**|
| **1995** | **HTML Working Group defined HTML 2.0**|
| **1997** | **W3C Recommendation: HTML 3.2**|
| **1999** | **W3C Recommendation: HTML 4.01**|
| **2000** | **W3C Recommendation: XHTML 1.0**|
| **2008** | **WHATWG HTML5 First Public Draft**|
| **2012** | **WHATWG HTML5 Living Standard**|
| **2014** | **W3C Recommendation: HTML5**|
| **2016** | **W3C Candidate Recommendation: HTML 5.1**|
| **2017** | **W3C Recommendation: HTML5.1 2nd Edition**|
| **2017** | **W3C Recommendation: HTML5.2**|