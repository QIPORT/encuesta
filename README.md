<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unidad Educativa Dr Arturo Freire - Encuesta de Productos</title>
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
        .question select {
            width: 100%;
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
        .product-image {
            width: 250px; /* Ajusta el ancho */
            height: 250px; /* Ajusta la altura para que sea cuadrada */
            object-fit: cover; /* Mantiene la imagen cuadrada, recortando si es necesario */
            display: block;
            margin: 10px auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Unidad Educativa Dr Arturo Freire - Encuesta de Productos</h1>
        <form action="submit_form.php" method="POST">
            <!-- Bebida energizante -->
            <div class="question">
                <label for="bebida_energizante">¿Qué te parece la bebida energizante?</label>
                <img class="product-image" src="imagenes/bebida_energizante.jpg" alt="Bebida Energizante">
                <select id="bebida_energizante" name="bebida_energizante" required>
                    <option value="excelente">Excelente</option>
                    <option value="buena">Buena</option>
                    <option value="regular">Regular</option>
                    <option value="mala">Mala</option>
                    <option value="muy_mala">Muy mala</option>
                </select>
            </div>
            <div class="question">
                <label for="energizante_sabor">¿Te gusta el sabor de la bebida energizante?</label>
                <select id="energizante_sabor" name="energizante_sabor" required>
                    <option value="si_mucho">Sí, mucho</option>
                    <option value="si">Sí</option>
                    <option value="indiferente">Indiferente</option>
                    <option value="no_mucho">No mucho</option>
                    <option value="no">No</option>
                </select>
            </div>
            <div class="question">
                <label for="energizante_frecuencia">¿Con qué frecuencia consumirías esta bebida?</label>
                <select id="energizante_frecuencia" name="energizante_frecuencia" required>
                    <option value="diariamente">Diariamente</option>
                    <option value="semanalmente">Semanalmente</option>
                    <option value="ocasionalmente">Ocasionalmente</option>
                    <option value="raramente">Raramente</option>
                    <option value="nunca">Nunca</option>
                </select>
            </div>
            <div class="question">
                <label for="energizante_preferencia">¿Prefieres esta bebida sobre otras energizantes?</label>
                <select id="energizante_preferencia" name="energizante_preferencia" required>
                    <option value="si_mucho">Sí, mucho</option>
                    <option value="si">Sí</option>
                    <option value="indiferente">Indiferente</option>
                    <option value="no_mucho">No mucho</option>
                    <option value="no">No</option>
                </select>
            </div>
            <div class="question">
                <label for="energizante_recomendacion">¿Recomendarías esta bebida a otros?</label>
                <select id="energizante_recomendacion" name="energizante_recomendacion" required>
                    <option value="si_mucho">Sí, mucho</option>
                    <option value="si">Sí</option>
                    <option value="indiferente">Indiferente</option>
                    <option value="no_mucho">No mucho</option>
                    <option value="no">No</option>
                </select>
            </div>
            <!-- Almojábana -->
            <div class="question">
                <label for="almojabana_sabor">¿Qué tan agradable te parece el sabor de la almojábana?</label>
                <img class="product-image" src="imagenes/almojabana.jpg" alt="Almojabana">
                <select id="almojabana_sabor" name="almojabana_sabor" required>
                    <option value="muy_agradable">Muy agradable</option>
                    <option value="agradable">Agradable</option>
                    <option value="indiferente">Indiferente</option>
                    <option value="desagradable">Desagradable</option>
                    <option value="muy_desagradable">Muy desagradable</option>
                </select>
            </div>
            <div class="question">
                <label for="almojabana_textura">¿Te gusta la textura de la almojábana?</label>
                <select id="almojabana_textura" name="almojabana_textura" required>
                    <option value="si_mucho">Sí, mucho</option>
                    <option value="si">Sí</option>
                    <option value="indiferente">Indiferente</option>
                    <option value="no_mucho">No mucho</option>
                    <option value="no">No</option>
                </select>
            </div>
            <div class="question">
                <label for="almojabana_frecuencia">¿Con qué frecuencia consumirías almojábanas?</label>
                <select id="almojabana_frecuencia" name="almojabana_frecuencia" required>
                    <option value="diariamente">Diariamente</option>
                    <option value="semanalmente">Semanalmente</option>
                    <option value="ocasionalmente">Ocasionalmente</option>
                    <option value="raramente">Raramente</option>
                    <option value="nunca">Nunca</option>
                </select>
            </div>
            <div class="question">
                <label for="almojabana_contenido">¿Qué te parece la cantidad de queso en la almojábana?</label>
                <select id="almojabana_contenido" name="almojabana_contenido" required>
                    <option value="perfecto">Perfecto</option>
                    <option value="bueno">Bueno</option>
                    <option value="neutro">Neutro</option>
                    <option value="poco">Poco</option>
                    <option value="muy_poco">Muy poco</option>
                </select>
            </div>
            <div class="question">
                <label for="almojabana_recomendacion">¿Recomendarías la almojábana a tus amigos?</label>
                <select id="almojabana_recomendacion" name="almojabana_recomendacion" required>
                    <option value="si_mucho">Sí, mucho</option>
                    <option value="si">Sí</option>
                    <option value="indiferente">Indiferente</option>
                    <option value="no_mucho">No mucho</option>
                    <option value="no">No</option>
                </select>
            </div>
            <!-- Natilla costeña -->
            <div class="question">
                <label for="natilla_sabor">¿Te gusta el sabor de la natilla costeña?</label>
                <img class="product-image" src="imagenes/natilla_costena.jpg" alt="Natilla Costeña">
                <select id="natilla_sabor" name="natilla_sabor" required>
                    <option value="si_mucho">Sí, mucho</option>
                    <option value="si">Sí
