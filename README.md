<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> Aprendizaje html </title>
</head>
<body>
    <br></br>
    <header>
        <center><h1>Ejemplo de Etiquetas Básicas de HTML</h1></center>
    </header>

    <section>
        <h2>Texto</h2>
        <p>Este es un <strong>párrafo</strong> de texto. Puedes usar etiquetas como <em>&lt;em&gt;</em> para <em>énfasis</em> y <strong>&lt;strong&gt;</strong> para <strong>negrita</strong>.</p>
        <p>Ejemplo de <a href="https://www.youtube.com/watch?v=M7-ScejKmjU">enlace</a> a otro sitio web.</p>
        <p>El siguiente es un <code>código en línea</code> y un <pre><code>código en bloque</code></pre>.</p>
    </section>

    <section>
        <h2>Imágenes</h2>
        <center><img src="imge.jpg" alt="imge.jpg"  /></center>
        <p>Imagen de ejemplo usando la etiqueta &lt;img&gt;.</p>
        <h11>para agregar una imagen es poner img luego src= "agregas el nombre de la imagen.jpg" alt="cualquier cosa", las iamgenes sirven para que se vea mejor o guiar la persona con imagenes, es importante tener en claro que debes poner la imagen donde van las demas documentacion. </h11>
    </section>

    <section>
        <h2>Listas</h2>
        <h3>Lista Ordenada</h3>
        <ol>
            <li>Elemento 1</li>
            <li>Elemento 2</li>
            <li>Elemento 3</li>
        </ol>
<h13>Las listas son elementos que posibilitan una mejor navegación en las páginas web, ya que permiten agrupar cierto contenido según se requiera. Para los archivos HTML, las listas se clasifican en ordenadas, desordenadas y descriptivas.</h13>
<br></brgh>
        <h3>Lista Desordenada</h3>
        <ul>
            <li>Elemento A</li>
            <li>Elemento B</li>
            <li>Elemento C</li>
        </ul>
        <b20>Son delimitadas por las etiquetas UL y su cierre (unordered list). Cada uno de los elementos de la lista es citado por medio de una etiqueta LI (La LI tiene su cierre, aunque si no lo colocas el navegador al ver el siguiente LI interpretará que estás cerrando el anterior).</b20>
    </section>
    <section>
        <h2>Formularios</h2>
        <form action="/enviar-formulario" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required /><br/><br/>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required /><br/><br/>

            <label for="mensaje">Mensaje:</label><br/>
            <textarea id="mensaje" name="mensaje" rows="4" cols="50"></textarea><br/><br/>

            <input type="submit" value="Enviar" />
        </form>
    </section>
    <br></br>
    <h22>
Un formulario HTML es una caja de texto que puede contener casillas de verificación, botones y campos alfanuméricos. Suelen encontrarse en los sitios web para recolectar los datos personales de los usuarios interesados en la oferta del sitio. Estos datos posteriormente se envían a una base de datos para ser procesados</h22>
      <p> siguiente pagina <a href="https://emma-gay.github.io/num2/"> enlace</a> a otro sitio web.</p>
    <footer>
        <p>Ejemplo de documento HTML con etiquetas básicas.</p>
    </footer>
    </style>
</head>
</body>
</html>
