<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encuesta de Productos</title>
    <style>
        body {
            background-color: #ADD8E6; /* Fondo azul claro */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 60%;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .question {
            margin: 20px 0;
        }
        .question label {
            font-size: 18px;
            font-weight: bold;
            color: #333;
        }
        .question textarea {
            width: 100%;
            height: 100px;
            padding: 10px;
            font-size: 16px;
            border-radius: 4px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }
        .product-description {
            font-size: 16px;
            color: #555;
            margin-bottom: 10px;
        }
        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            width: 100%;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Encuesta de Productos</h1>
        <form action="submit_form.php" method="POST"> <!-- Formulario con action para el procesamiento -->
            <!-- Bebida energizante -->
            <div class="question">
                <label for="producto1">Bebida energizante</label>
                <p class="product-description">
                    Esta bebida energizante está llena de antioxidantes que ayudan a fortalecer el sistema inmune. También es excelente para proporcionar energía natural sin los efectos secundarios de otras bebidas energéticas.
                </p>
                <textarea id="producto1" name="producto1" placeholder="¿Qué te parece la bebida energizante? ¿Te gustaría probarla?" required></textarea>
            </div>
            <!-- Almojabana -->
            <div class="question">
                <label for="producto2">Almojabana</label>
                <p class="product-description">
                    La almojabana es un delicioso panecillo hecho de queso fresco, con una textura suave por dentro y un sabor irresistible. Es una excelente opción para acompañar tu desayuno o merienda, aportando energía y calcio.
                </p>
                <textarea id="producto2" name="producto2" placeholder="¿Te gusta la almojabana? ¿La recomendarías?" required></textarea>
            </div>
            <!-- Natilla costeña -->
            <div class="question">
                <label for="producto3">Natilla costeña</label>
                <p class="product-description">
                    La natilla costeña es un postre cremoso y suave, acompañado con queso fresco, ideal para quienes disfrutan de los sabores tradicionales. Es una excelente fuente de nutrientes y una deliciosa manera de terminar una comida.
                </p>
                <textarea id="producto3" name="producto3" placeholder="¿Qué opinas de la natilla costeña? ¿La has probado antes?" required></textarea>
            </div>
            <!-- Preguntas adicionales -->
            <div class="question">
                <label for="producto4">¿Qué productos te gustaría que añadiéramos a la encuesta?</label>
                <textarea id="producto4" name="producto4" placeholder="Por favor, dime qué productos te gustaría ver en nuestra oferta."></textarea>
            </div>
            <div class="question">
                <label for="producto5">¿Estás satisfech@ con estos productos?</label>
                <textarea id="producto5" name="producto5" placeholder="Cuéntanos si estás satisfecho/a o qué mejorarías."></textarea>
            </div>
            <div class="question">
                <label for="producto6">¿Qué piensas de estos productos?</label>
                <textarea id="producto6" name="producto6" placeholder="Escribe tus opiniones o sugerencias sobre estos productos."></textarea>
            </div>
            <!-- Botón de envío -->
            <button type="submit">Enviar Respuestas</button>
        </form>
    </div>
</body>
</html>
