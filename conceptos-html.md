# Conceptos de HTML

<h2>Introducción</h2>
<p>En el desarrollo web, escribir código que funcione no es suficiente, también es necesario que sea claro, ordenado y comprensible, tanto para las personas como para las máquinas. Aquí es donde entra la semántica en HTML, que consiste en usar etiquetas que describen el significado y el próposito de cada parte del contenido, en lugar de limitarse a darle una apariencia visual.</p>
<p>

Antiguamente, era común construir páginas completas con elementos genéricos como `<div>` y `<span>`, lo que obligaba a quien leía el código a adivinar qué funció cumplía cada bloque. Con HTML5 se incorporaron elementos como `<heder>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`, que permiten identificar de forma inmediata la estructura de una página.

</p>

<p>

La semántica es importante por varias razones. Primero, mejora la accesibilidad. Segundo, favorece el posicionamiento en buscadores (SEO), proque estos comprenden mejor qué contenido es el principal y cómo está organizado. Tercero, facilita el mantenimiento y la colaboración, ya que un código legible es más fácil de entender, corregir y ampliar por cualquier programador.

</p>
<p>

Por estas razones, se abordará la semántica y sus principales estructuras, con el fin de comprender cómo se distribuyen a construir páginas web más organizadas, accesibles y profesionales

</p>

<ol>
<li>

<b>header:</b> Representa el encabezado de una página o sección. Suele contener el logotipo, el título principal o la navegación.

`<header></header>`

</li>
<li>

<b>nav:</b> Define un bloque de enlaces de navegación principal, como el menú de sitios. Es importante porque permite a los usuarios y a los buscadores reconocer cuáles son las rutas principales para moverse en el sitio. Normalmente va dentro del <b>header</b>, justo después del logotipo o el título del sitio, porque es parte de la zona introductoria que se repite en todas las páginas.

`<nav></nav>`

</li>
<li>

<b>main:</b> Contiene el contenido principal y único en la página. Solo debe haber uno por página. Es importante porque permite saltar directamente al contenido relevante y deja claro cuál es el núcleo del documento.

`<main></main>`

</li>
<li>

<b>section:</b> Agrupa contenido relacionado temáticamente. normalmente con su propio encabezado (servicios, contacto). Es importante porque organiza la página la página en bloques con significado, dando una estructura lógica y jerárquica al documento.

`<section></section`

</li>
<li>

<b>footer:</b> Define el pie de página o sección, donde suelen ir los derechos de autor, datos de contacto, enlaces legales o redes sociales. Es importante porque delimita la información complementaria y de cierre, y ayuda a los usuarios a encontrar datos de referencia de forma consistente.

`<footer></footer>`

</li>
</ol>
