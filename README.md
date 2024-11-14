<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encuesta sobre Productos</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #e0f7fa; /* Fondo azul suave */
            color: #333;
            padding: 40px;
            margin: 0;
        }
        h1 {
            text-align: center;
            color: #0277bd; /* Color de texto azul oscuro */
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        h2 {
            text-align: center;
            color: #0277bd; /* Color de texto azul oscuro */
            font-size: 1.2em;
            margin-bottom: 40px;
        }
        form {
            background-color: #ffffff; /* Fondo blanco para el formulario */
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1); /* Sombra suave */
            max-width: 800px;
            margin: 0 auto;
        }
        .pregunta {
            margin-bottom: 20px;
        }
        .pregunta label {
            font-weight: bold;
            font-size: 1.2em;
            display: block;
            margin-bottom: 10px;
        }
        .respuesta {
            margin-left: 20px;
        }
        .respuesta label {
            font-size: 1em;
            margin-right: 10px;
        }
        .imagen {
            text-align: center;
            margin-bottom: 20px;
        }
        .imagen img {
            width: 100%; /* Ajusta el tamaño de las imágenes al 100% del contenedor */
            max-width: 500px; /* Tamaño máximo para no exceder un límite */
            height: auto; /* Mantiene la proporción de la imagen */
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1); /* Sombra en las imágenes */
        }
        button {
            background-color: #0277bd; /* Azul oscuro */
            color: white;
            font-size: 1.2em;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            width: 100%;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #01579b; /* Color más oscuro cuando se pasa el ratón */
        }
    </style>
</head>
<body>
    <h1>Unidad Educativa Dr. Arturo Freire</h1>
    <h2>Los estudiantes del proyecto de emprendimiento proporcionan la siguiente encuesta para ofrecer los productos a seleccionar</h2>
    <form action="submit_form.php" method="POST">
        <!-- Bebida Energizante (Chicha Morada) -->
        <div class="pregunta">
            <label for="bebida1">¿Te gustaría probar una bebida energizante hecha con maíz morado, conocida por sus propiedades antioxidantes?</label>
            <div class="respuesta">
                <label><input type="radio" name="bebida1" value="Sí"> Sí</label>
                <label><input type="radio" name="bebida1" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="bebida2">¿Te resulta atractivo que nuestra bebida energizante tenga un sabor refrescante y natural, sin aditivos artificiales?</label>
            <div class="respuesta">
                <label><input type="radio" name="bebida2" value="Sí"> Sí</label>
                <label><input type="radio" name="bebida2" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="bebida3">¿Considerarías que una bebida energizante basada en ingredientes naturales como el maíz morado puede ser una opción saludable para tus días?</label>
            <div class="respuesta">
                <label><input type="radio" name="bebida3" value="Sí"> Sí</label>
                <label><input type="radio" name="bebida3" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="bebida4">¿Estarías dispuesto a consumir una bebida energizante que te brinde energía sin la sensación de pesadez?</label>
            <div class="respuesta">
                <label><input type="radio" name="bebida4" value="Sí"> Sí</label>
                <label><input type="radio" name="bebida4" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="bebida5">¿Te gustaría que nuestra bebida energizante sea una alternativa a las bebidas azucaradas y energéticas convencionales?</label>
            <div class="respuesta">
                <label><input type="radio" name="bebida5" value="Sí"> Sí</label>
                <label><input type="radio" name="bebida5" value="No"> No</label>
            </div>
        </div>
        <div class="imagen">
            <img src="chicha-morada.jpg" alt="Chicha Morada">
        </div>
        <!-- Almojabana -->
        <div class="pregunta">
            <label for="almojabana1">¿Te gustaría probar una almojabana, un panecillo tradicionalmente relleno de queso, suave y esponjoso?</label>
            <div class="respuesta">
                <label><input type="radio" name="almojabana1" value="Sí"> Sí</label>
                <label><input type="radio" name="almojabana1" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="almojabana2">¿Considerarías que una almojabana acompañada de una bebida energizante sería una opción sabrosa y ligera para tu desayuno o merienda?</label>
            <div class="respuesta">
                <label><input type="radio" name="almojabana2" value="Sí"> Sí</label>
                <label><input type="radio" name="almojabana2" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="almojabana3">¿Te atrae la idea de que nuestra almojabana esté hecha con ingredientes frescos, como queso cremoso y harina, ofreciendo una textura suave y sabrosa?</label>
            <div class="respuesta">
                <label><input type="radio" name="almojabana3" value="Sí"> Sí</label>
                <label><input type="radio" name="almojabana3" value="No"> No</label>
            </div>
        </div>
        <div class="imagen">
            <img src="almojabana.jpg" alt="Almojabana">
        </div>
        <!-- Natilla Costeña -->
        <div class="pregunta">
            <label for="natilla1">¿Te gustaría probar una natilla costeña, un postre cremoso a base de leche y coco, típico de la región costera?</label>
            <div class="respuesta">
                <label><input type="radio" name="natilla1" value="Sí"> Sí</label>
                <label><input type="radio" name="natilla1" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="natilla2">¿Te atrae la idea de un postre con una textura cremosa y un sabor delicado que combina leche fresca y coco?</label>
            <div class="respuesta">
                <label><input type="radio" name="natilla2" value="Sí"> Sí</label>
                <label><input type="radio" name="natilla2" value="No"> No</label>
            </div>
        </div>
        <div class="pregunta">
            <label for="natilla3">¿Te gustaría que la natilla tenga un toque dulce y sabroso con un toque de coco fresco?</label>
            <div class="respuesta">
                <label><input type="radio" name="natilla3" value="Sí"> Sí</label>
                <label><input type="radio" name="natilla3" value="No"> No</label>
            </div>
        </div>
        <div class="imagen">
            <img src="natilla-costena.jpg" alt="Natilla Costeña">
        </div>
        <!-- Botón de envío -->
        <button type="submit">Enviar Encuesta</button>
    </form>
</body>
</html>

