<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <meta name="description" content="Diseño y nuevos medios" />
        <link href="style.css" rel="stylesheet" />
        <title>DNO037</title>
        <!--
        <span style='font-size:100px;'>&#127801;</span>
        Esto es un comentario de HTML. No es necesario que lo borres.
        Si arriba, dentro de <title></title>, quieres un emoji, búscarlo en 
        - https://www.w3schools.com/charsets/ref_emoji.asp
        - https://www.w3schools.com/charsets/ref_emoji_smileys.asp
        Usa el número de columna "Dec", y súmale un "&#" al principio.
        -->
    </head>
    <body>
        <!-- Lee https://developer.mozilla.org/es/docs/Web/HTML/Elemento/header - Después de la lectura, borra este comentario -->
        <header>
            <h1>Isidora Millas</h1>
        </header>
        <!-- Lee https://developer.mozilla.org/es/docs/Web/HTML/Elemento/main - Después de la lectura, borra este comentario -->
        <main>
            <p>Tomé este opr porque desde chica me ha causado curiosidad la programación, por ejemplo cuando usaba tumblr o jugaba habbo.</p>
        </main>
        <!-- Lee https://developer.mozilla.org/es/docs/Web/HTML/Elemento/footer - Después de la lectura, borrar este comentario -->
        <footer>
            <div></div>
            <div></div>
            <div id="next"></div>
        </footer>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.min.js" integrity="sha512-N4kV7GkNv7QR7RX9YF/olywyIgIwNvfEe2nZtfyj73HdjCUkAfOBDbcuJ/cTaN04JKRnw1YG1wnUyNKMsNgg3g==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
        <script>
            // Esto es una línea de comentario en JAVASCRIPT
            var palabras = ["siguiente", "repüyen", "seguente", "suivant", "next", "Nächster", "次の", "다음의"];
            function setup() {
                var p = random(palabras);
                console.log(p);
                createA("page.html", p).parent("next");
                noCanvas();
            }
            /* 
            Esto también es un comentario en JAVASCRIPT
            Se usa así para varias líneas de comentario
            */
        </script>
    </body>
</html>
