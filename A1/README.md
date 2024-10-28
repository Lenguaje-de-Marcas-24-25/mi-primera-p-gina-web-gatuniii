**#AQUI VA EL CODIGO HTML DE MI PRIMERA PAGINA WEB#**

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML</title>
</head>

<body>
    <h1>HTML</h1> <!--Aqui va el titulo-->
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML5 Logo" width="150"> <!--Agregamos la imagen-->

    <h2>¿Qué es HTML?</h2> <!--otro titulo-->
    <p> <!--agregamos un  parrafo-->
        HTML, sigla en inglés de <strong>HyperText Markup Language</strong> (lenguaje de marcas de hipertexto), hace referencia al lenguaje<br> de marcado para la elaboración de páginas web.
        Es un estándar que sirve de referencia del software que conecta con la<br> elaboración de páginas web en sus diferentes versiones, define una estructura básica y un código (denominado código <br> HTML) para la definición de contenido de una página web, como texto, imágenes, videos, juegos, entre otros.
    </p>
    <p>Para más detalles haz click en <a href="https://es.wikipedia.org/wiki/HTML">En este Enlace</a></p> <!--el enlace a mas informacion-->

    <h2>Editores de texto recomendados</h2>
    <p>Algunos editores de texto recomendados son:</p>
    <ul> <!--esto es para crear una lista-->
        <li>Notepad <a href="https://notepad-plus-plus.org/downloads/">descargar</a></li>  <!--li es la forma de ir agregando elementos a la lista-->
        <li>SublimeText <a href="https://www.sublimetext.com/3">Descargar</a></li>
        <li>Dreamweaver <a href="https://helpx.adobe.com/es/dreamweaver/get-started.html">Descargar</a></li>
        <li>Gedit <a href="https://gedit.softonic.com/">Descargar</a></li>
    </ul>

    <h2>Navegadores Web</h2>
    <p>Los siguientes navegadores permiten visualizar páginas web:</p>
    <table border="1"> <!--añadimos una tabla de borde 1-->
        <thead> <!--cabecera de la tabla-->
            <tr>
                <th>Nombre</th>
                <th>Enlace descarga</th>
            </tr>
        </thead>
        <tbody> <!--cuerpo de la tabla-->
            <tr>
                <td>Firefox</td> <!--td para añadir elementos dentro del tr(tabla horizontal)-->
                <td><a href="https://www.mozilla.org/es-ES/firefox/new/">Descargar</a></td> <!--a href= es para poner enlaces a alguna pagina-->
            </tr>
            <tr>
                <td>Microsoft Edge</td>
                <td><a href="https://www.microsoft.com/es-es/edge/download?form=MA13FJ">Descargar</a></td>
            </tr>
            <tr>
                <td>Google Chrome</td>
                <td><a href="https://www.google.com/intl/es_es/chrome/">Descargar</a></td>
            </tr>
            <tr>
                <td>Safari</td>
                <td><a href="https://www.apple.com/es/safari/">Descargar</a></td>
            </tr>
        </tbody>
    </table>

</body>
</html>