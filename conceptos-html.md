# Conceptos de HTML

## Introducción

En el desarrollo web, escribir código que funcione no es suficiente; también es necesario que sea claro, ordenado y comprensible, tanto para las personas como para las máquinas. Aquí es donde entra la semántica en HTML, que consiste en usar etiquetas que describen el significado y el propósito de cada parte del contenido, en lugar de limitarse a darle una apariencia visual.

Antiguamente, era común construir páginas completas con elementos genéricos como `<div>` y `<span>`, lo que obligaba a quien leía el código a adivinar qué función cumplía cada bloque. Con HTML5 se incorporaron elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`, que permiten identificar de forma inmediata la estructura de una página.

La semántica es importante por varias razones. Primero, mejora la accesibilidad. Segundo, favorece el posicionamiento en buscadores (SEO), porque estos comprenden mejor qué contenido es el principal y cómo está organizado. Tercero, facilita el mantenimiento y la colaboración, ya que un código legible es más fácil de entender, corregir y ampliar por cualquier programador.

Por estas razones, se abordará la semántica y sus principales estructuras, con el fin de comprender cómo contribuyen a construir páginas web más organizadas, accesibles y profesionales.

## Elementos semánticos principales

### `<header></header>`

Representa el encabezado de una página o sección. Suele contener el logotipo, el título principal o la navegación.

### `<nav></nav>`

Define un bloque de enlaces de navegación principal, como el menú de sitios. Es importante porque permite a los usuarios y a los buscadores reconocer cuáles son las rutas principales para moverse en el sitio. Normalmente va dentro del **header**, justo después del logotipo o el título del sitio, porque es parte de la zona introductoria que se repite en todas las páginas.

### `<main></main>`

Contiene el contenido principal y único en la página. Solo debe haber uno por página. Es importante porque permite saltar directamente al contenido relevante y deja claro cuál es el núcleo del documento.

### `<section></section>`

Agrupa contenido relacionado temáticamente y normalmente lleva su propio encabezado (por ejemplo: servicios, contacto). Es importante porque organiza la página en bloques con significado, dando una estructura lógica y jerárquica al documento.

### `<article></article>`

Representa un contenido independiente y autosuficiente, como una noticia, una entrada de blog o una tarjeta de producto. Es importante porque indica que ese bloque tiene sentido completo por sí mismo.

### `<footer></footer>`

Define el pie de página o sección, donde suelen ir los derechos de autor, datos de contacto, enlaces legales o redes sociales. Es importante porque delimita la información complementaria y de cierre, y ayuda a los usuarios a encontrar datos de referencia de forma consistente.

## Conclusión

Usar etiquetas semánticas hace que el código sea más claro, accesible y fácil de mantener. En lugar de depender solo de `<div>`, cada elemento comunica su función dentro de la página, lo que beneficia tanto a los programadores como a los usuarios y a los buscadores.
